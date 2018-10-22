# Chance
Библиотека для расчёта шанса с заданной вероятностью

## Примеры

```php
// Получить шанс в одной пятой случаев
$chance = new Chance(Ratio(5));
if ($chance->get()) {
    ...
}
```
