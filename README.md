##Git
Для того, чтобы добавить все файлы из текущей директории введите: git add .
Если нужно добавить файлы из текущей директории и из всех поддиректориев, то используйте: git add --all
Для просмотра текущего состояния можно воспользоваться командой: git status
Создание версии проекта: git commit -m "comment"
Получение файлов: git pull

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:waskov/ML_training.git
git push -u origin main
