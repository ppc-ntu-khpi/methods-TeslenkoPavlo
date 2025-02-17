[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18247331)
# Практична робота "Створення і використання статичних методів"
Цей репозиторій містить стартовий код для виконання практичної роботи, який містить заготовки двох класів, якідемонструють структуру проекту для виконання завдань "обчислювального характеру"
<img src="https://github.com/ppc-ntu-khpi/identifiers-types-starter/blob/master/computation.png" width="100%"/>
## В рамках практичної роботи ви маєте зробити наступне:
1. модифікувати стартовий код таким чином, щоб метод ```Calculate``` класу ```Exercise``` містив код обчислення значення у відповідності до обраного вами завдання (у разі необхідності можна додавати до класу нові приватні методи)
2. рядок, який виводиться у результаті виконання методу ```main``` класу ```TestResult``` теж слід скоригувати у відповідності до специфіки завдання
3. **README.MD репозиторію має містити опис обраного вами завдання** (з картинками та форматуванням :blush:)!
4. **УВАГА!** Не слід вважати, що завдання дуже прості! Вам необхідно подбати про:
    * **оптимізацію програми - обрати оптимальні з точки зору обсягу використовуваної пам'яті типи даних**
    * **іменування змінних і констант у відповідності до рекомендацій**
    * за бажанням (якщо знаєте що це) - **javadoc-коментарі для класу ```Exercise```, які пояснюють що саме обчислюється і які вихідні дані для цього потрібні**
5. здати завдання. **Нагадую, що здаючи завдання через Google Classroom, слід вказати посилання на створений для вас репозиторій!**

**P.S.** Ви можете обрати завдання на власний розсуд - реалізувати алгоритм, який вас зацікавив, однак якщо буде багато однакових класів, завдання не буде зараховано - намагайтесь робити самотужки та у власному стилі! Звісно ж, ніхто не забороняє користуватись Інтернетом, шукати й використовувати знайдене у Мережі!

**P.P.S.** Не соромтесь обговорювати свої завдання та задавати питання в [Gitter](https://gitter.im/PPC-SE-2020/OOP?utm_source=share-link&utm_medium=link&utm_campaign=share-link) - місці, де спілкуються розробники, там вже є [чат-кімната](https://gitter.im/PPC-SE-2020/OOP?utm_source=share-link&utm_medium=link&utm_campaign=share-link) для наших завдань.

----

## Список завдань
1. Обчислити значення [функції Аккермана](https://uk.wikipedia.org/wiki/%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D1%96%D1%8F_%D0%90%D0%BA%D0%B5%D1%80%D0%BC%D0%B0%D0%BD%D0%B0) для двох невідʼємних цілих чисел n та m
2. Перетворити шестизначне число, подане у десятковій системі числення у двійкову, восьмеричну та шістнадцятиричну систему (метод ```Calculate``` має повернути рядок - список чисел через кому)
3. Знайти кількість робочих днів (субота і неділя - вихідні) у проміжку між двома заданими датами
4. Знайти кількість відпрацьованих співробітником годин у проміжку між двома заданими датами (враховувати лише робочі дні, тривалість робочого дня - 8 годин)
5. Знайти всі прості числа між двома заданими числами (метод ```Calculate``` має повернути рядок - список таких чисел через кому)
6. Знайти всі дільники заданого шестизначного числа (метод ```Calculate``` має повернути рядок - список таких чисел через кому)
7. Знайти всі прості дільники заданого шестизначного числа (метод ```Calculate``` має повернути рядок - список таких чисел через кому)
8. Знайти всі спільні дільники двох заданих тризначних чисел (метод ```Calculate``` має повернути рядок - список таких чисел через кому)
9. Знайти всі спільні прості дільники двох заданих тризначних чисел (метод ```Calculate``` має повернути рядок - список таких чисел через кому)
10. Знайти всі способи якими можна видати задану тризначну суму купюрами номіналом 1, 2, 5, 10, 20, 50, 100, 200, 500 гривень (метод ```Calculate``` має повернути рядок, в якому кожен спосіб - список купюр через кому - відділяється від наступного символом нового рядка ```\n```)
11. Перевірити чи задане слово є [анаграмою](https://uk.wikipedia.org/wiki/%D0%90%D0%BD%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%B0) іншого заданого слова (метод ```Calculate``` має повернути булевське значення)
12. Перевірити чи задане слово є [паліндромом](https://uk.wikipedia.org/wiki/%D0%9F%D0%B0%D0%BB%D1%96%D0%BD%D0%B4%D1%80%D0%BE%D0%BC) (метод ```Calculate``` має повернути булевське значення)
13. Зашифрувати задану фразу [шифром Цезаря](https://uk.wikipedia.org/wiki/%D0%A8%D0%B8%D1%84%D1%80_%D0%A6%D0%B5%D0%B7%D0%B0%D1%80%D1%8F) з заданою величиною зсуву N
14. Перетворити [CIDR](https://ru.wikipedia.org/wiki/%D0%91%D0%B5%D1%81%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%BE%D0%B2%D0%B0%D1%8F_%D0%B0%D0%B4%D1%80%D0%B5%D1%81%D0%B0%D1%86%D0%B8%D1%8F)-адресу на маску підмережі та діапазон IP-адрес (метод ```Calculate``` має повернути відповідним чином сформований рядок)
15. Обчислити контрольну суму (хеш) [MD5](https://uk.wikipedia.org/wiki/MD5) для заданого слова (пароля)
16. Зашифрувати задану фразу [шифром Віженера](https://uk.wikipedia.org/wiki/%D0%A8%D0%B8%D1%84%D1%80_%D0%92%D1%96%D0%B6%D0%B5%D0%BD%D0%B5%D1%80%D0%B0) за заданим словом-ключем
17. Зашифрувати задану фразу [шифром XOR](https://uk.wikipedia.org/wiki/%D0%A8%D0%B8%D1%84%D1%80_XOR) за заданим словом-ключем
18. Зашифрувати задану фразу [шифром Скитала](https://uk.wikipedia.org/wiki/%D0%A1%D0%BA%D0%B8%D1%82%D0%B0%D0%BB%D0%B0) (шифром давньої Спарти)
19. Зашифрувати задану фразу [шифром Плейфера](https://uk.wikipedia.org/wiki/%D0%A8%D0%B8%D1%84%D1%80_%D0%9F%D0%BB%D0%B5%D0%B9%D1%84%D0%B5%D1%80%D0%B0) за заданим словом-ключем
20. Обчислити ряд [чисел Нараяни](https://uk.wikipedia.org/wiki/%D0%A7%D0%B8%D1%81%D0%BB%D0%BE_%D0%9D%D0%B0%D1%80%D0%B0%D1%8F%D0%BD%D0%B8) за заданим його номером (метод ```Calculate``` має повернути рядок - список таких чисел через кому)
21. Знайти всі [злі числа](https://ru.wikipedia.org/wiki/%D0%97%D0%BB%D0%BE%D0%B5_%D1%87%D0%B8%D1%81%D0%BB%D0%BE) між двома заданими числами (метод ```Calculate``` має повернути рядок - список таких чисел через кому)
22. Перетворити задане число з двійкової системи на [код Грея](https://ru.wikipedia.org/wiki/%D0%97%D0%BB%D0%BE%D0%B5_%D1%87%D0%B8%D1%81%D0%BB%D0%BE)
23. Розрахувати [число долі](https://sergeiyurev.com/chislo-sudby-v-numerologii/) за заданою датою народження 
24. Розрахувати поточне (на сьогоднішній день) значення [біоритмів людини](http://uchinfo.com.ua/inform/excel/bioritm.htm) за заданою датою народження 

[![Run on Repl.it](https://repl.it/badge/github/ppc-ntu-khpi/identifiers-types-starter)](https://repl.it/github/ppc-ntu-khpi/identifiers-types-starter) [![Gitter](https://badges.gitter.im/PPC-SE-2020/OOP.svg)](https://gitter.im/PPC-SE-2020/OOP?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

