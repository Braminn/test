ls
cd
mkdir
rm -r
touch

git config --global user.name "Braminn"
git config --global user.email "svalip01@gmail.com"
git config --list

git init
git remote add test https://github.com/Braminn/test.git

git pull test master			//Скачиваем из проекта test директорию master
git add README.md 				//Индексируем файл
git add .						//
git commit -m "readme conit"	//Выполнить сборку проекта
git push test master			//Отправляем файлы в удаленный репозитарий

git status						

git clone https://github.com/twbs/bootstrap.git