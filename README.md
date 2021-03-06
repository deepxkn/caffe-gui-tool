#Caffe Gui Tool
==============
This a node based tool for creating caffe networks. It works inside the graphics application 'blender' as a plugin. The reason for this is blender's highly stable, and universally compatible node editor.
##Important
**CGT features change regularly. If you update and your nodetree no longer compiles, all the nodes in your tree must be Re-added. A prototxt load feature will be added in the next update to make this process redundant.**

###Potentially useful features:
* Autonaming of top,bottom, and layer names
* Visual editing of later properties
* Reliable duplication of layers with SHIFT+D
* Saving & Loading nodetrees in blender's native 'xxxx.blend' format for later editing
* Generation of Train_test, _deploy, _solver, and the training .sh script

###WIP features:
* .prototxt import
* Training network within blender, plotting train & test error

For [**installation instructions**](http://bit.ly/1AnTVD2) please see [http://chasvortex.github.io/caffe-gui-tool/](http://bit.ly/1AnTVD2)

####ConvNet

![alt tag](https://camo.githubusercontent.com/31e4f9dd627afa62bb0366eae79e9254dfb94934/68747470733a2f2f646c2e64726f70626f7875736572636f6e74656e742e636f6d2f752f31303836303234342f676875622f53637265656e73686f7425323066726f6d253230323031342d31302d31392532303133253341333025334132312e706e67)

####Autoencoder

![alt tag](https://camo.githubusercontent.com/d28a002ce2c7139877f2c1e8fa3f935ed57fa055/68747470733a2f2f646c2e64726f70626f7875736572636f6e74656e742e636f6d2f752f31303836303234342f676875622f53637265656e73686f7425323066726f6d253230323031342d31302d31392532303133253341333025334131352e706e67)
