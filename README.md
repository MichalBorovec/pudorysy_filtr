# Půdorysy – ověřené AI prompty

Repozitář pro verzované šablony fotorealistických úprav 3D půdorysů.

## Doporučená ověřená verze (2026-10-16)

**[v1.2 BALANCED SUNLIGHT](prompts/FLOORPLAN_ULTRA_REALISTIC_v1.2_BALANCED_SUNLIGHT.md) – UŽIVATELSKY OVĚŘENO / LOCKED.** Uživatel potvrdil, že verze funguje výborně. Zachovává geometrii, dispozici, okna, dveře, vybavení a kameru; přidává přirozené, přibližně o 30 % mírnější slunce, jemnější interiérové stíny a čisté pozadí okolo půdorysu. Tuto verzi **neupravovat**; pro další změny založit nové číslo verze.

## Dostupné šablony

- [FLOORPLAN_ULTRA_REALISTIC_v1.0_LOCKED.md](prompts/FLOORPLAN_ULTRA_REALISTIC_v1.0_LOCKED.md) – původní odzkoušený prompt, geometrie a kamera uzamčené, přirozené denní osvětlení. **Neměnit.**
- [FLOORPLAN_ULTRA_REALISTIC_v1.1_SUNLIGHT.md](prompts/FLOORPLAN_ULTRA_REALISTIC_v1.1_SUNLIGHT.md) – samostatně použitelná kompletní verze; oproti v1.0 změněna **pouze kapitola 4**, která zdůrazňuje přímé slunce a realistické stíny oken.
- [FLOORPLAN_ULTRA_REALISTIC_v1.2_BALANCED_SUNLIGHT.md](prompts/FLOORPLAN_ULTRA_REALISTIC_v1.2_BALANCED_SUNLIGHT.md) – mírnější přímé slunce (~−30 % proti v1.1), kratší vnitřní stíny a čisté okolí půdorysu bez dlouhých vržených stínů; ostatní kapitoly beze změny. **Ověřená výchozí šablona – LOCKED.**
- [FLOORPLAN_ULTRA_REALISTIC_v1.3_GEOMETRY_GUARD.md](prompts/FLOORPLAN_ULTRA_REALISTIC_v1.3_GEOMETRY_GUARD.md) – **TESTOVACÍ CANDIDATE (zatím ne LOCKED)**. Vychází z v1.2, světelná kapitola 4 je přesně zachovaná. Zpřísňuje ochranu oken, dveří, rámů, hran, celé siluety a neměnného měřítka/umístění vůči okrajům obrázku. Ověřit na půdorysu, na kterém došlo k deformacím.

## Použití

1. Nahraj původní 3D půdorys (např. z Coohomu).
2. Zkopíruj **celý obsah** požadovaného souboru s promptem.
3. Požádej o úpravu již existujícího renderu, nikoli o tvorbu nového půdorysu.
4. Zkontroluj stěny, dveře, okna, nábytek a kameru proti originálu.

**Pozor:** Prompt sám o sobě negarantuje pixelovou ani geometrickou identitu. Pro přesné zakázky porovnávej výstup se vstupem nebo použij maskované úpravy.

## Verzování

v1.0 zůstává původní zamčená reference, v1.1 sluneční varianta a **v1.2 je aktuální uživatelsky ověřená, doporučená a zamčená pracovní verze**. **v1.3 GEOMETRY GUARD** je zatím testovací kandidát, nikoliv náhrada v1.2; povýšit až po ověření na stejném originálním renderu, na kterém v1.2 deformovala dveře/okna. Žádnou z existujících verzí nepřepisuj.
