# Wildcards

Wildcards let you to precisely vary the properties of a specification to generate multiple visualizations in parallel. There are three types of wildcards: Wildcard Fields, Wildcard Shelves and Wildcard functions.

### Wildcard Fields

Wildcard fields let you create multiple views in parallel by enumerating over a set of fields. Quantitative, Categorical, and Temporal field wildcards are provided by [default](wildcard-fields.md#preset-wildcard-fields), though you can manually author [custom](wildcard-fields.md#custom-wildcard-fields) wildcards containing the desired fields.

![](../.gitbook/assets/screen-shot-2018-05-22-at-1.30.06-pm.png)

![](../.gitbook/assets/screen-shot-2018-05-22-at-1.30.42-pm.png)

#### Preset Wildcard Fields

These wildcards represent all fields of a particular data type \(Quantitative, Categorical, and Temporal\). You can simply drag-and-drop a wildcard field onto an encoding shelf to create multiple charts in parallel. 

![](../.gitbook/assets/wildcard_fields.gif)

#### Custom Wildcard Fields

To create a wildcard for a specific set of fields, you can author a custom wildcard field by dragging desired fields to the wildcard list. However, to avoid incongruous views, you are prevented from creating custom wildcard fields that contain multiple data types.

![](../.gitbook/assets/custom-wildcard-fields%20%281%29.gif)

### Wildcard Shelves

Wildcard shelves let you add fields without selecting a specific channel, allowing the system to suggest appropriate encodings.

![](../.gitbook/assets/ws.png)

The screenshot below shows the system automatically encoding the two quantitative fields onto the `x` and `y` channels since they were the most perceptually effective and expressive channels available.

![](../.gitbook/assets/wsgif.gif)

### Wildcard Function

Wildcard functions allow simultaneous specification of data field transformations. When the `Wildcard` button is checked, the radio buttons for each function will become check-boxes, allowing you to select the functions you want to enumerate. The field pill will denote that it has become a wildcard field by wrapping the field name with with “?”.

![](../.gitbook/assets/wildcard_functions.gif)

