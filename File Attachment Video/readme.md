# Lightning Web Component: File Attachment Audio

Mimic the Salesforce file view extended as an accordion with video player in the accordion content section.

<img src="docs/animation.gif" alt=""/>

## What's new ?

- 06/02/2025

  - Added "height" & "width" parameters.

## Features

- Mimic the Salesforce file view.
- Click on file will open the Salesforce file preview.
- Click on the accordion will show/hide the video player. When closing the accordion, it will pause the video player.

## Parameters

- Mandatory

  - videoContentDocumentId Video Content Document Id.

## Events

- sectionopen : dispatched when the section is opened. `event.detail.value` contains the content document id.

- sectionclose : dispatched when the section is closed. `event.detail.value` contains the content document id.

## Usage

```
<c-file-attachment-video video-content-document-id="069KA000003sakAYAQ"></c-file-attachment-video>
```

## Dependencies

- "File Attachment" component [Readme](<./../File Attachment/readme.md>).
- "Video Player" component [Readme](<./../Video Player/readme.md>).
