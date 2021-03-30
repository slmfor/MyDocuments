#使用Github管理文档

1.在github添加公钥
>cd ~/.ssh  
>open -a Sublime\ Text id_rsa.pub  

2.新建文档
>touch newFile.md  

3.push到Git(git常用命令)  
>git init  
>git add newFile.d  
>git commit -m "first commit"  
>git branch -M main  
>git remote add origin git@github.com:AccountName/Repository.git  
>git push -u origin main