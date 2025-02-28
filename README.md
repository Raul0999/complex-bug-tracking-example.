Complex Bug Tracking Example

Цели проекта

Демонстрация эффективного использования GitHub для отслеживания и управления ошибками в сложном программном проекте.** Мы стремимся показать, как использовать инструменты GitHub для организации процесса разработки, от обнаружения ошибок до их исправления и выпуска новых версий.
Освоение инструментов GitHub: Issues, Labels, Assignees, Milestones, Projects.** Цель - получить практический опыт работы с ключевыми функциями GitHub, необходимыми для командной разработки и управления проектами.
Разработка навыков командной работы и коммуникации (если применимо).** (Если вы работаете в команде) Мы хотим отработать навыки эффективного взаимодействия при решении задач, связанных с отслеживанием и устранением ошибок.

Описание функциональности

Этот проект представляет собой упрощенный пример веб-приложения (условно), которое обладает следующими основными функциями:

Загрузка изображений на сервер.** Пользователи могут загружать изображения различных форматов (JPEG, PNG, GIF) на сервер для использования в своих профилях или для других целей.  При этом должны учитываться ограничения на размер файлов и типы допустимых форматов.
Аутентификация пользователей.**  Приложение предоставляет возможность пользователям регистрироваться и входить в систему с использованием логина и пароля.  Должна быть предусмотрена защита от brute-force атак и возможность восстановления пароля.
Отображение списка задач (To-Do List).** Пользователи могут создавать, просматривать, редактировать и удалять задачи в своем личном списке дел.  Задачи должны иметь приоритет, срок выполнения и статус (например, "выполнено", "в процессе", "отложено").
Управление профилем пользователя.** Пользователи могут просматривать и редактировать информацию в своем профиле, такую как имя, адрес электронной почты, аватар и другие настройки.

Условия эксплуатации

Приложение должно соответствовать следующим критериям:

Безопасность:
Защита от распространенных веб-уязвимостей, таких как SQL-инъекции, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF).
Надежное хранение паролей пользователей (использование bcrypt или аналогичных алгоритмов хеширования).
Проверка и фильтрация вводимых данных для предотвращения атак.
Производительность:
Быстрая обработка запросов пользователей (время отклика не должно превышать 2 секунд для большинства операций).
Оптимизация загрузки изображений (использование сжатия и кеширования).
Эффективное использование ресурсов сервера (минимизация потребления памяти и процессора).
Удобство использования (Usability):
Интуитивно понятный и простой в использовании интерфейс.
Четкие и понятные сообщения об ошибках.
Адаптивный дизайн, обеспечивающий корректное отображение на различных устройствах (компьютеры, планшеты, смартфоны).
Надежность:
Стабильная работа в различных условиях (высокая нагрузка, сетевые сбои и т.д.).
Обработка исключительных ситуаций и предотвращение аварийного завершения работы.
Регулярное резервное копирование данных.
