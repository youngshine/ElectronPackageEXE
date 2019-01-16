## 基于Electron打包.exe的Windows应用脚本说明

1、shell脚本使用electron的打包指令，双击electron工程root目录下的dobiPackageEXE文件，即可打包

2、双击dobiPackageEXE文件后，输入打包.exe文件的包名及需要打的版本号

3、如果双击后提示无权限，请执行：sudo chmod +x dobiPackageEXE，赋予dobiPackageEXE文件权限

备注：由于用于打包的指令中已经写死了.exe的包的icon为：icon.ico文件，如果需要更换icon，请按照icon.ico的命名来

