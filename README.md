# Портал електронних закупівель — Ecooptima

Репозиторій містить документацію для веб-проєкту системи електронних закупівель обладнання для компанії [Ecooptima](https://ecooptima.com.ua/).

## Мета проєкту

Автоматизувати процес закупівлі обладнання та матеріалів у кількох постачальників за принципом відкритих тендерів — аналогічно до системи Prozorro, але адаптованої для потреб приватної енергогенеруючої компанії.

## Структура документації

> **Почніть з [Огляду проєкту](docs/overview.md)** — короткий путівник по всіх документах із ключовими висновками.

| Документ | PDF | Опис |
|----------|:---:|------|
| [docs/overview.md](docs/overview.md) | [PDF](pdfs/overview.pdf) | ⭐ Короткий огляд: путівник по документах та ключові висновки |
| [docs/requirements.md](docs/requirements.md) | [PDF](pdfs/requirements.pdf) | Функціональні та нефункціональні вимоги, обсяг першої версії |
| [docs/market-analysis.md](docs/market-analysis.md) | [PDF](pdfs/market-analysis.pdf) | Аналіз Prozorro/SmartTender/Newtend, порівняння SaaS vs власна розробка |
| [docs/functional-spec.md](docs/functional-spec.md) | [PDF](pdfs/functional-spec.pdf) | Детальний опис як користуватися системою + перелік усіх функціональних вимог |
| [docs/proposal-openprocurement.md](docs/proposal-openprocurement.md) | [PDF](pdfs/proposal-openprocurement.pdf) | Пропозиція на базі OpenProcurement — ядра Prozorro (найшвидша, ~9 міс) |
| [docs/proposal-opensource.md](docs/proposal-opensource.md) | [PDF](pdfs/proposal-opensource.pdf) | Пропозиція на базі ERPNext/Frappe (відкритий код, ~12 міс) |
| [docs/project-proposal.md](docs/project-proposal.md) | [PDF](pdfs/project-proposal.pdf) | Пропозиція власної розробки на FastAPI + React (~15 міс) |

## Коротко про проєкт

- **Тривалість першої версії:** 9–15 місяців (залежно від обраного підходу)
- **Команда:** 2 внутрішніх розробники Ecooptima
- **Хостинг:** на власних серверах Ecooptima (безкоштовно)
- **Зовнішні витрати:** ~30,000 грн/рік (SSL, поштовий сервіс, API перевірки контрагентів)

## Готові SaaS-рішення (аналіз)

Детальне порівняння — у [docs/market-analysis.md](docs/market-analysis.md). Короткий підсумок:

| Платформа | Тип | Приватні тендери | Орієнтовна вартість | Вердикт |
|-----------|-----|:----------------:|---------------------|:-------:|
| **[SmartTender](https://smarttender.biz)** | Комерційний SaaS (UA) | ✅ Так | ~15,000–80,000 грн/рік + 0.1–0.2% з угоди | ⭐ Найкращий варіант для старту |
| **[Newtend](https://newtend.com)** | Комерційний SaaS (UA) | ✅ Так | Подібно до SmartTender | ✅ Гідна альтернатива |
| **[Prozorro](https://prozorro.gov.ua)** | Державна платформа | ⚠️ Публічно | Комісія ~0.1–0.3% з угоди | ⚠️ Лише якщо прийнятна повна публічність |
| **Міжнародні** (Jaggaer, Coupa) | Enterprise SaaS | ✅ Так | від $50,000/рік | ❌ Надмірні для поточних потреб |

**Рекомендована стратегія:** розпочати на SmartTender або Newtend (швидкий старт, ~1–4 тижні), накопичити досвід за 12 місяців, після чого ухвалити обґрунтоване рішення щодо власної розробки.

## Статус

Фаза: **Аналіз та планування**

## Контакти

- Компанія: [ecooptima.com.ua](https://ecooptima.com.ua/)
