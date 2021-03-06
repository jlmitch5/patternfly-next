## Overview

The dropdown menu can contain either links or buttons, depending on the expected behavior when clicking the menu item. If you are using the menu item to navigate to another page, then menu item is a link. Otherwise, use a button for the menu item.

## Accessibility

| Attribute | Applied | Outcome |
| -- | -- | -- |
| `aria-haspopup="true"` | `.pf-c-dropdown__toggle` | Indicates the button has a popup menu. |
| `aria-expanded="false"` | `.pf-c-dropdown__toggle` |  Indicates that the menu is hidden |
| `aria-expanded="true"` | `.pf-c-dropdown__toggle` |  Indicates that the menu is visible |
| `role="menu"` | `.pf-c-dropdown__menu` | Indicates that the menu is a menu |
| `hidden="hidden"` | `.pf-c-dropdown__menu` | Indicates that the menu is hidden so that it isn't visible in the UI and isn't accessed by assistive technologies |
| `aria-expanded="true"` | `.pf-c-dropdown__menu` | Indicates that the menu is visible |
| `role="menuitem"` | `.pf-c-dropdown__menu-item` | Indicates that the menu item is a menu item |
| `role="separator"` | `.pf-c-dropdown__separator` | Indicates that the separator is a separator |
| `disabled="disabled"` | `button.pf-c-dropdown__menu-item` | When the menu item uses a button element, indicates that it is unavailable and removes it from keyboard focus |
| `aria-disabled="true"` | `a.pf-c-dropdown__menu-item` | When the menu item uses a link element, indicates that it is unavailable |
| `tabindex="-1"` | `a.pf-c-dropdown__menu-item` | When the menu item uses a link element, removes it from keyboard focus |

## Usage

| Class | Applied | Outcome |
| -- | -- | -- |
| `.pf-c-dropdown` | `<div>` | Defines the parent wrapper of the dropdown. |
| `.pf-c-dropdown__toggle` | `<button>` | Defines the dropdown toggle |
| `.pf-c-dropdown__menu` | `<div>` | Defines the parent wrapper of the menu items |
| `.pf-c-dropdown__menu-item` | `<a>` | Defines a menu item that navigates to another page |
| `.pf-c-dropdown__menu-item` | `<button>` | Defines a menu item that performs an action on the current page |
| `.pf-c-dropdown__separator` | `<div>` | Defines a separator within the menu |
| `.pf-m-expanded` | `.pf-c-dropdown` | Modifies for the expanded state |
| `.pf-m-ghost` | `.pf-c-dropdown` | Modifies to display the toggle with no border or background |
| `.pf-m-no-arrow` | `.pf-c-dropdown` | Modifies to display the toggle without the arrow |
| `.pf-m-dropup` | `.pf-c-dropdown` | Modifies to display the menu above the toggle |
| `.pf-m-right-aligned` | `.pf-c-dropdown` | Modifies to display the menu right-aligned with the toggle |
| `.pf-m-disabled` | `.pf-c-dropdown__menu-item` | Modifies to display the menu item as disabled |
