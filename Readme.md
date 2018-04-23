# How to change Filter Button alignment within a column header


<p>This example demonstrates how to change Filter Button alignment within a column header. For this, it's necessary to re-define the x:Key="{dxgt:GridColumnHeaderThemeKey ResourceKey=ControlTemplate}" control template, create the FilterAlignment attached property and attach it to the column. If you are using themes, you need to re-define a control template for your theme and add it's name to the key - x:Key="{dxgt:GridColumnHeaderThemeKey ResourceKey=ControlTemplate, ThemeName=DXStyle}"<br /><br /></p>
<p>Update:<br />Starting with version 14.1, the filter icon is arranged by the ColumnHeaderDockPanel element. To change the filter icon position, create a ColumnHeaderDockPanel descendant and override its ArrangeOverride method.</p>

<br/>


