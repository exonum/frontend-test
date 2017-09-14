### Single Page Application - Bitcoin blockchain explorer

Цель тестового задания - создать web-приложение, которое сможет проверять общее состояние сети Bitcoin, а также находить в этой сети некоторую информацию.

Сеть Bitcoin представляет собой цепочку блоков.
В каждом блоке есть ссылка на предыдущий.
Уникальный индентификатор блока - его высота (`height`).
Новый блок генерируется примерно каждые 10 минут.
В блоке хранится информация про определенное количество транзакций.
Транзакция - это перевод средств с кошелька на кошелек.
Уникальный индентификатор транзакции - её хеш (`hash`). 

#### Требуемый функционал:
1. Главная страница (список 10-ти последних блоков,
список 10-ти последних транзацкции,
график цены биткоина за последний месяц,
форма для поиска блоков по `height` и транзакций по `hash`);
2. Страница со списком блоков, содержащая пагинацию;
3. Страница блока, содержащая информацию про блок и список хранящихся в нем транзакций (с пагинацией);
4. Страницы транзакции со всех доступной информацией о транзакции.

#### Требования к реализации:
* Код написанный на версии JS не ниже ES5, либо TypeScript;
* Автоматическая сборка исходников (webpack/grunt/gulp);
* Responsive layout (использование Boostrap приветствуется);
* Redux или RxJS;
* Immutable структуры данных (Immutable.js, Seamless-immutable, etc.);
* Все необходимые данные доступны в публичном API [blockchain.info](https://blockchain.info/api/blockchain_api).

#### Результатом тестового задания будет:
* Исходный код проекта на GitHub или Bitbucket.

#### Ссылки на примеры:
[Главная №1](https://blockchain.info/ru/home)  
[Главная №2](https://blockexplorer.com/)  
[Список блоков](https://blockchain.info/en/blocks)  
[Полная страница блока](https://blockchain.info/ru/block/0000000000000000002e1baaee54d9e6fa34c6dbd4115b0f0df9dd88598c91e0)  
[Полная страница транзакции](https://blockchain.info/ru/tx/3ab30534c82e4a0ad071767610315cde64fb6923775ab5a96f0cb9a56368ca5e)

#### Ссылки на API:
[Blockchain HTTP API](https://blockchain.info/api/blockchain_api)  
[Blockchain WebSocket API](https://blockchain.info/api/api_websocket)  
[Bitcoin Rates API](https://blockchain.info/api/exchange_rates_api)