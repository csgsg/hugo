### Setup
```
git clone --recurse-submodules https://github.com/csgsg/hugo
cd hugo
cd public
git checkout master
cd ..
```
### To make/push changes
Update some files outside of the public folder
```
hugo
cd public
git add -A
git commit -m "<Some commit message for the github.io repo>"
git push

cd ..
git add -A
git commit -m "<Some commit message for the hugo repo>"
git push
```  
<br /> 
<br /> 
<br /> 
<br /> 
<br /> 
<br /> 
<br /> 
<br /> 
<br /> 
<br /> 

*If you would like to use SSH keys instead of password auth*: https://stackoverflow.com/questions/49191565/git-clone-works-git-submodule-fails-permission-denied
