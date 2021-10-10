---
layout: default
title: Hugo - generátor statických stránek
---

# Hugo - generátor statických stránek

Když v prohlížeči, třeba na této stránce,
kliknete myší pravým tlačítkem, uvidíte obrázek,
který bude vypadat asi takto: <br><br>

<img src="/assets/zobrazit-zdrojovy-kod-stranky.png" class="zobrazit-zdrojovy-kod"><br><br>

Klikněte na "Zobrazit zdrojový kód" a uvidíte zdrojový kód stránky, kterou si prohlížíte. Bude začínat asi takto.

```

<!DOCTYPE html>
<html lang="en">
<head>

```

Psát každou stránku ve zdrojovém kódu by bylo příliš složité, a proto většina tvůrců webových stránek používá nějaký nástroj pro tvorbu webových stránek. Většinou se jedná o nějaký redakční systém (Wordpress, Drupal nebo Joomla) nebo o nějaký online nástroj jako je Webnode.<br><br>

Pro tvorbu Pandita.cz ale používám nástroj. který není až tak dobře známý: generátor statických stránek (GSS). Generátory statických stránek mají ve srovnání s výše uvedenými nástroji několik výhod:

<ul style="padding-left:20px">
<li> umožňují snadné formátování dlouhých textů, i celých knih, do podoby webových stránek.</li>
<li> statické stránky se načítají velmi rychle, protože vůbec nepracují s databází. Především u redakčních systémů může být prodleva i několik sekund.</li>
<li> obsah stránek lze velmi snadno umístit na web ke stažení pro offline studium. </li>
</ul>

Navíc jsou generátory statických stránek velmi flexibilní. Původně jsem pandita.cz vytvářel pomocí GSS, který se jmenuje Jekyll. Až později jsem celý projekt migroval na GSS, který se jmenuje HUGO.<br><br>

### Formátování

Samotné formátování textů, neboli přeměna pdf souborů na webovou stránku, je velmi snadné. <br><br>

Pokud například chcete vytvořit nápis stránky, vložíte před něj znak

<span class="nadpis-hash">#</span>. Nápis pak vypadá takto:

<div class="citace">
<span class="nadpis-hash"># Hugo - generátor statických stránek.</span>
</div>

Pokud chcete vytvořit odstavec, vložíte na jeho konci dvakrát značku
<span class="nadpis-hash" style="font-size:16px"> `<br>` </span>.
Vytvořený odstavec pak v textu vypadá takto:

<div class="citace" markdown="1">
Když v prohlížeči, třeba na této stránce,
kliknete myší pravým tlačítkem, uvidíte obrázek,
který bude vypadat asi takto: <span class="nadpis-hash" style="font-size:16px">`<br>` `<br>`</span>.
</div>

Někdy budete možná chtít, aby určitá část byla napsána tučně. V takovém případě text uzavřete ve značce <span class="nadpis-hash" style="font-size:16px"> `<b>` </span>.<br><br>

Některé části budou napsány <b>tučně.</b>

<div class="citace" markdown="1">
Některé části budou napsány  <span class="nadpis-hash" style="font-size:16px">`<b>`</span> tučně.<span class="nadpis-hash" style="font-size:16px">`</b>`</span>
</div>

Pokud byste chtěli vidět, jak vypadá zformátovaný soubor, klikněte na odkaz níže. Najdete v něm i některé další instrukce k formátování.<br><br>

<a href="assets/priklad-md-formatovani.pdf">Zformátovaný soubor.</a><br><br>

### Instalace

Samotná instalace pracovního prostředí, ve kterém je možné obyčejné texty měnit na webové stránky, je určitě složitější, než formátování samotné. Pokud jste ale někdy už instalovali na svém počítači nějaký program, určitě to zvládnete.<br><br>

K práci s textem budete potřebovat:

<ul>
<li> <span class="dotted">Visual Studio Code (VSC)</span> je program, který používají pro svoji práci programátoři. Zároveň je to ale i textový editor, jako např. Microsoft Word.<br><br>

VSC je k dispozici zdarma a je možné si ho stáhout <a href="https://code.visualstudio.com/">na jeho domovské stránce.</a></li><br>

<li> <span class="dotted">Projekt Hugo-pandita</span> je jedna velká složka, ve které jsou umístěny jednotlivé kousky webu Pandita.cz: hlavička, patička, soubory s obsahem jednotlivých stránek, obrázky a soubory určující vzhled celého webu (CSS soubory).<br><br>

Celý projekt je ke stažení <a href="https://github.com/Borek78/pandita-hugo">na mém Githubu.</a> Pro stažení projektu klikněte na zelené tlačítko <span class="green-button">Code</span> a pak na položku "Download ZIP".<br><br></li>

<li> <span class="dotted">Hugo</span> je generátor statických stránek. Je to ta věc, která spojí jednotlivé části projektu Hugo-pandita do jednotlivých statických webových stránek.<br><br>

I HUGO je software, který je k dispozici zdarma. Můžete si ho stáhnout <a href="https://gohugo.io/getting-started/installing/">na jeho domovské stránce.</a>

</li>

</ul>

### Video návody

V této části najdete video návody pro práci s VSC, Hugo a projektem Pandita-hugo. Jsou především pro všechny dobrovolníky, kteří by se chtěli podílet na formátování textů do podoby webové stránky. Návody jsou rozděleny do dvou částí.<br><br>

<div style="margin-top:10px; margin-bottom: -10px"  >
<span class="grey-heading" >
Tvorba pracovního prostředí
</span>
</div>

- <a style="margin-top:50px" href="https://www.youtube.com/watch?v=4dUwjEX8n6c">Jak nainstalovat Visual Studio Code</a><br>

- <a href="https://www.youtube.com/watch?v=EURkOJ1iPBA">Jak stáhnout Pandita-hugo projekt</a><br>

- <a href="https://www.youtube.com/watch?v=Xirm3-Qj_i0">1. Instalace GSS Hugo - vytvoření složek a stažení Huga</a><br>

- <a href="https://www.youtube.com/watch?v=y0P4Ik07O8U">2.Instalace GSS Hugo - kopírování Huga a projektu Pandita-hugo do těch správných složek</a><br>

- <a href="https://www.youtube.com/watch?v=sx9c_tyRG1w">3. Instalace Hugo - navigace v příkazovém řádku (terminálu)</a><br>

- <a href="https://www.youtube.com/watch?v=hfqccvr4Of0">4. Instalace Hugo - hugo version + kopírování souboru hugo.exe do složky projektu</a><br>

- <a href="https://www.youtube.com/watch?v=i1qMHbnbV7w">5. Instalace Hugo - definování proměnné prostředí</a><br>

- <a href="https://www.youtube.com/watch?v=dpIyLsfeI5Y">6. Instalace Hugo - definování proměnné prostředí - dodatek</a><br><br>

<div style="margin-top:10px; margin-bottom: -10px"  >
<span class="grey-heading" >
Práce s Hugo
</span>
</div>

- <a style="margin-top:50px" href="https://www.youtube.com/watch?v=8x1IeUmlLHs">1. Práce s Hugo - výběr správného terminálu + vytvoření stránky Meditace mettá</a><br>

- <a href="https://www.youtube.com/watch?v=dl4sFR1tkmA">2.Práce s Hugo - používání příkazu hugo server + jak se stránky vytvoří z kousků</a><br>

- <a href="https://www.youtube.com/watch?v=RqCmKS93fiI">3. Práce s Hugo - práce s příkazem hugo server (2.část) + tvorba obsahu stránky Meditace mettá</a><br>

- <a href="https://www.youtube.com/watch?v=gTJrQ0UJWFg">4.Práce s Hugo - dva způsoby tvorby odkazů</a><br>

- <a href="https://www.youtube.com/watch?v=bVl1PlV0shU">5. Práce s Hugo - formátování obsahu knihy Meditace mettá</a><br>

- <a href="https://www.youtube.com/watch?v=mPJ99SxWknw">6. Práce s Hugo - formátování obsahu stránky Meditace mettá - část 2.</a><br>

- <a href="https://www.youtube.com/watch?v=1XK9l2twFrs">7. Práce s Hugo - formátování první kapitoly knihy Meditace metá</a><br>

- <a href="https://www.youtube.com/watch?v=_zR1XJkvdc8">8. Práce s Hugo - rozdělování odstavců, nadpisy nižší úrovně, hledání a odstraňování otazníků</a><br><br>

### Čitelnost

Šablonu pro web Pandita.cz jsem se snažil tvořit tak, aby byl text co nejlépe čitelný. Proto jsem při její tvorbě zvolil pro formátování textu následující parametry:

<ul>
<li><a href="https://baymard.com/blog/line-length-readability">počet znaků na řádek na pandita.cz je mezi 65-71</a></li>
<li><a href="https://accessibility.psu.edu/legibility/fontface/" >bezpatkové písmo (sans-serif)</a></li>
<li><a href="https://www.kevinpowell.co/article/line-height/" >výška řádku (line-height) je 1.6</a></li>
</ul>

Každý výše uvedený parametr odkazuje na stránku, která vysvětluje jeho optimální nastavení.<br><br>

Čitelnost také ovlivňují délky odstavců. Ty by pro online/offline čtení měly být kratší než u knih. Odstavce by neměly být delší <a href="https://devrix.com/tutorial/ideal-length-of-your-online-content/">než 150 slov. </a>Já raději dělám odstavce ještě kratší. Pokud to význam textu jenom trochu umožňuje, formátuji texty<a href="https://devrix.com/tutorial/ideal-length-of-your-online-content/"> na méně než 40-55 slov.</a><br>

<div style="display:none">
### Šablona

Tato část je pro všechny, kteří by web Panidta.cz chtěli někdy v budoucnosti spravovat.<br><br>

Obsah projektu Pandita.cz lze zobrazit pomocí jakékoli šablony, která je vytvořená pro generátory statických stránek Hugo. Pro web Pandita.cz jsem ale vytvořil speciální šablonu. Vytvořil jsem ji pomocí jazyků HTML, CSS, Javascript a několika funkcí jazyka GO.<br><br>

Zdánlivou nevýhodou použití generátorů statických stránek je tedy větší technická náročnost, protože správa webu Pandita.cz vyžaduje znalost z programování.<br><br>

Myslím si ale, že vždy se najde v naší buddhistické komunitě někdo, kdo bude schopný celý projekt spravovat.
Je pro to několik důvodů:<br><br>

<ul>
<li>naučit se alespoň základy CSS a HTML je relativně snadné. Uvádí se, že k tomu stačí 14 dní.</li>
<li>javascript není nutné znát ke správě webu: doplňování obsahu, mazání obsahu, nahrání nové verze webu na server atd.  </li>
<li>možná</li>

</ul>
</div>
