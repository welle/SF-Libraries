# Lightning Web Component: Streaming Player

<img src="docs/animation.gif" alt=""/>

## Features:

Youtube and Dailymotion streaming player.
Can be used either on record page, homepage and app page.

## Parameters

### Record page

<img src="docs/recordPageProperty.png" alt=""/>

- Mandatory

  - recordId current record id (provided by default in a lightning record page).
  - fieldApiName Field API name containing the Youtube or Dailymotion video URL to stream (including video ID)

- Optional

  - title title to display above the streaming.
  - allowModal Allow user to show streaming in modal ? (default is false)

### Home page and app page

<img src="docs/homePageProperty.png" alt=""/>

- Mandatory

  - videoUrl Full URL of the Youtube or Dailymotion video to stream (including video ID).

- Optional

  - title title to display above the streaming.
  - allowModal Allow user to show streaming in modal ? (default is false)

## TODO

- Add Vimeo support.
