# RaeedChat Profile Settings

## Example 

```json 
 {
  "settings":{
    "AllowAnimations": false,
    "AllowDev": false,
    "TextZoom":"Big",
    "LineSpacing": "1.5"
  }
 }
```

## Properties 

Everything must be inside of the "settings" parent in the JSON 

```json
 {
  "settings":{
   
  }
 }
```

Property List 

| property          | type      | parent     | description                                                                                          |
|-------------------|-----------|------------|------------------------------------------------------------------------------------------------------|
| `AllowAnimations` | `Boolean` | `settings` | This sets weather or not css animations will be played on pages                                      |
| `AllowDev`        | `Boolean` | `settings` | This sets weather or not developer mode is enabled                                                   |
| `TextZoom`        | `String`  | `settings` | This can be set to either "Normal", "Big","Bigger", or "Biggest", this controls the zoom of the text |
| `LineSpacing`     | `String`  | `settings` | Line spacing sets spacing between lines, can be "single", "1.5", or "double"                         |

