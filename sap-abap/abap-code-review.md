# ABAP Kód Review és Optimalizálás

## Cél
SAP ABAP kód minőségének ellenőrzése, performance optimalizálás és best practice javaslatok.

## Prompt

```
Végezz részletes ABAP code review-t a következő kódra:

**Kód típusa:** [Report, Function Module, Class, Enhancement]
**SAP verzió:** [ECC 6.0, S/4HANA]
**Teljesítmény kritikus:** [Igen/Nem]

Vizsgáld meg a következő szempontokat:

1. **ABAP Best Practices**
   - Elnevezési konvenciók (Y*, Z*)
   - Modularizáció (Forms, Methods)
   - Error handling (TRY-CATCH, MESSAGE)
   - Memória optimalizálás

2. **Performance**
   - Database access optimalizálás
   - SELECT optimalizálás (FOR ALL ENTRIES, JOIN)
   - Internal table kezelés (HASHED, SORTED)
   - Field symbols vs Work areas
   - Parallel processing lehetőségek

3. **ABAP 7.4+ Modern Szintaxis**
   - Inline deklarációk (DATA, FIELD-SYMBOL)
   - String templates
   - Constructor expressions
   - NEW, VALUE, CORRESPONDING operátorok

4. **S/4HANA Compatibility**
   - Code Inspector eredmények
   - ABAP Test Cockpit (ATC) check
   - Deprecated statements azonosítása
   - CDS view használat lehetősége

5. **Biztonság és Autoritzáció**
   - Authority-check használat
   - SQL injection védelem
   - Input validáció

Add meg a konkrét javítási javaslatokat kód példákkal!

[IDE MÁSOLD AZ ABAP KÓDOT]
```

## Használati példa

**Input:**
```abap
DATA: lt_mara TYPE TABLE OF mara,
      ls_mara TYPE mara.

SELECT * FROM mara INTO TABLE lt_mara.

LOOP AT lt_mara INTO ls_mara.
  WRITE: / ls_mara-matnr, ls_mara-maktx.
ENDLOOP.
```

**Output:** Részletes elemzés performance javítási javaslatokkal, modern szintaxis használatával.

## Változatok

### S/4HANA Migration Check
```
Elemezd ezt az ABAP kódot S/4HANA migrációs szempontból:
- Deprecated statements
- HANA optimalizálási lehetőségek
- CDS view konverzió javaslatok
- Custom code adaptation szükséglet

[ABAP KÓD]
```

### Performance Tuning
```
Optimalizáld ezt az ABAP kódot performance szempontból:
- SQL optimalizálás
- Internal table handling
- Memory management
- Parallel processing
- Konkrét mérési javaslatok (SAT, ST05)

[ABAP KÓD]
```

## Megjegyzések

- Code Inspector és ATC check-eket mindig futtasd le
- S/4HANA környezetben preferáld a CDS view-kat
- Használj ABAP Unit teszteket

---

**Kategória:** SAP ABAP  
**Verzió:** ECC 6.0, S/4HANA  
**Utolsó frissítés:** 2026. január