# CursusPub

### The Asynchronous Agent SDK for a Disconnected World
**CursusPub** is an open protocol and a set of SDKs designed to replace traditional, synchronous WebAPIs (REST, SOAP, WebHooks) with resilient, asynchronous interaction between autonomous agents (A2A).

---

## 🚀 Key Features
*   **A2A SDK Focus:** Primary implementation is a software development kit that allows apps to communicate via the protocol instead of direct API calls [User Query].
*   **Transport Agnostic:** Routing is delegated to pluggable transports (HTTPS, XMPP, LXMF, Email, etc.). The protocol logic is independent of the delivery medium [User Query, 181, 230].
*   **Cryptographic Identity:** Every participant is a Node identified by the hash of its **Ed25519** public key [1-3].
*   **Designed for Intermittency:** Ideal for mobile devices, gray IP addresses (behind NAT), and environments without stable connectivity [4-6].

---
![Инфографика CursusPub](cursuspub_en.png).

# Протокол CursusPub

### Асинхронный SDK для автономных агентов в разъединенном мире
**CursusPub** — это открытый протокол и набор SDK, предназначенных для замены традиционных синхронных WebAPI (REST, SOAP, WebHooks) на устойчивое асинхронное взаимодействие между автономными агентами (A2A).

---

## 🚀 Ключевые особенности
*   **Ориентированность на SDK:** Основная реализация — это набор инструментов (SDK), позволяющий приложениям заменить обычные вызовы API на взаимодействие через протокол.
*   **Независимость от транспорта:** Маршрутизация делегируется подключаемым транспортам (HTTPS, XMPP, LXMF, Email и др.). Логика протокола не зависит от среды передачи.
*   **Криптографическая идентификация:** Каждый участник — это Узел (Node), идентифицируемый хешем его открытого ключа **Ed25519**.
*   **Работа в нестабильных сетях:** Идеально подходит для мобильных устройств, «серых» IP-адресов (за NAT) и условий отсутствия постоянного соединения.

![Инфографика CursusPub](cursuspub_ru.png).
