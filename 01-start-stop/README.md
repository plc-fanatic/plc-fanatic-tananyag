
# 1. Start–Stop és öntartás

Ebben a leckében egy alapvető PLC-vezérlést készítünk el: a Start–Stop kapcsolást öntartással.

## Cél

A feladat végére megérted:

- a Start nyomógomb szerepét,
- a Stop nyomógomb szerepét,
- az öntartás működését,
- a kimenet be- és kikapcsolását.

## Feladat

Készíts olyan vezérlést, amelyben:

- a `Start` gomb megnyomására a kimenet bekapcsol,
- a Start gomb elengedése után is bekapcsolva marad,
- a `Stop` gomb megnyomására a kimenet kikapcsol.

## Megoldás

![Start–Stop öntartó kapcsolás](Start_Stop.jpg)


## Működés

A `Start` nyomógomb megnyomásakor a kimenet bekapcsol.

A kimenet saját segédérintkezője párhuzamosan kapcsolódik a Start nyomógombbal, ezért a Start elengedése után is fenntartja a működést. Ezt nevezzük **öntartásnak**.

A `Stop` nyomógomb megszakítja az áramutat, ezért a kimenet kikapcsol, és az öntartás megszűnik.


## PLCPractice projektfájl

👉 [01_Start_Stop.json letöltése](01_Start_Stop.json)

A fájl a PLCPractice szimulátorban betölthető.

## Gyakorlás

👉 **[Nyisd meg a PLCPractice szimulátort](https://www.plcpractice.com/simulator), és építsd meg te is.**
