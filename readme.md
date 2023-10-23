# Инструкция по работе с GIT

### О системе контроля версий (GIT)

Что такое «система контроля версий» и почему это важно? Система контроля версий (GIT) — это система, записывающая изменения в файл или набор файлов в течение времени и позволяющая вернуться позже к определённой версии. Для контроля версий файлов в этой книге в качестве примера будет использоваться исходный код программного обеспечения, хотя на самом деле вы можете использовать контроль версий практически для любых типов файлов.

Область индексирования — это файл, обычно находящийся в каталоге Git, в нём содержится информация о том, что попадёт в следующий коммит. Её техническое название на языке Git — «индекс», но фраза «область индексирования» также работает.

Каталог Git — это то место, где Git хранит метаданные и базу объектов вашего проекта. Это самая важная часть Git и это та часть, которая копируется при клонировании репозитория с другого компьютера.

---

Базовый подход в работе с Git выглядит так:

1. Изменяете файлы вашей рабочей копии.
2. Выборочно добавляете в индекс только те изменения, которые должны попасть в следующий коммит, добавляя тем самым снимки только этих изменений в индекс.
3. Когда вы делаете коммит, используются файлы из индекса как есть, и этот снимок сохраняется в ваш каталог Git.

Если определённая версия файла есть в каталоге Git, эта версия считается зафиксированной (committed). Если файл был изменён и добавлен в индекс, значит, он индексирован (staged). И если файл был изменён с момента последнего распаковывания из репозитория, но не был добавлен в индекс, он считается изменённым (modified).

---

### Содержание

1. [git init](./pages/init.md)
2. [git clone](./pages/clone.md)
3. [git add](./pages/add.md)
4. [git status](./pages/status.md)
5. [git commit](./pages/commit.md)
6. [git branch](./pages/branch.md)
7. [git checkout](./pages/checkout.md)
8. [git push](./pages/push.md)
9. [git diff](./pages/diff.md)
10. [git log](./pages/log.md)
11. [git revert](./pages/revert.md)
12. [git restore](./pages/restore.md)
13. [git clean](./pages/clean.md)

---

LICENSE: [MIT](./license.md)

GIT logo by Jason Long http://git-scm.com/downloads/logos, license: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

<img src="./assets/git_logo.png" alt="GIT logo by Jason Long" width="100"/>