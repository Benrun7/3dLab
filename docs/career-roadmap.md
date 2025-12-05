# Дорожная карта перехода в Product Management (Crypto/Fintech/Web3)

## 0. Отправная точка
- **Текущая роль:** технический руководитель лаборатории АП (FDM/SLA/SLS/SLM, 3D-сканирование, Google Sheets-финмодели, Kanban, knowledge base, управление командой).
- **Цель:** PM-роль в Crypto/Fintech/Web3 с доходом ≥ $4k/мес.
- **Стратегия:** опереться на глубину индустриального опыта, показать продакт-компетенции через портфель (2 внутренних автоматизации + 2 внешних доменных проекта), укрепить публичный профиль и сети.
- **Ограничения:** параллель с текущей работой ⇒ план разбит на недели с акцентом на быструю материализацию артефактов (PRD, дашборды, прототипы).

## 1. Быстрые победы и фиксация базы (Недели 1–2)
**Цель:** зафиксировать текущий опыт и создать опорные материалы.
- Провести product-gap self-review (матрица навыков: Discovery, Delivery, Data, Crypto domain).
- Оцифровать кейсы из текущей роли (затраты, throughput, SLA команд) в формате one-pager + storytelling STAR.
- Настроить централизованное хранилище артефактов (Notion/GitHub repo + Google Drive portfolio).
**Артефакты:**<br>skill-matrix, 3 storytelling cards, обновлённый README репозитория, high-level roadmap (текущий документ).
**Метрики:** заполнена матрица, ≥3 кейс-описания, структура репозитория согласована.

## 2. Продуктовая аналитика и Web3-экономика (Недели 3–6)
**Фокус:** подтянуть «жёсткие» PM-компетенции под целевой рынок.
- SQL/эксперименты: ежедневный 45-минутный трек (mode.com, StrataScratch) + 2 мини-задачи с cohort/retention.
- Web3 unit economics: декомпозировать 2 реальных токен-моделей (Lido, Aave), собрать заметки с формулами.
- Legal & compliance: конспект по KYC/AML, лицензированию, MiCA/SEC guidance (1 заметка/неделя).
- Delivery toolkit: обновить шаблоны PRD, Gantt/kanban, metrics tree для crypto-продуктов.
**Артефакты:** SQL notebook, токеномические разборы, шаблон PRD, reference metrics tree.
**Метрики:** ≥12 решённых SQL-задач, ≥2 токен-модели, PRD template опубликован в repo.

## 3. Автоматизация текущей роли (Недели 4–8, параллельно с блоком 2)
**Цель:** показать продуктовую дисциплину на базе существующего домена.
1. **Advanced STL Cost Calculator (SLM)** — расширить текущий калькулятор: импорт STL → объём/площади → калькуляция себестоимости + рекомендации по цене.
2. **Express Quotation Engine** — ввод габаритов, класс сложности, SLA → мгновенный скоринг пригодности и стоимость.
- Для каждого проекта: собрать discovery (pain, users, текущий процесс), сформировать PRD, roadmap, метрики, demo (Streamlit/Sheets/Colab).
- Данные/техдолг: автоматизировать Google Sheets формулы (Apps Script) и подготовить API-слой (FastAPI mock).
**Артефакты:** 2 PRD, demo ссылки, репозиторий кода, видео walkthrough.
**Метрики:** время расчёта ↓ 50%, точность прогноза ±5%, ≥1 внутренний stakeholder review.

## 4. Портфель в Crypto/Fintech (Недели 7–14)
**Проект A — DeFi Treasury Yield Planner**
- Пользователь: финдиректора крипто-стартапов.
- Фичи: агрегатор стратегий (staking, restaking, RWA), stress-test, уведомления по APY.
- Технологии: Python + Streamlit дашборд, on-chain API (DefiLlama), Notion/PRD, unit economics модель.

**Проект B — Web3 BNPL Risk Scoring**
- Пользователь: marketplace/BNPL платформы с crypto collateral.
- Фичи: скоринг кошелька (on-chain history), лимиты, уведомления о риске, legal controls.
- Технологии: SQL (Dune datasets), Python scoring pipeline, Figma UX флоу, PRD + GTM plan.

**Для обоих проектов:** провести user research (3 эксперта/интервью), описать discovery, JTBD, метрики (North Star + input metrics), сделать публичный repo с документацией и демо.
**Метрики:** ≥2 опубликованных кейса, 100+ просмотров на GitHub/LinkedIn, ≥3 внешних фидбека.

## 5. Личный бренд, CV и рынок (Параллельно, старт с Недели 2)
- **CV:** адаптация под crypto PM (highlight product outcomes, экономику, кросс-функции). Версия EN/RU + ATS-friendly PDF.
- **GitHub:** curate pinned projects (2 automation + 2 crypto), обновить README, добавить badges/tests.
- **LinkedIn/Twitter:** еженедельные посты (insights из проектов, токеномика, продакт-уроки). План контента на 6 недель.
- **Нетворк:** 5 targeted интро/неделя (ex-crypto PM, founders, recruiters). Материалы: elevator pitch, outreach templates.
- **Интервью-подготовка:** банк кейсов, система ответов (CIRCLES, AARM), mock interviews 1/нед.

## 6. Календарь и контроль
| Недели | Трек | Основные вехи |
|--------|------|---------------|
|1–2|Foundation|Skill-matrix, storytelling cards, repo skeleton|
|3–6|Analytics/Web3|SQL cadence, токеномика разборы, PRD template|
|4–8|Automation|Demo №1 (нед.6), Demo №2 (нед.8), stakeholder review|
|7–10|Crypto Project A|Research → Prototype → Public launch|
|10–14|Crypto Project B|Research → Prototype → Public launch|
|Параллельно|Brand & Job Search|CV v1 (нед.4), GitHub refresh (нед.5), outreach (еженед.)|

**Цикл контроля:**
- Понедельник — план спринта (3 outcome-ориентированных цели).
- Пятница — review: что shipped, метрики прогресса, блокеры.
- Каждые 4 недели — операционная ретроспектива + обновление roadmap.

## 7. Риски и планы смягчения
- **Перегрузка ресурсами:** лимитировать активные проекты до 2, остальное в backlog.
- **Недостаток доступа к данным crypto:** заранее составить список публичных API/Dune запросов, подготовить mock-данные.
- **Недостаток внешнего фидбека:** раннее шаринг прототипов в профильных комьюнити (Notion, Farcaster, Telegram DAO чаты).
- **Контекстный разрыв между АП и Web3:** подчёркивать transferable навыки (финмодели, операционный контроль, R&D) в каждом кейсе.

---
**Следующие действия:**
1. Уточнить/получить файл «Specialist Profile…» для кросс-проверки целей.
2. Заполнить skill-matrix (черновик можно вести в Google Sheets, шаблон подготовим отдельно).
3. Структурировать репозиторий: `/docs` (стратегия), `/automation` (текущие проекты), `/crypto-portfolio` (новые проекты).
