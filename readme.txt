cd /d E:\opi_Hromov\lab7_Hromov\lab7_start_git
git config --global user.name "HromovOleksandr"
git config --global user.email "sssanya.gromov@gmail.com"
git config --list
git init
git status
echo *.txt .gitignore
git add *.*
git status
git commit -m "19:15 01.12.2024 My first commit"
git remote
git remote add origin https://github.com/sanyainside/lab7_git_start
git push -u origin master
git add *.*
git commit -m "20:06 01.12.2024: add time 2"
git push -u origin master
cd /d E:\opi_Hromov\lab7_Hromov\lab7_Hromov2_git
git clone https://github.com/sanyainside/lab7_git_start
git commit -m "20:11 01.12.2024: files copyied"
cd /d E:\opi_Hromov\lab7_Hromov\lab7_Hromov2_git\lab7_git_start
cd /d E:\opi_Hromov\lab7_Hromov\lab7_start_git
git pull https://github.com/sanyainside/lab7_git_start
