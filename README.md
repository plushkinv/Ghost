# Автор
PLushkin https://t.me/plushkin_blog        

**На чай с плюшками автору:**
Полигон, БСК, Арбитрум - любые токены - `0x79a266c66cf9e71Af1108728e455E0B1D311e95E`

Трон TRC-20 только USDT, остальное не доходит - `TEZG4iSmr31wWnvBixKgUN9Aax4bbgu1s3`

# Чё делает
Скрипт автоматизирует функционал сайта https://ghostmint.tech/ , Основная задача сайта помощь в прогреве ваших кошельков в проекте ЛайерЗеро. 
Скрипт позволяет в автоматическом режиме сразу на большом количестве кошельков минтить НФТ от проекта Ghost и бриджить их через L0 в другие сети.

Скрипт позволят выбрать сети назначения и сети источники, позволяет ограничить выбор направления максимальной комиссией которую вы готовы заплатить  и многие другие настройки - читай все комментарии в файле config.py


# Настройка
Сеть зора из РФ работет только с проксями, рекомендую используйте ротируемые прокси
https://go.nodemaven.com/plushkinva
Промик просто на 500mb без оплат и привязки карты FREE500.

Этого вам хватит для работы скрипта на пол года. В настройках надо указать только один проксик, желательно ротируемый, он каждый запрос посылает с нового Ip адреса.

Остальные насйтроки произведите в соответствии с вашими представлениями о прогреве кошельков, каждый параметр подробно описан в комментариях.
все настройки производятся в файле config.py.

Если у вас возникнут вопросы по настройке скрипта, вы всегда можете обратиться за помощью в чат - https://t.me/plushkin_chat

# Установка и запуск:

Linux/Mac - https://www.youtube.com/watch?v=8rJ-96cPFwU
```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

python main.py
```
Windows - https://www.youtube.com/watch?v=EqC42mnbByc
```
pip install virtualenv
virtualenv .venv
.venv\Scripts\activate
pip install -r requirements.txt

python main.py
```


