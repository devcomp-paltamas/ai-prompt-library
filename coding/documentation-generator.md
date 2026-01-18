# Dokumentáció Generátor

## Cél
Automatikus, professzionális dokumentáció készítése kódhoz, API-khoz és projektekhez.

## Prompt

```
Készíts részletes dokumentációt a következő kódhoz. A dokumentációnak tartalmaznia kell:

1. **Áttekintés**
   - Mi a kód célja?
   - Milyen problémát old meg?

2. **Függvények/Osztályok dokumentálása**
   - Paraméterek leírása (típus, cél, alapértelmezett érték)
   - Visszatérési értékek
   - Kivételek, amelyeket dobhat
   - Használati példák

3. **Kód példák**
   - Egyszerű használati esetek
   - Komplex szcenáriók
   - Edge case-ek kezelése

4. **Telepítés és használat**
   - Függőségek
   - Telepítési lépések
   - Konfigurációs opciók

5. **API referencia** (ha releváns)
   - Végpontok
   - Request/Response formátumok
   - Hibakódok

Formázd a dokumentációt Markdown formátumban, használj kód blokkokat és egyértelmű szekció címeket.

[IDE MÁSOLD BE A KÓDOT]
```

## Használati példa

**Input:** Egy Python osztály vagy függvény

**Output:** Teljes körű markdown dokumentáció docstring-ekkel, példákkal és használati útmutatóval.

## Változatok

### README.md Generátor
```
Készíts professzionális README.md fájlt ehhez a projekthez. Tartalmazza:
- Projekt leírás és cél
- Telepítési útmutató
- Használati példák
- API dokumentáció
- Contributing guidelines
- Licenc információ

[PROJEKT LEÍRÁS/KÓD]
```

### API Dokumentáció
```
Generálj OpenAPI/Swagger kompatibilis API dokumentációt ehhez az endpoint-hoz:
- Útvonal és HTTP metódus
- Request paraméterek
- Response formátumok
- Hibakezelés
- Példa request/response párok

[API KÓD]
```

## Megjegyzések

- Különböző programozási nyelvekhez adaptálható
- Használható automatizált dokumentáció generáláshoz
- Kombinálható kód komment generátorral

---

**Kategória:** Kódolás  
**Támogatott nyelvek:** Python, JavaScript, Java, C++, stb.  
**Utolsó frissítés:** 2026. január