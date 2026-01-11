# Project Manifesto & Philosophy

### Inspiration: The Modern *Cursus Publicus*
The protocol is named after the **Cursus Publicus**, the ancient Roman courier network. Just as the Romans used a network of relay stations to move messages across various terrains,
CursusPub messages travel through a landscape of available transports (HTTPS, Radio, Mesh) rather than relying on a single central hub.

### Core Philosophy
CursusPub aims to end the "tyranny of synchronization and centralization". In our vision, every user should host their own **A2A agents** on personal devices (including mobile), ensuring digital sovereignty and independence from corporate cloud platforms.

### Main Concepts
*   **Node-Centricity:** Every entity is a Node. Identity is cryptographic (Ed25519) and permanent, regardless of the network location or transport used.
*   **SDK as Implementation:** CursusPub is primarily an **SDK for applications**. It replaces direct REST/SOAP calls with a protocol-based interaction layer.
*   **Asynchronous by Design:** The protocol does not expect an immediate response. Messages are signed and sent; delivery happens when the recipient's transport becomes available.
*   **Transport Agnosticism:** CursusPub does not handle routing internally. Instead, it delegates this task to the underlying transports. No internal relaying is performed within the CursusPub layer itself.

### Goals
1. Provide a universal way for software to interact directly without intermediaries.
2. Enable communication in environments with unstable links and "gray" IP addresses.
3. Decouple application logic from network infrastructure.

---

# Манифест и философия проекта

### Вдохновение: Современный *Cursus Publicus*
Протокол назван в честь **Cursus Publicus** — древнеримской курьерской сети. Подобно тому как римляне использовали сеть станций для передачи сообщений через разные ландшафты, сообщения CursusPub перемещаются через любые доступные транспорты (HTTPS, Радио, Mesh),
не полагаясь на единый центральный узел.

### Основная философия
CursusPub стремится положить конец «тирании синхронности и централизации». В нашем видении каждый пользователь должен иметь возможность хостить собственных **A2A-агентов** на личных устройствах (включая мобильные),
обеспечивая цифровой суверенитет и независимость от корпоративных облачных платформ.

### Основные концепции
*   **Узлоцентричность:** Каждый участник — это Узел. Идентичность криптографична (Ed25519) и постоянна, независимо от местоположения в сети или используемого транспорта.
*   **SDK как основа:** CursusPub — это прежде всего **SDK для приложений**. Он заменяет прямые вызовы REST/SOAP на уровень взаимодействия на базе протокола.
*   **Асинхронность по замыслу:** Протокол не ожидает мгновенного ответа. Сообщения подписываются и отправляются; доставка происходит, когда транспорт получателя становится доступен.
*   **Независимость от транспорта:** CursusPub не занимается внутренней маршрутизацией. Вместо этого он делегирует эту задачу нижележащим транспортам. Ретрансляция на уровне самого CursusPub не предполагается.

### Цели
1. Обеспечить универсальный способ прямого взаимодействия программ без посредников.
2. Обеспечить связь в условиях нестабильных каналов и «серых» IP-адресов.
3. Отделить прикладную логику от сетевой инфраструктуры.
