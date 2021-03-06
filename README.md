# Пакетный менеджер Cargo (The Cargo Book)

[![gitlocalized ](https://gitlocalize.com/repo/4485/ru/badge.svg)](https://gitlocalize.com/repo/4485/ru?utm_source=badge)

В данном репозитории содержится перевод книги [The Cargo Book](https://github.com/rust-lang/cargo/tree/master/src/doc).

## Зачем ещё один репозиторий?

Этот репозиторий подключён к системе перевода и вся работа ведётся там.
Сама система перевода нужна для отслеживания изменений в оригинале книги и
за счёт этого становится более удобной поддержка перевода, так как не надо
самому переводчику искать что изменилось - система сама это показывает.

## GitLocalize

Проект на GitLocalize: https://gitlocalize.com/repo/4485

## А как же перевод от rust-lang-ru?

Да, он [есть](https://github.com/rust-lang-ru/cargo-docs-ru), но он уж очень устарел.
В то время, как [оригинальная документация](https://doc.rust-lang.org/cargo) ушла далеко вперёд
и выглядит куда менее [вырвиглазно](https://rurust.github.io/cargo-docs-ru).

Тем не менее, я ориентируюсь на [перевод rustbook'а](https://github.com/rust-lang-ru/book) именно этих ребят.

## Немного нюансов

Так как для cargobook нет отдельного репозитория (вся документация лежит рядом с самим
[cargo](https://github.com/rust-lang/cargo)), я создал этот репозиторий прямо внутри репозитория с **cargo**,
поэтому *gitignore* немного странный, а папка с оригинальной документацией называется **doc**.
