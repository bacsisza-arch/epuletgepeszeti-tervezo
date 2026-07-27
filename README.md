# Épületgépészeti tervrajz szerkesztő

Böngészőben futó, telepítést nem igénylő kapcsolásivázlat-rajzoló épületgépészeti skiccekhez.
Az egész alkalmazás egyetlen fájl: `index.html` — elég megnyitni egy böngészőben.

## Funkciók

- **27 épületgépészeti elem** kategóriákba rendezve: gázkazán, hőszivattyú kültéri/beltéri egység,
  napkollektor, puffertartály, HMV tároló, hidraulikus váltó, hőcserélő, osztó-gyűjtő,
  szivattyú, váltó- és keverőszelep, golyóscsap, visszacsapó és biztonsági szelep, szűrő,
  mágnesszelep, radiátor, padlófűtés, fan-coil, mérőműszerek stb.
- **Vezetékrajzolás** színkódolt csövekkel: piros (fűtés előremenő), kék (visszatérő/hidegvíz),
  sárga (gáz), narancs (HMV), zöld, fekete; vonalvastagság és szaggatott vonaltípus is választható.
- A vezetékek **rátapadnak az elemek csatlakozási pontjaira**, és az elem mozgatásakor követik azt.
- Derékszögű (90°-os) vagy szabad vonalvezetés.
- Elemek mozgatása, forgatása, duplikálása, átnevezése; szabad szövegek elhelyezése.
- Visszavonás / mégis, automatikus mentés a böngészőbe.
- Mentés/megnyitás JSON fájlként, exportálás **SVG** és **PNG** képként, nyomtatás.
- Nagyítás görgővel, rajzlap mozgatása húzással.

## Használat

Nyisd meg az `index.html` fájlt böngészőben, vagy engedélyezd a GitHub Pages-t
(Settings → Pages → Deploy from branch) és a rajzoló webcímen is elérhető lesz.
A beépített súgó a `?` gombbal nyílik.
