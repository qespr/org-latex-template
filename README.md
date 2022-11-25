# Šablona pro LaTeX Export z org-mode pomocí GNU/Emacs

Cílem není být kompletní nebo správná podle českých sázecích pravidel. Prakticky slouží akorát pro mne jako rychlý start prací u
kterých na tom moc nezáleží nebo je jediná poskytnutá šablona ve wordu či v jiné hrůze.

## Použití

- Stáhněte jako zip (můžete i kolonovat repo ale to mi přijde jako víc práce)
- Někam rozbalte
- Odstraňte tento soubor pokud jej tam nechcete
- Začněte psát
- [Dokumentace o speciálním nastavení Orgu při LaTeX exportu](https://orgmode.org/manual/LaTeX-Export.html)
- Výsledný pdf se vyexportuje pomocí ``C-c C-e l p``
  - Pokud by došlo k chybám, otevřte složku v terminálu a spustťe váš LaTeX compiler na soubor ``dokument.tex`` ručně

## Předpoklady

- Funkční instalace LaTeX kompileru (pdflatex funguje bez dalšího nastavení org-mode)
- Nainstalovaný balik ``listingsutf8``
- Základní znalost LaTeXu
- Ve výchozí nastavení org-modu všechno funguje ale měli by jste aspoň trochu vědět co děláte případně pro export používat emacs s
  ``-q`` parametrem
