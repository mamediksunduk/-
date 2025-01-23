# 1. Заполните токены в ConfigType:

CONFIG: ConfigType = ConfigType(
    BOT_TOKEN='ваш_токен_группы_вк',  # Токен от группы ВК
    USER_TOKEN='ваш_личный_токен_вк',  # Токен от личной страницы
    GROUP_ID=ваш_айди_группы,  # Числовой ID группы
    SPECIAL_CHAT_ID=айди_чата_для_уведомлений  # Куда слать уведомления
)


2. Получить токены можно:

• Для бота: https://vk.com/dev/access_token

• Для личной страницы: https://vk.com/dev/implicit_flow_user

3. Запуск осуществляется через main() в конце скрипта
