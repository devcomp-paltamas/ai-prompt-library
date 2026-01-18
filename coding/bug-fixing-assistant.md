# Bug Fixing Asszisztens

## Cél
Hibák gyors azonosítása, debugging támogatás és javítási javaslatok készítése.

## Prompt

```
Segíts megtalálni és javítani a hibát ebben a kódban. Kérlek:

1. **Elemezd a hibát**
   - Milyen típusú hiba (szintaktikai, logikai, runtime)?
   - Mikor jelentkezik a hiba?
   - Mi okozza a hibát?

2. **Debugging stratégia**
   - Milyen lépésekkel lehet izolálni a problémát?
   - Milyen debug eszközöket érdemes használni?
   - Milyen teszteket kell végezni?

3. **Javítási javaslatok**
   - Add meg a javított kódot
   - Magyarázd el, miért működik a javítás
   - Mutass alternatív megoldásokat, ha vannak

4. **Megelőzés**
   - Hogyan kerülhető el a hiba a jövőben?
   - Milyen teszteket kell írni?
   - Milyen best practice-eket kell követni?

**Hibaüzenet:** [IDE MÁSOLD A HIBAÜZENETET]
**Kód:** [IDE MÁSOLD A KÓDOT]
**Elvárt működés:** [ÍRD LE, MIT VÁRUNK]
```

## Használati példa

**Input:**
```python
Hibaüzenet: IndexError: list index out of range

Kód:
my_list = [1, 2, 3]
for i in range(4):
    print(my_list[i])

Elvárt működés: Ki kell írnia az összes elemet a listából.
```

**Output:** Claude azonosítja, hogy a range(4) túlmutat a lista méretén, és javaslatot tesz a javításra.

## Változatok

### Performance Bug Hunting
```
Ez a kód lassan fut. Segíts azonosítani a teljesítmény bottleneck-eket:
- Profilozási javaslatok
- Lassú műveletek azonosítása
- Optimalizálási lehetőségek

[KÓD]
```

### Memory Leak Detector
```
Ez az alkalmazás túl sok memóriát használ. Segíts megtalálni a memory leak-et:
- Memória használat elemzése
- Leak források azonosítása
- Javítási javaslatok

[KÓD]
```

## Megjegyzések

- Minél több kontextust adsz (hibaüzenet, input adatok, környezet), annál jobb a diagnózis
- Használható unit tesztek írásához is
- Kombinálható code review prompttal

---

**Kategória:** Kódolás  
**Alkalmazási terület:** Debugging, Troubleshooting  
**Utolsó frissítés:** 2026. január