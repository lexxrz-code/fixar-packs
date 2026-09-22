# fixar-packs

Паки для площадки ФиксАР (agrigate.pro).

## orlov-tools/photo — Фото и видеосъёмка

Ведёт дело о съёмке на заказ от заявки до передачи материала: бриф, смета
и договор, съёмка, обработка, показ, акт и оплата. Помогает фотографу
держать сроки сдачи и аренду студии, а заказчику — видеть этапы и принимать
работу по акту. Сам студию не бронирует и файлы не пересылает — это
остаётся за людьми.

Состав пака: `packs/orlov-tools/photo/`

Проверка и сборка:

```bash
python3 tools/pack.py validate packs/orlov-tools/photo
python3 tools/pack.py build packs/orlov-tools/photo --out dist
```

`tools/pack.py` скопирован из репозитория площадки
[lech2000/fixar-packs](https://github.com/lech2000/fixar-packs) (MIT).
