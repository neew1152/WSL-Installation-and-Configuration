# How to Install and Configure WSL (Windows Subsystem for Linux)

<p align="center">
  <img src="https://github.com/microsoft/WSL/blob/master/Images/Square44x44Logo.targetsize-256.png" alt="WSL logo"/>
</p>

This guide walks you through the installation and configuration of WSL on your Windows machine.

---

## 🔧 Step 1: Enable Required Windows Features

1. Open **Control Panel**.
2. Go to **View by: Category** > **Programs** > **Turn Windows features on or off**.
3. Enable the following features:
   - ✅ Hyper-V  
   - ✅ Virtual Machine Platform  
   - ✅ Windows Hypervisor Platform  
   - ✅ Windows PowerShell 2.0  
   - ✅ Windows Subsystem for Linux  

4. Click **OK** and restart your computer.

---

## 💻 Step 2: Install WSL

1. Press `Super Key`, type **WSL**, right-click and select **Run as Administrator**.
2. Follow the prompt and press any key to install Windows Subsystem for Linux.

---

## ⚙️ Step 3: Configure WSL Settings

1. Press `Super Key`, type **WSL Settings**, and open the app.
2. Configure the following options:
   - **Developer**: Enable `Debug Console`
   - **Auto memory reclaim**: Set to `Gradual`

| Option        | Behavior                                                                 | Best Use Case                                                                                               |
| ------------- | ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| **Disabled**  | No automatic memory is reclaimed. WSL keeps all allocated memory.        | **Max Linux performance**: Useful when performance is more important than memory usage on the Windows side. |
| **Gradual**   | WSL gradually reclaims unused memory without forcefully dropping caches. | **General development**: Balanced option for most users — avoids sudden drops in performance.               |
| **DropCache** | WSL aggressively reclaims memory, including dropping filesystem caches.  | **Low RAM environment / containers**: Best for memory-constrained environments or server-like workloads.    |

---

## ✅ Done!

You’ve successfully installed and configured WSL on your system. You can now start using Linux directly on your Windows machine.

---
---

# วิธีติดตั้งและกำหนดค่า WSL (Windows Subsystem for Linux)

<p align="center">
  <img src="https://github.com/microsoft/WSL/blob/master/Images/Square44x44Logo.targetsize-256.png" alt="WSL logo"/>
</p>

## 🔧 Step 1 : เปิดใช้งานฟีเจอร์วินโดส์ที่จำเป็น

1. **Windows Search** > **Control Panel**
2. **View by: Category** > **Programs** > **Turn Windows features on or off**
3. เปิดใช้งานฟีเจอร์ :
   - ✅ Hyper-V  
   - ✅ Virtual Machine Platform  
   - ✅ Windows Hypervisor Platform  
   - ✅ Windows PowerShell 2.0  
   - ✅ Windows Subsystem for Linux  

4. **OK** แล้วรีบูตวินโดส์

---

## 💻 Step 2: ติดตั้ง WSL

1. **Windows Search** > **WSL** > **Run as Administrator**
2. ทำตามคำแนะนำแล้วกดปุ่มใดก็ได้เพื่อติดตั้ง Windows Subsystem for Linux

---

## ⚙️ Step 3: กำหนดค่า WSL Settings

1. **Windows Search** > **WSL Settings**
2. กำหนดค่าตามนี้ :
   - **Developer** : ✅ `Debug Console`
   - **Auto memory reclaim** : ✅ `Gradual`

| ตัวเลือก        | การทำงาน                                                 | การใช้งาน                                                                                              |
| ------------- | --------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Disabled**  | ไม่มีการคืนหน่วยความจำ WSL จะได้รับหน่วยความจำตามที่ได้กำหนดไว้ทั้งหมด | **Max Linux performance** : ประสิทธิภาพการทำงานของ WSL มีความสำคัญมากกว่าการแบ่งหน่วยความจำให้ Windows (Host) |
| **Gradual**   | WSL จะคืนหน่วยความจำที่ไม่จำเป็นโดยไม่ต้องทิ้งแคช                   | **General development** : หลิกเลี่ยงการลดลงอย่างกระทันหันของประสิทธิภาพ                                       |
| **DropCache** | WSL จะคืนหน่วยความจำอย่างรุนแรง รวมถึงการทิ้งแคชระบบ              | **Low RAM environment / containers** : สภาพแวดล้อมที่มีหน่วยความจำจำกัดหรือเวิร์กโหลดประเภทเซิร์ฟเวอร์             |


---

## ✅ เรียบร้อย !

คุณติดตั้งและกำหนดค่า WSL บนระบบวินโดว์เรียบร้อย ตอนนี้เริ่มใช้ WSL ได้เลย

---
---

ไม่น่าเชื่อ ! อยู่ ๆ เธอก็หายเกียดผมเฉยยยย
