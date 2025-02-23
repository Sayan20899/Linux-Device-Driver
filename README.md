# Linux Device Driver (Character Device)

## 📌 Overview
This project implements a simple Linux character device driver that allows user-space applications to read and write data to a virtual device.

## ⚙️ Features
- Registers a character device in `/dev/`
- Implements `open`, `read`, `write`, and `release` operations
- Allows user-space interaction via file operations

## 🛠 Prerequisites
- Linux Kernel Headers (`sudo apt install linux-headers-$(uname -r)`)
- Basic knowledge of C and Linux device drivers

## 🚀 Installation & Usage

### 1️⃣ Build the Driver
```sh
cd src
make
