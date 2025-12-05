# Storytelling Cards — From Additive Manufacturing Lead to Crypto/Fintech PM

## 1. SLM Cost Calculator Standardization
- **Role / Context:** Technical Lead, additive manufacturing lab (SLM/SLS/FDM). Manual costing took 1–2 hours per RFQ, estimates varied by engineer.
- **Task:** Build a repeatable system that combined geometry data, machine rates, labor, and margin guidance so sales could answer customers same day.
- **Actions:**
  - Сформировал пайплайн: импорт STL → вычисление объёма детали и поддержек → автозаполнение себестоимости в Google Sheets + Apps Script.
  - Провёл 5 интервью с инженерами и sales, идентифицировал ключевые переменные (плотность, коэффициенты постобработки, SLA).
  - Настроил контрольные точки (план/факт себестоимости, отклонения > 5 % в отчётах руководителю), подготовил knowledge base по сценариям ценообразования.
- **Result:** Оценочно сократил цикл ответа клиенту с ~90 минут до < 15 минут, точность предложений держал в диапазоне ±5 % от фактических затрат; снял нагрузку с инженеров (~6 часов в неделю).
- **Transferable PM Signals:** Discovery → прототип → rollout; построение метрик (SLA котировок, точность), кросс-функциональное управление (sales + engineering).
- **Next Step in Roadmap:** используем этот кейс в storytelling deck (Недели 1–2) и масштабируем в **Advanced STL Cost Calculator** с API-слоем и демо (Недели 4–8).

## 2. Express Quotation Engine & Screening Table
- **Role / Context:** Принимал поток мелкосерийных заказов; не все изделия подходили под 3D-печать, и оценка занимала часы.
- **Task:** Быстро отсеивать неподходящие модели и давать express-оценку менеджерам и клиентам на основе габаритов, класса сложности и SLA.
- **Actions:**
  - Создал scoring-модель (размеры, материал, класс точности, требуемый lead time) и таблицу скрининга с порогами допуска.
  - Автоматизировал расчёт в Google Sheets: формулы + выпадающие списки для менеджеров, подсказки по следующему шагу (собеседование с технологом, отказ, апселл).
  - Провёл обучение для sales, внедрил фидбек-цикл (код цвета по отклонениям факта, еженедельный обзор pipeline).
- **Result:** Время первичного ответа клиенту сократилось «с часов до минут», около 30 % неподходящих заказов отсекались автоматически, а менеджеры получили единый стандарт коммуникации.
- **Transferable PM Signals:** Создание lightweight-скоринг модели (аналог fintech risk), формализация процесса принятия решения, enablement для GTM команды.
- **Next Step:** Реплицировать подход в **Web3 BNPL Risk Scoring** (Недели 7–14), где скоринг кошельков и лимитов станет прямым аналогом текущей логики.

## 3. Knowledge Base & Team Operating System
- **Role / Context:** Лаборатория росла до 15+ специалистов, нужно было стабилизировать delivery и прозрачность.
- **Task:** Выстроить операционный цикл: планирование, 1:1, контроль SLA и прозрачные отчёты для руководства.
- **Actions:**
  - Настроил Kanban (prod + R&D), регулярные планёрки, 1:1 и ретроспективы; ввёл календарь компетенций и расписание оборудования.
  - Создал knowledge base: регламенты, чек-листы качества, шаблоны совещаний, отчётные дашборды в Google Sheets/Slides.
  - Решал конфликты и эскалации, распределял ресурсы между технологиями (SLM/SLS/FDM), синхронизировал с закупками и финансовым блоком.
- **Result:** Улучшили соблюдение SLA производства (по внутренним отчётам), упростили onboarding новых инженеров, повысили прозрачность для руководителя (weekly exec summary).
- **Transferable PM Signals:** Team leadership, stakeholder management, умение строить операционную систему продукта (rituals, dashboards, comms).
- **Next Step:** Оформить этот опыт в CV/GitHub README и использовать как доказательство leadership track, пока в крипто-проектах формируем новые ритуалы (stakeholder review для automation demo, community sync для DeFi проекта).

