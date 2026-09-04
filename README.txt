HOVNOLOG v6 FAMILY

Bezpečná rodinná verze se Supabase Auth:
- přihlášení Jiřího a Aničky vlastním účtem
- sdílený přístup ke Kristiánovi
- přepínač pro více dětí
- data v records_v6 chráněná RLS podle členství v rodině
- původní records ani záloha records_backup_pre_v6 se nemění

První přihlášení:
1. Otevřete https://hovnolog.vercel.app
2. Zvolte Zapomenuté heslo a zadejte svůj e-mail.
3. V e-mailu otevřete odkaz a nastavte nové heslo.

Nasazení na Vercel: nahrajte celý obsah této složky jako jeden projekt.

Původní popis v5.2:

Obsah:
- rychlé přidání záznamu s aktuálním datem a časem
- běžné hodnocení 1–10; speciální 11/10 pouze když hovínko skončí mimo plenu
- posledních 7 dní na dashboardu
- kompletní historie, editace a mazání
- statistiky
- instalovatelná PWA + offline cache

Data jsou v této verzi uložena lokálně v prohlížeči (localStorage).
Pro společnou synchronizaci dvou telefonů je potřeba připojit online databázi (např. Supabase/Firebase).

Spuštění:
Nasadit obsah složky na HTTPS hosting (GitHub Pages, Netlify, Vercel apod.).
Na iPhonu otevřít v Safari -> Sdílet -> Přidat na plochu.


v5.1: HOVNOLOG Event po uložení — velká 2.9s animovaná hláška, 4 režimy dle skóre, náhodné texty, speciální havárie 11/10.

v5.2: HOVNOLOG Event prodloužen na 4.0 s; 46+ náhodných kombinací hlášek ve 4 kategoriích; 11/10 má více havarijních scénářů.
