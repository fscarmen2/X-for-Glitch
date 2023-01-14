# Vless for Glitch

* * *

# 目录

- [项目特点](README.md#项目特点)
- [部署](README.md#部署)
- [鸣谢下列作者的文章和项目](README.md#鸣谢下列作者的文章和项目)
- [免责声明](README.md#免责声明)

* * *

## 项目特点:
* 本项目用于在 [Glitch](https://glitch.com/) 免费服务上部署 VLESS
* 集成哪吒探针，可以自由选择是否安装
* 部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 或者 worker 解决。

## 部署:
* 注册 [Glitch](https://glitch.com/)
* config.json 的 17 行修改 UUID
* server.js 的 106 行修改自己的 URL， 44 行修改哪吒参数
* 部署成功后 velss ws 的路径为: `/api`，如要修改，可以寻找并替换 server.js 的 90、96、97 行里的 api
* 需要应用的 js
  | 命令 | 是否必须 | 说明 |
  | ------------ | ------ | ------ |
  | <URL>/start | 是 | 运行 vless |
  | <URL>/nezha | 否 | 运行哪吒 | 以 / 开头 |
  | <URL>/api | 否 | 查看 vless 运行结果 Bad Request 即是 OK |
  | <URL>/status | 否 | 查看后台进程  |

![image](https://user-images.githubusercontent.com/92626977/212469541-9f1ceb5e-d525-4787-8142-0df4dafdbbe8.png)

![image](https://user-images.githubusercontent.com/92626977/212469554-4ccd234c-8a49-4927-bada-2a8e947e9a37.png)

![image](https://user-images.githubusercontent.com/92626977/212469562-5de97b9e-2d6f-41f1-9cea-fd2ade3df07b.png)

![image](https://user-images.githubusercontent.com/92626977/212469659-76bacf83-423f-4625-894a-eadf2ee1a17d.png)

<img width="1232" alt="image" src="https://user-images.githubusercontent.com/92626977/212469743-f54c1122-d145-4db1-a78e-c94e0c41d169.png">

<img width="1175" alt="image" src="https://user-images.githubusercontent.com/92626977/212469767-073a170b-dbb3-49bf-bdac-57eba2eae324.png">

<img width="1210" alt="image" src="https://user-images.githubusercontent.com/92626977/212470356-b3a03bf6-6484-4b43-ad75-671692c2be4b.png">

<img width="1410" alt="image" src="https://user-images.githubusercontent.com/92626977/212469906-a2ff6091-4802-4492-b282-cf652b5b17e7.png">

<img width="1467" alt="image" src="https://user-images.githubusercontent.com/92626977/212469937-bd448a4e-577c-4cac-9028-dfb8c9411e91.png">

<img width="577" alt="image" src="https://user-images.githubusercontent.com/92626977/212469959-f2762c30-5cb1-4a31-9f77-0dad6319bd90.png">

<img width="477" alt="image" src="https://user-images.githubusercontent.com/92626977/212470037-58621fe0-9f45-452e-97b4-419565920d61.png">

<img width="593" alt="image" src="https://user-images.githubusercontent.com/92626977/212469999-af9685ff-3392-42f1-88bb-0e615a61ab9b.png">

<img width="512" alt="image" src="https://user-images.githubusercontent.com/92626977/212470068-609dedea-2bfd-4ccf-80b2-6ed2a82e3dc5.png">

<img width="1140" alt="image" src="https://user-images.githubusercontent.com/92626977/212470157-77b77f8c-dcb8-425e-81a4-83bc1881126c.png">

<img width="499" alt="image" src="https://user-images.githubusercontent.com/92626977/212470733-446938ae-e403-424b-b7ce-51e775b30ed2.png">


## 鸣谢下列作者的文章和项目:
大佬 Nike Jeff 的 trojan 项目，https://github.com/hrzyang/glitch-trojan ，在此基础上作修改。

## 免责声明:
* 本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责。
