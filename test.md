---
title: Excel File Structure
markmap:
  colorFreezeLevel: 2
---

## Excel File (.xlsx)

### Root Files
- `[Content_Types].xml`
  - Defines content types
- `_rels/.rels`
  - Relationships between files

### `xl` Folder
- `workbook.xml`
  - Workbook structure
- `sharedStrings.xml`
  - Stores unique strings
- `styles.xml`
  - Styles for cells (fonts, borders, colors)
- `worksheets/`
  - `sheet1.xml` (Sheet 1)
  - `sheet2.xml` (Sheet 2)
- `theme/`
  - `theme1.xml` (Theme settings)
- `drawings/`
  - `drawing1.xml` (Drawing or chart 1)
  - `drawing2.xml` (Drawing or chart 2)
- `_rels/`
  - `workbook.xml.rels` (Relationships for workbook)

### `docProps` Folder
- `core.xml`
  - Metadata (author, creation date)
- `app.xml`
  - Application-specific properties (e.g., number of sheets)

### Optional Folders
- `customXml/`
  - `item1.xml`
  - `itemProps1.xml`
- `charts/`
  - `chart1.xml`
  - `chart2.xml`

