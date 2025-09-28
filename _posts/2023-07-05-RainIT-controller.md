---
title: "RainIT vezérlő"
author: rain-it
date: 2023-07-05 08:33:00 +0200
categories: [RainIT, Leiras]
tags: [RainIT, Leiras]
pin: true
img_path: '/assets/img/20230705'
---


{% include embed/youtube.html id='NSu8Ayk055k' %}

## 8 zónás wifis öntözésvezérlő

![Desktop View](20220718_173559.jpg){: width="972" height="589" .w-50 .right}

Aprócska 8 zónás időjárásalapú okos öntözésvezérlő wifi modullal. Helyi hálózaton számítógépről és mobil appból is elérhető, egyszerű regisztráció után házon kívülről is vezérelhető. Erős Wifi jel és internetkapcsolat javasolt, de nem feltétlenül szükséges a működéshez. Áramlásérzékelő használatával képes kijelezni az elhasznált és a megspórolt víz mennyiségét. Könnyen integrálható okosotthon rendszerekbe, Home Assistant Community Store (HACS) alkalmazással (OpenSprinkler integráció) vagy MQTT-n keresztül OpenHab alá. IFTTT (fizetős) szolgáltatásán keresztül további integrációk lehetségesek.
<hr style="width:50%;height:1px;border-width:0;color:gray;background-color:var(--main-bg)">

## időjáráskövető öntözés

![Desktop View](20190920-151232.png){: width="972" height="589" .w-50 .right}

Az elmúlt két nap időjárási adatai alapján automatikusan állítja be az öntözési mennyiséget, figyelembe véve a helyi hőmérsékletet, páratartalmat és a természetes esőzéseket. Optimalizálja a vízfelhasználást, hogy tavasszal, ősszel ne locsoljon túl, nyáron a kánikulában viszont rákapcsol, hogy ne száradjon ki a fű vagy az öntözött növények. Szezonálisan Budapest környékén 20-30% vizet is képes spórolni. Előfizetés nem szükséges az időjárás szolgáltatás használatához és képes saját időjárás állomás adatait is használni.
<hr style="width:50%;height:1px;border-width:0;color:gray;background-color:var(--main-bg)">

## kényelmes és rugalmas programozás

![Desktop View](20220512-151540_OpenSprinkler.jpg){: width="972" height="589" .w-50 .right}

Kényelmes felületen programozható, nem kell kis gombokat nyomkodni és a menükiosztást megjegyezni. A kezelőfelületen minden beállítási lehetőség látható. Tetszőleges zónák mehetnek párhuzamosan, akár több öntözési program is futhat egyszerre. Az alap vezérlő 8 zónát támogat, de bővítő modulokkal akár 72 zónára is növelhető a zónák száma. Két független mester zónát egymástól függetlenül tud vezérelni, a zónák tetszőlegesen sorolhatók mögéjük. Támogatja a távoli zónákat, íígy több vezérlő is egy felületen kezelhető. HTTP(s) zónákat is tud indítani, ezzel más okosotthonos eszközöket (pl. dugalj, lámpa) vezérelhetünk.
<hr style="width:50%;height:1px;border-width:0;color:gray;background-color:var(--main-bg)">

## frissített hardver

![Desktop View](20220305_203113.jpg){: width="972" height="589" .w-50 .right}

Ez egy saját tervezésű vezérlő, az eredeti opensprinkler DC verzió néhány hibája javítva lett, valamint IP55 védelemmel rendelkező dobozba került, így várható élettartama hosszabb lesz. A DC verzió rugalmasan használható különböző típusú szelepekkel és relékkel. Támogatja a 24V AC, a 9-12V dc szelepeket és reléket is, így biztosan kompatibilis a már meglévő rendszerekkel.
<hr style="width:50%;height:1px;border-width:0;color:gray;background-color:var(--main-bg)">

## további leírások, útmutatók

- <a href="https://rain-it.github.io/posts/Uzembe-helyezes/">Üzembe helyezés</a>
  + Lokáció beállítása
  + Mester szelep
  + Zónák
  + <a href="https://rain-it.github.io/posts/Idojaras/">Időjárás</a>
- Integrációs szolgáltatások
  + <a href="https://rain-it.github.io/posts/OTC-token/">OTC token a távoli eléréshez</a>    
  + <a href="https://rain-it.github.io/posts/Home-Assistant-integracio/">Home Assistant integráció</a>
  + MQTT
- Haladó beállítások
  + Biztonsági mentés
  + Szoftverfrissítés
- <a href="https://rain-it.github.io/posts/Visszaallitas-gyari-allapotra/">Visszaállítás gyári állaptra</a>
<hr style="width:50%;height:1px;border-width:0;color:gray;background-color:var(--main-bg)">
