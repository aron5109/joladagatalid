# Jólagleði – jóladagatal starfsfólks

Sjónræn, gagnvirk frumgerð að íslensku jóladagatali með 24 gluggum. Allt er í einni skrá, `index.html`, með innbyggðu HTML, CSS og JavaScript. Engin ytri söfn, leturgerðir eða netþjónn eru notuð.

Þetta er frumgerð: dagsetningin er valin með sýnidagastýringunni efst á síðunni (1., 18. og 24. desember) og síðan notar hvorki raunverulega dagsetningu né læsingu á netþjóni. Staða skoðaðra glugga er vistuð í `localStorage` vafrans undir lyklinum `jolagledi-opened`.

## Keyra staðbundið

Opnaðu `index.html` beint í vafra, eða keyrðu einfaldan vefþjón í möppunni:

```sh
python3 -m http.server 8000
```

og farðu á <http://localhost:8000>.

## Birting

Síðan er birt með GitHub Pages af `main`-greininni úr rótarmöppunni (`/`).
