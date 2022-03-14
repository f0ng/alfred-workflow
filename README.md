# alfred-workflow
自用的一些alfred工作流
## stringlen
查看字符串的长度
```
len e10adc3949ba59abbe56e057f20f883e
```
<img width="576" alt="1" src="https://user-images.githubusercontent.com/48286013/148642618-39c2ad2b-3e7f-4489-8e99-c96d1a54d9b0.png">

## timestamp
查看时间戳

<img width="576" alt="2" src="https://user-images.githubusercontent.com/48286013/148642635-8245eccb-2787-4d1b-a082-1b26182897ab.png">

```
tt 1641614631877
```

<img width="573" alt="3" src="https://user-images.githubusercontent.com/48286013/148642638-8fe3f826-8d49-4dd6-a630-885b7499ca67.png">

```
tt 1641614631
```
## qrcode
调用/usr/sbin/screencapture进行截图


<img width="347" alt="5" src="https://user-images.githubusercontent.com/48286013/148642654-731136bd-bc0e-4ed0-ab56-b70f0537fad8.png">

也可以直接生成二维码

<img width="329" alt="6" src="https://user-images.githubusercontent.com/48286013/148642658-a73dbdcc-82bd-4710-85e6-69f3a2c10e00.png">

<img width="565" alt="7" src="https://user-images.githubusercontent.com/48286013/148642662-dc802e44-323e-4ae3-850b-8f3556d79538.png">



<img width="448" alt="8" src="https://user-images.githubusercontent.com/48286013/148642664-fe7291c3-1334-4e66-b9ad-5b0e9c1206bc.png">


如果无法识别可以尝试打开alfred的debug模式

<img width="238" alt="9" src="https://user-images.githubusercontent.com/48286013/148642666-e11cdcd8-b7ba-462c-921f-c66ea58c5893.png">


这里我是报了这个错

```
ImportError: Unable to find zbar shared library
```
安装一下zbar就行了
```
# brew install zbar
```

## favicontohash
直接查看网站下面的favicon.ico的hash值

<img width="547" alt="10" src="https://user-images.githubusercontent.com/48286013/148642670-6a51e8ab-b7fb-44f3-bf28-4117a11bad6b.png">

## fofafind 

通过fofa去搜索域名、ip

<img width="569" alt="11" src="https://user-images.githubusercontent.com/48286013/148642671-5e03dc8a-743f-43e8-bf41-3f2d17f5dc3c.png">

<img width="565" alt="12" src="https://user-images.githubusercontent.com/48286013/148642672-818fd097-d11a-474c-baa1-fc4433343bef.png">

也可以点进去查看

<img width="1000" alt="13" src="https://user-images.githubusercontent.com/48286013/148642674-a740d4ce-87e2-49a7-9d6e-e8d63ac68a57.png">

需要进入`fofafind.py`文件输入自己的fofa api接口的email和key才可以正常使用

![16](https://user-images.githubusercontent.com/48286013/148642880-8df0e733-9eb9-4f01-bf81-81182650c312.png)

另外再推荐个其他的快捷编码解码的
## [Encode / Decode](https://github.com/willfarrell/alfred-encode-decode-workflow)

<img width="570" alt="14" src="https://user-images.githubusercontent.com/48286013/148642675-9b28be16-7468-41fb-a5ad-11f200647bf2.png">

<img width="572" alt="15" src="https://user-images.githubusercontent.com/48286013/148642676-a13e67fd-6dc2-4b4c-86ee-c076cadc1405.png">

