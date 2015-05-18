# visual_studio_config
<h1>OpenCV config:</h1>

Origin: http://my.phirobot.com/blog/2014-02-opencv_configuration_in_vs.html <br />

1. Create environment variable "OPENCV_DIR" to your opencv build path. (EX: D:\opencv\build) <br />

2. Append text ";%OPENCV%\x86\vc11\bin" in environment variable "Path". (x86/x64; vc10/vc11/vc12 => visual studio 2010/2012/2013) <br />

3. Modify the ".props" file to meet your config. (LibraryPath: vc10/vc11/vc12 => visual studio 2010/2012/2013; AdditionalDependencies: your opencv version)
