<!-- Version: v1.3 GEOMETRY GUARD | Derived from v1.2 BALANCED SUNLIGHT | Experimental / requires visual runtime validation. -->
# ULTRA PHOTOREALISTIC 3D FLOOR PLAN ENHANCEMENT
## ABSOLUTE GEOMETRY & LAYOUT PRESERVATION

Proveď mimořádně kvalitní fotorealistické vylepšení nahraného 3D půdorysu interiéru.

**HLAVNÍ ÚKOL:**

Proveď **konzervativní fotorealistický polish již existujícího renderu** s materiálovou a světelnou kvalitou připomínající profesionální Corona Renderer / V-Ray. Vstupní render není návrh k rekonstrukci: jeho geometrie, architektonické hrany, objekty i kamera jsou závazné.

Výsledek musí působit jako kvalitněji nasvícená a materiálově propracovaná fotografie **téhož nezměněného fyzického 3D modelu**, nikoliv jako nově vygenerovaný interiér.

**NEGENERUJ NOVÝ INTERIÉR. NEPROVÁDĚJ REDESIGN. NEMĚŇ DISPOZICI, GEOMETRII ANI VYBAVENÍ.**

Původní obrázek je závaznou geometrickou, dispoziční a kompoziční referencí.

Povolené jsou pouze změny materiálového realismu, osvětlení, textur, odrazů a drobných povrchových detailů.

---

## 1. ABSOLUTE GEOMETRY LOCK – NEJVYŠŠÍ PRIORITA

Veškerá stavební geometrie půdorysu musí zůstat naprosto zachována.

**PŘÍSNĚ ZAKÁZÁNO:**

- Měnit tvar půdorysu.
- Měnit obvodové stěny.
- Měnit vnitřní příčky.
- Posouvat, prodlužovat nebo zkracovat stěny.
- Měnit tloušťku stěn.
- Měnit výšku stěn nebo způsob jejich zobrazení.
- Měnit velikost, tvar nebo proporce místností.
- Spojovat nebo rozdělovat místnosti.
- Přidávat nebo odstraňovat příčky.
- Měnit polohu dveřních otvorů.
- Měnit šířku, výšku nebo orientaci dveří.
- Měnit směr otevírání dveří.
- Měnit polohu, velikost, počet ani typ oken.
- Měnit parapety a ostění.
- Měnit schodiště, podesty nebo výškové úrovně.
- Měnit původní polohu žádného stavebního prvku.

**KAŽDÁ STĚNA, KAŽDÝ ROH, KAŽDÉ OKNO A KAŽDÉ DVEŘE MUSÍ ZŮSTAT NA PŘESNĚ STEJNÝCH OBRAZOVÝCH SOUŘADNICÍCH JAKO V ORIGINÁLU.**

Pokud nelze nějakou část vylepšit bez změny stavební geometrie, ponech ji beze změny.

### 1.1 CRITICAL DOOR & WINDOW GEOMETRY GUARD

**NEJVYŠŠÍ PRIORITA: NEMĚNNÉ TVARY, HRANY, OTVORY A PRŮHLEDY.**

Při vylepšování renderu považuj všechna okna, dveře, zárubně, ostění, parapety, hrany stěn a jejich okolí za **chráněnou geometrii z původního obrázku**. Nejde o návrhové prvky a nesmějí se znovu konstruovat podle odhadu modelu.

**OKNA – ABSOLUTE WINDOW LOCK**

- Zachovej počet, polohu, výšku, šířku a proporce každého okna.
- Zachovej počet křídel, tabulí a dělicích příček i jejich přesné vzájemné rozložení.
- Zachovej přesné obrysy rámů, ostění a parapetů, jejich tloušťku a natočení.
- Zachovej rovné linie a původní perspektivní sbíhání; původní šikmé hrany způsobené kamerou **nenarovnávej**.
- Neměň průhled ani zakrytí oken okolními stěnami nebo vybavením.
- Nepřidávej ani neodstraňuj okna, skleněné výplně a příčky.
- Nedeformuj, nezakřivuj, nezaobluj a neprolamuj rámy.

**DVEŘE – ABSOLUTE DOOR LOCK**

- Zachovej počet a polohu dveří, obrys křídel, materiálový charakter, zárubně a prahy.
- Zachovej přesný úhel otevření a směr otevírání jednotlivých křídel.
- Zachovej polohy klik, závěsů a zasklení, pokud jsou viditelné.
- Nevytvářej nové dveře, další křídla, falešné otvory či jiné zárubně.
- Nesmíš ohýbat dveře, měnit jejich úhel ani je zdánlivě zavírat nebo otevírat.

**STĚNY A OTVORY – ABSOLUTE EDGE LOCK**

- Zachovej vnější i vnitřní siluetu půdorysu, tloušťky stěn, zalomení, rohy, styky a přesné hranice pokojů.
- Zachovej návaznost každého otvoru na jeho stěnu, včetně původních hran kolem dveří a oken.
- Žádné nové zaoblené rohy, zvlněné rovné hrany ani přegenerované nepravé otvory.
- Neměň stěny ani rozložení místností kvůli světlu nebo estetice.

**GEOMETRY FIRST – MATERIALS SECOND**

Na chráněných konstrukcích smíš zjemnit odlesky, osvětlení a povrchovou strukturu **pouze uvnitř existujících geometrických hran**. Nezvyšuj jejich „3D realismus“ tím, že znovu vygeneruješ rám, dveřní křídlo či stěnu.

Pokud není možné objekt upravit bez rizika deformace, ponech jej **vizuálně co nejvěrnější vstupnímu renderu**.

**DO NOT REGENERATE OR REDRAW WINDOWS, DOORS, FRAMES, OPENINGS, WALL EDGES OR THEIR SILHOUETTES. KEEP SOURCE EDGES AND PERSPECTIVE IN PLACE.**

### 1.2 IMAGE-COORDINATE & SILHOUETTE LOCK

- Zachovej shodný počet pixelů plátna, poměr stran a rozvržení obrazu, pokud to nástroj umožňuje.
- Hlavní obrys půdorysu musí ležet na **stejných souřadnicích obrazu** jako na originálu.
- Neměň jeho vzdálenosti od levého, pravého, horního a spodního okraje obrázku.
- Neotáčej, neposouvej, nezvětšuj ani nezmenšuj půdorys v obrazu.
- Zachovej překryvy a pořadí objektů v prostoru; neodkrývej ani neschovávej objekty v důsledku změny kamery.
- Okolní čisté pozadí ponech ve stejné ploše a podobné tonalitě; neupravuj framing kvůli stínům.
- **Žádný automatic reframe, zoom, crop, recenter, geometric warp nebo perspective correction.**

**THE SAME FLOOR PLAN MUST OCCUPY THE SAME PIXEL-COORDINATE FOOTPRINT AS THE ORIGINAL.**

## 2. FURNITURE & OBJECT PRESERVATION

Veškerý nábytek a vybavení musí zůstat zachovány.

Nesmíš:

- Přidávat nový nábytek.
- Odstraňovat původní nábytek.
- Přesouvat nábytek.
- Otáčet nábytek.
- Měnit rozměry a proporce nábytku.
- Nahrazovat jednotlivé kusy jinými.
- Měnit uspořádání kuchyně.
- Měnit polohu kuchyňské linky, dřezu nebo spotřebičů.
- Měnit polohu postelí, pohovek, stolů a židlí.
- Měnit polohu umyvadel, van, sprchových koutů a WC.
- Měnit radiátory, vestavěné skříně ani další pevné vybavení.
- Přidávat dekorace, květiny, obrazy nebo jiné předměty, které v originálu nejsou.

Původní nábytek může získat realistické materiály, textury a osvětlení, ale jeho tvar, poloha, orientace a základní vzhled musí zůstat nezměněné.

Pokud je v originálu například šedá pohovka, musí zůstat stejná šedá pohovka na stejném místě.

Pokud je v originálu konkrétní kuchyňská sestava, musí zůstat identická.

## 3. ULTRA PHOTOREALISTIC MATERIAL ENHANCEMENT

Zvyš realismus všech existujících materiálů bez změny jejich základního vzhledu.

**Podlahy:**
- Fotorealistické dřevo s jemnou kresbou letokruhů.
- Přirozené spáry mezi lamelami.
- Realistická keramická a kamenná dlažba.
- Jemné mikrotextury a drobné nerovnosti.
- Fyzikálně správné odrazy a drsnost povrchů.
- Zachovej původní směr pokládky a rozložení podlahových materiálů.

**Stěny:**
- Jemná realistická struktura omítky.
- Přirozené světelné přechody.
- Realistické hrany a rohy.
- Zachování původních barev a materiálového členění.

**Nábytek:**
- Realistické textilie s viditelnou strukturou vláken.
- Přirozená kresba dřeva.
- Realistické kovové a skleněné povrchy.
- Jemné kontaktní stíny.
- Přesné odrazy a přirozené materiálové vlastnosti.

**Koupelny:**
- Realistická keramika.
- Jemné odrazy na sanitárním vybavení.
- Přirozený vzhled sprchového skla.
- Materiálově věrné obklady.

Žádný materiál nesmí působit plastově, přehnaně leskle nebo uměle.

**KONZERVATIVNÍ MATERIAL-ONLY GUARD:** Nikdy neregeneruj nábytek, okna, dveře či stěny jen kvůli ostřejší textuře. Materiálový polish probíhá uvnitř původních siluet. Pokud zvýšení detailu hrozí změnou tvaru, vynech ho.

## 4. CONTROLLED SUNLIT ARCHITECTURAL LIGHTING – BALANCED DAYLIGHT

### 4.0 LIGHTING OBJECTIVE – SUNLIGHT APPROXIMATELY 30% SOFTER

Zachovej krásnou prosluněnou atmosféru profesionálního Corona Renderer / V-Ray renderu, avšak **oproti variantě v1.1 zjemni přímé sluneční osvětlení přibližně o 30 %**. Neztmavuj celý obrázek o 30 %. Sniž intenzitu ostrých slunečních skvrn a kontrast přímého světla, zatímco měkké nepřímé osvětlení udrží dobře čitelné místnosti.

**PRIMARY TARGET: WARM, NATURAL, CONTROLLED DAYLIGHT. SUNLIGHT −30% RELATIVE TO v1.1. SHORT SOFT INTERIOR SHADOWS. CLEAN SHADOW-FREE BACKGROUND OUTSIDE THE FLOOR PLAN.**

### 4.1 DIRECT SUNLIGHT – CONTROLLED RATHER THAN MAXIMUM

- Nech přirozené sluneční světlo vstupovat **pouze skutečnými existujícími okny**, v jejich původních polohách a velikostech.
- Zachovej příjemné sluneční skvrny na částech podlah a nábytku, ale zeslab jejich jas, rozsah a kontrast přibližně o 30 % oproti v1.1.
- Preferuj středně vysoké až vyšší slunce: světlo má příjemně osvětlit pokoje, nikoliv vytvářet extrémně dlouhé paprsky a stíny.
- Osvětlení musí sdílet konzistentní směr napříč celou dispozicí.
- Nepřidávej nové průsvitné otvory, neviditelná okna ani falešné zdroje přímého slunečního světla.
- Zachovej čisté světlé plochy, správnou expozici a kresbu materiálů; vyvaruj se přepalů.

### 4.2 INTERIOR WINDOW SHADOWS – SHORTER AND SOFTER

- Zachovej uvnitř realistické rozpoznatelné stíny rámů existujících oken a ostění.
- Stíny musí odpovídat skutečné geometrii oken, směru slunce a perspektivě původního pohledu.
- Oproti v1.1 mají být **kratší, jemnější, méně tmavé a méně dominantní**.
- Změkči přechody světla a stínu, zachovej přirozené kontaktní stíny pod nábytkem.
- Nenaplň každou místnost dlouhými pruhy slunce; rovnoměrná čitelnost dispozice je důležitější než dramatické světelné efekty.
- Nevytvářej stíny neexistujících oken ani nové pruhy světla procházející skrz stěny.

### 4.3 CRITICAL – NO LARGE SHADOWS OUTSIDE THE FLOOR PLAN

**TOTO JE PRIORITNÍ OPRAVA OPROTI v1.1.**

- Veškeré okolí mimo vlastní 3D půdorys má zůstat čisté, neutrální a světle šedé až bílé jako profesionální studiové pozadí.
- **Neprojektuj mimo siluetu půdorysu dlouhé stíny okenních rámů, ostré diagonální pruhy, výrazné sluneční skvrny ani kontrastní barevné stíny.**
- Pro oddělení modelu od pozadí ponech nanejvýš **velmi krátký, subtilní, měkký kontaktní stín těsně kolem spodní hrany modelu**; orientačně maximálně 2–3 % kratšího rozměru modelu v obrazu.
- Nepřidávej velké plochy šedé podlahy, dekorativní podstavce ani grafické pozadí.
- Nemeň obrys, perspektivu, polohu ani měřítko celého půdorysu kvůli úpravě stínů.
- Pozadí udržuj vizuálně klidné a snadno oddělitelné pro následné ořezy, grafiku, sazbu, maskování a další úpravy.
- Nevyrovnávej stíny mimo půdorys vymyšlenými změnami světla uvnitř budovy. Vnější pozadí zpracuj jako čistou neutrální prezentační plochu.

**NO CAST WINDOW SHADOWS OUTSIDE THE FLOOR PLAN. ONLY A TIGHT, SUBTLE CONTACT SHADOW UNDER THE MODEL.**

### 4.4 GLOBAL ILLUMINATION & EXPOSURE

- Zachovej kvalitní physically based global illumination a realistické odrazy světla od stěn, podlah a nábytku.
- Stíněné části interiéru ponech světlé a detailní pomocí přirozeného nepřímého světla.
- Omez jas slunečních skvrn, nikoliv plošně expozici celé scény.
- Zachovej fyzikálně věrohodné odrazy a mikrotextury materiálů.
- Žádný přepálený bílý nábytek, extrémně černé rohy, agresivní bloom ani umělý oranžový filtr.

### 4.5 ABSOLUTE STRUCTURE & CAMERA LOCK

Sluneční osvětlení nesmí změnit:
- Obvodové stěny, příčky a tvar jednotlivých místností.
- Polohu, rozměry, počet ani členění oken.
- Dveře, jejich směry otvírání ani stavební otvory.
- Nábytek, kuchyně, koupelny a další vybavení.
- Výšku a tloušťku stěn ani způsob jejich původního zobrazení.
- Kameru, kompozici, měřítko a výřez půdorysu.

Pokud nelze světelný efekt vytvořit bez změny některého z těchto prvků, daný efekt vynech.

### 4.6 FINAL LIGHTING CHECK

1. Je přímé sluneční světlo přibližně o 30 % mírnější než v1.1?
2. Zůstaly interiéry světlé díky přirozenému nepřímému světlu?
3. Jsou vnitřní stíny oken realistické, ale kratší a jemnější?
4. Je pozadí mimo půdorys čisté, bez dlouhých vržených stínů?
5. Zůstal pod půdorysem pouze subtilní kontaktní stín?
6. Jsou geometrie, nábytek a kamera úplně nezměněné?

**FINAL INSTRUCTION:**

Render the identical existing floor plan with beautiful but controlled natural daylight. Reduce harsh direct sunlight by approximately 30% relative to the previous sunlight-heavy version. Keep appealing, shorter, softer window shadows inside rooms, balanced global illumination, and a clean neutral background outside the entire floor-plan silhouette with no long cast shadows.

**NO GEOMETRY CHANGES. NO FURNITURE CHANGES. NO CAMERA CHANGES. NO EXTERIOR WINDOW-SHADOW PATTERNS.**

## 5. CAMERA & COMPOSITION LOCK

**PŮVODNÍ KAMERA MUSÍ ZŮSTAT NAPROSTO STEJNÁ.**

Zachovej:

- Přesný původní úhel pohledu.
- Původní ortografickou nebo perspektivní projekci.
- Původní natočení kamery.
- Původní přiblížení.
- Původní ořez.
- Původní kompozici.
- Původní měřítko půdorysu.
- Původní proporce jednotlivých místností.
- Původní poměr stran obrázku.

Pokud je vstupem 3D půdorys z ptačí perspektivy, zachovej přesně tento pohled.

Nepřecházej na interiérovou kameru.

Nevytvářej izometrický pohled, pokud v originálu není.

Nevytvářej novou architektonickou kompozici.

**DO NOT CHANGE CAMERA ANGLE, PROJECTION, FRAMING OR FLOOR PLAN ORIENTATION.**

**PIXEL-LEVEL COMPOSITION RULE:** Zachovej stejnou obrazovou pozici, sklon, velikost a maximální rozsah půdorysu. Nesnaž se scénu „lépe vycentrovat“ ani „ukázat zblízka“. Při porovnání překrytím musí obrys půdorysu, okna, dveře a stavební hrany lícovat s původním renderem. Nesmíš měnit poměr okolního volného pozadí.

## 6. STRICT IMAGE STRUCTURE PRESERVATION

Představ si původní obrázek jako neměnnou geometrickou šablonu.

Každý viditelný stavební prvek představuje uzamčenou oblast.

AI smí upravovat pouze vizuální kvalitu stávajících povrchů.

Povoleno:
- Zlepšení textur.
- Zlepšení materiálového realismu.
- Realistické odrazy.
- Jemnější světelné přechody.
- Přirozené kontaktní stíny.
- Zlepšení lokálního kontrastu.
- Fotorealistické povrchové detaily.

Zakázáno:
- Jakákoliv geometrická přestavba.
- Jakékoliv posunutí objektu.
- Přidání nebo odstranění vybavení.
- Změna dispozice.
- Změna polohy oken či dveří.
- Změna kamery.
- Rozšíření nebo zúžení místností.
- Překreslení půdorysu podle vlastní interpretace.
- Jakákoliv změna stavebních otvorů.

Pokud má model pochybnosti o některém detailu, musí zachovat původní podobu.

**STRICT EDIT SCOPE:** Upravuj jen vzhled již existujících povrchů a světelné poměry. Chráněné konstrukce (dveře, okna, rámy, otvory a hrany stěn) musí zůstat z původního obrazu. Neprováděj content-aware rebuild celé scény. Pokud nástroj umožňuje masky, **vyluč z úprav hrany, okna, dveře a stavební otvory** a uprav jen bezpečné plošné oblasti materiálů. Maskování a kompozice původních pixelů mají přednost před generativním překreslením.

**SOURCE IMAGE IS THE ABSOLUTE GEOMETRIC GROUND TRUTH.**

## 7. FINÁLNÍ VIZUÁLNÍ KVALITA

Výsledný půdorys musí působit jako profesionální fotorealistický architektonický render.

Požadovaná úroveň:
- Corona Renderer / V-Ray quality.
- Physically based rendering (PBR).
- Realistic global illumination.
- High-quality texture detail.
- Natural ambient occlusion.
- Realistic soft shadows.
- Physically plausible reflections.
- Professional real-estate visualization.
- Clean, sharp, natural appearance.
- No artificial AI-generated details.

Preferuj přirozený fotorealismus před přehnaně dramatickým nebo stylizovaným vzhledem.

## 8. FINAL VALIDATION – ZERO GEOMETRY DEVIATION

Před dokončením ověř:

1. Má půdorys přesně stejný obvodový tvar?
2. Jsou všechny místnosti na stejných místech?
3. Zůstaly všechny stěny a příčky nezměněné?
4. Jsou všechna okna na stejných pozicích?
5. Jsou všechny dveře na stejných pozicích a otevírají se stejně?
6. Zůstal veškerý nábytek na původních místech?
7. Zůstaly zachované původní barvy a typy materiálů?
8. Zůstala původní kamera, perspektiva a kompozice?
9. Změnil se pouze fotorealismus materiálů a osvětlení?
10. Mají okna přesně stejný počet a členění tabulí, stejné rámy, proporce a úběžníky?
11. Mají dveře stejná křídla, kliky, směr a přesný úhel otevření?
12. Lícují vnější obrys, stavební otvory a všechny hrany s originálem při překrytí?
13. Zůstaly shodné velikost a pozice celého půdorysu vůči okrajům plátna?
14. Zůstává měkčí slunce a čisté pozadí převzaté z v1.2, bez dlouhých vnějších stínů?

**Pokud jakákoliv úprava vyžaduje změnu dispozice nebo geometrie, nesmí být provedena.**

## ABSOLUTE FINAL INSTRUCTION

Conservatively polish the uploaded existing 3D floor-plan render. Treat the input as a fixed photographic and architectural underlay, not a scene to reconstruct. Never redraw protected structural shapes.

Enhance the uploaded 3D floor plan into an ultra-photorealistic, professional architectural render.

**Preserve the exact floor plan geometry, room boundaries, wall thicknesses, doors, windows, furniture, sanitary fixtures, camera projection and all object positions.**

Do not redesign. Do not reconstruct. Do not invent.

Improve ONLY the realism of materials, lighting, textures, reflections and shadows.

**ZERO LAYOUT CHANGES. ZERO GEOMETRY CHANGES. ZERO OBJECT REPLACEMENTS. ZERO CAMERA CHANGES.**

The output must represent the exact same property, seen from the exact same camera, with the exact same silhouette and image-coordinate placement, with improved realism only where safe.

**IF PHOTOREALISM CONFLICTS WITH ARCHITECTURAL ACCURACY, PRESERVE ORIGINAL GEOMETRY AND REDUCE THE ENHANCEMENT.**

**ABSOLUTE PRIORITY: GEOMETRY > CAMERA & IMAGE PLACEMENT > OBJECT IDENTITY > MATERIALS > LIGHTING DRAMA.**
