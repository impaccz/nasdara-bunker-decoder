RAVENTREK NASDARA BUNKER DECODER – OFFLINE WEB APLIKACE

DŮLEŽITÉ: Samotný HTML soubor v náhledu aplikace Soubory na iPhonu nespustí spolehlivě JavaScript. Proto tato verze obsahuje i manifest a servisní worker pro instalovatelnou offline webovou aplikaci (PWA).

JAK JI ZPROVOZNIT
1. Obsah tohoto ZIPu je potřeba zveřejnit na webové adrese s HTTPS (např. na vlastním webhostingu). Pouhé rozbalení v aplikaci Soubory nestačí.
2. Na iPhonu otevřít tuto HTTPS adresu jednou v Safari.
3. V Safari klepnout na Sdílet → Přidat na plochu. Pokud je volba dostupná, zapnout otevření jako webovou aplikaci.
4. Potom spouštět dekodér ikonou na ploše; po prvním načtení se jeho soubory ukládají pro offline použití.

OMEZENÍ
- iOS vyžaduje HTTPS (nebo localhost) pro servisní worker a přístup k mikrofonu.
- Nahrávání mikrofonem může vyžadovat povolení i po instalaci.
- Toto není podepsaná nativní IPA aplikace; tu nelze bezpečně nainstalovat pouhým stažením HTML a bez procesu podepisování Apple.
- Offline režim začne fungovat až po prvním načtení online a úspěšném uložení do cache.
