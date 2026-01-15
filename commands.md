# Linux Task – Commands Log

This file contains the Linux commands I executed while completing Task 1. These commands helped me understand basic system navigation, file handling, permissions, and system monitoring.

---

## 1. Directory Navigation

```bash
pwd
ls
cd /
ls
cd ~
pwd
```

---

## 2. Creating and Removing Files & Folders

```bash
mkdir linux_practice
cd linux_practice
touch sample1.txt sample2.txt
mkdir demo_folder
ls
rm sample2.txt
rmdir demo_folder
```

---

## 3. Viewing and Editing Files

```bash
cat sample1.txt
nano sample1.txt
less sample1.txt
```

---

## 4. Checking and Changing Permissions

```bash
ls -l
chmod 755 sample1.txt
ls -l
```

---

## 5. Monitoring System Resources

```bash
top
df -h
free -m
```

---

## 6. Installing and Using htop (Optional)

```bash
sudo apt update
sudo apt install htop
htop
```

---

## Notes

All these commands were executed in a Linux terminal. Screenshots of the outputs are available in the screenshots folder.
