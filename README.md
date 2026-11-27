# DataSorter.AI

Windows aplikace pro úklid, třídění a AI hledání duplicit fotek, videí a dokumentů.

- **Popelář** – smaže odpad (smetí z Macu, prázdné složky, dočasné soubory…)
- **Třídění dat** – roztřídí fotky, videa, dokumenty a další podle data a typu
- **AI hledač duplicit** – najde kopie, série a „smog“ (screenshoty, miniatury…)

## Stažení

Nejnovější instalátor je v části [**Releases**](https://github.com/dosekv/DataSorter.AI/releases/latest).
Spusť `DataSorter.AI_Setup_v….exe` – program se nainstaluje do `C:\DataSorter` a na ploše vznikne zástupce.

Windows může u staženého instalátoru ukázat „Neznámý vydavatel“ (instalátor není digitálně podepsaný) – zvol **Další informace → Přesto spustit**.

## Automatické aktualizace

Aplikace si při spuštění (nejvýš jednou denně) přečte soubor [`aktualizace.json`](aktualizace.json).
Když je k dispozici novější verze, nabídne ji, stáhne instalátor, ověří jeho otisk SHA-256 a nainstaluje ho.

Tento repozitář obsahuje jen instalátory a informace o verzích, ne zdrojový kód.
