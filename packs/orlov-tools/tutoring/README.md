# orlov-tools/tutoring — Репетиторство и предметные занятия

Пак для площадки ФиксАР (agrigate.pro).

## Что делает

- Ведёт дело по этапам сделки из `tutoring.yaml`; держит ведомости в самом деле (умение `progress_log`).

## Чего не делает

- Не делает того, что объявлено `not_built` («Записать ученика в расписание студии»), и не выходит за границы `never` агента.

## Как проверить

```bash
python3 tools/pack.py validate packs/orlov-tools/tutoring
python3 tools/pack.py build packs/orlov-tools/tutoring --out dist
```
