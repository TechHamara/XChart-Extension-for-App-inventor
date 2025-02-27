# XChart-Extension-for-App-inventor
XChart is a powerful radar chart component for App Inventor

<div align="center">
<h1><kbd>🧩 XChart</kbd></h1>
An extension for MIT App Inventor 2.<br>
XChart is a powerful radar chart component for App Inventor that allows you to create interactive and customizable radar/spider charts. Features include customizable colors, animations, shapes, labels, and click events. Developed by th using Fast.
</div>

## 📝 Specifications
* **
💾 **Size:** 25.68 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-02-27 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel)
<br>
**Paid** Price - 2💲 USD.<br>
**INR** - 175rs.<br>
**Telegram:** [here](https://t.me/techhamara91)<br>
**Find** more Extension [here](https://github.com/TechHamara/Th_Free_Extensions)<br>
<br>
## Buy In PayPal
  [💛paypal here](https://www.paypal.com/ncp/payment/P6VTC9YXC5YFG)
<br><br>
## Screen shot 
   ![Screenshot_2025-02-27-14-35-43-965_appinventor.ai_Techhamara91.xchart.jpg](https://github.com/user-attachments/assets/8b0ef5bb-8e3d-4df9-82c3-2a59c9fc8675)

## Demo Soon


## <kbd>Events:</kbd>
**XChart** has total 7 events.
<br>
![ClickBlock](https://github.com/user-attachments/assets/b2606ed2-8036-494e-b99b-c00610312a04)
### 💛 Click
Triggered when the radar chart is clicked.

![PointClickBlock](https://github.com/user-attachments/assets/89fcd070-d261-4ac3-b894-6f8cfb0a7351)
### 💛 PointClick
Triggered when a data point is clicked.

| Parameter | Type
| - | - |
| index | number

![AnimationStartBlock](https://github.com/user-attachments/assets/7b3f7261-7cdc-462f-ab66-3aca229977be)
### 💛 AnimationStart
Triggered when the chart animation starts.

![AnimationEndBlock](https://github.com/user-attachments/assets/3569d535-f528-40ca-8b77-dcc2d29afd55)
### 💛 AnimationEnd
Triggered when the chart animation ends.

![DataChangedBlock](https://github.com/user-attachments/assets/4511eb61-84c5-4269-84c6-42eae5f73764)
### 💛 DataChanged
Triggered when the chart data is updated.

![TitleClickBlock](https://github.com/user-attachments/assets/6528ddb6-88fe-4a92-8d2a-cbafc57d4a69)
### 💛 TitleClick
Triggered when a title is clicked.

| Parameter | Type
| - | - |
| index | number

![RegionClickBlock](https://github.com/user-attachments/assets/689392f1-0844-4927-8695-5b40e63e18d2)
### 💛 RegionClick
Triggered when a region is clicked.

| Parameter | Type
| - | - |
| index | number

## <kbd>Methods:</kbd>
**XChart** has total 3 methods.
<br>
![CreateBlock](https://github.com/user-attachments/assets/f0afc293-b34e-49b3-a3b5-b563d19e7f7e)
### 💜 Create
Creates a radar chart inside the specified arrangement. The arrangement must be a HorizontalArrangement or VerticalArrangement component.

| Parameter | Type
| - | - |
| arrangement | component

![SetDrawablesBlock](https://github.com/user-attachments/assets/4bafc40c-933f-4ce0-8da7-24fc68af055d)
### 💜 SetDrawables
Adds icon drawables to each vertex of the radar chart. Provide a list of drawable resource IDs.

| Parameter | Type
| - | - |
| drawablesList | list

![SetRegionShaderConfigBlock](https://github.com/user-attachments/assets/e0028a2f-cdd4-4823-8d4a-4e96626366d7)
### 💜 SetRegionShaderConfig
Configures a custom gradient shader for regions. Provide lists of colors and position values (0.0-1.0).

| Parameter | Type
| - | - |
| colorsList | list
| positionsList | list

## <kbd>Setters:</kbd>
**XChart** has total 33 setter properties.
<br>
![SetPercentsBlock](https://github.com/user-attachments/assets/015f3522-328d-4318-893e-1f4c5f302828)
### 💚 SetPercents
Sets the values for each data point as percentages between 0.0 and 1.0. The list length must match the number of sides.

* Input type: `list`

![SetTitlesBlock](https://github.com/user-attachments/assets/ec36e199-beb3-4b1e-876e-3c7d51e55bb5)
### 💚 SetTitles
Sets the label text for each vertex of the radar chart. The list length must match the number of sides.

* Input type: `list`

![SetValuesBlock](https://github.com/user-attachments/assets/0ec70732-9da1-45d5-83cf-bdb27f730a53)
### 💚 SetValues
Sets additional text values to display below each title. Useful for showing exact numbers or labels.

* Input type: `list`

![SetColorsBlock](https://github.com/user-attachments/assets/8456de9d-8b90-44c6-bce3-8dc94efa335f)
### 💚 SetColors
Sets custom colors for each region of the radar chart. Provide a list of color values in decimal format.

* Input type: `list`

![SetCountBlock](https://github.com/user-attachments/assets/f0575649-90c7-417c-a466-fb25be1ee3a4)
### 💚 SetCount
Sets the number of vertices (sides) for the radar chart. This determines how many data points can be displayed.

* Input type: `number`

![SetLayerCountBlock](https://github.com/user-attachments/assets/59c12a9b-f61a-4f44-9efb-3f76778d9b9f)
### 💚 SetLayerCount
Sets the number of concentric layers in the radar chart background. These create the grid effect.

* Input type: `number`

![SetDrawableSizeBlock](https://github.com/user-attachments/assets/2a3f7210-6db8-44bf-94ee-d013b3b4217d)
### 💚 SetDrawableSize
Sets the size of the icon drawables in pixels at each vertex.

* Input type: `number`

![SetDrawablePaddingBlock](https://github.com/user-attachments/assets/7857f817-a01d-46af-b9d4-105536045fad)
### 💚 SetDrawablePadding
Sets the padding between icon drawables and their labels in pixels.

* Input type: `number`

![SetDescPaddingBlock](https://github.com/user-attachments/assets/d1bcdf58-228b-4cff-9e09-00da0ca69165)
### 💚 SetDescPadding
Sets the padding for descriptions/labels around the chart in pixels.

* Input type: `number`

![SetTitleSizeBlock](https://github.com/user-attachments/assets/b076f0c6-76b3-41f3-9d76-4bf00b01f5db)
### 💚 SetTitleSize
Sets the font size for vertex titles in pixels.

* Input type: `number`

![SetDataSizeBlock](https://github.com/user-attachments/assets/4f569195-fae9-4909-b036-984724e621d2)
### 💚 SetDataSize
Sets the font size for data values in pixels.

* Input type: `number`

![SetRadarPercentBlock](https://github.com/user-attachments/assets/4b5c84f3-3956-41c9-9990-6ba17293737e)
### 💚 SetRadarPercent
Sets the size of the radar chart relative to its container (0.0-1.0). Example: 0.8 means 80% of container size.

* Input type: `number`

![SetStartColorBlock](https://github.com/user-attachments/assets/17e14430-d987-4ced-8ae6-320ac13cb22a)
### 💚 SetStartColor
Sets the starting color for gradient effects. Use decimal color values.

* Input type: `number`

![SetEndColorBlock](https://github.com/user-attachments/assets/c9ef2cb2-651a-4354-86b4-38fdfbfa2785)
### 💚 SetEndColor
Sets the ending color for gradient effects. Use decimal color values.

* Input type: `number`

![SetEnabledAnimationBlock](https://github.com/user-attachments/assets/fb73b17b-5f7b-440c-960f-c21a6f867c86)
### 💚 SetEnabledAnimation
Enables or disables animation effects when the chart updates.

* Input type: `boolean`

![SetEnabledShowPointBlock](https://github.com/user-attachments/assets/20ef20cf-8347-481c-878f-090ea902d272)
### 💚 SetEnabledShowPoint
Enables or disables the display of points at each vertex of the chart.

* Input type: `boolean`

![SetCobwebColorBlock](https://github.com/user-attachments/assets/d3ae02dc-a2ac-4ef6-92e3-375ea6c8d1df)
### 💚 SetCobwebColor
Sets the color of the background grid lines (cobweb). Use decimal color values.

* Input type: `number`

![SetLineColorBlock](https://github.com/user-attachments/assets/7cc66456-0dee-4b72-9020-fc8fc0ea1a6e)
### 💚 SetLineColor
Sets the color of the data lines that connect the vertices. Use decimal color values.

* Input type: `number`

![SetDataColorBlock](https://github.com/user-attachments/assets/72a52bb2-e0ef-469a-9663-945ae2362024)
### 💚 SetDataColor
Sets the color of the data value text. Use decimal color values.

* Input type: `number`

![SetTitleColorBlock](https://github.com/user-attachments/assets/67a996e8-567d-45e0-8912-5d70d0d64fb5)
### 💚 SetTitleColor
Sets the color of the title text at each vertex. Use decimal color values.

* Input type: `number`

![SetPointColorBlock](https://github.com/user-attachments/assets/7da13b13-a20a-43c4-8e30-db341aa2ce4a)
### 💚 SetPointColor
Sets the color of the vertex points. Use decimal color values.

* Input type: `number`
* 
![SetPointRadiusBlock](https://github.com/user-attachments/assets/1b0b4b5c-736f-45eb-8448-d574848e17e7)
### 💚 SetPointRadius
Sets the radius of the vertex points in pixels.

* Input type: `number`

![SetEnabledBorderBlock](https://github.com/user-attachments/assets/17cc8f25-66ea-4537-9a6d-c35529968715)
### 💚 SetEnabledBorder
Enables or disables the border around the entire chart.

* Input type: `boolean`

![SetBorderColorBlock](https://github.com/user-attachments/assets/b04a9ce1-1a26-469c-a1d4-225a4bef845e)
### 💚 SetBorderColor
Sets the color of the chart's border. Use decimal color values.

* Input type: `number`

![SetBoundaryWidthBlock](https://github.com/user-attachments/assets/c52824c2-0d73-416b-bd36-7177313484ff)
### 💚 SetBoundaryWidth
Sets the width of the chart's border in pixels.

* Input type: `number`

![SetEnabledPolygonBlock](https://github.com/user-attachments/assets/1022fd2b-b635-4861-971e-4034bebc876e)
### 💚 SetEnabledPolygon
Enables or disables the polygon shape connecting the data points.

* Input type: `boolean`

![SetCircleBlock](https://github.com/user-attachments/assets/ac6d79e9-a167-4076-bb86-3e2b32c69cdb)
### 💚 SetCircle
Sets whether the chart should be circular (true) or polygonal (false).

* Input type: `boolean`

![SetEnabledShadeBlock](https://github.com/user-attachments/assets/b44da137-be8b-44d6-8543-a431fba58719)
### 💚 SetEnabledShade
Enables or disables the shading effect inside the data polygon.

* Input type: `boolean`

![SetEnabledRadiusBlock](https://github.com/user-attachments/assets/4542fb2a-1744-4653-aa49-b26a9d93d094)
### 💚 SetEnabledRadius
Enables or disables the lines extending from the center to each vertex.

* Input type: `boolean`

![SetEnabledTextBlock](https://github.com/user-attachments/assets/35304159-c4c4-440d-8896-180c48dc3a73)
### 💚 SetEnabledText
Enables or disables all text labels (titles and values).

* Input type: `boolean`

![SetSingleColorBlock](https://github.com/user-attachments/assets/615b1b81-8a9f-4cc4-8178-e46017a80a75)
### 💚 SetSingleColor
Sets a single color for all regions of the chart. Use decimal color values.

* Input type: `number`

![SetEnabledRegionShaderBlock](https://github.com/user-attachments/assets/1d056a84-257b-4106-9092-c1f00ec7b2c7)
### 💚 SetEnabledRegionShader
Enables or disables the custom gradient shader effect for regions.

* Input type: `boolean`

![LoadAnimationBlock](https://github.com/user-attachments/assets/5cc28d1d-7720-4cde-8f1e-b738ded032b2)
### 💚 LoadAnimation
Reloads the chart with or without animation effects.

* Input type: `boolean`

## <kbd>Getters:</kbd>
**XChart** has total 27 getter properties.

![CountBlock](https://github.com/user-attachments/assets/a6b0375d-ce5b-42d6-a64c-53cc5694ebd6)
### 🟢 Count
Gets the current number of vertices (sides) in the radar chart.

* Return type: `number`

![LayerCountBlock](https://github.com/user-attachments/assets/d58e9ae5-4b17-4e76-ab13-c1a206c305d8)
### 🟢 LayerCount
Gets the current number of concentric layers in the chart.

* Return type: `number`

![DrawableSizeBlock](https://github.com/user-attachments/assets/d218d8ce-524d-46ec-ab3c-f2651142e4b0)
### 🟢 DrawableSize
Gets the current drawable size in pixels.

* Return type: `number`
* 
![DrawablePaddingBlock](https://github.com/user-attachments/assets/f7432007-507f-48b7-9cd5-57e8d84d66dc)
### 🟢 DrawablePadding
Gets the current drawable padding in pixels.

* Return type: `number`

![DescPaddingBlock](https://github.com/user-attachments/assets/9fa59a3a-6d7a-4de7-a653-44638d3470b9)
### 🟢 DescPadding
Gets the current description padding in pixels.

* Return type: `number`

![TitleSizeBlock](https://github.com/user-attachments/assets/8f75742a-5642-40c6-ab27-5d8fb3537928)
### 🟢 TitleSize
Gets the current title text size in pixels.

* Return type: `number`

![DataSizeBlock](https://github.com/user-attachments/assets/53cb694a-190d-49b7-8e34-edeea2f20f24)
### 🟢 DataSize
Gets the current data text size in pixels.

* Return type: `number`

![RadarPercentBlock](https://github.com/user-attachments/assets/9a195372-d119-4f98-977c-94d107cea0d1)
### 🟢 RadarPercent
Gets the current radar chart size percentage (0.0-1.0).

* Return type: `number`

![StartColorBlock](https://github.com/user-attachments/assets/48da6c7c-9c3f-4383-bb86-58e30a4afb2b)
### 🟢 StartColor
Gets the current start color value.

* Return type: `number`

### 🟢 EndColor
Gets the current end color value.

* Return type: `number`

![EnabledAnimationBlock](https://github.com/user-attachments/assets/a413c65b-f61d-4200-9ee4-d80feb24a045)
### 🟢 EnabledAnimation
Checks if animation is currently enabled.

* Return type: `boolean`

![EnabledShowPointBlock](https://github.com/user-attachments/assets/267defb5-2541-4892-bac5-cfc4f2f4e77f)
### 🟢 EnabledShowPoint
Checks if points are currently shown.

* Return type: `boolean`

![CobwebColorBlock](https://github.com/user-attachments/assets/19569b00-366d-460e-bb4a-434e3ee53747)
### 🟢 CobwebColor
Gets the current cobweb color value.

* Return type: `number`

![LineColorBlock](https://github.com/user-attachments/assets/69cc23bc-2a4d-4817-b9f9-e58ea8968f63)
### 🟢 LineColor
Gets the current line color value.

* Return type: `number`

![DataColorBlock](https://github.com/user-attachments/assets/6d077ea4-cce1-4806-b313-3e1bd24ed67b)
### 🟢 DataColor
Gets the current data color value.

* Return type: `number`

![TitleColorBlock](https://github.com/user-attachments/assets/4b30c486-c95d-454e-8601-684f2680b7c4)
### 🟢 TitleColor
Gets the current title color value.

* Return type: `number`

![PointColorBlock](https://github.com/user-attachments/assets/1a4d0ebe-b19b-45e3-8cf0-3e4a54989bac)
### 🟢 PointColor
Gets the current point color value.

* Return type: `number`

![PointRadiusBlock](https://github.com/user-attachments/assets/7bdf528c-03d5-4522-a69e-a2ab14816442)
### 🟢 PointRadius
Gets the current point radius in pixels.

* Return type: `number`

![EnabledBorderBlock](https://github.com/user-attachments/assets/d8251088-04cd-4a92-82f1-5353d060de73)
### 🟢 EnabledBorder
Checks if border is currently enabled.

* Return type: `boolean`

![BorderColorBlock](https://github.com/user-attachments/assets/1b8794a9-ddfd-4f78-bbdb-216946010786)
### 🟢 BorderColor
Gets the current border color value.

* Return type: `number`

![BoundaryWidthBlock](https://github.com/user-attachments/assets/46cac0a7-82bb-49b9-9955-51567688a03f)
### 🟢 BoundaryWidth
Gets the current boundary width in pixels.

* Return type: `number`

![EnabledPolygonBlock](https://github.com/user-attachments/assets/e501c6eb-0733-4f2a-b6eb-33984808efcf)
### 🟢 EnabledPolygon
Checks if polygon is currently enabled.

* Return type: `boolean`

![CircleBlock](https://github.com/user-attachments/assets/a9630639-7cba-4ea6-b605-2efdbd25fbb7)
### 🟢 Circle
Checks if circular shape is currently enabled.

* Return type: `boolean`

![EnabledShadeBlock](https://github.com/user-attachments/assets/f14138ea-f37f-43f4-84d6-c13bc75ecf81)
### 🟢 EnabledShade
Checks if shade effect is currently enabled.

* Return type: `boolean`

![EnabledRadiusBlock](https://github.com/user-attachments/assets/cca3bf27-956f-4516-8657-83e2b792288b)
### 🟢 EnabledRadius
Checks if radius lines are currently enabled.

* Return type: `boolean`

![EnabledTextBlock](https://github.com/user-attachments/assets/143d8579-3d10-4086-91a8-92f702d46b44)
### 🟢 EnabledText
Checks if text labels are currently enabled.

* Return type: `boolean`

![SingleColorBlock](https://github.com/user-attachments/assets/c0cbefec-e719-4127-9aa4-1b96d420170d)
### 🟢 SingleColor
Gets the current single color value.

* Return type: `number`

### Thanks
    TechHamara
    

