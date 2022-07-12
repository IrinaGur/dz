Создаем Telegram-бота, в котором будут две кнопки: «Скороговорки» и «Поговорки».
Если нажать любую кнопку, бот отправит пользователю соответствующее сообщение.

Чтобы создать бота, нам нужно дать ему название, адрес и получить токен — строку,
которая будет однозначно идентифицировать нашего бота для серверов Telegram.
Зайдем в Telegram под своим аккаунтом и откроем «отца всех ботов», BotFather.

Жмем кнопку «Запустить» (или отправим /start), в ответ BotFather пришлет нам список доступных команд:
/newbot — создать нового бота;

Для взаимодействия с Telegram API есть несколько готовых модулей.
Самый простой из них — Telebot. Устанавливаем.

1. импортируем библиотеку

2.Создаем экземпляр бота: добавляем токен, полученный от @botfather'.
3. Создаем список команд и функции
 
4.Чтобы пользователям нашего бота было удобно, покажем им сразу все в виде кнопок.
А потом сделаем так, что когда на них нажимаешь — появляется скороговорки или поговорки.

5.отслеживание, что запрашивает user

6.запускаем бота.
