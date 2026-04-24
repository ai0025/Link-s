# Link-s
Link-S 是一款点对点文件加密传输系统，加密传输不限速，不限大小。企业版支持私有化部署。采用AES-CTR+ML-KEM端到端加密技术，确保文件在传输过程中全程加密，密钥只在收发两端，服务器无法解密。支持局域网P2P直连（L-DC）、局域网与公网直连(W-DC)、P2P打洞直连(W-DC)和跨网中继转发连接(Relay)四种连接方式，满足企业内网、服务器与客户端和跨地域协作等多种场景的文件安全传输需求。总体来说安全、稳定、快。

# Link-s 试用版客户端使用方法
Link-S 客户端为绿色软件，无需安装。本仓库为试用版。下载后直接双击LinkrLauncher*** 即可运行。试用版使用公共控制服务端，所以响应可能会有些延迟。因为法律法规相关要求，试用版只支持局域网L-DC连接方式，企业版无限制。试用版需要简单注册后登录，企业版由本企业管理员开账号后登录。

[Link-s Windows版本](https://github.com/ai0025/Link-s/tree/main/Link-s-win)

[Link-s Linux版本](https://github.com/ai0025/Link-s/tree/main/Link-s-linux)

# 功能模块说明
登录成功后，直接进入主界面，主界面包含五个主要功能模块：发现文件、分享文件、联系人、下载管理和设置
<img width="1101" height="665" alt="外网" src="https://github.com/user-attachments/assets/88ee6137-de91-4d93-b49d-61c1854fef56" />

## 1、分享文件 
将本机的文件共享出来让其他用户下载。其他用户需先添加你为联系人，才能看到你共享的文件。
## 1.1 共享文件夹 
默认共享文件夹为工作目录的 Share文件夹。支持将其它文件夹设置为共享文件夹，方法为点击下方工具栏上第二个铅笔按扭。 
## 1.2 分享方式有两种： 
#### 方式一：将需要分享的文件直接复制到共享文件夹中 
#### 方式二：点击下方工具栏上的【+】按钮，在弹出的窗口中选择文件，选择的文件将会复制到共享文件夹中。
## 1.3 支持将不同的文件或文件夹分享给不同的联系人
#### 方式一：勾上要分享的文件(夹)，点击下方工具栏上的“双人”图标，在弹出的窗口中勾选目标联系人，然后确定。
#### 方法二：点击文件列表上的“双人”图标，在弹出的窗口中勾选目标联系人，然后确定。

<img width="1198" height="828" alt="image" src="https://github.com/user-attachments/assets/df0d313e-ee66-4672-a68e-6f4876338a63" />

# 2、联系人 
添加当前登录的其他用户到联系人列表中，目的是下载该联系人分享的文件。 
点击界面上的【添加联系人】按钮，在弹出的对话框中输入对方的用户ID和添加密码（由对方设置），点击【确定】。 
添加之后，在联系列表中将显示联系人的名字 

# 3、发现文件 
查看和下载联系人分享的文件（夹）。 
在联系人列表中点击某个联系人，右侧会显示该联系人分享的文件（夹）列表。点击文件（夹）列表上的【下载】按钮，即可开始下载该文件（夹）。 
下载过程中可实时查看进度，支持断点续传，支持网络中断后自动继续下载，支持断点处继续下载。 

# 4、下载管理 
主界面顶部显示正在下载的文件数量。点击该区域可进入下载管理页面。 
下载管理页面分为两个标签： 
下载中：显示正在下载的文件列表，可查看进度、暂停或删除下载 
已完成：显示已下载完成的文件列表，可打开文件所在文件夹或删除记录 

<img width="1200" height="834" alt="下载" src="https://github.com/user-attachments/assets/e29c2ed4-721b-442b-b446-8e1e53f225d8" />


# 5、设置 
设置功能支持设置添加密码、名字和下载保存位置和共享文件夹

# 6、常见问题

**无法登录**  
检查网络连接，确认服务器地址正确  

**找不到联系人**  
确认对方已添加你为联系人，且双方都在线  

**关于下载速度**  
影响下载速度的原因包括网络原因、CPU核数和磁盘性能。  
经测试：  
- 低配场景（2核+5400转机械硬盘）：下载速度约 200 Mbps  
- 高配场景（24核/16核+固态硬盘）：下载速度有时能达到 1000 Mbps，接近千兆网络上限  

**传输中断**  
支持自动重新开始、支持断点续传



       
# Link-S
Link-S is a peer-to-peer encrypted file transmission system with unlimited transmission speed and no file size limitations. The enterprise version supports private deployment. Adopting AES-CTR + ML-KEM end-to-end encryption technology, it ensures full encryption of files during transmission. Encryption keys are only held by the sender and receiver, and the server is unable to decrypt the data.

It supports four connection modes: Local Direct Connection (L-DC), Wide-area Direct Connection (W-DC), P2P hole-punching direct connection, and cross-network relay transmission (Relay). It meets secure file transfer requirements in various scenarios, including enterprise intranets, server-client communication, and cross-regional collaboration. Overall, it is secure, stable, and high-speed.

# Link-S Trial Client User Guide
The Link-S client is portable software that requires no installation. This repository provides the trial version. After downloading, simply double-click `LinkrLauncher` to launch the program.

The trial version runs on a public control server, which may cause slight response delays. Due to relevant laws and regulatory requirements, the trial version only supports Local Direct Connection (L-DC). There are no connection restrictions for the enterprise version.

Trial users need to complete simple registration before logging in. Enterprise users will receive accounts assigned by enterprise administrators.

[Link-S Windows Version](https://github.com/ai0025/Link-s/tree/main/Link-s-win)

[Link-S Linux Version](https://github.com/ai0025/Link-s/tree/main/Link-s-linux)

# Function Module Overview
After logging in successfully, you will enter the main interface, which contains five core functional modules: Discover Files, Share Files, Contacts, Download Management, and Settings.

<img width="1101" height="665" alt="Interface" src="https://github.com/user-attachments/assets/88ee6137-de91-4d93-b49d-61c1854fef56" />

## 1. Share Files
Share local files for other users to download. Other users must add you as a contact to view your shared files.

### 1.1 Shared Folder
The default shared folder is the `Share` directory in the working folder. You can set other folders as shared folders via:
**Settings → Shared Folder Settings** (top-right corner)

### 1.2 Two Sharing Methods
#### Method 1
Directly copy the files to be shared into the shared folder.

#### Method 2
Click the **Add Shared File** button on the interface, select files in the pop-up window, and the selected files will be automatically copied to the shared folder.

<img width="1009" height="659" alt="File Sharing" src="https://github.com/user-attachments/assets/6b8745f9-028d-46bd-87bb-dbb16cd60b7f" />

## 2. Contacts
Add other logged-in users to your contact list to download files shared by them.

Click the **Add Contact** button, enter the target user ID and addition password (set by the contact), then click **OK**.
Added contacts will be displayed in your contact list.

## 3. Discover Files
Browse and download files and folders shared by your contacts.

Click on a contact in the contact list, and the shared file/folder list of this user will be displayed on the right. Click the **Download** button to start downloading.

Real-time download progress is visible. The software supports breakpoint resume, automatic resumption after network interruption, and continuous downloading from breakpoints.

## 4. Download Management
The top of the main interface displays the number of ongoing download tasks. Click this area to enter the download management page, which has two tabs:

**Downloading**: Displays ongoing download tasks. You can view progress, pause or delete tasks.
**Completed**: Displays finished downloads. You can open the file directory or delete download records.

<img width="1200" height="834" alt="Download Management" src="https://github.com/user-attachments/assets/e29c2ed4-721b-442b-b446-8e1e53f225d8" />

## 5. Settings
The settings page allows you to configure contact addition passwords, display nickname, default download path, and shared folders.

# 6. Frequently Asked Questions

**Failed to log in**
Check your network connection and make sure the server address is correct.

**Unable to find contacts**
Confirm that the other user has added you as a contact and that both parties are online.

**Download Speed**
Download speed is affected by network conditions, CPU performance, and disk performance.

Test results:
- Low-spec environment (2-core CPU + 5400RPM mechanical hard disk): approx. 200 Mbps
- High-spec environment (16/24-core CPU + SSD): up to 1000 Mbps, nearly reaching the gigabit network upper limit

**Transmission Interruption**
Automatic reconnection and breakpoint resume transmission are fully supported.

