# orlov-tools/hotels — Проживание и брони

Пак для площадки ФиксАР (agrigate.pro).

## Что делает

- Ведёт дело по этапам сделки из `hotels.yaml`; держит ведомости в самом деле (умение `booking_calendar`).

## Чего не делает

- Не делает того, что объявлено `not_built` («Списать оплату брони самому»), и не выходит за границы `never` агента.

## Как проверить

```bash
python3 tools/pack.py validate packs/orlov-tools/hotels
python3 tools/pack.py build packs/orlov-tools/hotels --out dist
```
