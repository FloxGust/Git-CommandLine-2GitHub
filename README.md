> Command-Line Git 


MakeDirectory or folder
```
mkdir my_project
```

Go to Directory 
```
cd my_project
```

Backward : 
```
cd ..
```

# Check-git
จัดการการตั้งค่าต่างๆ ของ Git
```
git config -l 
```

``` 
git config  --list
```

``` 
git config --global --list
```
 # ดูเฉพาะการตั้งค่า global

```
git config --local --list 
```
# ดูเฉพาะการตั้งค่า local ใน repository ปัจจุบัน

```
git status 
```	 	                        
ตรวจสอบสถานะไฟล์ เพื่อดูว่าไฟล์ใดบ้างที่ถูกเปลี่ยนแปลง

```
git log
``` 				                        
ดูประวัติการเปลี่ยนแปลง

```
la
```

```
ls -la
```
แสดงไฟล์ทั้งหมดใน directory 

# Configure

```
git config --global user.name "Your Username"
```

```
git config --global user.email "your.email@example.com"
```

สร้างไฟล์ file.txt โดยมีคำว่า Hello World
``` 
echo "Hello World" > file.txt
```

# Git-Push

```
git init
```

```
git add README.md 
```

```
git add . 
```
(add all file)

```
git add file.txt
```

```
git commit -m "First commit"
```

```
git branch -M main
```

```
git remote add origin https://github.com/Yourgithubname/repository.git
```

```
git push -u origin main
```

# Remove git init 
```
rm -rf .git
```

# Git-pull

```
git pull <remote> <branch>
```
```
git pull origin main / git pull
```


# Git Clone คัดลอก Repository ที่มีอยู่

```
git clone <url>
```
```
git clone https://github.com/Yourgithubname/repository.git
```


# Resources
ODDS BU Document

https://emphasized-devourer-629.notion.site/ODDS-x-BU-Document-0b362875b56f4b9aa202bfd05c675e56

Git remote

https://git-scm.com/docs/git-remote

Document อื่นๆเกี่ยวกับ git เริ่มต้น

https://medium.com/tech-at-tdg/%E0%B9%80%E0%B8%A3%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B9%83%E0%B8%8A%E0%B9%89-git-command-line-%E0%B8%89%E0%B8%9A%E0%B8%B1%E0%B8%9A%E0%B8%A3%E0%B8%A7%E0%B8%9A%E0%B8%A3%E0%B8%B1%E0%B8%94%E0%B9%83%E0%B8%8A%E0%B9%89%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B9%83%E0%B8%99-5-%E0%B8%99%E0%B8%B2%E0%B8%97%E0%B8%B5-e871be9807eb

