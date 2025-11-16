# 🚀 TermPak Installation Guide

This guide will help you install **TermPak** on Termux and set up the **TermHub** repository to manage apps.

---

## 🛠 1. Install Required Tools

Update Termux packages and install necessary tools:

```bash
pkg update -y && pkg upgrade -y && pkg install -y wget git curl
```
### add termhub repository
```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/jmzao/TermHub/main/ ./" > $PREFIX/etc/apt/sources.list.d/termhub.list

```
### update repository
```bash
pkg update
