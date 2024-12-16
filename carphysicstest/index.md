**[`< Projekty własne`](https://codecanter.github.io/portfolio/)**

![Car](https://github.com/user-attachments/assets/595e41c4-589d-4dda-9716-ac916874ecf8)

**CarPhysicsTest** (listopad 2024 - obecnie)

Symulator samochodu, w którym nacisk położono na odwzorowanie fizyki pojazdu (uwzględnienie głównych sił). Opracowany model może być bazą dla symulatora nauki/doskonalenia jazdy.

Założenia projektu:
- rozważenie czy komponenty WheelCollider warto zastosować jako element modelu fizycznego pojazdu - zdecydowano się zrezygnować z używania tego komponentu
zawieszenie pojazdu opracowano w oparciu o Physics.SphereCast
- uwzględnienie głównych sił działających na pojazd:
    - siła oddziaływania zawieszenia (zespół sprężyna - amortyzator)
    - siła boczna (przeciwdziałająca ześlizgiwaniu się pojazdu w poprzek wzniesienia - jeśli siły przyczepności opony są wystarczające)
    - siła oporu czołowego
    - siła od kół napędowych (uwzględniono siłę tarcia i możliwość utraty przyczepności opony w trakcie przyspieszania)
    - siła hamowania (uwzględniono możliwość utraty przyczepności opony, obecnie bez symulacji systemu ABS)
    - siły oporu tocznego
- siły przeciwdziałające sile odśrodkowej w trakcie zmiany kierunku ruchu pojazdy (uwzględniono możliwość uślizgu pojazdu)
odtworzenie charakterystyk przyjętego pojazdu - masa, współczynniki oporu, charakterystyka silnika, droga hamowania, itp.
- model opracowany z myślą o sterowaniu przy użyciu kierownicy, pedałów i skrzyni biegów (automatycznej, sekwencyjnej lub manualnej)

![CarPhysics](https://github.com/user-attachments/assets/aa8984bb-f3ef-4aef-bfb0-1203f0837c12)

**[`< Projekty własne`](https://codecanter.github.io/portfolio/)**
