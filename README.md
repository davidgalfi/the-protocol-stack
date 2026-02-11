# The Protocol Stack

> **"Kiveszi az érzelmet és a döntéshozatalt a képletből. Csak a végrehajtás marad."**

Ez egy **kognitív SRE (Site Reliability Engineering) eszköztár**. Egy statikus weboldal, amely előre megírt, racionális protokollokat (csekklistákat) tartalmaz mérnöki, tanulási és mentális elakadások kezelésére.

## 🧠 Filozófia
Amikor pánikba esel (segfault, határidő, motivációvesztés), a prefrontális kéreg (a racionális agy) lekapcsol. Ilyenkor nem "gondolkodni" kell, hanem egy külső, megbízható folyamatot követni. Ez a repository ezt a folyamatot tárolja.

## 🚀 Használat
A rendszer egy egyszerű `index.html` és egy `data/protocols.json` fájlból áll. Nincs build process, nincs backend.
1. Engedélyezd a **GitHub Pages**-t ebben a repóban (Settings -> Pages -> Branch: main -> Save).
2. Nyisd meg a kapott linket mobilon vagy asztali gépen.
3. Amikor elakadsz, írd be a problémát (pl. "matek", "debug", "fáradt").
4. Kövesd a lépéseket gondolkodás nélkül.

## 🛠️ Testreszabás
Új protokoll hozzáadásához szerkeszd a `data/protocols.json` fájlt.
Formátum:
```json
{
  "id": "egyedi-id",
  "title": "Protokoll Neve",
  "category": "Kategória",
  "severity": "SEV-1 (Kritikus) - SEV-4 (Minor)",
  "steps": ["Lépés 1", "Lépés 2"],
  "exit_condition": "Mikor vagy kész?"
}
```

## ⚠️ Licenc
MIT License. Használd egészséggel, és válj zsenivé napról napra.