Функционал приложения:
    • Возможность создать нового пользователя с двумя ролями, ADMIN и USER, и установить первоначальное количество денежных средств для пользователя.

    • Для пользователя ADMIN предусмотрены возможности просмотра списка всех пользователей, добавление нового товара, просмотр списка всех товаров, при этом каждый товар представляет собой гиперссылку, перейдя по которой, можно изменить или удалить данный товар.

    • Для пользователя USER возможно также просмотреть список всех товаров, каждый из которых представляет собой гиперссылку, перейдя по которой, можно приобрести данный товар. При приобретении товара происходит обновление данных в базе по количеству товара и количеству денег у пользователя.

    • Добавлена одна кроссфилд проверка формы ввода данных для покупки товара, реализованная через собственную аннотацию, работающую на уровне класса. Также добавлены стандартные проверки через стандартные аннотации javax.validation. Результаты проверок выводятся на страницу с формой.

    • Добавлен один тест, проверяющий корректность обновления данных о продукте в базе  через репозиторий с помощью реализации собственного метода. Добавленные для тестирования данные после проверки удаляются.
