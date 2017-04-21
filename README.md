# FubonRD101
For Fubon new comer to know

## Pemrissions
- In Fubon bank, we need to apply EVERYTHING. I just try to list down all items we have to apply.
    * apply IPs in Nei-Hu building and Ren'ai Rd building. 
    * also associate Mac address of laptop and IPs.
    * allow mailbox to receive emails from non-Fubon senders and send emails to non-Fubon recipients.
    * allow mobile devices to receive emails and sync calendar.
    * install 64-bit windows on laptop instead of default 32-bit windows. some applications only have 64 bit version.
    * allow to modify IPs on ethernet card.
    * make sure wireless card is allowed to access access point. btw, there is NO access point in Fubon officially. This is only for us to connect access point when we leave office.
    * allow to access confluence page (http://172.17.240.93). Also, we need to access some project pages in confluence.
    * development/testing environment access permission - account & firewall rules.
    * it could be better to have 吃到飽 on your cellphone network. This will improve your work performance when you leave office.

## In eHR
- review all items including your information, your familiy informaiton, ..., and so on. 
- the most important is set up substitutes in eHR system. 

## About badge
- In general, this takes several weeks. You need to apply temporary badge. Please ask your supervisor to support.
- Access provision is per building, requires different application form for each location.

## About phone
- You phone number will be ready within 2 weeks. (At least mine was ready within 2 weeks.)

## About version control
### how to use git on windows?
- Please download 32-bit or 64 bit git portable version from (https://git-scm.com/download/win)
- Unzip the file after downloading
- After extracting the file, you will get a folder called "PortableGit". Please go into this folder.
- If you're familiar with Unix-like shell, please execute the command "git-bash.exe". If you would like to see windows prompt, please execute the command "git-cmd.exe" by clicking the icon directly.
### Q&A
- Q: I may get the following error message when executing the command "git clone" or "git push" 
```
fatal: unable to access 'https://github.com/sary357/FubonRD101.git/': SSL certificate problem: self signed certificate in certificate chain
```
- A: Please choose one of the following commands
```
 # If you would like disable ssl verification always
 $ git config http.sslVerify false

 # If you just hope to disable this time
 $ git -c http.sslVerify=false clone http://aaaa.bbb.ccc/aa.git
 or
 $ git -c  http.sslVerify=false push
```

## Shared folder
- 點選"電腦" -> 在 "搜尋程式及檔案" 打入 \\\\172.17.22.181\資料分析應用科
- Please read the file "README.txt" first

## Taxi fee
- 要去其他地方, 可以使用車單, 這樣就不用自己付費, 可以詢問主管那邊可以拿, 但目前我們只跟志英計程車簽約, 可以先叫志英計程車
- 如果直接搭乘, 可以透過總管系統申請車資
