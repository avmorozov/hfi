# Разработка системы контроля движения финансовых средств в домашнем хозяйстве

## Что нужно сделать
1. Записка (90 страниц)
	* Первая глава. Аналитика (35 стр.)
	* Вторая глава. Математика (25 стр.)
	* Третья глава. Программа (20 стр.)

2. Программа (надо демонстировать)
	* Сайт как mint.com
	* Автоматическая классификация
	* Бютжетирование
	* Отчеты

3. Презентация

## Научная новизна
1. Автоматическая классификация расходов (категории, отношение категорий)
2. Аналитика по расходам и доходам / поддержка принятия решений
	* Анализ сезонности
	* Как ограничить бюджеты 
	* Управление финансовыми целями
	* Какие кредиты погашать в первую очередь
	* Какие инвестиции и сбережения делать

## Архитектура
Для хранения данных будет использоваться документоориенторованная NoSQL БД.
*Причины:*
+ Возможность добавления реквизитов по мере надобности
+ Сложные связи между документами из коробки
+ Возможности масштабирования при росте нагрузки (поддержка map-reduce)

Пользовательский интерфейс - только веб.

Авторизация - через Oauth распространенных социальных сетей (VK, Odnoklassniki, Facebook, Twitter)

### Стек технологий
* Microsoft .NET / C# 
* ASP.NET MVC 5
* KnockoutJS ?
* MongoDB

## Пользовательские требования
Пользователи:
+ Неавторизованный пользователь
+ Авторизованный пользователь
+ Домовладелец <- авторизованный пользователь
+ Администратор

### Регистрация

### Авторизация

### Создание домовладения

### Ввод счетов (создание / редактирование / удаление)

### Ввод доходных и расходных статей (создание / редактирование / удаление)

### Присоединение пользователя к домовладению

### Ввод платежного документа (создание/редактирование/удаление)

### Загрузка выписки из СБЕРБАНКА

### Разбиение записи о платеже

### Просмотр платежных документов

### Редактирование бюджетов

### Просмотр бюджетов

### Редактирование финансовых целей

### Просмотр финансовых целей