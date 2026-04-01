<table>
<tr>

<td width="25%" valign="top">

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

<td width="25%" valign="top">

<h3 align="center">🎨 editor (core)</h3>

<pre>
Editor.jsx
EditorCanvas.jsx
ArcFloatingEditor.jsx
ArcTool.jsx
PropertiesPanel.jsx
TemplatesPanel.jsx
Toolbar.jsx
SelectedSeatSpacingControl.jsx

canvas/
  CanvasStage.jsx
  SeatComponent.jsx
  TextComponent.jsx
  layers/
    GridLayer.jsx
    SeatLayer.jsx
    SelectionLayer.jsx
    ShapeLayer.jsx
    TextLayer.jsx

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

<td width="25%" valign="top">

<h3 align="center">🎨 editor (logic)</h3>

<pre>
components/
  properties/
    PropertiesPanelPrimitives.jsx
    PropertiesSeatSection.jsx
    PropertiesShapeSection.jsx
    PropertiesTextSection.jsx

constants/
  SeatTypes.jsx
  tools.jsx

domain/
  elementTypes.jsx
  rowModel.jsx
  seatModel.jsx
  textModel.jsx

history/
  UndoRedoControls.jsx

hooks/
  useCanvasEvents.jsx
  useCanvasZoom.jsx
  useCursor.jsx
  useEditorPersistence.js
  useHistory.jsx
  useKeyboardShortcuts.jsx
  usePreviewElements.jsx
  useRenderedElements.jsx
  useResizeHandle.jsx
  useSeatSelection.jsx
  useToolHandler.jsx
  useViewport.jsx

layout-engine/
  coachConfig.js
  generateCoachLayout.js
  trainAdapter.js

serializer/
  layoutSerializer.jsx

services/
  arcService.js
  layoutService.js
  rowService.js
  seatService.js
  shapeService.js

store/
  editorStore.jsx
  slices/
    canvasSlice.js
    elementSlice.js
    elementSlice.arc.js
    elementSlice.train.js
    elementSlice.transforms.js
    historySlice.js
    seatHelpers.js
    selectionSlice.js
    templateGenerators.js
    toolsSlice.js

tools/
  ToolManager.jsx
  arcTool.jsx
  eraserTool.jsx
  rowTool.jsx
  seatTool.jsx
  selectTool.jsx
  textTool.jsx

utils/
  mathUtils.jsx
</pre>

</td>

<td width="25%" valign="top">

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

geometry.js
SeatRenderer.jsx
sectionLayout.js
SectionRenderer.jsx
StadiumCanvas.jsx
StadiumEditor.jsx
stadiumEditorHelpers.js
StadiumErrorBoundary.jsx
StadiumSectionEditor.jsx
stadiumVenue.js
StadiumVenue.jsx
useVirtualization.js
useZoom.js
</pre>

</td>

</tr>
</table>
