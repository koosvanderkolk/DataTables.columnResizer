Column Resize plugin for DataTables - v0.5

1) Make sure the table headers have a right border of about 3px. These borders are the 'handlers' by which the columns can be resized.
2) Put a 'z' in your dataTables config to enable the resizing $(tableElement).dataTable( {"sDom": 'zrtSpi'});

This is the first version, which needs a lot of testing! Do not use for production!

