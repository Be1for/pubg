# ⚡ BING — Installation Guide

<p align="center">
  <strong>Android Kernel-Based Tool</strong>
  <br>
  A complete guide to prerequisites, driver selection, installation, and launch.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Format-SH-222222?style=for-the-badge&logo=gnubash&logoColor=white" alt="Shell">
  <img src="https://img.shields.io/badge/Guide-Installation-5865F2?style=for-the-badge" alt="Installation Guide">
</p>

---

## 📑 Table of Contents

- [📦 Requirements](#-requirements)
- [📲 Installation](#-installation)
- [🔍 How to Identify Your Kernel Version](#-how-to-identify-your-kernel-version)
- [🚀 Launching Bing](#-launching-bing)
- [⚠️ Important Information](#️-important-information)
- [🔔 Updates](#-updates)

---

## 📦 Requirements

Before getting started, make sure you have the following files and tools.

| Component | Description |
|:---|:---|
| `Bing(内核)(四服通用)87.0.sh` | Main script |
| `FT驱动2.4.0.zip` | Driver package |
| **MT Manager** | File manager for working with `.sh` files |
| **Root access** | Superuser permissions required by the tool |


---

## 📲 Installation

### 01 — Move the Main Script

1. Download `Bing(内核)(四服通用)87.0.sh` to your **Downloads** folder.
2. Open **MT Manager** and locate the downloaded file.
3. Move the script to:

   ```text
   /data/local/tmp/
   ```

4. Set the file permissions to `777`.

### 02 — Install the Correct Driver

1. Download `FT驱动2.4.0.zip`.
2. Open the archive and locate the driver matching your device's kernel version.
3. Move the selected driver script to:

   ```text
   /data/local/tmp/
   ```

4. Set the file permissions to `777`, if required.

> [!WARNING]
> Select the driver that matches your device. An incompatible kernel driver may fail to load or cause device instability.

---

## 🔍 How to Identify Your Kernel Version

Follow these steps on your Android device:

**Settings → About Phone → Detailed Information and Specifications**

Find the **Kernel Version** field.

For example:

```text
6.6.118-android15-8-ge...
```

The version begins with `6.6`, so the corresponding driver family would be **6.6**, provided the driver package supports that kernel.

| Kernel version example | Driver family |
|:---|:---|
| `5.10.xxx` | `5.10` |
| `5.15.xxx` | `5.15` |
| `6.1.xxx` | `6.1` |
| `6.6.xxx` | `6.6` |

> [!NOTE]
> These examples are illustrative. Always verify the exact kernel and Android compatibility requirements supplied with the driver package. The location of the Kernel Version field may vary by device manufacturer.

---

## 🚀 Launching Bing

After placing the files in the target directory, verify that the selected driver is compatible with your device and follow the tool's official instructions.

The driver script may have a name such as:

```text
6.6.sh
```

If the script displays a completion message such as:

```text
Process completed. Press Enter to close.
```

follow its on-screen instructions.

### Launch Configuration

The main script may display the following prompt:

```text
是否开启无后台(1是0否):
```

**English translation:**

`Enable backgroundless mode? (1 = Yes, 0 = No)`

Choose the option specified by the tool's documentation. Loading time may vary depending on your device and internet connection.

---

## ⚠️ Important Information

### 🖥️ Overlay Behavior

The tool is described as using an overlay interface. However, visibility in recordings and screenshots depends on the overlay implementation, Android version, and capture method. It cannot be guaranteed to remain invisible in every situation.

### 🔐 Kernel-Level Operation

The tool is described as operating through a kernel driver rather than directly inside the game's process. Kernel-level operation does **not** guarantee immunity from detection, security checks, or bans.

### 🚨 Account and Device Risks

- Reports from other players may trigger a review.
- Manual reviews can identify suspicious gameplay.
- Anti-cheat systems may detect behavior or components associated with unauthorized tools.
- Incompatible drivers may cause crashes, instability, or other device problems.

**Use third-party tools at your own risk and follow the game's terms of service.**

---

## 🔔 Updates

For announcements and update information, check the following channels:

<p align="center">
  <a href="https://t.me/k32_leaks">
    <img src="https://img.shields.io/badge/Telegram-@k32__leaks-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="k32_leaks">
  </a>
  <a href="https://t.me/nullnb6">
    <img src="https://img.shields.io/badge/Telegram-@nullnb6-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="nullnb6">
  </a>
</p>

---

<p align="center">
  <sub>Documentation for informational purposes only.</sub>
  <br>
  <sub>Always verify compatibility and understand the risks before using kernel-level tools.</sub>
</p>
