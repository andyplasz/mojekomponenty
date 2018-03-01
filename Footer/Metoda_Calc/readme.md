Created using JS Bin
http://jsbin.com

Copyright (c) 2018 by andyplasz (http://jsbin.com/nefinuc/1/edit)

Released under the MIT license: http://jsbin.mit-license.org

 Opcja korzysta z wbudowanej funkcji calc(). Ta metoda polega na:

zawijaniu wszystkiego oprócz stopki w div,
ustawianiu stałej wysokości stopki i
obliczaniu wysokości kontenera treści jako "pełnej wysokości okna - wysokości stopki".
  Podstawą tego rozwiązania jest funkcja calc(). Dynamicznie obliczająca wysokość .content poprzez odejmowanie wysokości stopki od wysokości całego okna. W ten sposób .content zawsze będzie spychał stopkę na spód okna.

Jednakże ta metoda ma to samo ograniczenie co poprzednia - działa tylko wtedy, gdy Twoja stopka ma stałą wysokość. Jeszcze raz, to nie od razu spisuje na straty tę metodę, ale musisz być tego świadomy.
