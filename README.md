      
# Link-S
Link-S is a file sharing and peer-to-peer encrypted transmission system that offers unlimited speed and unlimited file size for encrypted transfers. It supports private deployment.
Using end-to-end encryption based on AES-CTR + ML-KEM, Link-S ensures files are fully encrypted during transmission. Encryption keys exist only on the sender and receiver devices, and cannot be decrypted by the server.
It supports four connection modes:
Local area network P2P direct connection (L-DC)
Local area network & public network direct connection (W-DC)
P2P hole-punching direct connection (W-DC)
Cross-network relay forwarding (Relay)
These cover diverse scenarios including secure file transfer within enterprise intranets, between servers and clients, and for cross-regional collaboration.
In short: secure, stable, and fast.

It supports four connection modes: Local Direct Connection (L-DC), Wide-area Direct Connection (W-DC), P2P hole-punching direct connection, and cross-network relay transmission (Relay). It meets secure file transfer requirements in various scenarios, including enterprise intranets, server-client communication, and cross-regional collaboration. Overall, it is secure, stable, and high-speed.

# Link-S Trial Client User Guide
The Link-S client is a portable application that requires no installation. Simply download, extract the archive, and double-click LinkrLauncher*** to launch.
The LAN edition uses a public control server, which may result in slight response delays. Due to legal and regulatory requirements, this edition only supports the LAN L-DC connection mode, while the enterprise edition has no such restrictions.
The LAN edition requires simple registration before login.
The enterprise edition uses accounts created by your enterprise administrator.
Once logged in, you will enter the main interface, which consists of five core modules:
Discover Files
Share Files
Contacts
Download Manager
Settings

[Link-S Windows Version](https://github.com/ai0025/Link-s/tree/main/Link-s-win)

[Link-S Linux Version](https://github.com/ai0025/Link-s/tree/main/Link-s-linux)

# Function Module Overview
After logging in successfully, you will enter the main interface, which contains five core functional modules: Discover Files, Share Files, Contacts, Download Management, and Settings.

<img width="1101" height="665" alt="Interface" src="https://github.com/user-attachments/assets/88ee6137-de91-4d93-b49d-61c1854fef56" />

## 1. File Sharing
Share local files for other users to download. Other users must add you as a contact first to view your shared files.
### 1.1 Shared Folder
The default shared folder is the Share directory under the working directory. You can set other folders as shared folders by clicking the second pencil icon on the bottom toolbar.
### 1.2 Two Sharing Methods
#### Method 1
Directly copy the files to be shared into the shared folder.
#### Method 2
Click the [+] button on the bottom toolbar, select files in the pop-up window, and the selected files will be automatically copied to the shared folder.
### 1.3 Share Different Files/Folders with Specific Contacts
#### Method 1
Check the files or folders you want to share, click the two-person icon on the bottom toolbar, select target contacts in the pop-up window, and confirm.
#### Method 2
Click the two-person icon next to the file item in the list, select target contacts in the pop-up window, and confirm.

<img width="1198" height="828" alt="image" src="https://github.com/user-attachments/assets/df0d313e-ee66-4672-a68e-6f4876338a63" />

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

# 7. For more information, please visit our official website
www.link-s.cc
