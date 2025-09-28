---
title: "Visszaállítás gyári állapotra"
author: rain-it
date: 2025-03-02 17:33:00 +0200
categories: [RainIT, Leiras]
tags: [RainIT, Leiras, Reset]
pin: false
img_path: '/assets/img/20250302'
---

## WiFi routert cserélek, mi a teendő?

Sajnos az opensprinkler vezérlő magától nem fog új wifit keresni.
Ezért erdemes az alábbi kép szerint kitörölni a wifi beállításokat, mielőtt száműzzük a régi routert.

![Desktop View](/001.jpg){: width="972" height="589" .w-50 .right}

## Későn jutott eszembe a vezeték nélküli beállítások törlése
Pánikra semmi ok, több lehetőség is van a helyzet megoldására.
1. Ugyanaz lesz a neve és a jelszava az új wifinek is, így semmi gond, a vezérlő automatikusan csatlakozni fog hozzá.
2. Ideiglenesen újra üzembe helyezzük a régi routert a régi beállításokkal és a fenti kép szerint járunk el.
3. Ha tönkrement vagy nincs mód visszaállítani a régi wifit, a beállítások ismeretében lehetséges mobiltelefonunk segítségével a korábbi wifi beállításoknak megfelelő hotspotot létre hozni. A telefon kisebb hatótávolságú wifit képes sugározni, így érdgemes közelebb menni a vezérlőhöz. Ha kész a hotspot a vezérkő gyorsabban visszacsatlakozik, ha egy rövid (20-30 másodperces) áramtalanítással újra indítjuk. Ha nem hasznélunk OTC tokent az eléréshez, a hotspot miatt az IP címe válzotni fog, így az appban újra kell kerestetni.
4. Haminden kötél szakad, vissza lehet állítani gyári beállítsokra a következők szerint.


## Beállítások visszaállítása gyári állapotra

Figyelem! Ez a módszer minden beállítást töröl, az öntözési ütemterveket, integráviókat (OTC token, MQTT), időjárás beállításokat és a wifi beállításokat is.

Visszaállítás gyári állapotra:
- Táp kihúz
- B1 nyomva tart
- Táp be
- B1 innentől 5 másodperc
- B3 nyomva tart, míg kéken villan (3-4 mp)
- Fél perc türelem
 
Ha jól ment, gyári beállításokra állt vissza, újra meg kell tanítani neki a wifit
