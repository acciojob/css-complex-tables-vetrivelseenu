# CSS Complex Tables

Create a Gallery using flex properties which adjusts image according to its size as shown in image below:
![demo image](https://storage.googleapis.com/acciojob-open-file-collections/7aeb5127-c5e5-414b-bf53-503f2cafd20f_Screenshot%202023-06-25%20at%205.19.55%20PM.png)

## Instructions
1. Your table should have a header (<thead>) containing six headers (<th>) as follows:
`Firm`
`Org`
`Lob`
`Sub Lob`
`Business Plans`
`Business Components`
2. Your table should have a body (<tbody>) that includes twelve rows (<tr>).
3. Populate the first row with the following data cells (<td>):
The first cell should have a content of `XYZ` and a `rowspan` of `11`.
The second cell should have a content of `CST` and a `rowspan` of `5`.
The third cell should have a content of `CT` and a `rowspan` of `3`.
The fourth cell should have a content of `ADS`.
The fifth cell should have a content of `1`.
The sixth cell should have a content of `10`.
4. The sixth row should be a `sub-total-row`. In this row:
The `first` cell should have a `class` of `sub-total-text` and a content of `Sub Total`. It should also have a `colspan` of `3`.
The `fourth` cell should have a content of `6`.
The `fifth` cell should have a content of `15`.
5. Add other rows and populate them with sample data while adhering to the rowspan and colspan properties.

## Styling Information
1. The table should have a `border` with a `width` of `1px`, `solid style`, and `orange` color.
2. The header cells should have a `background-color` of `dark grey (#888888)` and `white` text `color`.
3. Both header cells and data cells should have `text aligned` to the `center`, a `border` with a `width` of `1px`, `solid style`, and `orange color`. They should also have `padding` of `3px 5px`.
4. In the `sub-total-row`, the cell with class `sub-total-text` should have `text aligned` to the `right`.

