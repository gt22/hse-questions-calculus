# Билеты к экзамену по Мат. Анализу [![Build Status](https://travis-ci.org/gt22/hse-questions-calculus.svg?branch=master)](https://travis-ci.org/gt22/hse-questions-calculus)

## Собранные билеты лежат в ветке `pdf`. 
### При просмотре прямо на гитхабе не работает содержание и могут быть проблемы с загрузкой подздних страниц. Рекомендуется скачивать к себе.

## Стиль теханья:

Определения/Теоремы/etc вида:

```latex
\begin{TYPE}[Можно название] \thmslashn
    *пустая строка*
    трататата
    \begin{proof} \thmslashn
        *пустая строка*
        тратата
    \end{proof}
\end{TYPE}
```

Возможные TYPE: `theorem`, `definition`, `statement`, `remark`, `lemma`, `consequence`, `example`, `properties`, `property`

Функции обозначиются как `f : X \mapsto Y`

Генераторы множеств - `X = \{x \ssep x \in Y\}`

В `core.tex` определена ещё куча операторов.

Пары/Кортежи - `\left<X, Y\right>`

Пустое множество - `\emptyset`

Предикаты - `\forall{x \in X}\quad \exists{y \in Y}\quad x = y`
