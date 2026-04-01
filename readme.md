### Folder Structure


<table>
<tr>

<td width="20%" valign="top">

<h3 align="center">📁 src</h3>

<pre>
assets/

components/
  carousel/
    ImageCarousel.jsx
    ImageCarousel.module.css

  editor/

  layouts/
    Footer.jsx
    MainLayout.jsx
    Navbar.jsx

  pages/
    auth/
      AuthCallback.jsx
      Login.jsx
      OAuth.jsx
      SignUp.jsx

    Contact.jsx
    Documentation.jsx
    Feature.jsx
    Home.jsx
    Layouts.jsx
    MyLayouts.jsx
    Preview.jsx
    Pricing.jsx
    Profile.jsx
    Status.jsx

  utils/
    ScrollToTop.jsx

routes/
  AppRoutes.jsx

stadium/

utils/
  layoutIdGenerator.js
  seatIdGenerator.jsx

App.jsx
firebase.js
index.css
main.jsx
supabaseClient.js
userSlice.js
</pre>

</td>

<td width="20%" valign="top">

<h3 align="center">🎨 editor (UI)</h3>

<pre>
Editor.jsx
EditorCanvas.jsx
Toolbar.jsx
TemplatesPanel.jsx
PropertiesPanel.jsx
SelectedSeatSpacingControl.jsx
ArcFloatingEditor.jsx

canvas/
  CanvasStage.jsx
  SeatComponent.jsx
  TextComponent.jsx
  layers/

components/
  EditorChrome.jsx
  EditorOverlays.jsx
  LayoutModal.jsx
  SeatLegend.jsx
  SeatTypeModal.jsx
  SeatTypeSelector.jsx
  ShapeTypeSelector.jsx
</pre>

</td>

<td width="20%" valign="top">

<h3 align="center">🎨 editor (engine)</h3>

<pre>
domain/
  elementTypes.jsx
  rowModel.jsx
  seatModel.jsx
  textModel.jsx

services/
  arcService.js
  layoutService.js
  rowService.js
  seatService.js
  shapeService.js

layout-engine/
  coachConfig.js
  generateCoachLayout.js
  trainAdapter.js

serializer/
  layoutSerializer.jsx

utils/
  mathUtils.jsx
</pre>

</td>

<td width="20%" valign="top">

<h3 align="center">🎨 editor (state)</h3>

<pre>
store/
  editorStore.jsx
  slices/
    canvasSlice.js
    elementSlice.js
    historySlice.js
    selectionSlice.js
    toolsSlice.js

hooks/
  useCanvasEvents.jsx
  useCanvasZoom.jsx
  useCursor.jsx
  useEditorPersistence.js
  useHistory.jsx
  useKeyboardShortcuts.jsx
  useSeatSelection.jsx
  useToolHandler.jsx
  useViewport.jsx

tools/
  ToolManager.jsx
  arcTool.jsx
  eraserTool.jsx
  rowTool.jsx
  seatTool.jsx
  selectTool.jsx
  textTool.jsx
</pre>

</td>

<td width="20%" valign="top">

<h3 align="center">🏟️ stadium</h3>

<pre>
components/
  KeyboardShortcutsHelp.jsx
  Minimap.jsx
  SeatDetailsPanel.jsx
  SectionConfigPanel.jsx
  SectionDirectoryItem.jsx
  SelectedSectionPanel.jsx
  StadiumEditorChrome.jsx
  StadiumTemplates.jsx
  ToolRailButton.jsx

hooks/
  useSectionDrag.js
  useStadiumExport.js
  useStadiumHistory.js
  useStadiumPersistence.js

StadiumCanvas.jsx
StadiumEditor.jsx
StadiumVenue.jsx
sectionLayout.js
SeatRenderer.jsx
SectionRenderer.jsx
geometry.js
useVirtualization.js
useZoom.js
</pre>

</td>

</tr>
</table>
