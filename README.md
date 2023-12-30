# Counter Gradient

## Purpose
A replacement for using counters as gradient bars in Clickteam Fusion.

## Compiling:

### Requisites:
FXC (apart of the [Windows SDK](https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/))

### Windows: 
1. Insert `FXC.exe` into the root directory or insert the path for FXC in line 11 of `CompileShader.bat`
2. Run `CompileShader.bat`
3. You should get a successful compilation message:
```
fxc.exe "counter_gradient.hlsl" /nologo /WX /Ges /Qstrip_reflect /Qstrip_debug /Tps_4_0 /Eps_main /Fo"funky_fisheye.fxc"
compilation object save succeeded; see ROOT\funky_fisheye.fxc

fxc.exe "counter_gradient.hlsl" /nologo /WX /Ges /Qstrip_reflect /Qstrip_debug /Tps_4_0 /Eps_main_pm /Fo"funky_fisheye.premultiplied.fxc"
compilation object save succeeded; see ROOT\funky_fisheye.premultiplied.fxc
.
Shaders compiled ok
```

## TODO
- Android Support
- MacOS Support
- IOS Support
