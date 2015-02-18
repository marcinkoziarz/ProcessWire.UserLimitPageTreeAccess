# ProcessWire.UserLimitPageTreeAccess
Module for ProcessWire CMF that allows limiting user access to a certain page and its children.

## What's working
After installing module administrator can select a page that will be new root of Page Tree in administration panel.
It's a quick way to limit user editing permissions to a certain page and its children and still have per-template permissions applied.

## What needs to be done
By far, only Page Tree is being limited ("Pages" tab in ProcessWire administration panel).
There's a need to add a hook for checking privileges when editing page giving page ID by GET variable (remember that template permissions are still working!).


