Dluhy – oprava exportu a aktualizace cache

Nahraj do kořene GitHub repozitáře a přepiš oba soubory: index.html a sw.js.
Potom Commit changes do větve main.

Změny: export spustí stažení přímo po kliknutí a současně zobrazí viditelný odkaz; Service Worker má novou cache v4 a HTML načítá nejprve ze serveru.

Nemaž data aplikace ani localStorage. Zálohy JSON nikdy nenahrávej do GitHubu.
