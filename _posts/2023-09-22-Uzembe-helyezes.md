---
title:  "Üzembe-helyezés"
author: rain-it
date: 2023-09-22 08:33:00 +0200
categories: [RainIT, Leiras, OTC-token]
tags: [RainIT, Leiras, OTC-token]
pin: false
img_path: '/assets/img/20230922'
---


OpenSprinkler üzembe helyezése

## Bevezetés

![Vezérlő](/controller.jpg){: width="972" height="589" .w-50 .right}
<h3> 1.</h3>  Csatlakoztasd a mágnesszelepeket a COM-hoz és a zónákhoz (Z1....Z8)!
<h3> 2.</h3>  Csatlakoztasd az adaptert (DC 7.5-9V) a konnektor aljzathoz és a tápcsatlakozó bemenethez! A visszajelző led innentől világítani fog, amíg tápforráshoz van csatlakoztatva a vezérlő.
<h3> 3.</h3>  Az OpenSprinkler első indítása után hozzáférési pont módban indul, azaz a hálózatlistában egy új WLAN-t találsz OS_xxxxxxx SSID-vel (megnevezés). Csatlakoztasd okostelefonod vagy laptopod ehhez a WLAN-hoz. Megjegyzés: Android-eszközökön az az üzenet jelenik meg, hogy ennek a kapcsolatnak nincs internetkapcsolata. Válaszd az Igen lehetőséget, hogy csatlakozva maradj.
<h3> 4.</h3>  Nyissd meg a webböngészőt, és írd be a 192.168.4.1 címet. Ezután kövesd a képernyőn megjelenő utasításokat. A következő lépésekhez szüksége lesz a WLAN útválasztó (router) SSID azonosítójára és a WLAN jelszóra.
<h3> 5.</h3>  A sikeres beállítás után az OpenSprinkler újraindul, és csatlakozik a WLAN-hoz. Android eszközökön kiírja a kapott ip címet is.
<h3> 6.</h3>  Telepítsd az „OpenSprinkler” APP-ot a Play/App Store-ból, és indítsd el.
Alternatív megoldásként beírhatod a http://<ipcím> címet a webböngészőbe, és eléred a webes kezelőfelületet.
Az <ipcím> a hálózati útválasztó felületéről tudható meg. Érdemes fix ip címet hozzárendelni az eszközhöz a a hálózati útválasztó (router) felületén.
Az OpenSprinkler App fel tudja deríteni a hálózaton lévő OpenSprinkler vezérlő(ket) a scan gomra nyomva.
<h3> 7.</h3>  Az alapértelmezett jelszó "opendoor"
<h3> 8.</h3>  Ha nem jön létre kapcsolat, vagy ha rossz WLAN-jelszót adtál meg, nyomd meg a B3 és a B2 gombot a hozzáférési pont módba való visszatéréshez.
