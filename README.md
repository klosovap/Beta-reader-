# Moje beta čtení – prototyp pro GitHub Pages

## Nasazení z telefonu
1. Rozbal ZIP.
2. Nahraj všechny soubory do hlavní složky svého GitHub repozitáře.
3. Otevři **Settings → Pages**.
4. V **Build and deployment** vyber **Deploy from a branch**, větev `main`, složku `/(root)` a ulož.
5. Po zveřejnění otevři odkaz GitHub Pages v telefonu.

## Funkce prototypu
- České rozhraní v meruňkových a růžových barvách.
- Import TXT, RTF, DOCX, ODT, EPUB a textových PDF.
- Zobrazení textu, výběr pasáže, barevné zvýraznění, komentáře a seznam poznámek.
- Export poznámek do JSON.

## Omezení
Je to prototyp, nikoli hotová produkční aplikace. Dokumenty se převádějí na prostý text a nezachovávají původní rozvržení jako Adobe Acrobat. Skenované PDF bez textové vrstvy nemusí fungovat. EPUB/ODT extrakce je základní. Poznámky se vážou podle textové citace, takže opakující se pasáže mohou být nejednoznačné. Data se ukládají jen v konkrétním prohlížeči; online záloha ani synchronizace nejsou implementovány. Knihovny pro import se načítají z CDN, takže import vyžaduje internet. Před použitím s důvěrnými rukopisy si ověř nakládání se soubory.
