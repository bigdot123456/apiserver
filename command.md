# Command for change go project, initial step

git commit -m "use some log and viper config" *

git remote add origin https://github.com/bigdot123456/apiserver.git
git push -u origin master


# new command for change project data
cd apiserver
rm -f -r *
cp -a ../apiserver_demos/demo05/* .

git add .
git commit -m "add mysql" .
git push -u origin master
