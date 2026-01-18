# CDS View és RAP Fejlesztés

## Cél
SAP S/4HANA CDS (Core Data Services) view-k és RAP (RESTful ABAP Programming) fejlesztésének támogatása.

## Prompt

```
Segíts CDS View vagy RAP alkalmazás fejlesztésében:

**Típus:** [CDS View, RAP BO, Virtual Data Model]
**Használat:** [Analytical, Transactional, Consumption]
**S/4HANA verzió:** [2020, 2021, 2022+]

1. **CDS View fejlesztés**
   - View típus kiválasztása (Basic, Composite, Consumption)
   - Join-ok és Association-ok
   - Annotations (UI, OData, Analytics)
   - Authorization kontrolok (DCL)
   - Performance optimalizálás

2. **RAP Business Object**
   - Behavior Definition
   - Behavior Implementation
   - Determinations és Validations
   - Actions és Functions
   - Draft handling

3. **VDM (Virtual Data Model)**
   - Interface View
   - Composite View
   - Consumption View
   - Value Help
   - Text Association

4. **Annotations**
   - @UI annotations (LineItem, FieldGroup)
   - @OData annotations
   - @Analytics annotations
   - @ObjectModel annotations
   - @Search annotations

5. **Best Practices**
   - Naming conventions
   - Reusability
   - Performance (Pushdown)
   - Authorization concept

**Feladat:** [KÖVETELMÉNY LEÍRÁSA VAGY CDS KÓD]
```

## Használati példa

**Input:**
```
Készíts egy CDS view-t, amely a Sales Order (VBAK, VBAP) adatokat 
jeleníti meg customer adatokkal (KNA1) összekapcsolva, 
Fiori elemek számára optimalizálva.
```

**Output:** Teljes CDS view definíció annotations-ökkel, association-ökkel és consumption layer-rel.

## Változatok

### RAP Business Object Generálás
```
Készíts egy teljes RAP Business Object-et:
- Interface + Projection view
- Behavior Definition
- Behavior Implementation osztály
- CRUD műveletek
- Validations

[ÜZLETI KÖVETELMÉNY]
```

### CDS to Fiori Mapping
```
Vedd ezt a CDS view-t és add meg a szükséges UI annotations-öket 
egy List Report Fiori app számára:
- @UI.lineItem
- @UI.selectionField
- @UI.fieldGroup
- Value helps

[CDS VIEW KÓD]
```

## Megjegyzések

- HANA pushdown optimalizálás
- SQL View vs CDS View különbségek
- RAP managed vs unmanaged scenarios

---

**Kategória:** SAP ABAP  
**Terület:** CDS, RAP, S/4HANA  
**Utolsó frissítés:** 2026. január