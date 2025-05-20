Helpful to start the Git first time


1. Download Git CLI in laptop
2. login to GitHub (Browser)
   2.1 create a new repository using any name
3. Setup Identification in GitHub in terminal (local)
    3.1 git init  ### In terminal initiate git in local (laptop) 
    3.2 Browse Git Global config to set the user name and email id 
          3.2.1 open terminal type:  git config --global user.name "Sunita Bhatt"
          3.2.2 In terminal type: git config --global user.email "sunitabhatt.011@gmail.com"

4. git add README.md  ######  it can be any file that need to be added in git. this command is used to track the file 
5. git status   #### check the status 
6. git commit -m "the msg you wanna put"
7. git branch ######## It will give u the master 
8. git branch -M main     ##### changing branch name master to main
9. git branch ######### check the branch name, it should be changed to main from master  
10. git remote add origin https://github.com/Sunitabhatt/gitwork.git    #### http URL vary based on the repo 
11. git remote -v   #### It will show the staging stage (which is mostly origin) from where we can push to any repo
12. git push origin main  ####### Push code from origin to main 

 
For change in the README.md file 

modify file in Notepad and save at same location in local 
In terminal 
1. git status #### It will show in the modification in the README.md file 
2. there will be two option restore or add 
3. git restore README.md ##### file will restore 
3. git add README.md #### add the modify file 
4. git commit -m "msg............"
5. git push origin main 




    
