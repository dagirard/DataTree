-----------------------------------------------
DataTree
-----------------------------------------------
DataTree is a tree view component for LiveCode.

DataTree allows you to place native lookalike tree controls inside your LiveCode application.

# How to get started?

Download the repository, and extract it to your LiveCode extension folder.

You can locate the user plugins folder by doing so:
1. Open LiveCode preferences
2. In the Files & Memory preferences pane you can find the full path to the User Extensions folder. 
3. Open this folder in your system file browser.
4. If it doesn't exists, create a **"Plugins"** subfolder.
5. Extract DataTree into the **"Plugins"** subfolder.
6. Start LiveCode and the DataTree plugin window will be displayed.

**Make sure that "rev_DataTree_Launcher.rev" file is at the root of the Plugins folder, LiveCode will automatically execute this file that will load DataTree.**

# Documentation

Once DataTree is opened, click "Help Center".

# Embeed DataTree in your application

You need to embeed the stack "DataTree.res\System\Data Tree Library.rev" within your application, or dynamically load it.

Then call in your initialization procedure:
`open invisible stack "Data Tree Library"`

# Tests

DataTree doesn't have an automated test suite. For each release a set of manual tests cases need to be executed. 

The first one is to have all the samples in the Arboretum to work perfectly.

Then the second most important is to have [NativeDoc](https://github.com/dagirard/NativeDoc) to run flawlessly.

# How to contribute?

The workflow is a typical git workflow, where contributors fork the [dagirard/DataTree](https://github.com/dagirard/datatree) repository, make their changes on a branch, and then submit a pull request.

**Note:** Before a push request can be made, you will have to perform manual tests with the arboretum and NativeDoc, and mark them as you didn't introduced a regression.

# License

DataTree is under the LGPL 3.0 license.
A complete copy is available in the file COPYING.TXT, COPYING.LESSER.TXT

NativeSoft, DataTree, NativeDoc, NativeGeometry, the NativeSoft logo, the DataTree logo, the NativeGeometry logo, the NativeDoc logo, NativeSpeak, are registered trademarks of Damien André Edouard Girard, registered in France and other countries.