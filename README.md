# Épületgépészeti tervrajz szerkesztő

Böngészőben futó, telepítést nem igénylő kapcsolásivázlat-rajzoló épületgépészeti skiccekhez.
Az egész alkalmazás egyetlen fájl: `index.html` — elég megnyitni egy böngészőben.

## Funkciók

- **Valós termékek** a saját árlistából: minden elem konkrét termékhez kötött
  (Bosch Condens 2300i W fűtő és kombi kazán, BOSCH CS3400iAWS / AWS hőszivattyú,
  BOSCH HP200 2.UNODC 200 l HMV tároló, BOSCH AT 200 puffer, BOSCH HW 50 hidraulikus
  váltó, Wilo szivattyú, ESBE keverőszelep stb.) nettó árakkal.
- **Gyári csonkkiosztás** a kazánokon (FE / HMV / GÁZ / HV / FV, ill. fűtőkazánnál
  tárolócsonkok) és a tárolókon, mérettel (1/2", 3/4", 1") és felirattal; a csonk fölé
  érve a lábléc mutatja a nevét.
- **Vezetékrajzolás** színkódolt csövekkel (piros = fűtés előremenő, kék = visszatérő /
  hidegvíz, sárga = gáz, narancs = HMV) és **választható csőtípussal** (ötrétegű,
  réz, szénacél, inox, gázcső, PE-Rt, KPE) az árlista méteráraival.
- A vezetékek **rátapadnak a csonkokra**, és az elem mozgatásakor követik azt.
- **Anyaglista egy gombnyomásra**: berendezések darabszámmal és nettó árral,
  csővezetékek hossza csőtípusonként (állítható lépték: 100 px = X m), és
  **minden bekötött csonkhoz automatikus elzáró csap** (gázcsonkhoz gázcsap,
  szivattyúhoz hollandi). CSV-letöltés és vágólapra másolás.
- Elemek mozgatása, forgatása, duplikálása, átnevezése; szabad szövegek.
- Visszavonás / mégis, automatikus mentés a böngészőbe.
- Mentés/megnyitás JSON fájlként, exportálás **SVG** és **PNG** képként, nyomtatás.
- Nagyítás görgővel, rajzlap mozgatása húzással.

## Használat

Nyisd meg az `index.html` fájlt böngészőben, vagy engedélyezd a GitHub Pages-t
(Settings → Pages → Deploy from branch) és a rajzoló webcímen is elérhető lesz.
A beépített súgó a `?` gombbal nyílik.
