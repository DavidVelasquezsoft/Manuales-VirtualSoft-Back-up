---
description: >-
  Cada ejemplo contiene únicamente los elementos necesarios para mostrar la
  estructura esperada de documentación.
---

# Documentación de código Frontend.

***

### 1. TypeScript + Vue 3 (Sitebuilder)&#x20;

Utiliza esta plantilla para archivos `.vue` desarrollados con TypeScript.

```typescript
/**
* @file UserCard.vue
* @description Displays user information and handles user interactions.
*/

<script setup lang="ts">

/**
 * User information.
 *
 * @description Defines the structure of a user.
 */
interface User {
  /**
   * Unique user identifier.
   * @description A unique identifier for the user.
   */
  id: string;

  /**
   * User display name.
   * @description The name to display for the user.
   */
  name: string;
}

/**
 * User status.
 *
 * @description Defines the available user statuses.
 */
type UserStatus = 'active' | 'inactive' | 'pending';

/**
 * User card component properties.
 *
 * @description Defines the data received by the component.
 */
const props = defineProps<{
  /**
   * User information.
   * @description The user data to display.
   */
  user: User;

  /**
   * Current user status.
   * @description The status of the user.
   */
  status: UserStatus;
}>();

/**
 * Component events.
 *
 * @description Defines the events emitted by the component.
 */
const emit = defineEmits<{
  /**
   * Emitted when the user is selected.
   *
   * @description Triggered when the user card is clicked.
   * @param {string} userId - Identifier of the selected user.
   */
  select: [userId: string];

  /**
   * Emitted when the user status changes.
   *
   * @description Triggered when the user status is updated.
   * @param {UserStatus} status - New user status.
   */
  statusChange: [status: UserStatus];
}>();

/**
 * Displays the formatted user name.
 *
 * @description Generates the user name displayed by the component.
 */
const displayName = computed(() => {
  return props.user.name.trim();
});

/**
 * Selects the current user.
 *
 * @description Emits the user selection event.
 *
 * @param {string} userId - Identifier of the selected user.
 * @returns void.
 */
function selectUser(userId: string): void {
  emit('select', userId);
}

</script>
```

***

### 2. VUE + TypeScript (Usuarios Online)

```typescript
<template>
    <section>
        <AccessMenu
            :options="menuOptions"
            @select-option="(option: any) => selectOptionMenu(option)"
        />
    </section>
</template>

<script lang="ts" setup>

/**
 * @fileoverview AccessMenu
 *
 * Displays the access menu and handles user interactions.
 *
 * @component AccessMenu
 */

// ============== IMPORTS ==============
import { ref, computed, onMounted } from 'vue';

// ============== PROPS ==============

/**
 * Component properties.
 *
 * @description Provides the data required to configure the access menu.
 */
const { data } = defineProps(['data']);

// ============== STATE ==============

const menuOptions = ref([]);
const isLoading = ref(true);

// ============== INTERFACES ==============

/**
 * Represents a menu option.
 */
interface MenuOption {
    id: string;
    title: string;
    icon: string;
}

// ============== TYPES ==============

/**
 * Defines the available menu variants.
 */
type MenuVariant = 'default' | 'compact';

// ============== COMPUTED ==============

/**
 * Calculates the maximum width class according to the current layout.
 *
 * @returns {string} The CSS class applied to the component.
 */
const maxWidthClass = computed(() => {
    return 'max-w-[1200px]';
});

// ============== METHODS ==============

/**
 * Loads the available menu options.
 *
 * @returns {Promise<void>} A promise resolved when the menu options are loaded.
 */
async function getMenuOptions(): Promise<void> {
    // ...
}

/**
 * Formats the menu options for display.
 *
 * @param {MenuOption[]} data - The menu options to format.
 * @returns {MenuOption[]} The formatted menu options.
 */
function formatOptionsMenu(data: MenuOption[]): MenuOption[] {
    // ...
    return data;
}

/**
 * Handles the selection of a menu option.
 *
 * @param {MenuOption} option - The selected menu option.
 * @returns {void} No value is returned.
 */
function selectOptionMenu(option: MenuOption): void {
    // ...
}

// ============== LIFE CYCLE ==============

onMounted(() => {
    getMenuOptions();
});

</script>

<style scoped></style>
```

***

### 3. TypeScript + Angular (Torneos y bonos)

Utiliza esta plantilla para archivos `.ts` desarrollados con Angular.

```typescript
/**
 * @file confirmation-dialog.component.ts
 * @description Provides the confirmation dialog component.
 */

import { Component, Input, OnInit } from '@angular/core';

/**
 * Component for displaying a confirmation dialog.
 *
 * @description Allows users to accept or decline an action.
 */
@Component({
    selector: 'app-confirmation-dialog',
    templateUrl: './confirmation-dialog.component.html',
})
export class ConfirmationDialogComponent implements OnInit {

    /**
     * Title of the confirmation dialog.
     */
    @Input()
    title: string;

    /**
     * Message to be displayed in the confirmation dialog.
     */
    @Input()
    message: string;

    /**
     * Text for the OK button.
     */
    @Input()
    btnOkText: string;

    /**
     * Text for the Cancel button.
     */
    @Input()
    btnCancelText: string;

    /**
     * Creates the confirmation dialog component.
     *
     * @param activeModal - Active modal instance used to close or dismiss the dialog.
     */
    constructor(private activeModal: NgbActiveModal) {}

    /**
     * Lifecycle hook that runs after data-bound properties are initialized.
     */
    ngOnInit(): void {
        // ...
    }

    /**
     * Closes the modal indicating that the action was declined.
     */
    public decline(): void {
        this.activeModal.close(false);
    }

    /**
     * Closes the modal indicating that the action was accepted.
     */
    public accept(): void {
        this.activeModal.close(true);
    }

    /**
     * Dismisses the modal without returning a value.
     */
    public dismiss(): void {
        this.activeModal.dismiss();
    }
}
```

***

### 4. JavaScript + Astro (LandingVirtual)

Utiliza esta plantilla para archivos `.astro` desarrollados con JavaScript.

```javascript
/**
 * @file Field.astro
 * @description Provides a reusable form field.
 */

/**
 * Form field component properties.
 *
 * @description Defines the data received by the component.
 */
interface Props {
    /**
     * Field name.
     */
    name: string;

    /**
     * Visible label of the field.
     */
    label: string;

    /**
     * Input type rendered by the field.
     */
    type?: "text" | "tel" | "email";
}

/**
 * Component properties received from the parent.
 *
 * @description Applies the properties defined by the component.
 */
const {
    name,
    label,
    type = "text",
} = Astro.props;

/**
 * Identifier of the input element.
 *
 * @description Links the label to the input element.
 */
const inputId = `f-${name}`;

/**
 * Formats the field identifier.
 *
 * @param name - Field name.
 * @returns Formatted field identifier.
 */
function formatFieldId(name) {
    return `f-${name}`;
}
---

<div class="field">
    <label for={inputId}>{label}</label>

    <input
        id={inputId}
        name={name}
        type={type}
    />
</div>
```

***

### 5. JavaScript + Webix (BackOffice)

Utiliza esta plantilla para archivos `.js` desarrollados con Webix.

```javascript
/**
 * @file UserManagementView.js
 * @description Provides the user management view.
 */

import { JetView } from 'webix-jet';

/**
 * User management view.
 *
 * @description Displays the user list and handles user interactions.
 *
 * @extends JetView
 */
export default class UserManagementView extends JetView {

    /**
     * Configures the UI components of the view.
     *
     * @returns {Object} The configuration object for the view.
     */
    config() {
        const grid = {
            view: 'datatable',

            /**
             * Handles the user selection event.
             *
             * @param {Object} id - The identifier of the selected row.
             * @returns {void}
             */
            onItemClick: (id) => {
                this.selectUser(id.row);
            }
        };

        return {
            rows: [grid]
        };
    }

    /**
     * Initializes the view and sets up event listeners.
     *
     * @returns {void}
     */
    init() {
        // ...
    }

    /**
     * Loads the user list into the datatable.
     *
     * @param {Object} grid - The datatable instance.
     * @param {Object} filterData - The filter criteria.
     * @returns {void}
     */
    loadUsers(grid, filterData) {
        // ...
    }

    /**
     * Selects a user and stores the selection.
     *
     * @param {string} userId - The user identifier.
     * @returns {void}
     */
    selectUser(userId) {
        // ...
    }
}
```

***

### 6. Reglas generales

* Los archivos nuevos deben incluir el encabezado de documentación.
* El encabezado debe ubicarse al inicio del archivo.
* La documentación del código debe estar escrita en inglés.
* Cada elemento documentado debe tener una descripción.
* Las descripciones deben comenzar con mayúscula y terminar con punto.
* Los parámetros deben documentarse con `@param` cuando corresponda.
* Las funciones que retornan un valor deben incluir `@returns`.
* Los errores relevantes deben documentarse con `@throws`.
* La documentación debe ubicarse inmediatamente antes del elemento que describe.
* La documentación debe corresponder al comportamiento real del código.

***

### 7. Historial de versiones
