## Gephi 0.9.5 (May 3 2022)

[Download Gephi 0.9.5](https://github.com/gephi/gephi/releases/tag/v0.9.5)

### Bugfixes

- Deleting nodes results in program freezing and not responding [#2485](https://github.com/gephi/gephi/issues/2485)
- Unable to set range for the Partition Count filter on Component ID [#2493](https://github.com/gephi/gephi/issues/2493)
- NullPointerException in Preview StringBuilder [#2495](https://github.com/gephi/gephi/issues/2495)
- ArrayIndexOutOfBoundsException: Index -1 out of bounds for length 11 [#2498](https://github.com/gephi/gephi/issues/2498)
- NullPointerException in ImporterSpreadsheetCSV.autoDetectFieldDelimiter [#2499](https://github.com/gephi/gephi/issues/2499)
- ReportPanel: ArrayIndexOutOfBoundsException: Index 0 out of bounds for length 0 [#2500](https://github.com/gephi/gephi/issues/2500)
- IllegalArgumentException: The object class does not match with the column type (java.lang.Integer) [#2509](https://github.com/gephi/gephi/issues/2509)
- Display exception thrown in import in a report [#2516](https://github.com/gephi/gephi/issues/2516)

### Miscellaneous
- Windows installation in non-administrative mode [#2507](https://github.com/gephi/gephi/issues/2507)
- Add Romanian as supported localization 🇷🇴 [#2494](https://github.com/gephi/gephi/issues/2494)

## Gephi 0.9.4 (Apr 16 2022)

[Download Gephi 0.9.4](https://github.com/gephi/gephi/releases/tag/v0.9.4)

### Bugfixes

- No file listed in the Open... dialog box, Mac OS Big Sur [#2467](https://github.com/gephi/gephi/issues/2467)
- NullPointerException from TimelineControllerImpl.setInterval [#2471](https://github.com/gephi/gephi/issues/2471)
- NullPointerException in ImportContainerImpl.isEdgeDirected [#2472](https://github.com/gephi/gephi/issues/2472)
- NullPointerException in IndexImpl.values [#2473](https://github.com/gephi/gephi/issues/2473)
- Appearance IllegalArgumentException: The view doesn't exist [#2487](https://github.com/gephi/gephi/issues/2487)
- Visualization IllegalArgumentException: The view doesn't exist [#2488](https://github.com/gephi/gephi/issues/2488)
- IllegalArgumentException: The column does not belong to the right column store [#2489](https://github.com/gephi/gephi/issues/2489)
- Combining gexf files hangs in 093 [#2476](https://github.com/gephi/gephi/issues/2476)

### Miscellaneous
- Icon for MacOS Big Sur/Monterey [#2480](https://github.com/gephi/gephi/issues/2480)

## Gephi 0.9.3 (Apr 5 2022)

[Download Gephi 0.9.3](https://github.com/gephi/gephi/releases/tag/v0.9.3)

### New features
- Added _Statistical Inference_ community detection algorithm, a more advanced alternative to Modularity [#2431](https://github.com/gephi/gephi/pull/2431)
- Windows and Linux versions now also embed JRE so that it isn't needed anymore to install Java separately [#2336](https://github.com/gephi/gephi/issues/2336)
- [FlatLaf](https://www.formdev.com/flatlaf/) look and feel is now used by default on all platforms [#2415](https://github.com/gephi/gephi/issues/2415)
- Appearance attributes like colors used in partition are now saved in the project [#1861](https://github.com/gephi/gephi/issues/1861)
- Last Export settings are now saved as Preferences so they persist between session [#1790](https://github.com/gephi/gephi/issues/1790)

### Bugfixes
- Improve UI to better suit HighDPI displays [#2332](https://github.com/gephi/gephi/issues/2332)
- Graph Toolbar items overlap on smaller screen sizes [#765](https://github.com/gephi/gephi/issues/765)
- Some layouts act on settled nodes [#2385](https://github.com/gephi/gephi/issues/2385)
- Ignoring GraphML desc standard tags [#2030](https://github.com/gephi/gephi/issues/2030)
- java.util.MissingResourceException gephi version 0.9.2 [#2063](https://github.com/gephi/gephi/issues/2063)
- NullpointerException on filtering datalab columns that have empty attribute values [#2015](https://github.com/gephi/gephi/issues/2015)
- Leaving "Create missing nodes" unchecked does not have the desired effect [#1878](https://github.com/gephi/gephi/issues/1878)
- 'Interval' not copied to new workspace [#1988](https://github.com/gephi/gephi/issues/1988)
- CSV Edges file not importing because Gephi does not detect Source and Target columns [#2178](https://github.com/gephi/gephi/issues/2178)
- ArrayIndexOutOfBoundsException on when deleting nodes [#1623](https://github.com/gephi/gephi/issues/1623)
- No mode indicator in Appearance panel in Gephic Mac 0.9.2 [#2098](https://github.com/gephi/gephi/issues/2098)
- Neighbors Network filter freezes with max depth [#2099](https://github.com/gephi/gephi/issues/2099)
- Unable to import a large file [#1841](https://github.com/gephi/gephi/issues/1841)
- Update crash reporter and make it GDPR compliant [#2340](https://github.com/gephi/gephi/issues/2340)
- ClassCastException: org.gephi.graph.api.types.TimestampSet cannot be cast to org.gephi.graph.api.types.TimeMap [#2297](https://github.com/gephi/gephi/issues/2297)
- Support INF, -INF in GEXF for double-type ±∞ values [#2158](https://github.com/gephi/gephi/issues/2158)
- Node betweenness is negative for big graphs when normalized [#2139](https://github.com/gephi/gephi/issues/2139)
- generatePalette is wrong [#2112](https://github.com/gephi/gephi/issues/2112)
- Loading gexf file with 0-weighted edges crashes import [#1945](https://github.com/gephi/gephi/issues/1945)
- Crash when exporting VNA graph file [#1909](https://github.com/gephi/gephi/issues/1909)
- Import CSV error edges [#1848](https://github.com/gephi/gephi/issues/1848)
- Import of graphml still confuses d3 and label fields [#1840](https://github.com/gephi/gephi/issues/1840)
- Add support of Byte Order Mark to CSV parser [#1815](https://github.com/gephi/gephi/issues/1840)
- CSV files are no longer imported correctly when double quotes inside strings are delimited with backslashes [#1812](https://github.com/gephi/gephi/issues/1812)
- NullPointerException on EdgeTypeFilter [#1811](https://github.com/gephi/gephi/issues/1811)
- GephiFormatException can cause ArrayIndexOutOfBoundsException: 0 [#1810](https://github.com/gephi/gephi/issues/1810)
- Exception with no-merge strategy in some cases. Incompatible edge should not be created [#1802](https://github.com/gephi/gephi/issues/1802)
- NullPointerException: The fileObject parameter cannot be null [#1789](https://github.com/gephi/gephi/issues/1789)
- GephiFormatException: Gephi failed saving the project.[ #1788](https://github.com/gephi/gephi/issues/1788)
- Edge labels not retained on graphml export [#1516](https://github.com/gephi/gephi/issues/1516)
- Unhide toggle global/local ranking button [#2146](https://github.com/gephi/gephi/issues/2146)
- Unwanted and inconsistent behavior for "node size" [#2224](https://github.com/gephi/gephi/issues/2224)
- Infinite repulsion in ForceAtlas with negative weights [#1714](https://github.com/gephi/gephi/issues/1714)
- Citation for PageRank algorithm [#1944](https://github.com/gephi/gephi/issues/1944)
- Dynamic attributes for dynamic network not properly merged with multiple files [#1885](https://github.com/gephi/gephi/issues/1885)
- Add 'postProcess()' method to Preview's Renderer SPI [#1490](https://github.com/gephi/gephi/issues/1490)
- Changes in labels not rendered in preview mode [#1877](https://github.com/gephi/gephi/issues/1877)
- Sum edges merge strategy gives surprising results [#2038](https://github.com/gephi/gephi/issues/2038)
- Use timezone in GEXF import, export and Create time interval in Data Laboratory [#1864](https://github.com/gephi/gephi/issues/1864)
- Overview viewport too small [#1518](https://github.com/gephi/gephi/issues/1518)
- Wrong edge coloring of selected nodes for directed graphs [#2259](https://github.com/gephi/gephi/issues/2259)
- Modularity index groups are allways 0-index based. [#1977](https://github.com/gephi/gephi/issues/1977)
- Workspace tabs panel is missing when opening project file [#1827](https://github.com/gephi/gephi/issues/1827)
- Regression setting node color by partition [#1838](https://github.com/gephi/gephi/issues/1838)
- Not all selected nodes/edges are moved/copied to new workspace [#2088](https://github.com/gephi/gephi/issues/2088)

### API Changes
- Graph API
  - Add `getEdges(int type)` to `Graph` to allow retrieval of only edges of a specific type.
  - Add `getEdgeTypeLabels(boolean)` to `GraphModel`.
  - Add min/max to `TimeSet` and `Element.getTimeBounds()`.
  - Add `Column.exists()` as new utility.
  - Add `GraphLock` to the API in `Graph` to expose locking states.
  - Make `Table` a `Collection` of `Column`.
  - Add new method `Column.isDynamicAttribute()`.
  - Add `toSet()` in addition of `toCollection()` to element iterables.
  - Add new `Table.countColumns(Origin)` method.
  - Add `getElementIndex()` methods to `GraphModel` when providing a `Table`.
  - Add `isNodeTable()` and `isEdgeTable()` methods to `Table`.
- Appearance API (under development)
  - `Partition` and `Ranking` now always receive the `Graph` as parameter for all methods that do need access to the underlying index to facilitate local scale support.
  - Add `getColumn()` to `Ranking` so it aligns with `Partition`.
  - Add `getNormalizedValue()` to `Ranking` to more easily retrieve the normalised value.
  - `Partition` now has a static `DEFAULT_COLOR` when the color is not found for a given value.
  - Removed `Partition.setColors()` as it was prone to confusion.
  - Add `transformAll(Iterable<? extends Element>)` to `Function`.
  - Split `isLocalScale()` into `isRankingLocalScale()` and `isPartitionLocalScale()` in `AppearanceModel`.
  - Make `Function` getters in `AppearanceModel` independent from `Graph` as this should be handled automatically based on the local/global state.
- Preview API
  - A `postProcess()` method has been added to the `Renderer` SPI to allow customization once all items have been rendered.

## Gephi 0.9.2 (Sep 24 2017)

[Download Gephi 0.9.2](https://github.com/gephi/gephi/releases/tag/v0.9.2)

### New features highlight
- New CSV/Spreadsheet importer migrated to Import API. More user friendly, autodetects imported columns types and data format. Integrated with the rest of file importer formats through import report. Now supports importing excel files.

### Other new or improved features
- Add support for MS SQL Server ([#1648](https://github.com/gephi/gephi/issues/1648))
- Add option for minimum edge width in preview mode ([#1568](https://github.com/gephi/gephi/issues/1568))
- Add support for edge kind in spreadsheet import/export ([#1248](https://github.com/gephi/gephi/issues/1248))
- Suggestions: improvements to spreadsheet import ([#532](https://github.com/gephi/gephi/issues/532))
- Feature request: remember last save location (dir) ([#1726](https://github.com/gephi/gephi/issues/1726))
- Add column id tooltip to data laboratory column headers ([#1711](https://github.com/gephi/gephi/issues/1711))

### Bugfixes
- Impossible to rename an Operator filter ([#329](https://github.com/gephi/gephi/issues/329))
- BOM missing in exported GEXF and .Gephi ([#474](https://github.com/gephi/gephi/issues/474))
- nodes position to NaN on applied layout ([#603](https://github.com/gephi/gephi/issues/603))
- Spreadsheet import should be available in File > Open ([#611](https://github.com/gephi/gephi/issues/611))
- Modularity Calculation Throws Exception On Empty Graph ([#713](https://github.com/gephi/gephi/issues/713))
- svg class ids are invalid ([#770](https://github.com/gephi/gephi/issues/770))
- Clearly present the range bound numbers as editable on Filter UI ([#838](https://github.com/gephi/gephi/issues/838))
- Scaling factors for expension/contraction ([#860](https://github.com/gephi/gephi/issues/860))
- Direct import of Excel adjacency matrix format data ([#1143](https://github.com/gephi/gephi/issues/1143))
- Gephi XML parser fails when encountering U+0001 ([#1164](https://github.com/gephi/gephi/issues/1164))
- Conditions should not unconditionally evaluate to "TRUE" or to "FALSE" ([#1232](https://github.com/gephi/gephi/issues/1232))
- Add support for edge kind in spreadsheet import/export ([#1248](https://github.com/gephi/gephi/issues/1248))
- multiple edges won't be merged ([#1251](https://github.com/gephi/gephi/issues/1251))
- Migrate spreadsheet importer to Import API ([#1282](https://github.com/gephi/gephi/issues/1282))
- Feature/db ignore unknown columns refactoring ([#1284](https://github.com/gephi/gephi/issues/1284))
- HITS centrality ([#1290](https://github.com/gephi/gephi/issues/1290))
- No Suitable driver found for jdbc:mysql:// ([#1317](https://github.com/gephi/gephi/issues/1317))
- Importing Adjacency Matrices ([#1372](https://github.com/gephi/gephi/issues/1372))
- Gephi 0.9 bug saving projects that are in Geo Layout? ([#1373](https://github.com/gephi/gephi/issues/1373))
- Exception on ranking with column with null values ([#1387](https://github.com/gephi/gephi/issues/1387))
- Stuck on DOT import ([#1391](https://github.com/gephi/gephi/issues/1391))
- Cannot rank according to attribute data ([#1392](https://github.com/gephi/gephi/issues/1392))
- Added per-node opacity property ([#1407](https://github.com/gephi/gephi/issues/1407))
- import spreadsheet (csv) The id class does not match with the expected type ([#1418](https://github.com/gephi/gephi/issues/1418))
- Getting null pointer error when trying to calculate modularity ([#1419](https://github.com/gephi/gephi/issues/1419))
- Error saving any dynamic network in gexf format ([#1426](https://github.com/gephi/gephi/issues/1426))
- filters and new workspace bugged ([#1428](https://github.com/gephi/gephi/issues/1428))
- csv data missing some information ([#1431](https://github.com/gephi/gephi/issues/1431))
- Duplicate statement in DirectoryChooserUI.java ([#1434](https://github.com/gephi/gephi/issues/1434))
- Duplicate statement in ExporterDL.java ([#1435](https://github.com/gephi/gephi/issues/1435))
- Java error message when running Geo Layout ([#1441](https://github.com/gephi/gephi/issues/1441))
- node size changed during gexf import ([#1445](https://github.com/gephi/gephi/issues/1445))
- Streaming Graphs Do Not Appear in Overview ([#1447](https://github.com/gephi/gephi/issues/1447))
- Suddenly not importing all of my edges ([#1454](https://github.com/gephi/gephi/issues/1454))
- Incorrect average degree for directed graphs ([#1455](https://github.com/gephi/gephi/issues/1455))
- Filter settings incorrect and causing crashes after reloading a .gephi file ([#1458](https://github.com/gephi/gephi/issues/1458))
- Node size options not available if node colour set to partition mode ([#1459](https://github.com/gephi/gephi/issues/1459))
- Spaces in header columns of edge CSV file fails to load ([#1461](https://github.com/gephi/gephi/issues/1461))
- No Suitable Driver Found for jdbc:postgresql ([#1466](https://github.com/gephi/gephi/issues/1466))
- Impossible to color arcs with a color gradient with 0.9.1 ([#1469](https://github.com/gephi/gephi/issues/1469))
- Self-loops not removed after filter>self-loop>export to new workspace ([#1471](https://github.com/gephi/gephi/issues/1471))
- Improve range slider user experience for manually setting values ([#1476](https://github.com/gephi/gephi/issues/1476))
- Import wizard 0.9.1 now showing any options. ([#1477](https://github.com/gephi/gephi/issues/1477))
- Node size by attribute issue ([#1484](https://github.com/gephi/gephi/issues/1484))
- Fix - add try/finally logic to wrap graph reentrant locks for layouts ([#1487](https://github.com/gephi/gephi/issues/1487))
- csv import error: found rows with empty source or target columns  ([#1489](https://github.com/gephi/gephi/issues/1489))
- Some label characters fade away when zooming out! ([#1494](https://github.com/gephi/gephi/issues/1494))
- Fill column with value doesn't affect visualization immediately ([#1499](https://github.com/gephi/gephi/issues/1499))
- "Partition count" filter does not work ([#1501](https://github.com/gephi/gephi/issues/1501))
- Setting Labels using GraphML ([#1502](https://github.com/gephi/gephi/issues/1502))
- Get collection of selected nodes ([#1506](https://github.com/gephi/gephi/issues/1506))
- Undirected Average Path Length Not available ([#1507](https://github.com/gephi/gephi/issues/1507))
- added getSelectedNodes in SelectionManager ([#1508](https://github.com/gephi/gephi/issues/1508))
- Filter is changed after saving file and opening again ([#1511](https://github.com/gephi/gephi/issues/1511))
- Components don't show up as variable in partition filter ([#1512](https://github.com/gephi/gephi/issues/1512))
- NullPointerException on Modularity Statistics with gexf with kind / parallel nodes. ([#1526](https://github.com/gephi/gephi/issues/1526))
- Adapt crash reporter to send data to a new service ([#1530](https://github.com/gephi/gephi/issues/1530))
- ArrayIndexOutOfBoundsException in AutoLayout.InterpolateDynamicProperty ([#1532](https://github.com/gephi/gephi/issues/1532))
- Add Edge dialog only remembers source index ([#1536](https://github.com/gephi/gephi/issues/1536))
- Wrong quantity of connected component ([#1545](https://github.com/gephi/gephi/issues/1545))
- Export from Data Laboratory overwrites existing file without warning ([#1550](https://github.com/gephi/gephi/issues/1550))
- Implement VizualizationController.selectNodes/selectEdges ([#1562](https://github.com/gephi/gephi/issues/1562))
- NPE with trying to filter by partition with a null value ([#1563](https://github.com/gephi/gephi/issues/1563))
- Partition filter doesn't work with edges ([#1564](https://github.com/gephi/gephi/issues/1564))
- GePhi freezes after successfully importing dynamic gexf file ([#1566](https://github.com/gephi/gephi/issues/1566))
- Import of GraphML: Specific attribute IDs are dismissed ([#1575](https://github.com/gephi/gephi/issues/1575))
- GraphML export: Gephi doesn't generate the id attribute on edges ([#1585](https://github.com/gephi/gephi/issues/1585))
- Proposed fix for issue #1585 ([#1586](https://github.com/gephi/gephi/issues/1586))
- GML import: '.0' always added to numeric ids ([#1588](https://github.com/gephi/gephi/issues/1588))
- inconsistency in calculating degree and weighted degree ([#1593](https://github.com/gephi/gephi/issues/1593))
- Columns aren't properly sorted in appearance ([#1604](https://github.com/gephi/gephi/issues/1604))
- NullPointerException when no attribute is selected in Ranking or Partition ([#1605](https://github.com/gephi/gephi/issues/1605))
- How to make RankingLabelSizeTransformer work? ([#1606](https://github.com/gephi/gephi/issues/1606))
- Dynamic node attribute (from csv file) causes unexpected exception ([#1607](https://github.com/gephi/gephi/issues/1607))
- Ranking min/max for uncommon types - UnsupportedOperationException: 'commlist' is not a sortable column (int[]). ([#1612](https://github.com/gephi/gephi/issues/1612))
- Exporting data tables with the automatically added [Nodes] and [Edges] tags does not work ([#1613](https://github.com/gephi/gephi/issues/1613))
- Self loop edges display ([#1619](https://github.com/gephi/gephi/issues/1619))
- Fixed typo in german translation of statistics plugin ([#1632](https://github.com/gephi/gephi/issues/1632))
- gephi 0.9.1 freezes for dynamical graphs ([#1633](https://github.com/gephi/gephi/issues/1633))
- Ranking operation not working (node color and size) ([#1636](https://github.com/gephi/gephi/issues/1636))
- taken screenshot will be overwritten ([#1640](https://github.com/gephi/gephi/issues/1640))
- Presets not working ([#1643](https://github.com/gephi/gephi/issues/1643))
- Node size by attribute not listing property ([#1650](https://github.com/gephi/gephi/issues/1650))
- Add dynamic edge attribute (weight),using csv file ([#1653](https://github.com/gephi/gephi/issues/1653))
- GraphML Importer Attribute Loading Problem ([#1656](https://github.com/gephi/gephi/issues/1656))
- Export data table with large numbers in metrics rows ([#1658](https://github.com/gephi/gephi/issues/1658))
- DNA - import .CSV (from DNA software) in GEPHI ([#1661](https://github.com/gephi/gephi/issues/1661))
- Merge CSV and Spreadsheet import ([#1662](https://github.com/gephi/gephi/issues/1662))
- StackOverflowError while using GraphStream ([#1668](https://github.com/gephi/gephi/issues/1668))
- icon pencil for "creating node" and "creating edge" should not be the same? ([#1672](https://github.com/gephi/gephi/issues/1672))
- count the average path length of directed graph ([#1683](https://github.com/gephi/gephi/issues/1683))
- v0.9.1 unable to read v0.9 gephi file ([#1691](https://github.com/gephi/gephi/issues/1691))
- Add support for excel (xls and xlsx) import ([#1699](https://github.com/gephi/gephi/issues/1699))
- Make sure all layouts + timeline work fine with dynamic weights ([#1709](https://github.com/gephi/gephi/issues/1709))
- Incorrect graph import from GraphML file ([#1719](https://github.com/gephi/gephi/issues/1719))
- Node colors fade to white regardless of background color choice ([#1728](https://github.com/gephi/gephi/issues/1728))
- Setting graph space size/borders ([#1729](https://github.com/gephi/gephi/issues/1729))
- Very Lost Newbie: Even Dynamic Graph Example (through Gephi) Doesn't Work with Timeline? ([#1730](https://github.com/gephi/gephi/issues/1730))
- ImporterDOT supports # comments ([#1739](https://github.com/gephi/gephi/issues/1739))
- Import of GEXF format rearranges order of node attributes ([#1742](https://github.com/gephi/gephi/issues/1742))
- NullPointerException on DL Ucinet Exporter when exporting as List mode ([#1746](https://github.com/gephi/gephi/issues/1746))
- Windows installer should use 64 bit exe when available ([#1748](https://github.com/gephi/gephi/issues/1748))
- Settings get stored in a specific language ([#1749](https://github.com/gephi/gephi/issues/1749))
- Cytoscape to Gephi ([#1753](https://github.com/gephi/gephi/issues/1753))
- Add full screen mode to view menu ([#1762](https://github.com/gephi/gephi/issues/1762))
- MacOS build cleanup ([#1766](https://github.com/gephi/gephi/issues/1766))
- Appearance: add partition label color transformer ([#1768](https://github.com/gephi/gephi/issues/1768))
- Fix timeline graphics ([#1771](https://github.com/gephi/gephi/issues/1771))
- Gephi freezes with specific network ([#1774](https://github.com/gephi/gephi/issues/1774))

### API Changes
- A new **optional** `FileAware` interface in `FileImporter` in `ImporterAPI`. This allows file importers to receive the file to import in a `setFile` method instead of the `setReader` method being called. If your `FileImporter` implements this interface, `setFile` will be called, and `setReader` will not be called. 

## Gephi 0.9.1 (Feb 14 2016)

[Download Gephi 0.9.1](https://github.com/gephi/gephi/releases/tag/v0.9.1)

### New features highlight

- New German localization

### Other new or improved features

- Implement new mutual edge filter ([#1312](https://github.com/gephi/gephi/issues/#1312))
- Re-add import wizard support ([#1322](https://github.com/gephi/gephi/issues/#1322))
- Merge dynamic attributes and timeset when merging parallel edges ([#1345](https://github.com/gephi/gephi/issues/#1345))
- Hide Edit Window description area ([#1354](https://github.com/gephi/gephi/issues/#1354))
- Add label properties in Edit ([#1355](https://github.com/gephi/gephi/issues/#1355))

### Bugfixes

- Filter Saved queries not saved in project files ([#123](https://github.com/gephi/gephi/issues/#123))
- Filter not applied when opening Gephi file ([#734](https://github.com/gephi/gephi/issues/#734))
- SVG, PDF export generate 'null pointer' exception ([#1239](https://github.com/gephi/gephi/issues/#1239))
- App Hangs - OS X El Capitan ([#1241](https://github.com/gephi/gephi/issues/#1241))
- Attributes not appearing in Size setting ([#1242](https://github.com/gephi/gephi/issues/#1242))
- Edge weights are not read ([#1243](https://github.com/gephi/gephi/issues/#1243))
- Data laboratory shows double precision error decimals for columns with type Float/Double ([#1245](https://github.com/gephi/gephi/issues/#1245))
- CSV import only show one node ([#1247](https://github.com/gephi/gephi/issues/#1247))
- Improvements in spreadsheet import and fix default weight when not indicated ([#1249](https://github.com/gephi/gephi/issues/#1249))
- Multiple edges won't be merged ([#1251](https://github.com/gephi/gephi/issues/#1251))
- Workspace persistence XML duplicate markup in .gephi ([#1262](https://github.com/gephi/gephi/issues/#1262))
- Partitions filters not available at start ([#1263](https://github.com/gephi/gephi/issues/#1263))
- Gexf liststring attribute type not working ([#1266](https://github.com/gephi/gephi/issues/#1266))
- Screenshot in overview: Dialog shows "Saved in {0}" ([#1271](https://github.com/gephi/gephi/issues/#1271))
- NullPointerException on SQLite import ([#1272](https://github.com/gephi/gephi/issues/#1272))
- GEXF export doesn't properly export list types ([#1279](https://github.com/gephi/gephi/issues/#1279))
- Array attributes aren't properly printed in Overview and Preview ([#1280](https://github.com/gephi/gephi/issues/#1280))
- Data laboratory - NullPointerException when switching workspaces ([#1281](https://github.com/gephi/gephi/issues/#1281))
- Data laboratory - Convert column to dynamic does not accept timestamps, only dates ([#1283](https://github.com/gephi/gephi/issues/#1283))
- Edge weights not available as a label choice ([#1287](https://github.com/gephi/gephi/issues/#1287))
- Silent fail on merge columns > create time interval ([#1288](https://github.com/gephi/gephi/issues/#1288))
- Red Roses palette generator freezes Gephi ([#1296](https://github.com/gephi/gephi/issues/#1296))
- Modularity class percentages multiplied by an additional factor of 100 ([#1297](https://github.com/gephi/gephi/issues/#1297))
- Inter and Intra edges filter raises null pointer exception (java.lang.NullPointerException)([#1298](https://github.com/gephi/gephi/issues/#1298))
- Rotation layouts both counter clockwise ([#1304](https://github.com/gephi/gephi/issues/#1304))
- Select on Overview not working 0.9 ([#1306](https://github.com/gephi/gephi/issues/#1306))
- Cannot delete a column ([#1310](https://github.com/gephi/gephi/issues/#1310))
- PNG export looses alpha value ([#1314](https://github.com/gephi/gephi/issues/#1314))
- "Set Label color to be of same color of the Object" in Overview does not work ([#1315](https://github.com/gephi/gephi/issues/#1315))
- Exception on opening project with multiple workspaces ([#1318](https://github.com/gephi/gephi/issues/#1318))
- Attributes not appearing in Appearance dropdown list ([#1319](https://github.com/gephi/gephi/issues/#1319))
- Gephi 0.9 doesn't display node attributes from a .gephi file saved by Gephi 0.8.2b ([#1320](https://github.com/gephi/gephi/issues/#1320))
- StringIndexOutOfBoundsException after Import Spreadsheet ([#1321](https://github.com/gephi/gephi/issues/#1321))
- Appearance Window hangs after setting size ([#1324](https://github.com/gephi/gephi/issues/#1324))
- Equal filter does not work with array columns ([#1331](https://github.com/gephi/gephi/issues/#1331))
- Use Interval time representation by default on new workspaces ([#1332](https://github.com/gephi/gephi/issues/#1332))
- "Convert column to dynamic" does not obey chosen time representation ([#1334](https://github.com/gephi/gephi/issues/#1334))
- Time interval graphics don't work correctly often ([#1335](https://github.com/gephi/gephi/issues/#1335))
- Error when parsing spells in gexf files ([#1337](https://github.com/gephi/gephi/issues/#1337))
- Exception when editing array types ([#1338](https://github.com/gephi/gephi/issues/#1338))
- Closeness in GraphDistance incorrect ([#1341](https://github.com/gephi/gephi/issues/#1341))
- Current time format is not respected when representing TimestampSet in data laboratory ([#1343](https://github.com/gephi/gephi/issues/#1343))
- NPE when opening dynamic graph from Data Laboratory on Mac OS X ([#1344](https://github.com/gephi/gephi/issues/#1344))
- Exception when appending parallel edges ([#1347](https://github.com/gephi/gephi/issues/#1347))
- Appending edges with auto-created nodes resets existing node's label ([#1348](https://github.com/gephi/gephi/issues/#1348))
- Merge multiple workspaces doesn't work with timestamp representation ([#1349](https://github.com/gephi/gephi/issues/#1349))
- Edge colour - overview - always remain grey, no node colour, no change of colour ([#1353](https://github.com/gephi/gephi/issues/#1353))
- Edit window doesn't respect current time format ([#1358](https://github.com/gephi/gephi/issues/#1358))
- Exception when right click on double array in Data Laboratory ([#1359](https://github.com/gephi/gephi/issues/#1359))
- Table alternative rows sometimes have the wrong highlight color (unreadable) ([#1360](https://github.com/gephi/gephi/issues/#1360))
- Selecting nodes with object coloring mode doesn't highlight neighbours ([#1361](https://github.com/gephi/gephi/issues/#1361))
- Edge label position should be in the middle of the edge when undirected ([#1362](https://github.com/gephi/gephi/issues/#1362))
- Edge labels don't respect the "Hide non-selected" option ([#1363](https://github.com/gephi/gephi/issues/#1363))
- Label color and size modes are not localized ([#1364](https://github.com/gephi/gephi/issues/#1364))
- IllegalArgumentException when importing sliced gexf with attvalues ([#1366](https://github.com/gephi/gephi/issues/#1366))
- Dynamic metrics don't work with interval time representation ([#1367](https://github.com/gephi/gephi/issues/#1367))
- VNA file error in Gephi 0.9.0 ([#1369](https://github.com/gephi/gephi/issues/#1369))
- Workspace panel sometimes doesn't select the proper tab when adding workspaces  ([#1378](https://github.com/gephi/gephi/issues/#1378))

### API Changes

- A new `setColors` method has been added to `Partition` in `AppearanceAPI`.
- The `SpigotImporter` and `SpigotImporterBuilder` interfaces in `ImportAPI` have been renamed to `WizardImporter` and `WizardImporterBuilder`. Methods have been accordingly renamed in `ImportController` as well.
- The `FilterBuilder.getFilter()` and `CategoryBuilder.getBuilders()` methods in `FiltersAPI` now take a `Workspace` as a parameter.

## Gephi 0.9.0 (Dec 20 2015)

### New features highlight

- Compatibility with Java 7 and 8 on all platforms
- Performance and memory-usage improvements thanks to a redesigned core
- New _Appearance_ module that merges the _Ranking_ and _Partition_ modules
- New palette chooser and generator for partitions. The generator algorithm is designed to find the most suitable color palette
- Multi-graph support, it's now possible to import multiple edges with different relationship types between nodes
- Dynamic graphs can now be represented by a collection of timestamps, in addition of intervals
- Multiple graphs can be imported at the same time, typically a collection of graphs at different timestamps

### Other new or improved features

- Auto-apply on dynamic partition ([#606](https://github.com/gephi/gephi/issues/#606))
- Workspace selection as tabs ([#1105](https://github.com/gephi/gephi/issues/#1105))
- Add Applications shortcut in DMG file ([#1117](https://github.com/gephi/gephi/issues/#1117))
- Implement directional zoom ([#1126](https://github.com/gephi/gephi/issues/#1126))
- Add progress when taking screenshots ([#1133](https://github.com/gephi/gephi/issues/#1133))
- Add support for color names and hex/oct codes in importers ([#1146](https://github.com/gephi/gephi/issues/#1146))
- Add edge color parsing in GML importer ([#1147](https://github.com/gephi/gephi/issues/#1147))
- Add multiple files import support ([#1150](https://github.com/gephi/gephi/issues/#1150))
- GEXF 1.3 support for import/export ([#1152](https://github.com/gephi/gephi/issues/#1152))
- Add Import Spreadsheet option to File menu ([#1155](https://github.com/gephi/gephi/issues/#1155))
- Update ForceAtlas2 adaptive speed to better formula ([#1158](https://github.com/gephi/gephi/issues/#1158))
- Add Noverlap layout ([#1161](https://github.com/gephi/gephi/issues/#1161))
- Add OpenOrd layout ([#1162](https://github.com/gephi/gephi/issues/#1162))
- Add clear UI hook for mouse selection configuration panel ([#1165](https://github.com/gephi/gephi/issues/#1165))
- Bundle JRE in Mac OS App ([#1170](https://github.com/gephi/gephi/issues/#1170))
- Print application log to output window ([#1171](https://github.com/gephi/gephi/issues/#1171))
- Add copy to clipboard context menu on Import's report panel ([#1182](https://github.com/gephi/gephi/issues/#1182))
- Add new edge filter based on edge type ([#1189](https://github.com/gephi/gephi/issues/#1189))
- Add filter that keeps only nodes that have self-loop ([#1203](https://github.com/gephi/gephi/issues/#1203))
- Add import support for TGF graph format ([#1240](https://github.com/gephi/gephi/issues/#1240))

### Removed features
- Remove hierarchical graphs support
- Remove support for 3D graph navigation
- Remove proprietary DB drivers (SQLServer, Teradata)
- Remove pie charts in context and partition modules
- Removed HITS statistics
- Removed Clustering module

### Project file compatibility

The .gephi files created with Gephi 0.9.0 won't work on earlier versions as the format code has been redesigned. However, files from 0.8.2 and anterior can be opened by Gephi 0.9.0. Therefore, we advise not to overwrite your project files if you still plan to use earlier versions of Gephi.

### Bugfixes

- graphml `edgedefault` not handled to spec ([#147](https://github.com/gephi/gephi/issues/#147))
- Misleading average edge weights in dynamic networks ([#156](https://github.com/gephi/gephi/issues/#156))
- Color the edge with the opposite node color when selected in Overview ([#292](https://github.com/gephi/gephi/issues/#292))
- ImportController.getFileImporter() should match importer name and extension ([#319](https://github.com/gephi/gephi/issues/#319))
- DOT parser is broken ([#320](https://github.com/gephi/gephi/issues/#320))
- Control Command on Mac ([#327](https://github.com/gephi/gephi/issues/#327))
- Can't import two files on the same time ([#338](https://github.com/gephi/gephi/issues/#338))
- Excessive Redrawing of windows Mac OS X ([#401](https://github.com/gephi/gephi/issues/#401))
- Database edge list UI not remembering settings, and a validation error ([#451](https://github.com/gephi/gephi/issues/#451))
- Partition colors generated at each workspace switch ([#453](https://github.com/gephi/gephi/issues/#453))
- Colors in partition filter inconsistent with real partition colors Filters ([#455](https://github.com/gephi/gephi/issues/#455))
- Freeze color mappings across graphs ([#461](https://github.com/gephi/gephi/issues/#461))
- Partition not applicable after filtering ([#471](https://github.com/gephi/gephi/issues/#471))
- Change filter button aspect to "Stop" when filtering is active Filters ([#476](https://github.com/gephi/gephi/issues/#476))
- No way to reset workspace layout ([#480](https://github.com/gephi/gephi/issues/#480))
- Picking a second partition colour does not bring up the colour picker, but changes the colour ([#533](https://github.com/gephi/gephi/issues/#533))
- Edge filter reduces displayed thickness of UNfiltered edges ([#538](https://github.com/gephi/gephi/issues/#538))
- Preview outputs margin automatic fitting ([#572](https://github.com/gephi/gephi/issues/#572))
- Node label outlines offset in Preview ([#654](https://github.com/gephi/gephi/issues/#654))
- Appending to exiting graph resets layout ([#657](https://github.com/gephi/gephi/issues/#657))
- Export filter as a true/false column does nothing ([#680](https://github.com/gephi/gephi/issues/#680))
- Reset size option/dialog should default to the current default node size (10.0?) and not 1.0 ([#699](https://github.com/gephi/gephi/issues/#699))
- Catch blank nodes during CSV import ([#723](https://github.com/gephi/gephi/issues/#723))
- NumberFormatException when loading dot file containing "[H,S,V]" colors ([#739](https://github.com/gephi/gephi/issues/#739))
- Gephi isn't compatible with Java 7 and 8 on all platforms (Windows, Mac OS X, Linux) ([#748](https://github.com/gephi/gephi/issues/#748))
- No way to filter out nodes that do not have a particular value? ([#750](https://github.com/gephi/gephi/issues/#750))
- WTF: Gephi deletes my GML file ([#757](https://github.com/gephi/gephi/issues/#757))
- Make partition colors persistent with the attribute column ([#760](https://github.com/gephi/gephi/issues/#760))
- Incorrect average degree on directed graphs ([#767](https://github.com/gephi/gephi/issues/#767))
- Add edge issue: node id not displayed in the GUI Data Laboratory ([#782](https://github.com/gephi/gephi/issues/#782))
- UNION filter does not work ([#809](https://github.com/gephi/gephi/issues/#809))
- Gephi hangs when applying degree filter ([#813](https://github.com/gephi/gephi/issues/#813))
- Networkx gexf parser conflict with gephi ([#818](https://github.com/gephi/gephi/issues/#818))
- Error and file deletion when importing non-gzipped .gexf files ([#835](https://github.com/gephi/gephi/issues/#835))
- Error while exporting a graph as a GML file ([#905](https://github.com/gephi/gephi/issues/#905))
- GDF import defaults to "directed" edge type, should be "undirected" ([#906](https://github.com/gephi/gephi/issues/#906))
- Center on graph is not working on flat graph ([#916](https://github.com/gephi/gephi/issues/#916))
- Cannot open graph files in /tmp ([#918](https://github.com/gephi/gephi/issues/#918))
- Gephi generates invalid GML files ([#919](https://github.com/gephi/gephi/issues/#919))
- File can't have repeated column names ([#921](https://github.com/gephi/gephi/issues/#921))
- Gephi should be DPI-aware or offer a DPI setting ([#961](https://github.com/gephi/gephi/issues/#961))
- Duplicate dynamic attribute value in GEFX causes Gephi to fail silently ([#964](https://github.com/gephi/gephi/issues/#964))
- gephi shouldn't delete files when it can't open them ([#1041](https://github.com/gephi/gephi/issues/#1041))
- fail to parse valid DOT file if no node attribute present ([#1053](https://github.com/gephi/gephi/issues/#1053))
- Edge colors are unnecessarily dark ([#1060](https://github.com/gephi/gephi/issues/#1060))
- GraphML Importer doesn't recognize node attributes ([#1084](https://github.com/gephi/gephi/issues/#1084))
- Add icon to rename workspace action ([#1104](https://github.com/gephi/gephi/issues/#1104))
- Upgrade DBDrivers JDBC dependencies versions ([#1115](https://github.com/gephi/gephi/issues/#1115))
- Error when saving a project file if the file has been deleted ([#1119](https://github.com/gephi/gephi/issues/#1119))
- Gephi.app won't start from case-sensitive filesystem ([#1144](https://github.com/gephi/gephi/issues/#1144))
- ImportGML forces all columns to be string even though Double is parsed ([#1151](https://github.com/gephi/gephi/issues/#1151))
- Window title is truncated in some cases ([#1156](https://github.com/gephi/gephi/issues/#1156))
- Memory leak when closing projects ([#1157](https://github.com/gephi/gephi/issues/#1157))
- Control zoom so it can't move further than viewfield ([#1159](https://github.com/gephi/gephi/issues/#1159))
- Rectangle selection with ctrl key doesn't work on OS X ([#1166](https://github.com/gephi/gephi/issues/#1166))
- Filter duplicate doesn't properly clone properties ([#1190](https://github.com/gephi/gephi/issues/#1190))
- Support quoted attributes in DOT import ([#1195](https://github.com/gephi/gephi/issues/#1195))
- Color undirected edge with mixture of adjacent node colors in Overview ([#1211](https://github.com/gephi/gephi/issues/#1211))
- Preview display with retina display support ([#1222](https://github.com/gephi/gephi/issues/#1222))
- Make data laboratory refresh when the graph is filtered ([#1238](https://github.com/gephi/gephi/issues/#1238))

### API Changes

- The functionalities of `DynamicAPI` have either been replaced by native `GraphAPI` support or added to the `TimelineAPI`, effectively removing `DynamicAPI` from the codebase. The `TimeFormat` can be set via `setTimeFormat()` on `GraphModel`. Estimators are now configurable per column and can directly be set from the `Column`. Obtaining the minimum time bounds can now be obtained from the `TimeIndex` directly from `GraphModel`.
- The `createQuery()` method in `FilterController` now takes a `FilterBuilder` instead of a `Filter`. It allows to track down builders down to the query level.
- The `ImportAPI` now supports importing multiple graphs at the time and supports graph slices through an additional parameter on `ContainerLoader`. The `setTimestamp()` and `setInterval()` allows to define a point or period of existence for the entire graph. The `ImportController` also allow multiple containers to be processed through a new `process()` method. In parallel, `ImporterUI` now takes multiple importers and so does the `Processor` interface that now takes multiple containers.
- The `NodeFilter` and `EdgeFilter` interfaces now inherit from a new `ElementFilter` so it's easier to create filters that work at the element level.
- The `filter()` method in `Operator` now takes an array of `Subgraph` instead of `Graph`. This gives access to operations such as `union` or `not`.
- Remove `ClusteringAPI` from codebase. It needs a complete rewrite.
- Add ability to configure timezone with `setTimeZone()` on `ContainerLoader` in `ImportAPI`.
- Remove standalone `ContainerFactory` class in `ImportAPI` and replace it with `Container.Factory`. Also add the ability to configure the `TimeRepresentation` in `ContainerLoader`. Finally, add color parsing utility in `ImportUtils`. It can be used to parse color names or codes.
- The `AttributeModel` parameter in the `execute()` method of `Statistics` interface in `StatisticsAPI` has been removed as all features are now in `GraphModel`.
- The `ChangeListener` in `WorkspaceInformation` has been replaced with a `PropertyChangeListener`.
- Both `RankingAPI` and `PartitionAPI` have been replaced by a new `AppearanceAPI`, which supports both concepts. The SPI allows to create `Transformer` services, which can support either ranking or partition transformations. `Ranking` and `Partition` instances are defined in the API and gives access to underlying data. The core concept in appearance are functions, which wrap the transformation entirely and can be accessed in `AppearanceModel`.
- The _Processing_ dependency in `PreviewAPI` has been removed and replaced by regular Java2D. Therefore, the `ProcessingTarget` is now the `G2DTarget`. Also add a `resize()` method to facilitate integration.
- Addition of a `EdgeWeightMergeStrategy` enum to control the way parallel edge weights are merged in `ImportAPI`.
- Add ability to create `WorkspacePersistenceProvider` with a new SPI interface: `WorkspaceBytesPersistenceProvider`. The XML-based interface has being renamed into `WorkspaceXMLPersistenceProvider`.
- Importers can now use the `setValueString()` method on `ElementDraft`. This will automatically parse the value based on the declared type reducing parsing code on the importer side. If the type is already in the right type, use the `setValue()` instead.
- Refactoring of the import API. Introduction of a `ColumnDraft` interface which represents a to-be-created column and the method to manipulate them in `ContainerLoader`. The `NodeDraft` and `EdgeDraft` classes now inherits from a new `ElementDraft`, centralizing a lot of the code. The `EdgeDraftGetter` and `NodeDraftGetter` have been removed and their methods moved directly to the node/edge draft. New elements are now created using the `ElementDraft.Factory`, which can be obtained with the `factory()` method on `ContainerLoader`. Previously the `ContainerUnloader` returned an `AttributeModel`. This has been replaced with iterables over column drafts. The `EdgeDefault` enum becomes `EdgeDiretionDefault` and represents a graph-level configuration. The `EdgeDefault` is now edge-level configuration and can be set by `setEdgeDirection()` on `EdgeDraft`. Finally, convenient `setColor()` methods have been added to `ElementDraft`.
- Complete rewrite of the `GraphAPI` and add [GraphStore](http://github.com/gephi/graphstore) as dependency. The new API is entirely defined in the GraphStore project and Gephi makes it available through the `GraphAPI`. The `AttributesAPI` functionalities have been consolidated into the new graph API and therefore has been removed. There is too many API changes to be listed all but notable ones are the following.
    - All attribute features (e.g. add column) are now directly accessible from the `GraphModel`, and there's no more `AttributeModel`.
    - The `AttributeColumn` is renamed into `Column`, the `AttributeTable` is renamed into `Table`, `AttributeOrigin` is renamed into `Origin` and the `AttributeType` has been replaced by the direct usage of `Class` objects. Moreover, the `AttributeUtils` is now entirely static (i.e. no more needed to obtain an instance) and has multiple important additions such as full parse support.
    - The support for hierarchical graphs has been removed, but multi-graph support added. Each edge now can have a relationship type, and is zero by default. These types can be associated with an arbitrary label object, which can be configured in `GraphModel.addEdgeType()`.
    - All node/edge data are now directly accessible from the interface. For instance, attribute values can be retrieved with the `getAttribute()` methods. All properties such as color or position are also accessible directly on the Node/Edge interfaces.
    - Dynamic graphs can now be represented with timestamps as well. Intervals are still supported but the API user must configure the preferred representation through the `Configuration` (must be done at initialization). The way elements' existence overtime has been greatly simplified with the addition of timestamp/interval management methods on `Element`, which both `Node` and `Edge` extends. See for instance `addTimestamp()`, `addInterval()`, `getTimestamps()` or `getIntervals()`. Similarly, each attribute getter or setter in `Element` is available with timestamps and intervals parameters so attribute values over time can be configured. Behind the scenes, the dynamic types used are defined in `org.gephi.graph.api.types`.
    - There's a new `Subgraph` interface that extends `Graph` and is available from `GraphModel.getGraph(GraphView)`. This subgraph interface has additional features such as `union()` or `intersection()`.
    - The graph listening system with `GraphListener` has been entirely replaced with a pull-based system of observers. The system no longer sends events at each update but listeners can create observers, which periodically check if something has changed. There's multiple types of observers: `GraphObserver` for topology changes, `TableObserver` for new/removed columns and `ColumnObserver` for attribute value changes. These observers can obtain diff objects such as `GraphDiff` or `TableDiff` to exactly obtain what has changed.

## Gephi 0.8.2beta (Jan 03 2013)

### New features

- Add Retina Display support to the Mac OS X version
- Data Laboratory's time interval merge strategy now supports custom date format
- Improved parser for dynamic types. Literal strings are now supported.

### Bugfixes

- Filters 'Duplicate' does not work (issue 176)
- Exporting SVG File throws DomException due to invalid stroke-widths (issue 697)
- File name entered is lost when changing folder (issue 463)
- Datalab: can't export all columns (issue 628)
- NullPointerException when importing from database (issue 691)
- Filter on column created with regex causes crash (issue 663)
- "Long cannot be cast to a String" when either exporting a graph or saving a gephi file (issue 679)
- Mapping of Escape Keyboard Shortcut for "Save changes before closing?" dialog box (issue 686)
- DataLab: filling edge weight column doesn't work when dynamic (issue 619)
- Spreadsheet import of dynamic data: support of "infinity" (issue 631)
- Missing license headers (issue 664)
- Spreadsheet import and self-loops (issue 683)
- Timelime interval set in infinite loop (issue 712)
- OutDegreeRange broken (issue 651)
- Shortest path on filtered graphs fails (issue 650)
- Weighted degree computation fails (all values 0) when a filter is applied (issue 636)
- Dot parser fixes (issue 621)
- Filtering leads to Null Pointer exception when saving (issue 617)
- Partition percentages incorrectly composed across filters (issue 637)
- Start/end attributes are always imported using DATETIME format (issue 649)
- HeatMap / Shortest Path on undirected Graph wrongly paints / calculates (issue 630)
- Typo fix connetion to connection (issue 642)
- Timeline sparkline bug (issue 615)
- Fixes calculation of clustering coefficient on graph (issue 625)
- Unix timestamp support (issue 612)
- GML loading cannot accept scientific notation for float-type edge property (issue 300)
- GML export does not respect specs (issue 604)
- GEXF export outputs incorrect files (issue 570)
- Problems with export of PNG files (issue 601)
- Edge pencil: unable to set edge directedness (issue 549)
- Presets of "Preview settings" are incorrectly / not saved (issue 575)
- Option "Time intervals as dates" in Timeline (issue 613)
- 8.1 and 8.0 both freeze at start-up when on network (issue 592)
- Data laboratory max columns unintuitive (issue 590)
- Modularity with Edge Weight Causes Array Out-of-Bounds (issue 577)

### API Changes

- Add support for mouse listeners in Preview plugins. Create a PreviewMouseListener and implement MouseResponsiveRenderer interface in the renderers that use the listener.

## Gephi 0.8.1beta (Mar 29 2012)

### New features

- New Timeline with animation, custom bounds settings, date ticks and embedded sparkline.
- Ranking now supports local and global scale.
- Modularity (Community detection) adds edge weight support and resolution setting.
- Self-loop filter

### New localization

- Russian
- Chinese (China)
- Czech

### Performance

- Better Preview performance when edges hidden

### Bugfixes

- Exception when deserializing a preview preset (issue 554)
- ClassCastException when saving a gephi file after PDF export (bug 553)
- Dynamics: DateTime values are converted to numbers when workspace is duplicated. (issue 552)
- Cannot Preserve Z-Coordinate in GEXF exporter (issue 547)
- Gephi won't start on Mac OS X Lion because of a missing JAWT library (issue 542)
- Add a local/global scale button to Ranking (issue 541)
- Spreadsheet import: edge weight not imported (issue 540)
- NOT operator wrong with topology filters (issue 539)
- Multiple partition filters not named: cannot tell them apart (issue 537)
- AttributeContollerImpl should be renamed to AttributeControllerImpl (issue 530)
- Timeline - Set Custom Bounds does not support DATETIME (issue 529)
- Data Laboratory - Dynamic Attributes Edit function resets values (issue 528)
- DL exporter fix (issue 525)
- Validator of MySQL's "host" field (issue 521)
- Edge/Node attributes don't support datetime format (issue 518)
- Directed Graph cluster coefficient provides incorrect values in certain situations (issue 517)
- NullPointer in GUI when defining range Filters (issue 516)
- datalab: empty column fails edge csv import (issue 515)
- updateDimensions in PreviewController does not take into account node size (issue 514)
- Overview's graph area does not redraw edges automatically (issue 513)
- c+p correction: HITS hub chart was repeated twice in output. (issue 510)
- database import from Postgres does not handle node color attribute (issue 506)
- Incorrect Teradata JDBC url (issue 505)
- [Datalab] Duplicated nodes on import spreadsheet (issue 498)
- [Datalab] Failing silently to load attribute values on import spreadsheet (issue 497)
- Attribute Columns Property editors don't support dynamic numbers (issue 494)
- Arrows not hidden when edges hidden on Preview (issue 493)
- Some text appears garbled when loaded from a project file (issue 488)
- Exception when adding a new Perspective plugin development (issue 486)
- NullPointer Exception with Edge Labels (issue 478)
- Filter range does not filter if min == max (issue 477)
- Heatmap Tool Sometimes Doesn't Work (issue 472)
- deleting a field in data lab yields an error (issue 468)
- Email imports can't be cancelled (issue 466)
- Invalid XML character error when loading a gephi file (issue 465)
- Range Slider writes N/A if the min and max values are the same (issue 464)
- datalab: exception on hiding a column used to sort the table (issue 454)
- Can't build without Netbeans installed (issue 452)
- Auto-refresh not updated after changing the spline (issue 448)
- AttributeRangeFilter returns main graph when nothing matches filter (issue 435)
- Timeline need more precision when dealing with dates (issue 202)
- Degree Filter Not Filtering as Subfilter in Tookit (issue 69)
- UnsatisfiedLinkError on startup on Mac OS X (issue 44)

### API Changes

- Add a needsItemBuilder method to Renderer in Preview API. This helps to avoid building unnecessary items while refreshing preview.
- Preview API changes: Added a getDisplayName to Renderer and support for extending default preview renderers. Added a renderer manager to preview controlled with new methods in PreviewModel and PreviewController.
- Add a local scale flag in Ranking API. The value can be set from theRankingController.
- Add RangeFilter interface in Filters API to help create range filters. The filter system now automatically manages the range values and bounds. The Range object now also supports exclusive intervals.
- Add a new AttributableFilter filter type. This is useful for filters manipulating Attributable objects regardless whether they belong to a node or edge. Also note new useful abstract plugin implementations have been added to the FiltersPlugin module. Use AbstractFilter for any filter and AbstractAttributeFilter for filters based on attributes. Filter builders are also provided.
- Update to Netbeans Platform 7.1 and it's new perspective system. The PerspectiveMember SPI has to go away and will break compatibility. Top components now directly declare the perspective they belong to in the @TopComponent.Registration annotation, for instance roles = {"overview"} for the Overview perspective.
- Add a REPLACE_COLUMN event type in AttributeEvent.
- New Timeline API exposed as a stable API. Th API controls the Timeline UI component and the animation framework.
- Add a new TIME_FORMAT event in DynamicModelEvent. The event is triggered when the time format is initialized.
- Add a getGraphTable() in the AttributeModel. The GraphView elements can also have attributes using the same system as nodes and egdes. The data can be accessed through the Graph.getAttributes() method.

## Gephi 0.8beta (Oct 03 2011)

### New features

- New Preview architecture, one can now write Preview Plugins
- ForceAtlas2 layout algorithm, with multi-thread option
- Dynamic Ranking
- PNG Export
- Dynamic Metrics
- Data Lab node merging
- Node and Edge transparency in Preview
- Edge labels on curved edges
- Text outline now in Preview
- Database importer now supports time columns (start & end)
- Switch off the light in Overview (see the blueprint)
- DL Export (Thanks to Taras Klaskovsky)
- GML Export (Thanks to Taras Klaskovsky)
- NET Export (Thanks to Daniel Bernardes)
- K-core filter
- Inter and Intra partition filter
- Now supports SQLite databases
- Display the number of layout iterations in status bar when ended
- Recent Palette in Ranking
- Weighted degree now also for directed graphs

### New localization

- Portuguese (Brazilian) (Thanks to Célio Faria Jr)
- Japanese (Thanks to Siro Kida and Koji Chono)

### Performance
- Memory starvation manager
- Less memory usage with attributes

### Removed features

- Preview arrow design changes. Arrows now look like in Overview.
- Preview mini-labels have been removed, they might be readded later
- Mutual edges specific options in Preview

### Bugfixes

- Timeline need more precision when dealing with dates (bug 521937)
- Exception on range slider (bug 541808)
- Inconsistent label data from Overview to Preview (bug 660204)
- Statistics: sub-optimal modularity (bug 727701)
- Timeline cann't drag if the two sliders moved to the left (bug 745476)
- Missing Polish characters when exporting to pdf (bug 746740)
- Edge selection color is not correct on OSX (bug 752300)
- Workspace name truncated, hard to read (bug 758578)
- Average degree cannot be switched to directed / undirected (bug 760454)
- Window->Favorites appears in 0.8 alpha (bug 764494)
- Disable 'directed' on metric settings if the graph is undirected (bug 771318)
- Timeline does not work (exception) (bug 774455)
- Layout properties can't be saved in a language and loaded in another language (bug 783637)
- Preview: edge label not shown (bug 783868)
- Possible memory leak on Dynamic Range Filter (bug 784606)
- Edge attributes not saved in .gephi project file (bug 785268)
- Data Lab: Exception when selecting only one column for merging (bug 785269)
- Data Lab Import Spreadsheet should not ignore parallel edges (bug 785635)
- Data Laboratory: wrong edge type created (mutual instead of directed) (bug 787401)
- Data Lab: impossible to edit time intervals in a date format (bug 793163)
- Spelling of Proportionnal (bug 794358)
- Graphics errors when JOGL installed as a JRE/JDK extension (bug 799545)
- NPE if source/target is empty in GEXF import (bug 799574)
- Toolkit can't open .gephi files (bug 802101)
- Resizing edge sizes changes edge weight values (bug 803763)
- Preview does not use node label settings from overview tab (bug 805763)
- Data Lab 'Import Spreadsheet' dialogue should accept other file types than .csv (bug 806798)
- Edge weights not imported from CSV matrix (bug 808078)
- Preview tab: no option to switch off node borders? (bug 808606)
- Gephi runs out of memory without warning the user (bug 811373)
- Counter-intuitive filename in Data export dialog (bug 814178)
- NullPointerException when creating newProjects too quickly (bug 817170)
- Nodes and edges Id attribute dictionary is not properly created when loading a .gephi file (bug 818181)
- Database driver doesn't persist in Edge List Database import UI (bug 822316)
- NodeEqualNumberFilter does not work (bug 823038)
- Gephi does not build on JDK 7 (bug 823543)
- SVG node, edge export should include relevant node IDs as classes (bug 827706)
- Import Spreadsheet: need to trim column names (bug 829956)
- Layout list not sorted by name (bug 830149)
- In/Out degree metric is computed on the main graph instead of the visible graph (bug 830752)
- Layout is not giving the algorithm's number of iterations (bug 831782)
- Banner height issues, need a fixed height (bug 834400)
- NPE when running ClusteringCoefficient on a filtered graph (bug 852799)
- Missing node properties from dot file (bug 855410)
- 'The value column doesn't exist' error when opening a gephi file (bug 857595)
- Import fails for NET (Pajek) file with position/color data (bug 860825)
- GEXF export referes to v1.1 schema, should be v1.2 schema (bug 864484)

### API Changes

- Complete rewrite of the Preview API with a new SPI which allows to extend the Preview with new renderers, item builders or render targets. The API also now offers better customization through a central property system and is optimized for external applications as well. The API is also now considered as stable.
- New DynamicStatistics SPI in the StatisticsAPI module. The interface extends Statistics and implement the calculation of metrics over time.
- Important changes in graph events breaking API compatibility. The ADD_NODES and ADD_EDGES are merged into a ADD_NODES_AND_EDGES event. Similarly REMOVE_NODES and REMOVE_EDGES are merged into a REMOVE_NODES_AND_EDGES event. - GraphEventData remains the same and still contains both added/removed nodes and edges. Users may simply test if arrays returned by addedNodes(), addedEdges(), removedNodes() and removedEdges() are null before using them.
- Add new executeLayout(numIterations) method in LayoutController.
- The StatisticsController now supports synchronous algorithm execution through the execute(Statistics) method.
- Add new startAutoTransform() and stopAutoTransform() in Ranking API to control auto transformations. The model also allows to retrieve the ranking used in the auto transformation. An additional refreshRanking() method has been added in the RankingBuilder SPI for a smoother auto transformation support.
- Added a new AttributeRowsMergeStrategy interface to Data Laboratory API. This is a type of manipulator that defines and strategy for merging values of a row (node or edge) for an specific column. It should be used by other manipulators such as NodesManipulator MergeNodes
- Complete refactoring of the Ranking API to improve modularity and reach a stable version of the API. The API now also has a SPI for ranking builders and transformers. Instead of getNodeRanking() and getEdgeRanking in the model, we introduce the concept of element type and generalize methods to it. Use Ranking.NODE_ELEMENT to obtain a node ranking and Ranking.EDGE_ELEMENT for an edge ranking. Same idea for transformers, which are now defined by a unique name. Default transformers' name can be found in the Transformer interface. A RankingEvent has also been created. API users have to update to their client code to be compatible.
- Add a new interface nodes and edges share: Attributable. That allows to manipulate objects with attributes regardless if the object is a node or an edge. Node, Edge, NodeData and EdgeData now implements this interface, and a getAttributes() method has been added to Node and Edge to make development easier.

## Gephi 0.8alpha (Apr 08 2011)

### New features

- Spanish and French localization (Menu Tools > Languages)
- GEXF 1.2 support (partial)
- Integrate Email Spigot - create network from emails
- Add Neighbour Filter
- Improve support of meta-edges in Statistics and Filters
- Improve usability of Filters
- Edge weight option in PageRank, which can now be used by the algorithm
- Duplicate workspaces (Edit Menu)
- Open Recent menu in File
- Graph files now supports GZ compression
- Better Filters support in .gephi files
- VNA Import (Thanks to Vojtech Bardiovsky)

### Performance

- Label Adjust algorithm 3 times faster
- Saving/Loading projects is faster and use less memory

### Removed features

- Degree Power Law metric. Reason: this is not a metric but a fit on a model. The produced chart is not sufficient to link building service determine if data fits the model correctly.
- Watts-Strogatz generator, a brand new 'Scientific Generators' plugin is about to be released, including Watts-Strogatz and many others
- 'Open project' menu has been merged in simply 'Open'

### Bugfixes

- Windows installer should not require admin privileges (bug 663337)
- Cancelled Vector Export Disabled "File" Menu (bug 728871)
- Misformated SQL-Server JDBC url (bug 745414)
- Partition Filter Loses Categories As Subfilter (bug 726107)
- Workspace name does not increment (629376)
- Cannot select directory to export (bug 711185)
- Ranking Color can't be changed on OSX (bug 737727)
- Filter panel not cleared after query removed (bug 737992)
- Ego Filter "with self" option doesn't work with depth > 1 (bug 671007)
- Maximum Degree Range Doesn't Update on Subfilter (bug 725688)
- Cannot save and reload dynamic network as project (bug 709270)
- GDF exports attributes when option is disabled (bug 735927)
- Rename "Edit" menu to "Workspaces"? (bug 735475)
- Data laboratory context menu takes too much time to appear when a lot of nodes are selected (bug 735721)
- export svg/pdf with no edges causes NPE (bug 693789)
- Can't import the same file twice in Welcome window (bug 598157)
- Graph Window in Overview Tab Fails to Load (bug 659773)
- Timeline appears first wrong when timeformat="date" (bug 709234)
- Filter query not saved when Filter button is active (bug 671004)
- GEXF option <spells> doesn't work(bug 709235)
- Ego Network Filter Searches for Substring, Does Not Match Value (bug 726114)
- Label text settings not saved in .project (bug 660205)
- saved preset for layouts creates several instances (bug 612848)
- Partition colors in Filters are different from those in Partition (bug 616037)
- import of pajek net has floating pt problem (bug 619893)
- NullPointerException on saving project (bug 622154)
- Name of currently opened file not updated after a "save as" (bug 629374)
- Labels are not hidden on Preview (bug 654006)
- Chaining Dynamic Filter (bug 654018)
- NullPointerException on importing CSV data in Data Laboratory (bug 654030)
- Statistics report not refreshed after a new execution (bug 654036)
- Maximum lock count exceeded error when running Label Adjust (bug 655544)
- GEXF export: missing attvalues element (bug 655975)
- Can't use ranking label transformers with toolkit (bug 656172)
- GEXF export: attribute definitions exported even if Attributes option is unchecked (bug 656276)
- Preview throws an Exception with negative edges (bug 656955)
- Closeness centrality chart empty with normalized values (bug 658361)
- Statistics fail to work on a hierarchy level different from the leaves (bug 658394)
- Exported Data Table doesn't use sorted columns (bug 658816)
- Importing a TIME_INTERVAL column in Data Laboratory CSV import doesn't enable dynamic features (bug 659017)
- Error when using filter export features and filtering off (bug 659229)
- Exception when using flatten filter (bug 659270)
- GDF export generates invalid files (bug 660200)
- Wrong color type exported in GraphML (bug 660356)
- GEXF exporter doesn't export the label if they are the same as the id (bug 660382)
- Tool Selection tooltip under the graph window (bug 660459)
- Column settings in Data Lab are not saved in .project (bug 660469)
- Data Lab filter not executed when changing the column (bug 660471)
- Data Lab: column used by node filter is automatically reset (bug 660517)
- Personalized color of a specific partition is rolled back (bug 660529)
- DOT importer ignores edge weight and .gv file extension (bug 661257)
- Exceptions when importing mixed graph (bug 662488)
- Error on selecting nodes from filter if graph window not shwn at startup (bug 663561)
- Blank preview screen (bug 664300)
- Edge text not visible on preview with other attributes (bug 664444)
- Data does not appear on nodes table (bug 667440)
- saving a project uses too much memory for large graphs (bug 672071)
- Data Lab: search/replace only on a given column (bug 676087)
- Workspace number incremented by opening a new project (bug 681038)
- Filter "out degree range" does not work (bug 681184)
- NullPointerException on exporting dynamic GEXF file with Toolkit (bug 686432)
- Wrong relative betweenness (bug 687267)
- graphml generated syntax is incorrect (bug 688678)
- Import Report freezes when the number of issues or logs is too high (bug 688865)
- Filters fail to work on a hierarchy level different from the leaves (bug 691278)
- Wrong edge count in Context Panel with hierarchies (bug 692225)
- RepaintCell exception on Mac OS X (bug 692379)
- Exceptions when group/ungroup from Partition after delete (bug 692382)
- GML importer don't process 'weight' column as weight (bug 703877)
- Degree doesn't take edge weight into account (bug 703933)
- Edge attribute values not imported from graphml file (bug 707390)
- PageRank not for weighted networks (bug 715621)
- Data Lab: boolean column edition facility (bug 717869)
- Exception on Delete Column if sorted by this column (bug 719987)
- Data Lab: edge rows not displayed when the hierarchy level /= 0 in Overview (bug 720033)
- Java Null Pointer when using Merge Columns (bug 722287)
- Open Recent files doesn't work with project files (bug 734105)
- Timeline disappears after saving project.gephi file (bug 695558)
- Exception on Visualization Settings if opened before Overview (bug 734117)
- Database import is not cancelable (bug 734126)
- 'A task is still executing' error after cancelling a custom importer, not LongTask (bug 734132)
- Edge weight slider not refreshed between workspaces (bug 731599)
- Exception on New workspace after deleting last workspace (bug 735273)
- Colors not imported in Pajek Net format (bug 530028)

### API Changes

- Add setCurrentQuery() method on FilterController
- Important change how modules save/load data into project files. The WorkspacePersistenceProvider interface from - ProjectAPI now uses StAX instead of DOM. The writeXML() method now uses XMLStreamWriter and readXML() XMLStreamReader. Backward compatibility can't be assured, modules have to use switch to StAX.
- Added support of shortcut keys, availability of items and sub-items creation to Data Laboratory context menu actions (NodesManipulator and EdgesManipulator). Also now Visualization API has an SPI for adding context menu actions (GraphContextMenuItem) to nodes like DataLaboratory does with NodesManipulator. Note that they share the interface ContextMenuItemManipulator from Data Laboratory API, so they are compatible, being able to reuse actions on nodes for Overview and Data Laboratory.
- Add removeMetaEdge(Edge) to manually remove meta edges. Add getTotalEdgeCount() method to globally count the number of edges, regardless if the edge is proper or meta.
- Add methods in Graph API to better combine edges and meta edges features. Add getEdgesAndMetaEdges(Node) and getTotalDegree(Node) methods, as well as their in and out variants for HierarchicalDirectedGraph.

## Gephi 0.7beta (Oct 01 2010)

### New features

- New Data Laboratory (Manipulate columns, Search/Replace, Merge, Sparklines...)
- Longitudinal network visualization, topology changing over time, as well as attributes
- Timeline is now working properly, appears automatically when the graph is dynamic, single button to enable filtering
- Show/Hide labels from filters - can be reset by the 'Reset Visible' action (left of graph window)
- Display edge weight as labels on visualization
- New StAX GEXF importer and exporter, with hierarchy and dynamic support
- New List/Arrays attribute types. Can only be imported from GEXF for now.
- NOT Operator (Filters)
- MASK Operator (Filters) - keep edges according to source/target/both/any - can easily obtain neighbors of a set of nodes
- Flatten Filter - Flatten a hierarchical graph to the visible view, transform meta-edges into normal edges
- New Giant Component Filter
- Time Frame import, new option in 'Import Report' to import successive static files and transform into dynamic
- Zoom slider in visualization options
- 'Import missing nodes' option in import report - choose whether to create them or not
- Set size for the 'Reset Size' action, by right-clicking on the reset size button
- Get degree column from Undirected graphs
- Statistics reports now saved in Gephi projects
- New 'Rescale Weight' option in Preview, to force weight looks the same as Overview
- New 'Original' option for edges color in Preview, keeps the original edge color, coming from Partition for instance
- Copy and move nodes to new or existing workspace
- New preview presets
- Localization is now possible, and change language from Gephi
- When parallel edges are found during import, it now increases the weight of the edge by default
- Meta-edges have now a separate scale slider in Visualization settings, change how thick they are compared to normal edges
- Option in Ego Filter to include the parent node or not
- Ranking and Partition list of attributes are now sorted
- Ranking now updates itself with filtered graphs. Clicking on Apply will refresh bounds and the transformation (color, size) is correct
- It's now possible to drag a filter sub query to become a main query
- With dynamic attributes, Ranking, Partition, Visualization and Filters will use the current Timeline range to find values
- Edge weight can be dynamic, type DYNAMIC_FLOAT. Force Atlas layout will use the current Timeline range
- Filters are refreshed when the graph is modified, the current filter is reexecuted

### Bugfixes

- Wrong edge removed from Edge Weight filter (bug 603469)
- Filtering with convex hulls displayed (bug 541819)
- NullPointerException when filtering undirected graphs (bug 571153)
- NullPointerException on importing dynamic graph (bug 581872)
- gtk+ slider problem (bug 529913)
- Meta-edges are not displayed (bug 584283)
- Preview is not displaying meta-edges (bug 584289)
- Errors with Yifan Hu MultiLevel Layout on a filtered graph (bug 594643)
- Node Size Mode and Filter Paramaters don't save in project (bug 596430)
- Memory Leak in GEXF/GraphML Parser (bug 596872)
- Incorrect mutual edge weight on Preview (bug 610469)
- Progress is not shown when opening/saving project (bug 594644)
- Unable to cancel a project opening (bug 616415)
- Slowness on picking a partition entry (bug 519549)
- EdgeList Database Configuration is not saved (bug 571263)
- 'start' and 'end' attributes are missing when exporting dynamic GEXF (bug 521848)
- Partition "All Blacks" feature randomizes colors (bug 601066)
- Filtered graph not exported with "Select" pressed (bug 573685)
- Partition Settings in Filter not saved on switching workspaces (bug 616052)
- Opening Archived ZIP files is broken (bug 578876)
- Exception on clicking on 'Hierarchy' while running multilevel layout (bug 631663)
- GraphML importer doesn't import node labels data (bug 581629)
- Cannot save / saves as when opening a Gephi by doubleclick a graph in Windows (bug 583397)
- ForceAtlas and Fruchterman Reingold not layouting with meta-edges (bug 584286)
- Memory Leak in Graph Distance (bug 587450)
- NullPointerException when executing the "Eigenvector Centrality" Statistic (bug 589731)
- NullPointerException when switching between workspaces while a layout is running (bug 597458)
- Can't drag a filter sub-query to become a root query (bug 626495)
- Ranking parameters re-initialized at each new ranking (bug 594231)
- Ranking not refreshed when graph filtered (bug 632459)
- Node invisible (too small) when created with the node pencil (bug 574807)
- Error when opening Plugin Center (bug 616829)
- Can't select Postgresql driver in database import settings (bug 595223)
- Can't display edge weight as text (bug 603134)
- Import transform to Undirected don't merge weight (bug 603478)
- Right click on workspace after deleting a node throws "node can't be null" (bug 605947)
- In/Out degree metric doesn't work with undirected graphs (bug 606305)
- NullPointerException when selecting "--Choose a Layout" in the Layout ComboBox (bug 606964)
- Workspace Selection failed to refresh after closing workspace (bug 616814)
- Visualization selection color inversion between 'out' and 'both' color (bug 618726)
- 'Format' not recognized on DL import (bug 619069)
- Edit window not hidden on tabs (bug 552494)
- dynamic graph unrecognized if everlasting nodes (bug 555637)
- FileNotFoundException during saving of PDF file (bug 572876)
- "Node must be in the graph" error when importing a hierarchical graph with height greater than 1 (bug 577180)
- Auto-scale flips the graph (bug 577843)
- Impossible to cancel the Average Path Length Statistic calculation (bug 590226)
- Preview ratio not available at first time (bug 594176)
- Default selection of Nodes in Data Laboratory necessary (bug 594515)
- "CommandLineParsing null" message when error on opening file from command line or desktop (bug 594630)
- Can't import the same file twice in Welcome window (bug 598157)
- csv file export problem (bug 598767)
- Can't close project when generating a graph (bug 631341)
- Visualization size limitation (bug 602470)
- duplicate label in filter window (bug 604003)
- Partitions don't refresh when opening project not from Overview (bug 612902)
- z-coordinate not exported in GraphML (bug 614606)
- Wrong node positions when setting X or Y to zero (bug 615844)
- Selected filter query not properly refreshed in UI (bug 626483)
- Export to pdf background is always white (bug 583386)
- SVG files not listed in Export dialog (bug 626394)
- Wrong node size when Ranking has same min and max size (bug 631689)
- Read positions from dot files (bug 594793)
- Ranking and Partition parameters list not ordered (bug 594520)
- Node Degree not in Label Text settings (bug 598170)
- Wrong folder selected in the Export Panel when changing file type (bug 620337)
- Generating a graph on a previously loaded undirected graph (bug 624671)
- Wrong stroke weight when SVG imported in Illustrator (bug 626378)
- Filtering not refreshed when sub-queries set or removed (bug 594511)
- Errors at PDF export when labels have font size zero (bug 626865)
- Text not displayed in Preview (bug 627567)
- Edges native color are not displayed in Preview (bug 586237)
- Edge weight scale is different between Graph and Preview (bug 569329)
- Negative edges not rendered in Preview (bug 628223)
- Edges weight not merged with parallel edges (bug 648600)
- Partition filter automatically filters null value (bug 648600)
- Exception on opening project file (bug 648617)
- Ego Filter doesn't include the node itself (bug 649908)
- PDF Export only with default font (bug 651273)
- Nodes not unselected after turning off Selection on Filter Panel (bug 649920)

### API Changes

- Add a 'flatten()' method to 'HierarchicalGraph' to flatten the hierarchical graph and transform meta edges into regular edges.
- Add 'destroy(Filter filter)' in 'FilterBuilder' to receive notification when a filter query is removed and clean-up.
- Add 'MetaEdgeBuilder' in Graph SPI to allow custom builders. Add 'GraphSettings.setMetaEdgeBuilder()' in the graph model settings.
- Modify 'StatisticsModel' to store reports directly instead of 'Statistics' instance. As a consequence, the model has now a 'getReport()' and a 'getResult()' method that UI can use. The currently running statistics can now be get with a new 'getRunning()' method.
- Simplify and improve attribute events management. Event listeners now subscribe directly from the 'AttributeModel' instead of 'AttributeTable' and will receive events for all tables. Refactoring of the 'AttributeEvent' class with 'AttributeTable' as source and a new 'AttributeEventData' object as data. A new 'SET_VALUE' has been implemented for getting events when attribute values are set.
- Changes in 'AttributeRowFactory', the 'newNodeRow()' method now takes the owner object 'NodeData' as a parameter. Similarly for 'newEdgeRow()' and 'newRowForTable()'.
- Add 'getEdge(Node, Node)' in GraphAPI for consistency reasons.
- Changes in Processor SPI. The 'Processor' has now setters instead of a 'process()' method with parameters. How processors are created remains the same. Creation of a 'ProcessorUI' interface for processors settings configuration. A 'ProcessorUI' implementation provides a panel, which is shown when the import report is closing. The 'ProcessorUI' also allows to disable a processor with some conditions.
- Add 'getColor()' method in 'NodeDraft' and 'EdgeDraft'.
- Define the "Overview, "Data Laboratory" and "Preview" as perspectives. Create a new SPI for perspecives and perspective members. Members are simply the 'TopComponent' that belong to a perspective. Plugins can implement 'PerspectiveMember' to define the open and close behaviour.
- Add list/array types in Attributes API. All native types has now a related list type, except dynamic types. The list types inherits from 'AbstractList'.
- Changes in the way Import API deals with time intervals and dynamic data. Support for dynamic attributes has been added with a new 'addAttributeValue()' method in 'NodeDraft' and 'EdgeDraft'. For improving data cleanup possibilities, 'NodeDraftGetter' and 'EdgeDraftgetter' now returns an 'AttributeRow' instead of a list of attribute values only. Finally to profit from latest improvements, draft elements returns directly a 'TimeInterval' type instead of the list of slices. Methods with 'Slice' have been renamed to 'Interval' for consistency reasons.
- Add dynamic types into Attributes API. Dynamic types store values with a time interval and query can be customized with estimators. All dynamic types inherit from 'DynamicType'
- Graph API event management improvements. The 'GraphEvent' has now precise events, including 'ADD_NODES', 'REMOVE_NODES', 'ADD_EDGES', 'REMOVE_EDGES' and 'VISIBLE_VIEW'. A new 'GraphEventData' interface has been created to retrieve elements related to the events.
- Export API refactoring, inspired from ImportAPI. Create an 'ExporterBuilder' interface for exporter creation and different exporters: 'GraphExporter', 'VectorExporter', 'ByteExporter' and 'CharacterExporter' that covers common cases. The way exporters write data has been rationalized by using either 'java.io.Writer' (text) or 'java.io.OutputStream' (byte). The 'ExportController' has been improved to support all use-cases, including file, writer and stream export.
- Add Spigot support to the ImportAPI and SPI. Like 'DatabaseImporter', the 'SpigotImporter' interface is a new type of Importers. Modifications have also be made to the 'ImportController' to support spigot import.
- Refactoring and improvements in the Import API and SPI. The refactoring aim is to solve the singleton issue with importers and let users implement builders interface that create importers instance. Therefore an 'ImporterBuilder' interface has been created and should be registered with the '@ServiceProvider' annotation. The various importers types have been simplified and leave more choice to the implementations about how the input is managed. XML and Text file importers has been merged in a 'FileImporter' interface, working with the 'java.io.Reader'. Utility static methods, for instance <em>get Document from Reader</em> can now be found in a new 'ImportUtils' class. The 'ImportController' has been simplified for File import and now accepts 'java.io.Reader' also. The main improvement on these modules in the support of UI components for importers. The aim is to let importers define an 'ImporterUI' implementation to manage settings of these importers.
- Improvements in the GraphAPI identifiers management. The system is now storing String identifiers coming from users. New getters and setters methods have been created in 'Graph': 'Graph.setId(Node, String)', 'Graph.setId(Edge, String)', 'Graph.getNode(String)', 'Graph.getEdge(String)'. The 'NodeData.setId()' and 'EdgeData.setId()' methods have been removed, compatibility can't be kept. Factory has also be changed to allow to create elements with String ID directly, as it's not possible anymore to do it from 'NodeData'.
- Changes in AttributesAPI with event management. The lookup system in 'AttributeTable' has been replaced by a more traditional event management system, with new 'AttributeEvent' and 'AttributeListener' interfaces. The dispatch implementation is also now on a separate thread.
- Changes in Import modules to separate core and user interfaces. The 'ImportController' is now doing import task only and a new 'ImportControllerUI' is displaying the user interface (Report Panel). The 'ImportControllerUI' interface is located in the DesktopProject module and should be user to properly import file from Plugins. The 'ImportController' methods could be used from the toolkit.

## Gephi 0.7alpha4 (Apr 30 2010)

### New features

- GraphML export
- PDF Export. Special thanks to Jeremy Subtil.
- EgoNetwork Filter - Get neighbours at depth 1, 2, 3 and Max
- CSV export - Export adjacency list and matrix
- New LabelAdjust algorithm, faster and better quality. Thanks to Mathieu Jacomy.
- Watts-Strogatz Small World Generator

### Bugfixes

- Shortest Path and Heatmap tools not working for Undirected Graphs (bug 559866)
- Colors not imported in DOT (bug 559846)
- Can't import a CSV (bug 557305)
- Expansion/Contraction layout mispositionning when graph not centered (bug 561327)
- Statistics disabled when opening project not from Overview (bug 561483)
- Exception when drawing Filter's histogram (bug 570975)
- NullPointerException when filtering undirected graphs (bug 571153)
- Wrong current query on Filters Query Panel (bug 571274)
- Exception when changing filter parameter on a Operator (bug 571287)
- Error when importing nodes with empty labels in NET format (567263)
- ConcurrentModificationException when Import Report opens (bug 571871)
- GraphML importer doesn't detects Undirected graphs (bug 571875)
- Auto-scale doesn't recenters the graph (bug 571907)
- The Statistics report is not updated after executing the Metric again (bug 570971) (Thanks Paul-Antoine Bittner)
- "Node must be in the graph" error (bug 538701)
- Menubar is incomplete (bug 531505)
- Import throws Exception when file is invalid instead of Warning user (bug 530970)
- Settle command not working for Yifan Hu layouts (bug 562822)
- Heatmap tool description snippet corrected

### API Changes

- In PreviewAPI, the background color has been put in the PreviewModel. The PreviewController has been updated as well.
- Change FilterController.filter() to FilterController.filterVisible() and FilterController.select() to FilterController.selectVisible(). The controller is managing this process in a separate thread, with progress, and takes care of properties change. A more simple direct way to filter is required for headless access. The FilterController.filter() has been created and return the GraphView builded by the filter process.
- Expose basic visualization features in a newly created Visualization API. No proper visualization API exists but its creation is necessary to avoid implementation module dependencies.

## Gephi 0.7alpha3 (Mar 31 2010)

### New features

- Welcome screen, with recent opened files and samples.
- CSV Importer. Import adjacency lists.
- UCINET DL files importer. Import edge lists and full matrix.
- DOT Import. Import DOT GraphViz files. Support directed, undirected, labels and colors only. No subgraph support.
- Better memory starvation detection

### Bugfixes

- Edge Weight Filter cannot be chained (bug 523941)
- GEXF hierarchy not imported correctly (bug 522896)
- craches on closing project with dynamic bug 523110)
- Filter button still active across workspaces (bug 523124)
- Meta-Edges are not displayed after opening project (bug 526040)
- hierarchy1.gexf not imported correctly (bug 522896)
- Problems when restoring Ranking Window (bug 526126)
- NullPointerException on selecting Attribute Range filter (bug 526739)
- Incorrect range values when selecting Range Filters for the first time (bug 526745)
- Mutual edges not imported when undirected (bug 538991)
- NullPointerException at org.gephi.partition.impl.PartitionControllerImpl.transform (bug 538705)
- 0.6 project files are opened and causes errors (bug 539121)
- Export action stays disabled on Mac OS X (bug 539485)
- Export Dialog Give NullPointerException on OS X Snow Leopard (bug 526537)
- NullPointerException at org.gephi.graph.dhns.utils.DHNSSerializer.writeDhns (bug 545997)
- NullPointerException at org.gephi.visualization.opengl.text.TextModel.writeXML (bug 545993)
- When creating a new project, adding nodes doesn't work (bug 545993)
- drag tool becomes ineffective after color tool has been selected (bug 525054) (Thanks Eduardo Ramos)
- ClassCastException when opening a non-gephi project file (bug 551679)
- Labels are not visible when opening a Gephi file (bug 551694)
- Font not loaded on preview presets (bug 551877)
- Labels doesn't stay "proportionnal" after preview and export (bug 530175)
- NullPointerException when previewing a empty graph (bug 528563) (Thanks Eduardo Ramos)
- Visualization bars stays disabled if Gephi started from Preview (bug 552394)
- Partition error on filterted graph (bug 552563)

### Usability

- Modularity Statistics has now a description panel as well
- Opening and saving tasks have progress description now
- Filtering progress indication
- Selected query in filters is now more visible with it's node name in bold
- Tools can be unselected (Thanks Eduardo Ramos)
- New option in preview to have label size proportional to node size, like in Overview

### API Changes

- ImportAPI has now a "doImport" method with "InputStream"
- New "AttributeUtils" methods.
- Add "getWeight()" in EdgeDraft to let importers increment weight.

## Gephi 0.7alpha2 (Feb 17 2010)

### New features

- Better edge weight support. Weight is not modified anymore by "Auto-scale" option on Import.
- Better nodes/edges counting. Counts only visible nodes.
- Improve Statistics/Metrics settings panels. Add description and documentation about metrics and their settings.
- Project save/load has been corrected. Note that compatibility with 0.7alpha1 is broken.
- Fix AutoUpdate mechanism. Further updates will be available through built-in updater.

### Bugfixes ==

- Application freeze when importing file on Linux - bug 519423
- Layout Window cannot be restored when has been undocked - bug 519424
- anner not visible on Mac OS X and Linux - bug 522403
- Preview doesn't hide filtered elements - bug 522402
- Project load/save interface fails - bug 522889
- empty node label causes incorrect error message during import "unkown node id" - bug 519254
- In GDF export, removing a column doesn't remove the comma - bug 519810
- In GDF export, the Id field is badly escaped - bug 519820
- Attribute edge filtering misbehavior - bug 522771
- Context data doesn't work on Undirected Graph - bug 522886
- Dynamic filter displays 0 node - bug 523128
- options tag works only for one-letter values - bug 519252
- Favorites, Properties and Output menu appears in Window and cannot be closed - bug 521400
- improved performances when adjusting the range with the mouse - bug 521939
- fixed bug when dealing with dynamic data types other that date - bug 521544
- fixed bug with the visual repartition of graduations - bug 521941

### Usability

- Node and Edge toggle button in VizBar have the same tooltip text
- Report Panel (Import) is vertically extensible

## Gephi 0.7alpha (Feb 08 2010)

### New features

Modularize application, extensible by plugins
- Built on top of Netbeans Platform
- Plugins center, auto-update
- Graph API, with grouping and meta-edges support
- Directed, Undirected and Mixed graph support
- Hierarchical graphs support, with tree opearions
- Automatic meta-edges computation, without recomputing
- Fast traversal, with user-oriented interators
- View maintaining in HierarchicalGraph, expand/retract operation
- Streaming ready, logarithmic update time
- Thread-safe
- SubGraph support, with memory efficienty
- Layout API, real-time layout, autostop, presets and branding
- Fruchterman Reingold
- ForceAtlas
- YifanHu
- YifanHu proportionnal
- YifanHu Multilevel (see below)
- Label Adjust
- Random
- Rotate
- Expand/Contract
- Multi-level graph layout algorithms, Yifan Hu (Google Summer of Code)
- Coarse/Refine layout, Barnes-Hut
- Dynamic network support (Google Summer of Code)
- TimeInterval type
- Dynamic range filter
- GEXF File format "start" & "end" attributes support
- Timeline component, with live update
- Statistics/Metrics, with HTML report panel (Google Summer of Code)
- Clustering Coefficient
- PageRank
- HITS
- Distance
- Average shortest path
- Diameter
- Betweness
- Closeness
- Modularity (Community detection)
- Degree Distribution
- Vectorial preview, SVG Export (Google Summer of Code)
- Map preview, with zoom and pan (Processing)
- Settings properties sheet
- Presets management
- Mature OpenGL visualization engine
- Mouse zoom
- Rectangle selection
- Edge thickness
- 2D shape design, and rectangle
- Convex hulls
- Self-loops
- Events model
- Settings, visualization bar
- Highlighting
- Custom selection
- Edge labels
- Lighting settings
- Optimization and safer synchronization
- High-res screenshot
- Full Antialiased Custom resolution screenshot
- Filters API, dynamic filtering with complex queries grammar
- Degree range, In-Degree range, Out-Degree range, Mutual Degree range
- Edge weight
- Partition set
- Partition count
- Non-null
- Equals (Bool, String, Numbers...), with regex support
- Attributes Range
- UNION & INTERSECTION operators
- Project API, project and workspace management
- Modular workspace model, based on lookup
- Gephi project files, with ZIP Compression
- Open Project from Drag&Drop and command line
- Crash reporter
- Import API, import from files, streams and database
- Secure workflow, separated from main structure, containers load/unload
- Import warnings/error management
- Report panel, show issues and logs
- Processor interface, Full or Append
- File formats: GEXF 1.0, GEXF 1.1, GDF (magic regex), GraphML, NET, GML, TLP
- Database: EdgeList Database, basic querying
- Generator API, host graph generators
- Random graph
- Export API, export interface (file, db, stream)
- Neat integration with UI
- Graph file: GEXF, GDF
- Vectorial: SVG (from Preview)
- Data Laboratory, data table view with dynamic filtering
- Tools API, with visualization events engine
- Brush
- Pencil
- HeatMap
- Edit
- Painter
- ShortestPath
- Sizer
- Partition API, automatic partition on attributes
- Color transformer, with randomize colors and sorting
- Partition Pie chart
- Group by partition (Attribute Clustering)
- Ranking API, put signs from metrics and attributes
- Transformers interface, extendable
- Color tranformer: gradient color UI and palette utils (right-click)
- Size transformer: gradient size
- Label Color transformer: gradent label color
- Label Size transformer: gradient label size
- Automatic min/max computation, Range parameter
- Spline Editor, for transformer interpolation
- Result Panel, with special color renderer. Take panel screenshot (right click)
- Clustering API, host clustering algorithm
- MCL (experimental)
- Results as tree, group/ungroup
- Redevelop UI
- Packaging
- Splash Screen
- Windows Installer (InnoSetup)
- Mac OS X DMG archive