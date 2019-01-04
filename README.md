# Project Description

This fork of Dnn.Platform was created to fix a bug that I was experiencing where all pages on DotNetNuke sites would intermittently return 404 responses. 

I have created a pull request to submit the fixes made to the Dnn.Platform project so that, hopefully, it will be included in future releases of the platform. The pull request can be found [here](https://github.com/dnnsoftware/Dnn.Platform/pull/2032).

Further information about the issue can be found on the DNN issue tracker [here](https://dnntracker.atlassian.net/browse/DNN-10795)

Subsequently, I've had a number of requests from people to include this fix into previous versions of the DNN platform so that they no longer experience the 404 error on earlier versions. As such I've updated the code in all versions of DotNetNuke that were released between version 8.0.4 and 9.2.2 so that others can use this code to build a version of the DotNetNuke.dll that includes the fix.

## Updated Source code

If you're able to build the DotNetNuke platform from source code, updated code can be built from the following branches:
* [8.0.4 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/8.0.4)
* [8.0.4-patches branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/8.0.4-patches)
* [9.0.0 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.0.0)
* [9.0.0.patches branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.0.0.patches)
* [9.0.1 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.0.1)
* [9.0.2 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.0.2)
* [9.1.0 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.1.0)
* [9.1.1 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.1.1)
* [9.1.1-patches branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.1.1-patches)
* [9.2.0 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.2.0)
* [9.2.1 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.2.1)
* [9.2.2 branch](https://github.com/cameron-moore/Dnn.Platform/tree/release/9.2.2)

## Compiled DLLs
For those that would prefer not to have to build the code themselves I've also provided a compiled version of the DotNetNuke.dll that incorporates the changes. These can be downloaded using the following links.

* [DNN 8.0.4.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/8.0.4.0/DotNetNuke.dll)
* [DNN 8.0.4.226](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/8.0.4.226/DotNetNuke.dll)
* [DNN 9.0.0.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.0.0.0/DotNetNuke.dll)
* [DNN 9.0.0.1002](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.0.0.1002/DotNetNuke.dll)
* [DNN 9.0.1.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.0.1.0/DotNetNuke.dll)
* [DNN 9.0.2.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.0.2.0/DotNetNuke.dll)
* [DNN 9.1.0.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.1.0.0/DotNetNuke.dll)
* [DNN 9.1.1.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.1.1.0/DotNetNuke.dll)
* [DNN 9.1.1.129](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.1.1.129/DotNetNuke.dll)
* [DNN 9.2.0.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.2.0.0/DotNetNuke.dll)
* [DNN 9.2.1.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.2.1.0/DotNetNuke.dll)
* [DNN 9.2.2.0](https://github.com/cameron-moore/Dnn.Platform/raw/bug/DNN-10795/Fixed-DLLs/9.2.2.0/DotNetNuke.dll)

Whilst this code has fixed the 404 issues on my own sites & others I make no guarantees that is will work for yours. As always, backup your site before applying any changes so that can revert to the backup if things go wrong.
