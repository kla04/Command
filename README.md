# GITWORKSHOP
## git config
- git config -–global user.name "[user name]"
- git config -–global user.email "[email address]" 
## git init : เริ่มต้นการใช้งาน git
## git status : ตรวจสอบสถานะ
## git diff : รีวิวไฟล์ที่แก้ไปแล้ว (สถานะ modified) ผ่าน diff view
- git diff --staged :  diff ไฟล์ที่ add แล้ว (สถานะ staged) แต่ยังไม่ได้ commit
## git add : เพิ่มไฟล์เข้าสู่ staged status
- git add [path]
- git add . : เพิ่มไฟล์ทั้งหมด
## git commit 
- git commit -a : commit ทั้งหมด
- git commit -m "text"
- git commit -am "text"
## git remote
- git remote add origin [URL]
## git push
- git push -u origin master
- git push -f
## git reset : เอาไฟล์ที่ add ไปแล้วออกมาจาก staged ให้กลับมาเป็น modified
## git clone 
- git clone [URL]
# SSH key 
- ssh-keygen -t rsa -b 4096 -C "your_email@example.com" หรือ  ssh-keygen -o
- cat ~/.ssh/id_rsa.pub 
- copy ข้อความไปใส่ใน Setting --> SSH keys