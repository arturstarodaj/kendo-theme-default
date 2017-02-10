---
title: Customization
description: "The available variables for customization of the Kendo UI theme."
position: 9
---

<style>
.colorPreview {
  border-radius: 50%;
  width: 1em;
  height: 1em;
  vertical-align: middle;
  display: inline-block;
  border: 1px solid rgba(0,0,0,.08);
}
</style>

# Customization

## Variables


### Common

<table>
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 300px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$font-size</td>
<td>
    
    14px
</td>
<td>Base font size across all components
</td>
</tr>
<tr>
<td>$font-family</td>
<td>
    
    inherit
</td>
<td>Font family across all components
</td>
</tr>
<tr>
<td>$font-family-monospace</td>
<td>
    
    Consolas, "Ubuntu Mono", "Lucida Console", "Courier New", monospace
</td>
<td>Font family for monospaced text, used for styling code
</td>
</tr>
<tr>
<td>$line-height</td>
<td>
    
    (20 / 14)
</td>
<td>Line height used along with $font-size
</td>
</tr>
<tr>
<td>$border-radius</td>
<td>
    
    2px
</td>
<td>Border radius for all components
</td>
</tr>
<tr>
<td>$accent</td>
<td>
    <span class="colorPreview" style="background-color: #ff6358"></span>
    #ff6358
</td>
<td>Color that focuses the user attention<br/>
Used for primary buttons and across the theme
</td>
</tr>
<tr>
<td>$accent-contrast</td>
<td>
    <span class="colorPreview" style="background-color: #ffffff"></span>
    #ffffff
</td>
<td>Color used along with the accent color denoted by $accent.<br/>
Used to provide contrast between the background and foreground color
</td>
</tr>
<tr>
<td>$base-text</td>
<td>
    <span class="colorPreview" style="background-color: #656565"></span>
    #656565
</td>
<td>Text color of components' chrome area
</td>
</tr>
<tr>
<td>$base-bg</td>
<td>
    <span class="colorPreview" style="background-color: #f6f6f6"></span>
    #f6f6f6
</td>
<td>Background of chrome area of components
</td>
</tr>
<tr>
<td>$base-border</td>
<td>
    
    rgba( black, .08 )
</td>
<td>Border color of the components' chrome area
</td>
</tr>
<tr>
<td>$base-gradient</td>
<td>
    
    $base-bg, darken( $base-bg, 2% )
</td>
<td>Gradient background of components' chrome area
</td>
</tr>
<tr>
<td>$hovered-text</td>
<td>
    <span class="colorPreview" style="background-color: #656565"></span>
    #656565
</td>
<td>Text color of hovered items
</td>
</tr>
<tr>
<td>$hovered-bg</td>
<td>
    <span class="colorPreview" style="background-color: #ededed"></span>
    #ededed
</td>
<td>Background of hovered items
</td>
</tr>
<tr>
<td>$hovered-border</td>
<td>
    
    rgba( black, .15 )
</td>
<td>Border color of hovered items
</td>
</tr>
<tr>
<td>$hovered-gradient</td>
<td>
    
    $hovered-bg, darken( $hovered-bg, 2% )
</td>
<td>Gradient background of hovered items
</td>
</tr>
<tr>
<td>$selected-text</td>
<td>
    
    $accent-contrast
</td>
<td>Text color of selected items
</td>
</tr>
<tr>
<td>$selected-bg</td>
<td>
    
    $accent
</td>
<td>Background of selected items
</td>
</tr>
<tr>
<td>$selected-border</td>
<td>
    
    rgba( black, .1 )
</td>
<td>Border color of selected items
</td>
</tr>
<tr>
<td>$selected-gradient</td>
<td>
    
    none
</td>
<td>Gradient background of selected items
</td>
</tr>
<tr>
<td>$error</td>
<td>
    <span class="colorPreview" style="background-color: #f5503e"></span>
    #f5503e
</td>
<td>Color for error messages and states
</td>
</tr>
<tr>
<td>$warning</td>
<td>
    <span class="colorPreview" style="background-color: #fdce3e"></span>
    #fdce3e
</td>
<td>Color for warning messages and states
</td>
</tr>
<tr>
<td>$success</td>
<td>
    <span class="colorPreview" style="background-color: #5ec232"></span>
    #5ec232
</td>
<td>Color for success messages and states
</td>
</tr>
<tr>
<td>$info</td>
<td>
    <span class="colorPreview" style="background-color: #3e80ed"></span>
    #3e80ed
</td>
<td>Color for informational messages and states
</td>
</tr>
</table>


### Buttons

<table>
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 300px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$button-text</td>
<td>
    
    $base-text
</td>
<td>The text color of the buttons
</td>
</tr>
<tr>
<td>$button-bg</td>
<td>
    
    $base-bg
</td>
<td>The background of the buttons
</td>
</tr>
<tr>
<td>$button-border</td>
<td>
    
    $base-border
</td>
<td>The border color of the buttons
</td>
</tr>
<tr>
<td>$button-gradient</td>
<td>
    
    $base-gradient
</td>
<td>The background gradient of the buttons
</td>
</tr>
<tr>
<td>$button-hovered-text</td>
<td>
    
    $hovered-text
</td>
<td>The text color of hovered buttons
</td>
</tr>
<tr>
<td>$button-hovered-bg</td>
<td>
    
    $hovered-bg
</td>
<td>The background of hovered buttons
</td>
</tr>
<tr>
<td>$button-hovered-border</td>
<td>
    
    $hovered-border
</td>
<td>The border color of hovered buttons
</td>
</tr>
<tr>
<td>$button-hovered-gradient</td>
<td>
    
    $hovered-gradient
</td>
<td>The background gradient of hovered buttons
</td>
</tr>
<tr>
<td>$button-pressed-text</td>
<td>
    
    $selected-text
</td>
<td>The text color of pressed buttons
</td>
</tr>
<tr>
<td>$button-pressed-bg</td>
<td>
    
    $selected-bg
</td>
<td>The background color of pressed buttons
</td>
</tr>
<tr>
<td>$button-pressed-border</td>
<td>
    
    $selected-border
</td>
<td>The border color of pressed buttons
</td>
</tr>
<tr>
<td>$button-pressed-gradient</td>
<td>
    
    none
</td>
<td>The background gradient of pressed buttons
</td>
</tr>
<tr>
<td>$button-focused-shadow</td>
<td>
    
    0 3px 4px 0 rgba(0, 0, 0, .06)
</td>
<td>The shadow of focused buttons
</td>
</tr>
</table>


### Charts

<table>
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 300px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$series-a</td>
<td>
    <span class="colorPreview" style="background-color: #ff6358"></span>
    #ff6358
</td>
<td>First color of chart series
</td>
</tr>
<tr>
<td>$series-b</td>
<td>
    <span class="colorPreview" style="background-color: #ffd246"></span>
    #ffd246
</td>
<td>Second color of chart series
</td>
</tr>
<tr>
<td>$series-c</td>
<td>
    <span class="colorPreview" style="background-color: #78d237"></span>
    #78d237
</td>
<td>Third color of chart series
</td>
</tr>
<tr>
<td>$series-d</td>
<td>
    <span class="colorPreview" style="background-color: #28b4c8"></span>
    #28b4c8
</td>
<td>Fourth color of chart series
</td>
</tr>
<tr>
<td>$series-e</td>
<td>
    <span class="colorPreview" style="background-color: #2d73f5"></span>
    #2d73f5
</td>
<td>Fifth color of chart series
</td>
</tr>
<tr>
<td>$series-f</td>
<td>
    <span class="colorPreview" style="background-color: #aa46be"></span>
    #aa46be
</td>
<td>Sixth color of chart series
</td>
</tr>
<tr>
<td>$chart-major-lines</td>
<td>
    
    rgba(0, 0, 0, .08)
</td>
<td>The color of the chart grid lines (major)
</td>
</tr>
<tr>
<td>$chart-minor-lines</td>
<td>
    
    rgba(0, 0, 0, .04)
</td>
<td>The color of the chart grid lines (minor)
</td>
</tr>
</table>


## Mixins

### `exports`
Outputs a module once, no matter how many times it is included.


#### Parameters
- name : `String` - Name of exported module
