# Git command
## git push 
### Step
+ In your github build a blank repository and clone the HTTP_link

+ cd  need_push_floder

  ```
  - git init  
  - git add -A ( or git add . )   
  - git commit -m "first commit"( or  git commit -m "hello" )  
  - git remote add origin HTTP_link 
  - git push -u origin master  
  ```
### Notes

 + "git status" , See files status   
 + "git log" check push track    
 + "git diff" check change part  
 + git remote -v   （ we can check this term's origin ） 
+ git remote rm origin   (delete origin)
### Sometimes

+ There will be hint set default remote about you github username 
  + git config --global user.email "user@qq.com"    
  + git config --gloabl user.name "keyword"    

## Fetch from master

```
git fetch		// 下拉内容
git merge		// 合并
notes:
	Don't use git pull
```



## Git Branch

```
- git branch hello 		( "hello" is branch name )   
- git checkout hello 	( Enter branch )  
	you can push you code in your branch hello    
- git checkout master  
- git merge hello ( Combine branch directory to master directory )  
	agreement request
```



## Git Release
+ When the item have .exe file, need to  release.
+ While you need to git push code , add release .exe file.

