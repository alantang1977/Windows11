rufus下载：https://rufus.ie/zh/

rufus制作win11启动盘准备工作及注意事项：

1、准备一个8G容量或以上的U盘

2、rufus下载地址：rufus官方版下载地址

3、win11官方镜像下载：win11正式版iso镜像下载

4、采用rufus制作win11启动时应注意引导模式和分区类型匹配，比如分区类型为GPT，我们目标系统类型就要选择UEFI。如果分区类型为MBR，我们目标系统类型就要选择BIOS。现在一般新机型采用的都是uefi+gpt，小编这里己UEFI+GPT方式给大家讲解。

5、最新版的Rufus v3.18.1877添加了Windows 11扩展安装支持（解除TPM/安全启动/内存要求限制）

rufus制作win11启动盘步骤

1、然后插入 U 盘，打开 Rufus 软件，Rufus 软件会自动对U盘进行识别，如下图所示；
![107459091](https://pic4.zhimg.com/v2-1e0b1d6ea5b72a1dec34eae06ab5d075_1440w.jpg)
2、然后点击＂选择＂，浏览本地磁盘中下载好的Win11镜像文件，如下图所示；
![107459091](https://pic3.zhimg.com/v2-f6f770023ed6b2bd3b6e252bc15b575a_1440w.jpg)

3、在“镜像选项”下拉菜单中选中“Extended Windows 11 installation（no TPM+no Secure Boot）”选项，也就是使用Rufus 3.18的“扩展Windows 11安装模式”，如下图所示；
![107459091](https://pic1.zhimg.com/v2-afdb9594a29ab71993bc74e1443caf3e_1440w.jpg)

4、其它默认，然后点击界面下方＂开始＂，这时会弹出 U 盘格式化警告，如果确认 U 盘数据已备份或转移，那么点击＂确定＂，如下图所示；
![107459091](https://pica.zhimg.com/v2-f5340d06844fb1a260641c77750fae7c_1440w.jpg)

5、接下来软件就会自动制作 U 盘启动盘，耐心等待进度条完成即可，如下图所示；
![107459091](https://picx.zhimg.com/v2-8eda25207384e94836604463c23389ed_1440w.jpg)

6、启动盘制作完成后就会出现“准备就绪”的字样，点击＂关闭＂即可，如下图所示；
![107459091](https://pic4.zhimg.com/v2-b07f4ac76d57470a13c6504b73c26583_1440w.jpg)

7、接下来就可以使用 U 盘启动盘去安装win11系统了。

设置rufus制作的win11启动盘安装系统过程

1、制作win11启动盘成功后，我们可以通过启动键查询来看下如何快速设置u盘启动开始进入win11系统的安装，如下图所示；
![107459091](https://pica.zhimg.com/v2-663769912a104d5c1021df2f24493ac6_1440w.jpg)
