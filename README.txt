# Dluhy – PWA příprava

Tato složka obsahuje připravenou PWA variantu z dodaného `index.html`:
- název na ploše: Dluhy
- výchozí vzhled: tmavý režim
- manifest pro instalaci na plochu
- service worker pro základní offline shell
- ikona aplikace

## Důležité před použitím
1. Tohle je přípravný balíček, zatím není zveřejněný na internetu.
2. PWA musí být hostována přes HTTPS, aby fungovala instalace/offline service worker.
3. PWA bude mít vlastní úložiště prohlížeče. Pro přenos dat použijte export JSON ze staré aplikace a import do nové PWA. Nejprve otestujte na kopii zálohy; neodinstalovávejte původní iOS aplikaci.
4. Uložení dat v `localStorage` je vázané na konkrétní doménu a prohlížeč. Pravidelně exportujte zálohu.
5. Základní service worker ukládá pouze aplikační soubory; nepřenáší ani nezálohuje finanční data.

## Nasazení
Nahrajte obsah této složky do statického HTTPS hostingu. Pak na iPhonu otevřete web v Safari → Sdílet → Přidat na plochu.
