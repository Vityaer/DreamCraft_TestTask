# DreamCraft_TestTask
версия Unity: 2021.3.x LTS

ожидаемый результат в общих чертах:
- бесконечный раннер, игрок управляет автомобилем
- авто двигается вперед, по нажатию на стрелки маневрирует влево и вправо, затем автоматически возвращаясь к направлению "вперёд"
- карта генерируется по мере движения; структура предполагается блочная, генерация случайная, некоторые блоки могут не сочетаться между собой
- * на карте спаунятся объекты случайным образом; столкновение с объектом уничтожает его
- * на HUD выведен счётчик сбитых объектов
- * объекты и блоки карты переиспользуются через пулы

нюансы:
- самый принципиальный момент - использование подхода ECS. в идеале - фреймворк LeoECSLite, хотя допускается использование любого релевантного решения; решающую роль играет понимание подхода и умение его применять
- визуальная составляющая не важна, в качестве авто может выступать серая коробка
- исходники проекта представить репозиторием на github (за соблюдение conventional commits большущий плюс в карму)
- преимуществом будет внятное и ёмкое комментирование кода там, где встретились проблемы или пришлось использовать заглушку вместо полноценного решения
