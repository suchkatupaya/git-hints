# git-hints

## Небольшой гит-репозиторий для самостоятельной работы

Хеш коммита — уникальный идентификатор коммита. 
посмотреть историю с хешами: git log
коротко: git log --oneline
Лог — история коммитов.

HEAD — указатель на текущий коммит / ветку, где ты сейчас находишься.
git branch - посмотреть текущую ветку

CТАТУСЫ ФАЙЛОВ
git status
Основные статусы:

untracked — Git не следит за файлом

modified — файл изменён

staged — файл добавлен в индекс, готов к коммиту

tracked — файл уже отслеживается Git

git status          # посмотреть состояние файлов
git add .           # добавить изменения
git commit -m "..." # создать коммит
git log             # полная история
git log --oneline   # краткая история

Cтили оформления сообщений: например: Добавить раздел про HEAD, Дополнить информацию про git log, Add user entity, Fix login bug

`git clone https://github.com/PraktikumJava/git-hints.git`
/System/Library/CoreServices/Finder.app/Contents/Resources/MyLibraries/myDocuments.cannedSearch