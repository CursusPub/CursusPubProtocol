# CursusPub Roadmap

*Note: This is an enthusiast-driven project developed in spare time. Phases represent technical milestones rather than fixed dates.*

### Phase 0: Specification & Foundation
*   Finalize the core CursusPub specification (v0.1).
*   Define standard JSON message envelopes and Ed25519 signing procedures.

### Phase 1: Reference SDK & Bootstrap
*   Release the reference **CursusPub SDK** for initial integration.
*   Deliver a basic Relay/Message Box (PHP/SQLite) as a starting point for message exchange.

### Phase 2: Transport Expansion
*   Develop adapters for diverse transports: **XMPP**, **LXMF (Reticulum)**, and **Email**.
*   Ensure delivery logic: the sender must be connected to at least one transport supported by the receiver.

### Phase 3: Automatic Discovery
*   Implement a discovery mechanism (via **DHT**, Adverts, or public catalogs).
*   Enable nodes to retrieve a recipient's public key and supported transport list using only their **Node ID**.

### Phase 4: High-Level Abstractions
*   Standardize message type catalogs for interoperability.
*   Create legacy bridges (e.g., REST-to-CursusPub adapters).


---

# План развития (Roadmap) CursusPub

*Примечание: Это энтузиастский проект, разрабатываемый в свободное время. Фазы представляют собой технические этапы, а не фиксированные даты.*

### Фаза 0: Спецификация и фундамент
*   Финализация базовой спецификации CursusPub (v0.0.1).
*   Определение стандартов JSON-конвертов сообщений и процедур подписи Ed25519.

### Фаза 1: Эталонный SDK и запуск
*   Выпуск эталонного **CursusPub SDK** для первичной интеграции.
*   Создание базового ретранслятора/почтового ящика (PHP/SQLite) для обмена сообщениями на старте.

### Фаза 2: Диверсификация транспортов
*   Разработка адаптеров для различных транспортов: **XMPP**, **LXMF (Reticulum)** и **Email**.
*   Реализация логики доставки: отправитель должен быть подключен хотя бы к одному транспорту, поддерживаемому получателем.

### Фаза 3: Автоматическое обнаружение (Discovery)
*   Внедрение механизмов обнаружения (через **DHT**, адверты или публичные каталоги).
*   Возможность получения публичного ключа и списка транспортов получателя по его **Node ID**.

### Фаза 4: Высокоуровневые абстракции
*   Стандартизация каталогов типов сообщений для совместимости.
*   Создание мостов для устаревших систем (например, адаптеры REST-в-CursusPub).
  
