DLUHY V2 – NASAZENI DO OSTRÉ VERZE

Obsah balíčku:
- index.html
- manifest.webmanifest
- sw.js
- icon.svg

PŘED NASAZENÍM:
1. Otevři současnou aplikaci na iPhonu i na Macu (pokud ji používáš na obou zařízeních).
2. V Nastavení aplikace udělej Export zálohy a ulož soubor mimo GitHub.
3. GitHub repo Kony462/dluhy-pwa si nejdřív stáhni jako ZIP nebo vytvoř kopii původních souborů.

NASAZENÍ:
1. Otevři https://github.com/Kony462/dluhy-pwa
2. Nahraď v kořeni repozitáře soubory index.html, manifest.webmanifest, sw.js a icon.svg těmito soubory.
3. Commit změn.
4. Počkej na dokončení GitHub Pages a otevři https://kony462.github.io/dluhy-pwa/.
5. Pokud se zobrazí stará verze, zavři aplikaci úplně a znovu ji otevři; nový service worker používá novou cache.

DATA A BEZPEČNOST:
- Aplikace ukládá data lokálně v prohlížeči / zařízení. Nasazení na stejnou GitHub Pages adresu samo o sobě nemaže localStorage.
- Mac a iPhone mají oddělená lokální data; mezi zařízeními se nesynchronizují.
- Záloha musí zůstat soukromá. Nikdy ji nenahrávej do veřejného GitHub repozitáře.
- PIN není šifrování dat.
- Před aktualizací měj export aktuálních dat. Pokud se něco pokazí, lze vrátit původní soubory a obnovit zálohu.

POZNÁMKA K OVĚŘENÍ:
JavaScript prošel syntaktickou kontrolou. Před tímto nasazením nebyl dokončen test importu na iPhonu ani kontrola zobrazení na reálném iPhonu. Po nasazení proto nejdřív ověř data, faktury a platby; nic nemaž a neprováděj hromadné opravy, dokud nesedí součty.
