1.渠道打包工具的使用


  修改 autopkg_wof*.bat
  使用说明：
  java -jar autotools.jar orgapk  pkgname appname(可选) iconname(可选)
  实例：
  (1) 只修改应用包名
      java -jar autotools.jar wof.apk com.clemu.wofclc

  (2) 修改应用包名和应用名称
      java -jar autotools.jar wof.apk com.clemu.wofclc 三国志2014
  
  (3) 修改应用包名、应用名称、应用ICON
      java -jar autotools.jar wof.apk com.clemu.wofclc 三国志2014  icon_wof.png
  参数说明：
  (1)  orgapk(wof.apk)                   apk文件名
  (2)  pkgname(com.clemu.wofclc)         应用包名
  (3)  appname(三国志2014)               应用名称
  (4)  icon(icon_wof.png)                应用ICON名称(放到打包工具所在目录即可)
  (5)  map.txt 里面修改渠道列表(CLA 潘应云开头，CLB 刘德华开头 CLC 韩皖开头 CLD 胡志宇开头)
