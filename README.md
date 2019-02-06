# calendar_pl


Funkcja **time_change** zwraca zmiany czasu w Polsce (w postaci słownika z datą wystąpienia i nazwą/rodzajem zmiany czasu).

```python
time_change(year_start, year_end=None)
```

Funkcja **calendar_pl*** zwraca święta wraz z niedzielami wolnymi od handlu w Polsce (w postaci słownika z datami wystąpięnia i nazwami świąt/niedziel).

```python
calendar_pl(year_start, year_end=None, holidays=True, sundays=True)
```
*Uwaga: Datę Świąt Wielkanocnych wyznaczono zgodnie z algorytmem [Meeus/Jones/Butcher](https://en.wikipedia.org/wiki/Computus).

