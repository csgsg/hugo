### Setup
```
git clone --recurse-submodules https://github.com/csgsg/hugo
cd hugo
cd public
git checkout master
cd ..
```
### Making Changes
Update some files outside of the public folder (***WARNING: Please do not edit the files in the public folder directly. running "hugo" will handle this***)
Test changes by running:
```
hugo server
```

### Pushing changes
Run these commands from the root directory of the repository
```
hugo # builds the website
cd public
git add -A
git commit -m "<Some commit message for the github.io repo>"
git push # pushes changes to csgsg.github.io repository (this will also deploy changes to the live website)

cd ..
git add -A
git commit -m "<Some commit message for the hugo repo>"
git push # this will push the changes to the hugo repository
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
