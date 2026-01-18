# Meeting Jegyzetelő

## Cél
Értekezlet jegyzetek strukturálása, összefoglalása és actionable itemek kinyerése.

## Prompt

```
Dolgozd fel és strukturáld az alábbi meeting jegyzeteket:

**Meeting típusa:** [team standup, client call, stratégiai, brainstorming]
**Résztvevők:** [nevek vagy szerepkörök]
**Időtartam:** [percben]

A feldolgozott jegyzeteknek tartalmazniuk kell:

1. **Executive Summary**
   - 2-3 mondatos összefoglaló
   - Legfontosabb döntések
   - Kulcs kimenetel

2. **Résztvevők és szerepek**
   - Jelenlévők listája
   - Kulcsszemélyek kiemelése

3. **Megbeszélt témák**
   - Téma kategorizálása
   - Főbb pontok téma szerint
   - Felmerült kérdések

4. **Döntések**
   - Meghozott döntések listája
   - Felelős személyek
   - Határidők

5. **Action Items**
   - Konkrét feladatok
   - Felelős: [név]
   - Határidő: [dátum]
   - Prioritás: [magas/közepes/alacsony]

6. **Következő lépések**
   - Soron következő meeting
   - Nyitott kérdések
   - Follow-up szükséglet

[IDE MÁSOLD A NYERS JEGYZETEKET VAGY MEETING TRANSCRIPT-ET]
```

## Használati példa

**Input:** Nyers meeting jegyzet vagy átirat

**Output:** Strukturált, áttekinthető meeting összefoglaló action itemekkel, felelősökkel és határidőkkel.

## Változatok

### Quick Meeting Summary
```
Készíts gyors összefoglalót a meetingről:
- 3 fő téma
- Döntések listája
- Azonnali teendők

[JEGYZETEK]
```

### Action Items Extractor
```
Vond ki az összes action item-et ebből a meeting jegyzetből:
- Feladat leírása
- Felelős személy
- Határidő
- Dependencies

[JEGYZETEK]
```

## Megjegyzések

- Működik meeting transcript-ekkel is (Zoom, Teams, Google Meet)
- Kompatibilis projektmenedzsment eszközökkel (Asana, Jira)
- Használható automatizált workflow-kban

---

**Kategória:** Produktivitás  
**Alkalmazási terület:** Meeting Management, Project Management  
**Utolsó frissítés:** 2026. január