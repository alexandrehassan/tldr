# ghci

> Интерактивная среда Glasgow Haskell Compiler.
> Больше информации: <https://downloads.haskell.org/ghc/latest/docs/html/users_guide/ghci.html>.

- Запустить REPL (интерактивную оболочку):

`ghci`

- Запустить REPL и загрузить указанный исходный файл Haskell:

`ghci {{исходный_файл.hs}}`

- Запустить REPL и включить опцию языка:

`ghci -X{{опция_языка}}`

- Запустить REPL и включить определённый уровень предупреждений компилятора (например, `all` или `compact`):

`ghci -W{{уровень_предупреждений}}`

- Запустить REPL со списком папок, разделённых двоеточием, в которых нужно искать исходные файлы:

`ghci -i{{путь/до/папки1:путь/до/папки2:...}}`
