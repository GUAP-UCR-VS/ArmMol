# ArmMol

Устаревший формат данных (до 2024 г.):\
[old.xml](scheme/old.xml)

Новый формат данных (с 2024 г.):\
[new2024.xml](scheme/new2024.xml)

Новая схема данных:\
[guap.parus.import.xsd](scheme/guap.parus.import.xsd)

## Изменения

1. Формат даты приведен к системному: `YYYY-MM-DD` (type="xs:date")
1. Убраны лишние группировочные сущности (`AccountsPlan`, `OKDP`, `Nomenclator`, `MeasureUnits`, `Deps`, `ValuesTurns`, `MOLVTurns`, `Inventory`)
1. Имена атрибутов минимизированы и приведены к `camelCase` по принципу «кто+что» (`parentName`, `parentTitle`, `incomeDate`)
1. У сущности `item` убран атрибут `id` (он не имеет смысла)


