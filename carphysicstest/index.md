**[`< Projekty własne`](https://codecanter.github.io/portfolio/)**

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

**[`< Projekty własne`](https://codecanter.github.io/portfolio/)**
