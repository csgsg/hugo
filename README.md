### Setup
```
git clone --recurse-submodules https://github.com/csgsg/hugo
cd public
git checkout master
cd ..
```
### To make changes
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
