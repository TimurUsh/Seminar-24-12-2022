# Инструкция на работе с Git

## Что такое Git?
**Git** - это наиболее популярная реализация распрделенной системы контроля версий. Самая популярная реализация **Git**- это [GitHub](https://github.com/) 
## Подготовка репозитория
Для создания репозитроия используется командка *git init*. Для этого необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминале с папкой написать команду *git init*.

## Создание коммитов
### Добавление файла к коммиту
Для добавления файла к будущему коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.  

## Создание коммита
Для создания коммита используется команда *git commit*. Для этого в терминале с папкой репозиторием необходимо написать *git commit -m <название к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***.

## Перемещение между коммитами

Для перемещения на предыдущие коммиты используется *git checkout*. Для этого необходимо в журнале изменений, как показано в предыдущей части, найти необходимый коммит и его номер. После чего в терминале с папкой-репозиторем написать кманду *git checkout <номер коммиты>*. После применения этой команды Вы попадёте в состояние **Detached head*, в котором никакие изменения фиксироватся не будут. Для возврата в обычное состояние необходимо написать команду *git checkout master*.

## Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого в терминале с папкой - репозиторем необходимо написать *git log*. 

## Ветки в Git
Ветви в Git используются для отдельного редактирования некоторй части файла Для создания *ветвей*(branch) необходимо применить программу *git branch <название ветви>*.

##  Слияние веток и разрешение конфликтов
Для слияния ветвей необходимо перейти в ветвь, в которую мы хотим добавить другую ветвь, и применить команду *git merge <название ветви>*. Если в какой-то строке ветви были различные данные, может возникнуть конфликт, который можно в ручную удалив стрелочки.

## Удаление веток   
Для удаления ветвей необходимо перенести файлы из этой ветви, если они нужны, после чего использовать команду *git branch -d <название ветви>*. 
*Повтор текста*