Схема v3.0.0
======

Стейкхолдеры
------

![Стейкхолдеры](images/hw_3/SH.jpg)

Матрица влияние-интерес
------

![Матрица влияние-интерес](images/hw_3/SH_IM.jpg)

Консёрны
------

![Консёрны](images/hw_3/Concerns.png)

Ограничения
------

- инфраструктуру считаем бесплатной
- соблюдение CatFinComplience, который говорит об особом способе хранения данных и особой наблюдаемости за системой. Компания не хочет повторять опыт с маски-шоу, которые были в Happy Cat Box.

Характеристики
------

| Характеристики | Источник |
|------------|------------|
| scalebility, securebility | [US-081] Мы ожидаем 1к заявок в день от рандомных котов, также, судя по отзывам, наши конкуренты могут попытаться нас заддосить в этом месте. Они так делали уже несколько раз с другими компаниями, после чего компании закрывались с позором. |
| agility, testability, deployability | Низкий ТТМ |
| modifiability, testability, deployability | Для бизнеса критично проверять новые гипотезы по отсеву котов и изменять уже существующие с максимальной скоростью и надёжностью.|
| agility, testability, deployability, scalability, availability, fault tolerance | Конкурентное преимущество (найм + матчинг) |
| availability, continuity, reliability, еxtensibility, modifiability, maintainability, supportability, readability, accessibility, security, usability | 2 core-поддомена (найм + матчинг) являются конкурентным преимуществом |
| maintainability, readability, supportability | 3 supporting-поддомена |
| maintainability, reliability | Общий консёрн админов и разрабов |
| Consistency | Хранение данных о фин. операциях |

![Характеристики](https://raw.githubusercontent.com/OkinawaNet/MCF/main/images/hw_3/BC_chars.png)


Выбор архитектуры
------

agility, deployability и testability исключают монолит.

