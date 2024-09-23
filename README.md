# M3U8-Uploader
借助图床转存m3u8视频内容，并生成新的m3u8文件

## ts播放格式
得益于HLS协议版本4推出的#EXT-X-BYTERANGE，它可以只读取指定字节范围，从而让播放器跳过文件伪装标识

## 特点
1. 文件伪装上传
2. 分片AES解密
3. 断点续传
4. 网络出错重连

![截图_20240923233206](https://github.com/user-attachments/assets/42b9d16d-1787-4390-848c-bf932eabb85e)
