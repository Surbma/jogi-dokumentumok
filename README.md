Jogi dokumentumok
=================

Itt találhatóak a mindenkor aktuális jogi dokumentumok és azok előző verziói. Így az egyes változtatások nyomonkövetése, visszaellenőrzése is egyszerűbb.

**Elérhető dokumentumok:**
- Általános Szerződési Feltételek - Üzemeltetés
- Általános Szerződési Feltételek - Optimalizálás
- Vállalkozási Keretszerződés

## Verziószám

A verziószám két részből áll:

1. Az első szám határozza meg a főverziót. Minden olyan módosítás, ami a meglévő feltételeket, adatokat, meghatározásokat módosítja bármelyik dokumentumban, egy új főverziót kap. A repository főbb változásai esetén is ez a szám változik.
2. A második szám határozza meg az adott főverzió javításait. Minden stilisztikai, elrendezésbeli, helyesírás és egyéb javítás ide tartozik, ami nem módosít a dokumentumok jelentésén, értelmezésén és a feltételek meghatározásán, érvényességén. Új főverzió esetén ez a szám nullázódik, tehát mindig az adott főverzióra vonatkozik. A repository kisebb változásai esetén is ez a szám változik.

## Utolsó frissítés

Az utolsó frissítés dátuma minden esetben a dokumentumok tartalmi módosításaira vonatkozik, tehát a stilisztikai, megjelenésbeli és egyéb kis hibajavítások esetén nem frissül. A dátum azt az állapotot mutatja, amikor a szerződés lényegi elemei utoljára módosultak, azaz a főverzió frissülésével megegyező dátumot.

## Jogi dokumentumok formátumai

A jogi dokumentumok három formátumban készülnek:
- A dokumentumok eredetileg .md, azaz Markdown formátumban készülnek, mely egy egyszerűsített szemantikus szerkesztői nyelv egyszerű szöveg formában elmentve.
- Az .md formátumból generált .pdf, azaz Portable Document Format formátum, mely egy platform és felbontás független, kifejezetten dokumentumok (képek, szövegek, ábrák) tárolására alkalmas fájlformátum. A jogi dokumentumok ebben a formában érhetők el és tölthetők le a weboldalon.
- Az .md formátumból egy HTML fájl is készül, ami a webes formázásokat tartalmazza, így teszi alkalmassá, hogy a weboldalon is közzé legyenek téve a dokumentumok a hozzájuk kapcsolódó menüpontok alatt.

A Markdown és Portable Document Format konvertálásához a következő online szolgáltatást használjuk:
https://www.markdowntopdf.com/

## Formázási szabványok

A jogi dokumentumok egységes megjelenése érdekében az alábbi formázási szabványokat kell követni minden dokumentum szerkesztésekor. A referencia dokumentum: `md/aszf-premiumwp-optimalizalas.md`

### Dokumentum struktúra

| Elem | Szabvány | Példa |
|------|----------|-------|
| **Dokumentum cím** | H1 címsor (`#`) | `# Általános Szerződési Feltételek - Optimalizálás` |
| **Verzió metaadat** | Félkövér, pipe-szeparált, 2. sor | `**VERZIÓ: 1.0 \| UTOLSÓ FRISSÍTÉS: 2025.12.01.**` |
| **Fő fejezetek** | H2 címsor (`##`) számmal + pont | `## 1. Szerződő felek` |
| **Alfejezetek** | H3 címsor (`###`) hierarchikus számozás | `### 1.1. Vállalkozó` |
| **Al-alfejezetek** | H4 címsor (`####`) 3-szintű számozás | `#### 2.3.1. Extra tuning` |

### Fejezet számozás

| Szabály | Leírás |
|---------|--------|
| **Formátum** | Szám + pont (NEM zárójelezve!) |
| **H2 fejezetek** | Egyszintű: `1.`, `2.`, `3.` |
| **H3 alfejezetek** | Kétszintű: `1.1.`, `1.2.`, `2.1.` |
| **H4 al-alfejezetek** | Háromszintű: `2.3.1.`, `2.3.2.` |

**Fontos:** Zárójelek használata TILOS a számozásban! ❌ `1.)` ✅ `1.`

### Szövegformázás

| Elem | Szabvány | Példa |
|------|----------|-------|
| **Kiemelés/Címkék** | Félkövér (`**szöveg**`) | `**Álomvilág Kft.**` |
| **Lista címkék** | Félkövér címke + kettőspont | `- **Székhely:** 7761 Kozármisleny...` |
| **Jogi kereszthivatkozás** | Pont jelölés | `4.1. pontban` |
| **Százalék értékek** | Nincs szóköz a `%` előtt | `50%` |
| **Pénznem értékek** | Magyar formátum | `15.000 Ft` |

### Dátum és verzió formátumok

| Elem | Formátum | Példa |
|------|----------|-------|
| **Dátum formátum** | `ÉÉÉÉ.HH.NN.` (záró ponttal) | `2025.12.01.` |
| **Verzió formátum** | Fő.Mellék | `1.0`, `14.1`, `2.1` |

### Lista formázás

| Típus | Szabvány | Példa |
|-------|----------|-------|
| **Felsorolás** | Kötőjel (`-`) | `- Első elem` |
| **Címkézett lista** | Félkövér címke + kettőspont + érték | `- **Telefon:** +36 70 209 3432` |
| **Egyszerű lista** | Sima szöveg elemek | `- Domain DNS kezelés` |

### Térköz és elrendezés

| Szabály | Leírás |
|---------|--------|
| **Fejezet térköz** | Üres sor minden címsor előtt és után |
| **Lista térköz** | Nincs üres sor a lista elemek között |
| **Bekezdés térköz** | Egy üres sor a bekezdések között |

### Jogi terminológia

A felek megnevezése a dokumentum típusától függően változhat:

| Dokumentum típus | Szolgáltató | Ügyfél |
|------------------|-------------|--------|
| **ÁSzF - Üzemeltetés** | Szolgáltató | Előfizető |
| **ÁSzF - Optimalizálás** | Vállalkozó | Megrendelő |
| **VKSz** | Vállalkozó | Megrendelő |

### Dokumentum sablon

Minden új dokumentum az alábbi struktúrát kövesse:

```markdown
# [Dokumentum típus] - [Altípus]
**VERZIÓ: X.X | UTOLSÓ FRISSÍTÉS: ÉÉÉÉ.HH.NN.**

[Opcionális bevezető bekezdés]

## 1. Első fő fejezet

### 1.1. Első alfejezet

- **Címke:** Érték
- **Másik címke:** Másik érték

### 1.2. Második alfejezet

[Tartalom...]

## 2. Második fő fejezet

[Tartalom...]
```
