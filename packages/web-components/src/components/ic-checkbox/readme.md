# ic-checkbox



<!-- Auto Generated Below -->


## Properties

| Property                       | Attribute                        | Description                                                                                                                                                                                   | Type                              | Default                                        |
| ------------------------------ | -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- | ---------------------------------------------- |
| `additionalFieldDisplay`       | `additional-field-display`       | The style of additionalField that will be displayed if used.                                                                                                                                  | `"dynamic" \| "static"`           | `"static"`                                     |
| `checked`                      | `checked`                        | If `true`, the checkbox will be set to the checked state. This is only the initial state and will be updated to unchecked if the checkbox is clicked.                                         | `boolean`                         | `false`                                        |
| `disabled`                     | `disabled`                       | If `true`, the checkbox will be set to the disabled state.                                                                                                                                    | `boolean`                         | `false`                                        |
| `dynamicText`                  | `dynamic-text`                   | The text to be displayed when dynamic.                                                                                                                                                        | `string`                          | `"This selection requires additional answers"` |
| `form`                         | `form`                           | The <form> element to associate the checkbox with.                                                                                                                                            | `string`                          | `undefined`                                    |
| `formaction`                   | `formaction`                     | The URL that processes the information submitted by the checkbox. It overrides the action attribute of the checkbox's form owner. Does nothing if there is no form owner.                     | `string`                          | `undefined`                                    |
| `formenctype`                  | `formenctype`                    | The way the submitted form data is encoded.                                                                                                                                                   | `string`                          | `undefined`                                    |
| `formmethod`                   | `formmethod`                     | The HTTP method used to submit the form.                                                                                                                                                      | `string`                          | `undefined`                                    |
| `formnovalidate`               | `formnovalidate`                 | If `true`, the form will not be validated when submitted.                                                                                                                                     | `boolean`                         | `undefined`                                    |
| `formtarget`                   | `formtarget`                     | The place to display the response from submitting the form. It overrides the target attribute of the checkbox's form owner.                                                                   | `string`                          | `undefined`                                    |
| `groupLabel`                   | `group-label`                    | The group label for the checkbox.                                                                                                                                                             | `string`                          | `undefined`                                    |
| `hideLabel`                    | `hide-label`                     | If `true`, the label will be hidden and the required label value will be applied as an aria-label.                                                                                            | `boolean`                         | `false`                                        |
| `indeterminate`                | `indeterminate`                  | If `true`, the indeterminate state will be displayed when checked.                                                                                                                            | `boolean`                         | `false`                                        |
| `label` _(required)_           | `label`                          | The label for the checkbox.                                                                                                                                                                   | `string`                          | `undefined`                                    |
| `name`                         | `name`                           | The name for the checkbox. If not set when used in a checkbox group, the name will be based on the group name.                                                                                | `string`                          | `undefined`                                    |
| `nativeIndeterminateBehaviour` | `native-indeterminate-behaviour` | If `true`, the checkbox will behave like a native checkbox where the `indeterminate` prop sets the indeterminate visual styling, independent of the `checked` state.                          | `boolean`                         | `false`                                        |
| `size`                         | `size`                           | The size of the checkbox to be displayed. This does not affect the font size of the label. If a checkbox is contained in a checkbox group, this will override the size set on checkbox group. | `"default" \| "large" \| "small"` | `undefined`                                    |
| `small`                        | `small`                          | <span style="color:red">**[DEPRECATED]**</span> This prop should not be used anymore. Set prop `size` to "small" instead.<br/><br/>                                                           | `boolean`                         | `false`                                        |
| `value` _(required)_           | `value`                          | The value for the checkbox.                                                                                                                                                                   | `string`                          | `undefined`                                    |


## Events

| Event             | Description                                                                                                           | Type                |
| ----------------- | --------------------------------------------------------------------------------------------------------------------- | ------------------- |
| `checkboxChecked` | <span style="color:red">**[DEPRECATED]**</span> This event should not be used anymore. Use icCheck instead.<br/><br/> | `CustomEvent<void>` |
| `icCheck`         | Emitted when a checkbox has been checked.                                                                             | `CustomEvent<void>` |


## Methods

### `setFocus() => Promise<void>`

Sets focus on the checkbox.

#### Returns

Type: `Promise<void>`




## Slots

| Slot                 | Description                                   |
| -------------------- | --------------------------------------------- |
| `"additional-field"` | Content to be displayed alongside a checkbox. |


## Dependencies

### Depends on

- [ic-typography](../ic-typography)

### Graph
```mermaid
graph TD;
  ic-checkbox --> ic-typography
  style ic-checkbox fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------


