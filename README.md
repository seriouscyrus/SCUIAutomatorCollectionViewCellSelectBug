# SCUIAutomatorCollectionViewCellSelectBug

This project shows a bug with the XCode 9.0 UI Automator and selecting cells in collection views.

The only test in the project should pass, when a cell is tapped in the collection view, the segue should be triggered and the test will pass.

Instead the tap command is ignored, and the test fails as the label in the 2nd view controller can't be found.
