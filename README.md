# QRcode_Scan
Android利用zxing用相机识别二维码，打开闪光灯，以及识别本地图片二维码，解压后用Android可直接打开。附教程：https://blog.csdn.net/mountain_hua/article/details/80699778

# QRcode_Scan
2018-09-08 改动
zxing扫描本地二维码/条形码
本次针对以下2个问题：
一：读取本地图片时，取不到数据的问题。
参考
android 获取本地图片路径失败,cursor.getString(column_index);返回null
https://blog.csdn.net/m0_37559046/article/details/55517618
二：取到本地图片数据后，获取Result数据时报NotFoundException异常问题。
参考
Android Zxing 读取本地图片不得不说的坑
https://blog.csdn.net/qq_28057541/article/details/52119896
