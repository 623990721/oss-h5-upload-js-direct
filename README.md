# oss-h5-upload-js-direct
OSS web直传---直接在JS签名

1. 基于plupload封装
2. 支持html5,flash,silverlight,html4 等协议上传
3. 可以运行在PC浏览器，手机浏览器，微信
4. 可以选择多文件上传
5. 显示上传进度条
6. 可以控制上传文件的大小
7. 最关键的是，让你10分钟之内就能移植到你的系统，实现以上牛逼的功能！
8. 注意一点，bucket必须设置了Cors(Post打勾）,不然没有办法上传
9. 注意一点，把upload.js 里面的host/accessid/accesskey改成您上传所需要的信息即可
10. 此方法是直接在前端签名，有accessid/accesskey泄漏的风险, 线上生产请使用后端签名例子点击查看详细文档
https://help.aliyun.com/document_detail/oss/practice/pc_web_upload/js_php_upload.html

