# ASP.NET Core - авторизация через VK
Пример авторизации на сайте через VK

Перед началом работы необходимо [создать приложение](https://vk.com/apps?act=manage) со следующими настройками (для локальной разработки):
* Платформа - Веб-сайт
* Адрес сайта - `https://localhost/signin-vkontakte`
* Базовый домен - localhost

Начало работы:
* Обновить базу данных (она создастся автоматически) через `dotnet ef database update` или с помощью консоли диспетчера пакетов в VS: `update-database`.
* Изменить AppId (ID приложения) и AppSecret (защищённый ключ) в файле `appsettings.json`. Их можно взять в настройках приложения
* Запустить и авторизоваться через ВК

Для проверки работоспособности авторизации можно перейти по [ссылке Secret](https://localhost:5001/Home/Secret) в навбаре
