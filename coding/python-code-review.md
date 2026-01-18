# Python Kód Review

## Cél
Python kód alapos áttekintése, hibák azonosítása, best practice javaslatok és teljesítmény optimalizálás.

## Prompt

```
Kérlek, végezz részletes code review-t a következő Python kódra. Vizsgáld meg a következő szempontokat:

1. **Kód minőség és olvashatóság**
   - Változó és függvény elnevezések
   - Kód struktúra és szervezés
   - Kommentek és dokumentáció

2. **Hibák és potenciális problémák**
   - Szintaktikai hibák
   - Logikai hibák
   - Edge case-ek kezelése
   - Exception handling

3. **Teljesítmény**
   - Algoritmus hatékonyság
   - Memória használat
   - Optimalizálási lehetőségek

4. **Best practices**
   - PEP 8 szabványok betartása
   - Pythonic megoldások
   - Design patterns alkalmazása

5. **Biztonság**
   - Input validáció
   - Biztonsági rések

Add meg a javaslataidat konkrét kód példákkal, és rangsorold őket prioritás szerint.

[IDE MÁSOLD BE A KÓDOT]
```

## Használati példa

**Input:**
```python
def calc(a,b):
    result=a+b
    return result

print(calc(5,3))
```

**Output példa:**
A Claude részletes elemzést ad a kódról, beleértve:
- Javaslat típus hintekre
- Jobb függvénynév
- Docstring hozzáadása
- PEP 8 formázási javaslatok

## Változatok

### Gyors Review Változat
```
Végezz gyors code review-t erre a Python kódra, csak a legfontosabb problémákat és javítási javaslatokat említsd.

[KÓD]
```

### Biztonsági Fókuszú Változat
```
Elemezd ezt a Python kódot kizárólag biztonsági szempontból. Keress sebezhetőségeket, insecure practice-eket és adj biztonsági javaslatokat.

[KÓD]
```

## Megjegyzések

- Nagyobb kódbázis esetén érdemes modulonként vagy függvényenként review-zni
- Használd a promptot CI/CD pipeline-ban automatizált code review-hoz
- Kombinálható unit testek generálásával

---

**Kategória:** Kódolás  
**Nyelv:** Python  
**Nehézség:** Kezdő - Haladó  
**Utolsó frissítés:** 2026. január