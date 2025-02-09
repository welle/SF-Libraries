# Lightning Web Component: Button Custom Filter

<img src="docs/animation.gif" alt=""/>

## Parameters

- Mandatory

  - options Array of label-value pairs for each checkbox.

- Optional

  - value
    The list of selected checkboxes.
    Each array entry contains the value of a selected checkbox.
    The value of each checkbox is set in the options attribute.

## Noptification

- When the "Apply" button is clicked, a "change" notification is dispatched. The event.detail.values contains the checked options.
