# CLAUDE.md - Project Instructions

## Project Identity

**Project Name:** Ottoman Empire Academic Research Database
**Type:** Standalone Academic Research Project
**Purpose:** Comprehensive historical research on the Ottoman Empire (~1299 - 1922 CE, with Turkic context back to ~1000 CE)

---

## Critical Instruction

**This is a STANDALONE academic research project.**

- This database is the **source of truth** for historical information about the Ottoman Empire
- Fiction projects are **consumers** of this research
- This project should **NOT reference specific fiction works, characters, or storylines**
- Maintain academic objectivity in all entries
- Include "For Fiction Writing" sections with **generic** guidance for any writer

---

## Project Scope

### Geographic Coverage
- **Anatolian Heartland:** Asia Minor / modern Turkey, the empire's demographic and administrative core
- **Balkan Territories:** Greece, Bulgaria, Serbia, Bosnia, Albania, Romania, Hungary (partial)
- **Arab Provinces:** Syria, Palestine, Egypt, Hejaz, Yemen, Iraq
- **North Africa:** Libya, Tunisia, Algeria (as Ottoman regencies)
- **Caucasus & Black Sea:** Georgia, Armenia, Crimea (vassal khanate)
- **Mediterranean Islands:** Crete, Cyprus, Rhodes, Aegean islands
- **Central European Frontier:** Hungary, parts of Austria, Transylvania (vassal)
- **Arabian Peninsula:** Hejaz (Mecca and Medina), parts of Yemen and the Gulf coast
- **Mesopotamia:** Baghdad, Basra, Mosul vilayets
- **Interaction Zones:** Persia/Safavids, Russia, Habsburg Austria, Venice, Poland-Lithuania, Morocco, Mughal India (diplomatic)

### Temporal Coverage
- **Turkic Background:** ~1000-1299 CE (Seljuk Sultanate of Rum, ghazi frontier culture, Mongol aftermath)
- **Founding / Ghazi Period:** ~1299-1402 (Osman I through Bayezid I; rapid Balkan expansion)
- **Interregnum and Recovery:** 1402-1453 (civil war after Ankara, Murad II's consolidation)
- **Classical Age:** 1453-1566 (Mehmed II through Süleyman I; peak territorial expansion, institutional perfection)
- **Transformation Era:** 1566-1700 (Sultanate of Women, Köprülü reforms, second siege of Vienna)
- **Eighteenth-Century Crisis:** 1700-1808 (Tulip Period, Russo-Turkish Wars, Selim III's reforms, Janissary resistance)
- **Reform and Dissolution:** 1808-1922 (Mahmud II, Tanzimat, Constitution, Young Turks, WWI, abolition of sultanate)
- **Note:** Post-1923 Republic of Turkey covered only as endpoint context

### Thematic Coverage
- **Political History:** Sultans, succession, imperial administration, palace politics, grand viziers
- **Military History:** Battles, sieges, campaigns, Janissary corps, sipahi cavalry, navy, fortification
- **Prosopography:** Sultans, queen mothers (valide sultan), haseki, grand viziers, admirals, architects, scholars, ulema
- **Economic History:** Trade routes, timar system, taxation (cizye, harac), guilds, vakifs (endowments), capitulations
- **Social History:** Millet system, devshirme, slavery, harem, daily life, urban and rural society
- **Cultural History:** Architecture (Sinan), calligraphy, miniature painting, music, literature (divan poetry), coffee culture
- **Religious History:** Sunni Islam, Sufi orders, the caliphate claim, relations with Christians and Jews, Shiite heterodoxy
- **Geography:** Cities, provinces (eyalets/vilayets), strategic fortresses, trade routes, waterways

---

## Content Standards

### Academic Quality
- All entries should meet academic research standards
- Cite primary and secondary sources
- Include confidence assessments for claims
- Note scholarly debates and uncertainties
- Distinguish between historical fact, court chronicle tradition, and legend
- Acknowledge Ottoman chronicle bias and European observer bias

### The "Decline Thesis" Debate
Modern Ottoman historiography has fundamentally revised the old narrative of steady decline after Süleyman I. Key points to maintain:
- **Reject simple "decline" language.** The empire transformed, adapted, and innovated in different ways across different centuries
- **Use "transformation" or "adaptation"** when discussing the post-classical period
- **Acknowledge periodization debates.** The "Golden Age" / "decline" framework reflects 19th-century European and Ottoman reformist biases
- **Note regional variation.** Economic and cultural vitality persisted or emerged in different provinces at different times
- **Cite the revisionist scholarship** (Kafadar, Faroqhi, Tezcan, Quataert) that dismantled the decline paradigm
- When decline language appears in primary sources (Ottoman reform treatises, European diplomatic reports), note it as **period perspective, not analytical framework**

### "For Fiction Writing" Sections
These sections ARE appropriate as they serve any fiction writer:
- Sensory details (sight, sound, smell, taste, texture)
- Character notes (personality, voice, demeanor, dress)
- Scene-setting information (architecture, weather, daily rhythms)
- Dialogue opportunities (Ottoman Turkish phrases, forms of address, court protocol)
- Period-appropriate cultural details
- These should be **generic** guidance, not tied to specific fictional works

### Cross-Referencing
- Use Obsidian wiki-links: `[[filename]]`
- Maintain consistent linking between entries
- Index files should provide navigation
- Note connections to Byzantium, Crusades, Islamic Caliphates, European History, Russian History, and Persian Empire projects

### Source Types and Reliability
Ottoman history draws on distinctive source categories:

- **Ottoman Court Chronicles (Vakanüvis tradition):** Official court historians appointed from the late 17th century onward; earlier chronicles by independent authors (Ashikpashazade, Neşri, Tursun Beg). Note: court chronicles are propaganda-adjacent; they celebrate sultanic power
- **Imperial Decrees (Fermans/Berats):** Administrative orders preserved in the Başbakanlık Osmanlı Arşivi (Ottoman Prime Ministry Archives, Istanbul) — one of the world's largest archives
- **Sharia Court Records (Sicils/Şeriye Sicilleri):** Town-level legal records documenting property, marriage, commerce, crime — invaluable for social history
- **European Diplomatic Reports:** Venetian baili reports (relazioni), Habsburg ambassadorial dispatches, French consular correspondence — detailed but biased toward European interests
- **Traveler Accounts:** Evliya Çelebi (Ottoman, 17th c.), Ogier de Busbecq (Habsburg, 16th c.), Lady Mary Wortley Montagu (British, 18th c.) — vivid but subjective
- **Miniature Paintings and Visual Sources:** Surname-i Hümayun (festival books), Topkapı Palace collections — rare visual documentation of court life
- **Greek, Armenian, and Arabic Sources:** Non-Muslim Ottoman subjects produced chronicles and correspondence offering alternative perspectives
- **Archaeological and Architectural Evidence:** Standing monuments (mosques, bridges, fortresses), inscriptions, material culture

---

## File Organization

```
/Ottoman_Empire
├── CLAUDE.md (this file)
├── README.md
├── SESSION-STATE.md
├── 00-Reference/
│   └── Bibliography.md
├── 01-Timelines/
│   ├── TL-00-Master-Timeline.md
│   ├── TL-01-Founding-Period.md
│   ├── TL-02-Classical-Age.md
│   ├── TL-03-Transformation.md
│   ├── TL-04-Reform-Dissolution.md
│   └── TL-05-Parallel-Chronology.md
├── 02-Prosopography/
│   ├── Key-Figures-Index.md
│   ├── Sultans/
│   ├── Royal-Women/
│   ├── Grand-Viziers/
│   ├── Military-Commanders/
│   ├── Architects-Artists/
│   ├── Scholars-Writers/
│   └── Adversaries/
├── 03-Battles-Campaigns/
│   ├── Major-Conflicts-Index.md
│   ├── Founding-Wars/
│   ├── Conquests/
│   ├── European-Theater/
│   ├── Naval-Campaigns/
│   ├── Eastern-Campaigns/
│   └── Decline-Era-Wars/
├── 04-Geography/
│   ├── Geography-Index.md
│   ├── Cities/
│   ├── Provinces/
│   ├── Fortresses/
│   └── Trade-Routes/
├── 05-Religion-Mythology/
│   ├── Religion-Index.md
│   ├── Islam-Ottoman/
│   ├── Sufi-Orders/
│   ├── Millet-System/
│   └── Caliphate/
├── 06-Society-Economy/
│   ├── Society-Index.md
│   ├── Devshirme/
│   ├── Harem/
│   ├── Timar-System/
│   ├── Guilds-Trade/
│   └── Daily-Life/
├── 07-Culture-Arts/
│   ├── Culture-Index.md
│   ├── Architecture/
│   ├── Literature/
│   ├── Visual-Arts/
│   └── Music/
├── 08-Primary-Sources/
│   ├── Sources-Index.md
│   ├── Ottoman-Chronicles/
│   ├── European-Accounts/
│   ├── Imperial-Documents/
│   └── Travel-Narratives/
└── Fiction-Ready/
    ├── Story-Potential.md
    ├── Sensory-Guide.md
    └── Character-Templates.md
```

---

## Naming Conventions

### File Prefixes
- **Historical Figures:** `HF-Name.md` (e.g., HF-Mehmed-II.md, HF-Hurrem-Sultan.md)
- **Battles/Campaigns:** `BC-Location-Year.md` (e.g., BC-Constantinople-1453.md, BC-Lepanto-1571.md)
- **Geography:** `GE-Location.md` (e.g., GE-Istanbul.md, GE-Edirne.md)
- **Dynasty/Political:** `DY-Topic.md` (e.g., DY-Succession-Law.md, DY-Sultanate-of-Women.md)
- **Timelines:** `TL-##-Name.md` (e.g., TL-00-Master-Timeline.md)
- **Religion/Culture:** `RE-Topic.md` (e.g., RE-Sufi-Orders.md, RE-Millet-System.md)

### Year Notation
- Use CE notation consistently (Ottoman period is entirely CE)
- For file names: Use positive numbers
- Example: BC-Mohacs-1526.md, BC-Vienna-1683.md

---

## Turkish/Ottoman Name Conventions

### Default Spellings
Use **modern Turkish spellings** as the default form for Ottoman proper names:
- **Mehmed** (not Muhammad or Mohammed, for sultans)
- **Süleyman** (not Suleiman or Soliman)
- **Hürrem Sultan** (not Roxelana, though note this as her European name)
- **Bayezid** (not Bajazet)
- **Murad** (not Amurath)
- **İbrahim** (note the dotted İ)
- **Köprülü** (not Kuprili)

### Documentation Protocol
For each figure, document:
- **Modern Turkish form** (primary/default)
- **Ottoman Turkish form** where relevant (Arabic-script transliteration)
- **Anglicized/European forms** commonly found in English-language scholarship
- **Arabic forms** where relevant (especially for religious titles)
- Example: Kanuni Sultan Süleyman → Süleyman I → Suleiman the Magnificent → Soliman le Magnifique

### Special Characters
Ottoman Turkish uses characters not in standard English:
- **ç** (ch sound), **ş** (sh sound), **ğ** (soft g, lengthens preceding vowel)
- **ö** and **ü** (front rounded vowels)
- **İ/ı** (dotted/undotted i — distinctive in Turkish)
- Always preserve these in file content; simplify for file names where needed (e.g., Suleyman not Süleyman in filenames)

---

## Confidence Levels

- **[Established]:** Multiple independent sources; scholarly consensus; archaeological/archival confirmation
- **[Probable]:** Single reliable primary source or strong scholarly agreement
- **[Debated]:** Active scholarly disagreement; competing interpretations with evidence on multiple sides
- **[Speculative]:** Scholarly hypothesis with limited evidence; plausible but unconfirmed
- **[Traditional]:** Ottoman court tradition or popular legend without strong documentary support (e.g., Osman's dream, Ertuğrul's biography)

---

## Key Research Priorities

### Phase 1: Foundation & Timeline (SEED)
1. Project structure and standards (CLAUDE.md, README.md, SESSION-STATE.md)
2. Bibliography of core academic sources
3. Key Figures Index (prosopography overview)
4. Major Conflicts Index (battles and campaigns overview)
5. Fiction potential assessment

### Phase 2: Prosopography — Sultans
Priority figures:
- **Founding:** Osman I, Orhan, Murad I, Bayezid I
- **Recovery:** Mehmed I, Murad II
- **Classical:** Mehmed II, Bayezid II, Selim I, Süleyman I
- **Transformation:** Selim II, Murad III, Ahmed I, Murad IV, Mehmed IV
- **Late:** Ahmed III, Mahmud II, Abdülhamid II, Mehmed V

### Phase 3: Prosopography — Key Non-Sultans
- **Royal Women:** Hürrem Sultan, Nurbanu Sultan, Kösem Sultan, Turhan Sultan, Mihrimah Sultan
- **Grand Viziers:** Çandarlı Halil Pasha, Sokollu Mehmed Pasha, Köprülü Mehmed Pasha, İbrahim Pasha (Süleyman's)
- **Military:** Hayreddin Barbarossa, Turgut Reis, Kara Mustafa Pasha
- **Cultural:** Mimar Sinan, Evliya Çelebi, Fuzuli, Baki

### Phase 4: Major Battles and Campaigns
- Fall of Constantinople (1453) — highest priority
- Battle of Mohács (1526)
- Siege of Vienna (1529, 1683)
- Battle of Lepanto (1571)
- Gallipoli campaign (1915)

### Phase 5: Geography and Institutions
- Istanbul (comprehensive profile)
- Topkapı Palace
- Edirne
- Provincial system (eyalet/vilayet)
- Timar system
- Devshirme system

### Phase 6: Society, Religion, Culture
- Harem institution
- Millet system
- Sufi orders (Mevlevi, Bektashi)
- Ottoman architecture
- Court culture and ceremony

### Phase 7-10: Supporting Context, Primary Sources, Fiction Resources, Gap-Filling

---

## Major Events to Document

### Founding Period (1299-1402)
- Osman's establishment of the beylik (~1299)
- Battle of Bapheus (1302) — first major Ottoman victory
- Capture of Bursa (1326) — first capital
- Crossing into Europe (1352/1354)
- Battle of Kosovo (1389) — Murad I killed
- Battle of Nicopolis (1396) — Crusader defeat
- Battle of Ankara (1402) — Bayezid I captured by Timur

### Interregnum and Recovery (1402-1453)
- Ottoman Civil War / Interregnum (1402-1413)
- Murad II's consolidation
- Battle of Varna (1444) — Crusader defeat
- Second Battle of Kosovo (1448)

### Classical Age (1453-1566)
- **Fall of Constantinople (1453)** — Highest priority
- Conquest of Serbia, Greece, Bosnia (1450s-1460s)
- Conquest of Egypt / end of Mamluk Sultanate (1517)
- Battle of Chaldiran (1514) — defeat of Safavids
- Battle of Mohács (1526) — Hungary destroyed
- Siege of Vienna (1529)
- Siege of Malta (1565)
- Süleyman's death at Szigetvár (1566)

### Transformation Era (1566-1700)
- Battle of Lepanto (1571)
- Long Turkish War (1593-1606)
- Celali Revolts (1590s-1610s)
- Regicide of Osman II (1622)
- Murad IV recaptures Baghdad (1638)
- Siege of Candia/Crete (1645-1669)
- Second Siege of Vienna (1683)
- Treaty of Karlowitz (1699)

### Reform and Dissolution (1700-1922)
- Tulip Period (1718-1730)
- Patrona Halil Revolt (1730)
- Russo-Turkish Wars (multiple)
- Greek War of Independence (1821-1829)
- Mahmud II destroys Janissaries (1826)
- Tanzimat reforms (1839-1876)
- Crimean War (1853-1856)
- Young Turk Revolution (1908)
- Balkan Wars (1912-1913)
- World War I (1914-1918)
- Gallipoli / Çanakkale (1915)
- Armenian Genocide (1915-1923) — note as established historical fact
- Armistice of Mudros (1918)
- Abolition of Sultanate (1922)

---

## Ottoman-Specific Research Notes

### Dating Systems
- Ottoman sources use the Hijri (Islamic lunar) calendar; convert to CE consistently
- Rumi calendar (solar Hijri variant) used for fiscal/administrative purposes from 1839
- Always provide CE equivalents in all entries
- Note: Hijri-to-CE conversion is not a simple offset; lunar vs. solar calendars diverge

### Periodization Debates
- The traditional division into "Rise-Peak-Decline" is rejected by modern scholarship
- Use the periodization in this document (Founding, Classical, Transformation, Reform) as a neutral framework
- Note: even "Classical Age" is debated — it privileges military/territorial expansion as the measure of success
- Alternative frameworks: Kafadar's "between two worlds," Tezcan's "second Ottoman empire"

### Bias Awareness
- **Ottoman court chronicles** celebrate sultanic power and may suppress inconvenient facts
- **European diplomatic reports** are detailed but reflect Christendom-vs-Islam framing
- **Nationalist historiographies** (Turkish, Greek, Balkan, Arab) each appropriate or reject Ottoman heritage differently
- **Orientalist tradition** in Western scholarship produced distortions (harem fantasies, "Eastern despotism") now recognized as problematic
- Note bias explicitly in all source assessments

### Archival Wealth
The Ottoman Empire left extraordinarily rich archives:
- **Başbakanlık Osmanlı Arşivi (BOA):** Istanbul, estimated 150+ million documents
- **Topkapı Palace Archives:** Court and harem records
- **Sharia Court Registers (Sicils):** Thousands of volumes across former provinces
- **Tapu Tahrir Defterleri:** Tax survey registers providing demographic snapshots
- This archival richness means Ottoman history can be written with far more granularity than many pre-modern states

---

## Related Projects

| Project | Connection |
|---------|------------|
| Byzantium | Direct predecessor — Ottomans conquered Constantinople (1453); inherited infrastructure, territory, administrative traditions |
| Crusades | Later Crusade context; Ottoman capture of Crusader-era territories; Nicopolis and Varna as "late Crusades" |
| Islamic_Caliphates | Ottomans claimed caliphal authority after 1517 conquest of Egypt; institutional and religious continuity |
| European_History | Centuries of war, diplomacy, and trade; Reformation-era alliances; Eastern Question; WWI |
| Russian_History | Twelve Russo-Turkish wars (1568-1918); Crimean rivalry; Straits question; WWI |
| Persian_Empire | Safavid-Ottoman rivalry; Battle of Chaldiran; Mesopotamian frontier wars |
| Mongol_Empire | Timur's defeat of Bayezid I (1402); post-Mongol Anatolian context |

---

## Update Protocol

When updating this database:
1. Maintain academic objectivity
2. Do not add fiction-specific references
3. Keep "For Fiction Writing" sections generic
4. Update cross-references as needed
5. Note last updated date
6. Document source confidence levels
7. Flag scholarly debates — especially the decline thesis
8. Preserve Turkish special characters in content
9. Avoid Orientalist framing (harem as exotic, "Eastern despotism," etc.)

---

*Last Updated: February 2026*
