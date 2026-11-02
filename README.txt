OPRAVA EXPORTU ZÁLOHY – DLUHY V2

Tato oprava nahrazuje pouze soubory aplikace, nikoli uložená data.

NASAZENÍ NA GITHUB PAGES:
1. Rozbal ZIP.
2. V kořenové složce repozitáře na GitHubu nahraj a přepiš:
   - index.html
   - sw.js
3. Commitni změny do větve main.
4. Po nasazení otevři aplikaci v Opeře a obnov stránku přes Cmd+Shift+R.

CO SE MĚNÍ:
- Export nejprve připraví zálohu a zobrazí viditelný odkaz ke stažení.
- Přidána je záložní možnost zkopírovat JSON do schránky.
- Service worker dostal novou verzi cache, aby zařízení nepoužívalo starý index.html.
- Uložená data v localStorage se nemění.

DŮLEŽITÉ:
- Nikdy nenahrávej svůj JSON se zálohou do GitHubu.
- Tato oprava nemá přístup k datům uloženým v prohlížeči a sama je nikam neposílá.
