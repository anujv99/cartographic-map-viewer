### Cartographic Map Viewer

##### TODO

- [x] Adjust buffer dimensions when maximizing.
- [x] Add smooth movement and zoom to the ortographic camera.
- [x] crash when change background color in edit mode
- [x] crash when loading corrupt file, please ignore file if it gives error
- [x] the camera moves when you click outside the viewport (in any menu)
- [x] in menu options are missing: change line and point color, and point size
- [x] geojson loader is ignoring columns containing null data
- [x] rows of LUG layer attributes cannot be selected in table
- [ ] Fix error, the camera malfunctions when zooming closely, and the FPS drops.
- [x] <s>Fix error, the add vertex and move vertex functions work badly, when zooming closely</s>. (same as above, it's the problem with camera, the world position returned by the camera is losing precision at lower values, fixing the above will probably fix this too)
- [x] in layer menu drag and drop works badly, move the first layer to see the error, it goes to the last position, I know it is still in process
- [ ] don't hide other polygons in edit mode
- [x] in editor mode the lines are drawn above the point, it must be the opposite
- [ ] please allow loader to recognize geojson files with header information
- [x] clear selection of a layer when selecting a different layer (now the selection is kept in memory)
- [x] clear the attribute filtering when select a different layer (now the filtering is kept in memory)
- [ ] <s>please remove the console window and move it to an ingui log window so that there is only one general window for the app</s> (will log to file instead because logs should not be dependent on ImGui, if ImGui fails then there won't be any log and it will be a nightmare to debug)
- [ ] the content browser does not allow browsing through other hard drives
- [ ] add support to create layer of points, multipoints, lines and multilines in the geojson loader
- [ ] make the table filter the attributes every time you make a new selection, as long as the "filter selected" checkbox is activated
