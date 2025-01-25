# Lightning Web Component: Generic Related Chart.

<img src="docs/sample.png" alt=""/>

## Parameters

* Mandatory
    - recordId current record id (provided by default in a lightning record page).
    - relatedSObject related Object API Name.
    - relationshipFieldAPIName relationship Field API Name (how is the record object and the related SObject linked ?).
    - label Field API name of label to display.
    - field API name of field to display.

* Optional
    - title Specify the title to display.
    - showTitle Specify if the title should be display.
    - width Specify the chart width.
    - height Specify the chart height.
    - min Specify minimum number for the scale.
    - max Specify maximum number for the scale.
    - step Specify step size for the scale.
    - align Specify the horizontal alignment (left, center, right).
    - backgroundColor Specify the RGBA value of the background (ie: 255,0,255,0.2)
    
## Todo

Support only spider chart for the moment, other charts should be added.