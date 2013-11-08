
X add background color
X show temporary highlight while selecting new data
X add flashing feature highlight when mousing over a layer
X temporarily hide layers

- composited layers
- line caps/joins
- pois
- text
- click on features on the map to highlight the layer
  - use feature bitmaps?
- duplicate layer
- add reset north compass
- enable/disable the feature
- fadein/fadeout depending on zoom level
- zoom level dependent colors

- support multiple styles/switching between styles

- add new data
  - select tile layer
  - filter by value (string matching, number ranges!)
  - show taginfo stats
    - update them while the user pans around
- restore the unparsed style
- undo/redo support
- duplicate entire style
  - diverging styles

- add more color operations (darken); dependent colors
- add color palette
- add opacity control


- rebuild interface with [angular | ember | backbone]
- dependent parameters
  - change line width dependent on other, connected line(s)
  - line with = <other line width> + 1 
  - color = operation(<other color>)      operation = darken(%), lighten(%)
