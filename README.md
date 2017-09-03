-----------------------------------------------
DataTree
-----------------------------------------------
DataTree is a tree view component for LiveCode.

DataTree allows you to place native lookalike tree controls inside your LiveCode application.

# How to get started?

Download the repository, and extract it to your LiveCode extension folder.

You can locate the user extensions folder by doing so:
1. Open LiveCode preferences
2. In the Files & Memory preferences pane you can find the full path to the User Extensions folder. 
3. Open this folder in your system file browser.
4. If it doesn't exists, create a "Plugins" subfolder.
5. Extract DataTree into the "Plugins" subfolder.

**Make sure that "rev_DataTree_Launcher.rev" file is at the root of the extension folder, LiveCode will automatically execute this file that will load DataTree.**

# Documentation

Once DataTree is opened, click "Help Center".

# Embeed DataTree in your application

You need to embeed the stack "DataTree.res\System\Data Tree Library.rev" within your application, or dynamically load it.

Then call in your initialization procedure:
`open invisible stack "Data Tree Library"`

# Tests

DataTree doesn't have an automated test suite. For each release a set of manual tests cases need to be executed, and the most important one is to have [NativeDoc](https://github.com/dagirard/NativeDoc) to run flawlessly.

Before a push request can be made, you will have to perform manual tests with
NativeDoc 3, and mark them as you didn't introduced a regression.

# How to contribute?

If you wish to contribute to development of DataTree, you must sign the [Contributor's Agreement](http://www.nativesoft.net/oss/contribute).  This agreement is required because the DataTree project is dual-licensed both under the GPLv3 and a commercial (closed-source) license; you need to give Damien Girard permission to use your submissions in this way.

**Note:** Any pull-requests from individuals who have not signed this agreement will be refused.

The workflow is a typical git workflow, where contributors fork the [dagirard/DataTree](https://github.com/dagirard/datatree) repository, make their changes on a branch, and then submit a pull request.

# License

DataTree is under the GPL 3.0 license.
A complete copy is available in the file COPYING.TXT

If you wish to develop a commercial application using DataTree,
please contact sales@nativesoft.net for an enquiry.

NativeSoft, DataTree, NativeDoc, NativeGeometry, the NativeSoft logo, the DataTree logo, the NativeGeometry logo, the NativeDoc logo, NativeSpeak, are registered trademarks of Damien André Edouard Girard, registered in France and other countries.