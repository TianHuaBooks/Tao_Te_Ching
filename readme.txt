mkdir Tao_Te_Ching
cd Tao_Te_Ching
git init
touch README
git add README
git commit -m 'first commit'
git remote add origin https://github.com/TianHuaBooks/Tao_Te_Ching.git
git push -u origin master

// for change update
git commit -m 'reason for change'
git remote add change https://github.com/TianHuaBooks/Tao_Te_Ching.git
git push -u change master
