# Wallpaper-on-Mac (only 'scene' and 'video')
1. 从Wallpaper Engine 选择video/sence种类壁纸导出

2. video类型不做更改

3. scene需要利用RePKG解包从而得到video。方法：打开Windows Terminal: path/RePKG.exe extract path/filename.pkg -o directoryname_path
   需要注意的是这里的scene文件不是直接导出的，需要再wallpaper 里通过“导出.mpkg 文件”的方式得到pkg文件，并且在导出时选择“高性能”，然后导出后将“.mpkg”改为".pkg"文件

5. 打开Mac的Dynamic Wallpaper

6. 导入本地视频文件

## Reference
1. https://blog.csdn.net/Enderman_xiaohei/article/details/102933300
3. https://steamcommunity.com/sharedfiles/filedetails/?id=2277660793
