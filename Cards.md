# 1.Случайное событие. Операции над ними

**Случайное событие** является одним из основных понятий теории вероятностей и связано с проведением некоторого эксперимента.

Возможный набор исходов эксперимента $\Omega$ = { $\omega$ } будем называть пространством элементарных событий. Точки или элементы этого пространства называются элементарными исходами или элементарными событиями.

**Пример 1**. Бросание правильной игральной кости один раз, где исходом является число очков (от 1 до 6) на выпавшей грани — пример эксперимента с большим числом исходов. Здесь возможные исходы образуют множество $\Omega$ = {1,2,3,4,5,6}. Б) Бросание игральной кости дважды, где исходами являются пары (i,j) — число очков на выпавшей грани, соответственно, первой и второй кости. Здесь $\Omega$ = {(1,1), (1,2), (1,3), (1,4), (1,5), (1,6), (2,1), (2, 2), ... ,(6, 5), (6, 6)}.

## Операции
1. Cобытие А содержится в событии В (или А влечет за собой В) (обозначение: А $\subseteq$ В), если любое элементарное событие $\omega$ из А входит в В($\forall \omega\in A \Rightarrow  \omega\in B$)
2. События А и В совпадают или равны ( А = В ), если А $\subseteq$ В и В $\subseteq$ А.
3. Объединением (суммой) двух событий А и В (А $\bigcup$ В) будем называть событие, состоящее из элементарных событий, которые входят или в А или в В.
4. Пересечением (произведением) двух событий А и В (А $\bigcap$ В) будем называть событие, состоящее из элементарных событий, которые входят и в А, и в В
5. События А и В называются несовместными, если А $\bigcap$ В = $\oslash$ (т.е. пересечение А и В есть невозможное событие).
6. Дополнением ( Ā ) к событию А (или противоположным к А) называется событие, состоящее из тех элементарных событий $\forall \omega\in \Omega$, которые не входят в А.
7. Разностью между событиями А и В ( А\\\В ) будем называть событие, состоящее из тех элементарных событий, которые входят в А, но не входят в В. { $\omega\in A$ | $\omega\notin B$}

# 2. Статистическое определение вероятности. Свойства вероятности

Пусть некоторый эксперимент повторяется n раз. Фиксируем случайное событие А и предполагаем, что это событие появлялось
$\nu_n$(A) раз. Рассмотрим отношение $\nu_n$(A)/n, которое называется частотой события А в данной серии. С ростом п колебания этого отношения вокруг некоторого постоянного числа Р(А) все меньше и в различных сериях практически совпадают при больших n, 
т.е $\nu_n$(A)/n $\simeq$ Р(А). 

Итак, событию А сопоставляется численная характеристика Р(A), которая и называется вероятностью события А. Такую трактовку понятия вероятности называют частотным или **статистическим определением вероятности**.

# Свойства вероятности
1. Р(Ø) = 0
2. P(Ā) = 1 - P(A)
Поскольку $\Omega$ = A $\bigcup$ Ā и A, Ā несовместные события, то по аксиоме получаем 1 = Р($\Omega$) = Р(A $\bigcup$ Ā ) = Р(A) + Р(Ā)
4. Если А $\subseteq$ В, то Р(В \\\ A) = Р(В) - Р(A).
Пусть В \\\ А == С, тогда С ⋂ А=Ø и С ⋃ А= В. Отсюда согласно аксиоме  получим: Р(В) = Р(С) + Р(А)
5. 