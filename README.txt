Handmade Quake, tutorial from Philip Buuck https://www.youtube.com/playlist?list=PLBKDuv-qJpTbCsXHsxcoSSsMarnfyNhHF

Notes: On Windows7 I had to set the followings paths to (Thanks MS Universal CRT):

INCLUDE: $(VC_IncludePath);$(WindowsSDK_IncludePath);C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\include;C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\atlmfc\include;C:\Program Files (x86)\Windows Kits\NETFXSDK\4.6\Include\um;$(IncludePath);C:\Program Files (x86)\Windows Kits\10\Include\10.0.10150.0\ucrt

LIBRARY:$(VC_LibraryPath_x86);$(WindowsSDK_LibraryPath_x86);$(NETFXKitsDir)Lib\um\x86;C:\Program Files (x86)\Windows Kits\10\Lib\10.0.10150.0\ucrt\x86

For compiling on Windows 10 where this project was started, the paths were originally:

INCLUDE: $(VC_IncludePath);$(WindowsSDK_IncludePath);
LIBRARY: $(VC_LibraryPath_x86);$(WindowsSDK_LibraryPath_x86);$(NETFXKitsDir)Lib\um\x86

