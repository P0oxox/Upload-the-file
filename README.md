# Upload-the-file
How to upload

1. 先 cd 去用來放檔案的資料夾，把剛剛新建的專案 git clone 下來
2. git config --global credential.helper store
3. git add <first.py>
4. git commit -m "<備註，像是新增了甚麼內容>"
5. git config --global user.email "you@example.com"
6. git config --global user.name "Your Name"
7. git commit -m "update"

要把檔案抓下來
git push

新增第二個檔案
1. vim second.py
2. git add second.py
3. git commit -m "add second.py"
4. git push
