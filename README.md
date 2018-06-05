
cornerstone WADO Image Loader
=============================

 一个通过 HTTP (WADO-URI) 或 DICOMWeb (WADO-RS) 的 "DICOM P10 instances" 基于[cornerstone](https://docs.cornerstonejs.org/) 的医学影像解析程序。
 可以将 [cornerstone](https://docs.cornerstonejs.org/) 与 WADO-URI servers、DICOMWeb servers 或 任何返回 DICOM P10 instances (例如: [Orthanc](http://www.orthanc-server.com/) 或 自定义 servers )的任何基于 HTTP 的 servers 集成在一起。

故障排除
---------------
使用过程中遇到遇到问题[联系我](https://github.com/bianliuzhu/DicomParsing),看到后第一时间回复.

使用方法
---------------
* 1.安装 [ XAMPP ](https://www.apachefriends.org/zh_cn/download.html)

* 2.清空 [ htdocs ] 目录下所有东西[必须清空], tdocs 在 XAMPP 安装目录下仔细找哦! 我的在: [D:\xampp\htdocs]

* 3.将 DICOM Parsing 下载到 htdocs 目录下 [并解压!必须解压!]

* 4.打开浏览器 在地址栏输入 127.0.0.1 点击 DICOMParsing 文件夹 

* 5.看控制台是否有报错, 没有的话[DICOMParsing 跑起来了]

注意
-------
可能 有的时候 会报错 没有找到 cornerstoneWADOImageLoader.js 这样的错 都备好了 打开后 [ CTRL+S] 到相目录就好了

未压缩:

* [cornerstoneWADOImageLoader.js](https://unpkg.com/cornerstone-wado-image-loader/dist/cornerstoneWADOImageLoader.js)
* [cornerstoneWADOImageLoaderCodecs.js](https://unpkg.com/cornerstone-wado-image-loader/dist/cornerstoneWADOImageLoaderCodecs.js)
* [cornerstoneWADOImageLoaderWebWorker.js](https://unpkg.com/cornerstone-wado-image-loader/dist/cornerstoneWADOImageLoaderWebWorker.js)

压缩版:

* [cornerstoneWADOImageLoader.min.js](https://unpkg.com/cornerstone-wado-image-loader/dist/cornerstoneWADOImageLoader.min.js)
* [cornerstoneWADOImageLoaderCodecs.min.js](https://unpkg.com/cornerstone-wado-image-loader/dist/cornerstoneWADOImageLoaderCodecs.min.js)
* [cornerstoneWADOImageLoaderWebWorker.min.js](https://unpkg.com/cornerstone-wado-image-loader/dist/cornerstoneWADOImageLoaderWebWorker.min.js)
