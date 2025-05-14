# OMX
OMX Viewer gemaakt in opdracht van SIVMO

# Usage guide

## Navigating

This application provides three pages: the "Open OMX" page, the "Help" page, and
a page for viewing an OMX file (once a file has been selected). The sidebar on
the left can be used for navigating between these pages. When on the viewing
page, the sidebar can be closed and reopened using the double arrows in the
bottom-left corner. Use the button in the top-right corner to toggle fullscreen
mode.

## Opening an OMX file

Open a new OMX file by first navigating to the "Open OMX" page using the sidebar
on the left and the clicking on the "Select OMX File" button. By default, only
files with the ".omx" extension will be shown. Select "All Files" in the
dropdown in the bottom-right corner of the filepicker to be able to pick any
file.

## Viewing an OMX file

After selecting a valid OMX file, up to three lists will be shown: two for the
row and column header mappings (only if they are included in the OMX file), and
one for the matrices. Each of the lists can be collapsed. To filter matrices by
text appearing anywhere in their names, type in the searchbar that accompanies
the list.

## Viewing a matrix

Select a matrix from the list to display its contents (this may take several
seconds for very large matrices). You can navigate the matrix using the
following standard input methods:

- Dragging the scrollbars
- Mousewheel scroll (hold _Shift_ to scroll horizontally)
- Two-finger scroll on touchpad
- Arrow keys

### Viewing options

Two viewing options are available in the bar above the matrix viewport:

- The _Cell width_ can be adjusted. This is especially useful when dealing with
  very long column headers.
- The _Decimal Precision_ can be set to the desired precision, the default is
  set to 3.

### Header mappings

By default, the rows and headers are labeled by numbers counting up from 1. To
apply the header mappings present in the OMX file (if any), select them from the
"Row headers" and "Column headers" lists. Header mappings can be deselected as
well (by clicking on them again). When a row header is too long and cannot be
shown in its entirety, scroll it horizontally (by holding shift when using a
mousewheel, or using two fingers on a touchpad) while hovering over its text
with the mouse cursor.

## Exporting to CSV

To export a selected matrix, use the menu in the top right corner. The row and
column headers are included in the export. Exporting a very large matrix may
take several minutes.
