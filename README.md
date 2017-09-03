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
4. Extract DataTree to this folder
/!\ Make sure that "rev_DataTree_Launcher.rev" file is at the root of the extension folder, LiveCode
    will automatically execute this file that will load DataTree.

# Documentation

Once DataTree is opened, click "Help Center".

# Embeed DataTree in your application

You need to embeed the stack "DataTree.res\System\Data Tree Library.rev" within your application,
or dynamically load it.

Then call in your initialization procedure:
`open invisible stack "Data Tree Library"`

# Tests

DataTree doesn't have an automated test suite. For each release a set of manual tests cases
need to be executed, and the most important one is to have [NativeDoc 3](https://github.com/dagirard/NativeDoc) to run flawlessly.

Before a push request can be made, you will have to perform manual tests with
NativeDoc 3, and mark them as you didn't introduced a regression.

# How to contribute?

Due to his work, the original author "Damien Girard" is very very busy, but if you
are an experienced LiveCode and DataTree developper, then don't hesitate
to reach him on GitHub to become a main contributor to the project.

GitHub page: https://github.com/dagirard/datatree

# License

DataTree is under the MIT license.
A complete copy is available in the file LICENSE.TXT