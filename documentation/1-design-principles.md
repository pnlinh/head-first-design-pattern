## Принципи проектирования

1. Выделите аспекты приложения, которые могут изменяться, и отделите их от тех, которые всегда остаються постоянными.
    - Выделите то, что изменяеться, и "инкапсулируйте" эти аспекти, чтобы они не влияли на роботу остального кода.
    - Результат? Меньше непревиденных последствий от изменения кода, большая гибкость ваших систем!
2. Програмируйте на уровне интерфейсов, а не на уровне реализации.
3. Отдавайте предпочтение композиции перед наследованием.
4. Слабосвязаные обьекты.
    - Если два обьекта могут взаимодествовать, не обладая практически никакой информацие друг о друге, такие обьекты называються слабосвязанными. 
5. Open/Closed
    - Классы должны быть открыты для расширения, но закрыты для изменения.
6. Принцип инверсии зависимости
    - Код должен зависить от абстракци, а не от конкретных классов.
    - Высокоуровневые компоненты не должны зависить от низкоуровневых компонентов, вместо этого и те и другие должны зависить от абстракций
7. Принцип минимальной информированости: общайтесь только с близкими друьями. (in facade pattern)
8. Не вызывайте нас - мы вас сами вызовем (in template method)
9. Клас должен иметь только одну причину для изменения (iterator)

TODO:
- [ ] add notice from the 173 page
- [ ] add notice from the 175 page
    