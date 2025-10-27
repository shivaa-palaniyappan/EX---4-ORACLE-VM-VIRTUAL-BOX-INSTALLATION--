# **EX—3: ORACLE VM VIRTUAL BOX INSTALLATION**
# Name: SHIVAA PALANIYAPPAN V
# Roll : 212223110050

# **Virtualization**

## **AIM**
To install Oracle VM VirtualBox, a free and open-source hosted hypervisor, on a computer system, enabling the creation and management of virtual machines for running multiple operating systems on a single host machine.

## **EQUIPMENTS REQUIRED**
- **Hardware:** PC with at least 4 GB RAM and 20 GB free disk space  
- **Software:** Oracle VirtualBox, CentOS  
- **Kali Linux ISO image** (download from official website)

---

## **PROCEDURE**

### **Step 1: Download VirtualBox**
- Go to the **[VirtualBox official website](https://www.virtualbox.org/wiki/Downloads)**  
- Choose the version for your OS:
  - **Windows hosts** (for Windows users)
  - **macOS hosts** (for Mac users)
  - **Linux distributions** (for Linux users)

---

### **Step 2: Install VirtualBox (Windows/macOS)**

**For Windows:**
1. Open the downloaded installer (**VirtualBox-x.x.x-xxxx-Win.exe**)
2. Follow the setup wizard:
   - Click **Next**
   - Select installation location (default is recommended)
   - Choose components and click **Next**
   - Allow network interface warning (**Yes**)
3. Click **Install** and wait for completion

---

### **Step 3: Verify Installation**
1. Launch **VirtualBox**  
2. The **VirtualBox Manager** should open with options to create/manage VMs

---

## **STEP-BY-STEP INSTALLATION GUIDE**

### **Step 1: Download Kali Linux ISO**
1. Go to the **[Kali Linux download page](https://www.kali.org/get-kali/)**  
2. Download the **Installer version** (64-bit recommended)

---

### **Step 2: Open Oracle VM VirtualBox**
Launch VirtualBox on your computer

---

### **Step 3: Create a New Virtual Machine**
1. Click **New**
2. Configure:
   - **Name:** Kali Linux
   - **Type:** Linux
   - **Version:** Debian (64-bit)
3. Click **Next**

---

### **Step 4: Allocate Memory (RAM)**
Allocate **2 GB (2048 MB)** minimum (4 GB recommended) → Click **Next**

---

### **Step 5: Create a Virtual Hard Disk**
Select **Create a virtual hard disk now** → Click **Create**

---

### **Step 6: Select Hard Disk File Type**
Choose **VDI (VirtualBox Disk Image)** → Click **Next**

---

### **Step 7: Storage on Physical Hard Disk**
Select **Dynamically allocated** → Click **Next**

---

### **Step 8: Allocate Storage Space**
Allocate **20 GB** minimum → Click **Create**

---

### **Step 9: Configure Kali Linux ISO**
1. Select VM → Click **Settings**
2. Go to **Storage**
3. Click **Empty CD icon** under Controller: IDE
4. Choose **Choose a disk file...**
5. Select **Kali Linux ISO**
6. Click **OK**

---

### **Step 10: Start the Virtual Machine**
Click **Start** to boot the VM

---

### **Step 11: Begin Kali Linux Installation**
Select **Graphical Install** → Press **Enter**

![image](https://github.com/user-attachments/assets/9820c7f2-4d81-47f8-91b7-4fbe2233037c)

---

### **Step 12: Select Language and Region**
Choose language, location, keyboard layout → Click **Continue**

---

### **Step 13: Configure the Network**
Enter hostname (e.g., kali). Leave domain blank if not needed.

---

### **Step 14: Set Up Users and Passwords**
Create **root password** and confirm

---

### **Step 15: Partition Disks**
Choose:
- **Guided – use entire disk**
- Select virtual disk
- **All files in one partition**
- Finish partitioning and confirm

---

### **Step 16: Install the System**
System will copy files and install Kali Linux

---

### **Step 17: Install GRUB Bootloader**
Choose **Yes** → Install GRUB on virtual hard disk

---

### **Step 18: Complete Installation**
Click **Continue** to reboot

---

### **Step 19: Login to Kali Linux**
Login using **root account** and password

![image](https://github.com/user-attachments/assets/edd107e7-3f25-41fc-9fcb-79dd7ad37c3d)

---

## **EXPECTED OUTPUT**
`.sh` method successful installation and boot

---

## **PROGRAM**

![program1](https://github.com/user-attachments/assets/bb0d77fb-b9d7-4e15-8e9d-38cd50301639)
![program2](https://github.com/user-attachments/assets/8a205c53-5dd8-4d51-a9a9-211cc91ae6a1)

---

## **EXPECTED & TERMINAL OUTPUT**

![output1](https://github.com/user-attachments/assets/ff192786-bc64-4924-917f-f2e04261b243)
![output2](https://github.com/user-attachments/assets/95f68cd4-4664-409b-aa69-9ab3aaca7e06)

---

## **LINUX COMMANDS**

![linuxcmd](https://github.com/user-attachments/assets/047ce7e9-45c0-49a6-9e62-aa52303dcd7f)

---

## **RESULT**
**Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.**
