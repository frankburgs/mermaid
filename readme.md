# Mermaid
There are 3 ways to style a Mermaid graph.

Below the graph definition with class and classDef.

By customizing the theme as shown below

``` mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': 'black', $ shape background color
      'primaryTextColor': 'aqua', $ shape text color
      'primaryBorderColor': 'aqua', $ shape border color
      'lineColor': 'aqua', $ Arrow color
      'secondaryColor': 'red', $ No idea
      'tertiaryColor': 'aqua', $ subgraph background color
      'tertiaryBorderColor': 'aqua', $ subgraph border color
      'tertiaryTextColor': 'aqua' $ subgraph text color
    }
  }
}%%
```

And by applying CSS rules as shown below

``` css
.cssClass > rect {
  fill: #000 !important;
  stroke: #99ffff !important;
  stroke-width: 2px !important;
}

.cssClass > path {
  fill: #000 !important;
  stroke: #99ffff !important;
  stroke-width: 2px !important;
}

g > path {
  fill: #99ffff !important;
  stroke: #99ffff !important;
  stroke-width: 2px !important;
  color: #99ffff !important;
}

.nodeLabel {
  color: #99ffff !important;
}
```