# Background_Removal_C++
Background Removal using C++ and OpenCV. Replacing the background with a video

This version is imporoved in removeing the background without great noise.

How to compile:

Windows:
```
How to compile:
"F:\\Program Files\\Microsoft Visual Studio\\2022\\Community\\VC\\Auxiliary\\Build\\vcvarsall.bat" x64
cl /EHsc /I"F:\AI_Componets\OpenCV\build\install\include" background_subtraction.cpp /link /LIBPATH:"F:\AI_Componets\OpenCV\build\install\x64\vc17\lib" opencv_core500.lib opencv_imgproc500.lib opencv_highgui500.lib opencv_videoio500.lib opencv_imgcodecs500.lib
```

Note:
Similar syntax can be used to compile in Unix/Linux systems.
