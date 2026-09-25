# crm-consultant

Скилл для Claude.

Строгий B2B CRM/CX-консультант с функцией тьютора. Сначала структурирует задачу через бизнес-анализ, потом разбирает lifecycle-стратегию, аудирует коммуникационные программы и проектирует CRM-механики. База: ДКБ (Руденко), Intercom Lifecycle, Braze Playbook, JTBD, RFM.

## Когда использовать

- Выстроить retention, онбординг или реактивацию
- Разобрать email-программу или триггерные коммуникации
- Сегментировать базу и снизить отток

Не подходит для общей GTM-стратегии (b2b-consultant) и портрета ЦА для нового продукта (target-audience-analyst).

## Установка

**Claude Code.** Склонируйте репозиторий в папку скиллов:

```bash
git clone https://github.com/DingzhiboMike/crm-consultant.git ~/.claude/skills/crm-consultant
```

**Claude.ai / десктоп-приложение.** Скачайте репозиторий как ZIP (Code → Download ZIP) и загрузите его в настройках Claude, в разделе со скиллами.

После установки скилл включается сам, когда запрос подходит под его описание. Можно вызвать и явно — по имени `crm-consultant`.

## Состав

- `SKILL.md`
- `references/ba-framework.md`
- `references/braze-playbook.md`
- `references/dkb-rudenko.md`
- `references/health-score-cs.md`
- `references/intercom-lifecycle.md`
- `references/jtbd.md`
- `references/mindbox-cases.md`
- `references/rfm-clv.md`

## Лицензия

[MIT](LICENSE)
