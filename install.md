# triton不支持windows
INFO: pip is looking at multiple versions of autoawq to determine which version is compatible with other requirements. This could take a while.
ERROR: Could not find a version that satisfies the requirement triton (from autoawq) (from versions: none)
ERROR: No matching distribution found for triton

参考下面的文章
https://zhuanlan.zhihu.com/p/27131210741
https://triton.csdn.net/6774fb462db35d1195281436.html

下载 Visual Studio Installer，下载地址为：https://aka.ms/vs/17/release/vs_BuildTools.exe
安装单个组件，参考这篇文章 https://blog.csdn.net/m0_57309959/article/details/139815240
安装单个组件
windows 11 SDK 的最新版
MSVC v143 VS 2022 C++ x86/64 生成工具（最新）

系统环境变量

PATH
C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.43.34808\bin\Hostx64\x64
C:\Program Files (x86)\Windows Kits\10\bin\10.0.26100.0\x64

LIB
C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.43.34808\lib\x64
C:\Program Files (x86)\Windows Kits\10\Lib\10.0.26100.0\ucrt\x64
C:\Program Files (x86)\Windows Kits\10\Lib\10.0.26100.0\um\x64

INCLUDE
C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.43.34808\include
C:\Program Files (x86)\Windows Kits\10\Include\10.0.26100.0\ucrt
C:\Program Files (x86)\Windows Kits\10\Include\10.0.26100.0\um
C:\Program Files (x86)\Windows Kits\10\Include\10.0.26100.0\winrt
C:\Program Files (x86)\Windows Kits\10\Include\10.0.26100.0\cppwinrt
C:\Program Files (x86)\Windows Kits\10\Include\10.0.26100.0\shared

安装TRITON
pip install https://github.com/woct0rdho/triton-windows/releases/download/v3.2.0-windows.post10/triton-3.2.0-cp310-cp310-win_amd64.whl
