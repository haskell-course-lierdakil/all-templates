## all-templates

Все шаблоны в одном месте.

Для запуска всех тестов используйте `cabal v2-test all` или `stack test`.

Для запуска всех тестов производительности используйте `cabal v2-bench all` или `stack bench`.

## division-template

Шаблон для реализации деления с остатком вычитанием, с тестами корректности.

Все функции, которые необходимо реализовать, находятся в `library/Lib.hs`.

Для запуска тестов корректности: `cabal v2-test` или `stack test`

Рассчитано на GHC 8.10.4. При использовании cabal учитывайте это.

## dlist-template

Шаблон для реализации DList, с тестами корректности и производительности.

Все функции, которые необходимо реализовать, находятся в `library/Data/DList.hs`.

В `library/Data/DList/Internal.hs` определён сам тип `DList`.

Для запуска тестов корректности: `cabal v2-test` или `stack test`

Для запуска тестов производительности: `cabal v2-bench` или `stack bench`

От тестов производительности ожидается, что время конкатенации списков линейно растёт с размером списков, в то время как конкатенация DList занимает константное время.

## fibonacci-template

Шаблон для реализации функций Фибоначчи, с тестами корректности и производительности.

Все функции, которые необходимо реализовать, находятся в `library/Lib.hs`.

Для запуска тестов корректности: `cabal v2-test` или `stack test`

Для запуска тестов производительности: `cabal v2-bench` или `stack bench`

Рассчитано на GHC 8.10.4. При использовании cabal учитывайте это.

## instances-template

Шаблон для реализации экземпляров Functor, Applicative, Monad, Traversable, Foldable, с тестами корректности.

Все функции, которые необходимо реализовать, находятся в `library/Lib.hs`.

**Определения типов менять не нужно**. Только реализовать функции классов, которые здесь вместо реализации имеют `undefined`.

Для запуска тестов корректности: `cabal v2-test` или `stack test`

Рассчитано на GHC 8.10.4. При использовании cabal учитывайте это.

## queue-template

Шаблон для реализации Queue, с тестами корректности и производительности.

Все функции, которые необходимо реализовать, находятся в `library/Data/Queue.hs`

В `library/Data/Queue/Internal.hs` определён сам тип `Queue`.

Для запуска тестов корректности: `cabal v2-test` или `stack test`

Для запуска тестов производительности: `cabal v2-bench` или `stack bench`

От тестов производительности ожидается, что только время первого `pop` растёт от размера очереди, прочие операции O(1).

## vigenere-template

Шаблон для реализации шифрования Виженера, с тестами корректности.

Все функции, которые необходимо реализовать, находятся в `library/Lib.hs`.

Для запуска тестов корректности: `cabal v2-test` или `stack test`

Рассчитано на GHC 8.10.4. При использовании cabal учитывайте это.