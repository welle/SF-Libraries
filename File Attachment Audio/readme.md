# Lightning Web Component: File Attachment Audio

Mimic the Salesforce file view extended as an accordion with audio player in the accordion content section.

<img src="docs/animation.gif" alt=""/>

## Features

- Mimic the Salesforce file view.
- Click on file will open the Salesforce file preview.
- Click on the accordion will show/hide the audio player. When closing the accordion, it will pause the audio player.

## Parameters

- Mandatory

  - audioContentDocumentId Audio Content Document Id.

## Events

- sectionopen : dispatched when the section is opened. `event.detail.value` contains the content document id.

- sectionclose : dispatched when the section is closed. `event.detail.value` contains the content document id.

## Usage

```
<c-file-attachment-audio audio-content-document-id="069KA000003sakAYAQ"></c-file-attachment-audio>
```

## Dependencies

- "File Attachment" component [Readme](<./../File Attachment/readme.md>).
- "Audio Player" component [Readme](<./../Audio Player/readme.md>).
