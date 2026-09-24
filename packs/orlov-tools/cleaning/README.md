# orlov-tools/cleaning — Клининг и уборка

Пак для площадки ФиксАР (agrigate.pro).

## Что делает

- Ведёт дело по этапам сделки из `cleaning.yaml`; держит ведомости в самом деле (умение `checklist_sheet`).

## Чего не делает

- Не делает того, что объявлено `not_built` («Нанять клинеров на смену самому»), и не выходит за границы `never` агента.

## Как проверить

```bash
python3 tools/pack.py validate packs/orlov-tools/cleaning
python3 tools/pack.py build packs/orlov-tools/cleaning --out dist
```
