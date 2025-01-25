# Lightning Aura Component: Copy object information to clipboard

## Features:
On 20/01/2020, in LWC it is not possible to copy text to clipboard.

Modulable "copy to clipboad" aura components.

1. genericObjectToClipboardQuickAction
    Lightning Aura "lightningQuickAction" to allow use in record Action button.
2. genericGetRecordFromLabel
    Retrieve all fields contained in a label.
    Field(s) should be surrounded by ``{}`` (ie: Record name is {Name} and the phone is {Phone}. You can send an email to {EMAIL})
3. genericCopyToClipboard
    Just copy a given text to the clipboard.
4. genericObjectToClipboard
    To use in a record page, allow to copy to clipboard the record information based on:
    * Parameters: 
        - labelName Custom label API name to use.
        - recordId current record Id.

## TODO:

- Refactor in LWC when solution available.