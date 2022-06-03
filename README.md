## 本项目主要用于学习研究，请勿用于非法用途，若出事一切后果请自行承担！本人概不负责，谢谢！

### 介绍

> 这是一个小北学生自动打卡脚本，用了此脚本导员再也不用在群里一直@你了，不用为了每天忘记打卡而想各种理由了，这玩意之前就想就想搞一个了，只不过没时间好好看一下，之前使用小米手机抓包一直有问题，最近用iPhone抓 却抓到了
> 这个脚本是[@lovabai](https://github.com/lovebai/xiaobei)上班摸鱼期间写的，带薪摸鱼🐟  真的很舒服~~

**该仓库基于[@lovabai](https://github.com/lovebai/xiaobei)的代码进行了二次开发。相比原仓库增加以下功能：**

* 支持了多用户打卡功能
* 支持PushDeer原生推送

### 使用

---

**该版本支持本地运行，未对GitHub actions做自动化适配，如没有动手能力请查看[@lovabai](https://github.com/lovebai/xiaobei)原仓库。**

#### 本地运行

---

1. 安装python3环境，之后下载本仓库代码，如果安装了Git则直接使用命令 `git clone https://github.com/lovebai/xiaobei.git`
   如果未安装则直接在右上角下载zip。
2. 执行 `pip install requests`或者 `python -m pip install requests`以安装依赖。
3. 在 `students.py`中填写账号信息，注意格式，可随实际情况增减。
4. 在 `xiaobei_health_multiplay.py中`配置其他信息
5. 运行 `xiaobei_health_multiplay.py`文件观察控制台提示，如无其他问题，可配合操作系统实现自动化（例如Windows计划任务）。

### 说明

---

* 该仓库Fork自[@lovabai](https://github.com/lovebai/xiaobei)，本人在他的代码基础上进行了二次开发。

### 免责声明

---

本项目只做为技术研究，本人及[@lovabai](https://github.com/lovebai/xiaobei)不对其程序所带来的后果担责。
