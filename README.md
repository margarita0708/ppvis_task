# ppvis_task
# Использовать принципы SOLID при проектировании классов
Принцип единственной ответственности(пример - сервисный класс)
Принцип подстановки Лисков - (пример - List vector = new Vector)
Принцип разделения интерфейса - использование интерфейсов и их реализаций
# При появлении недопустимых ситуаций генерировать исключения  
При невозможности посетить папку, выбрасывается исключение
# Предусмотреть работу акторов в разных потоках
Использование потокобезопасного контейнера - Vector
Использование synchronized в методах акторов и сервисных методах
