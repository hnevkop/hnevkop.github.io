---
title: 'Vývojář a AI. Sňatek z rozumu'
show_date: true
classes: wide
tags:
   - Poznámečky
   - AI
   - IT
   - Umělá inteligence
   - Rozum
   - Budoucnost
   - Technologie
categories:
   - Blog
category: Blog
header:
   teaser: /assets/images/artur-tumasjan-Ox-x45IaxSA-unsplash.jpg
   og_image: /assets/images/artur-tumasjan-Ox-x45IaxSA-unsplash.jpg
   last_modified_at: 2024-05-23T01:01:25-05:00
layout: single
---

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/artur-tumasjan-Ox-x45IaxSA-unsplash.jpg){: .align-center}

**Umělá inteligence se dere na místa juniorů. Rychle, efektivně a za zlomek ceny. Máme připravené bezdomovecké stany, nebo to ještě chvíli počká, až k nim přibudou i senioři? A pomůže nám se stavěním Copilot ?**

V IT oboru v poslední době sleduji prohlášení ohledně snižování náboru na juniorské pozice a úpravy v nabídkách práce v důsledku nasazování AI. Někteří *[experti](https://zpravy.aktualne.cz/datavize/kdo-muze-prijit-o-praci-kvuli-ai/r~33182af0d4b111eeabbe0cc47ab5f122/)*  se domnívají, že testování a tzv. boilerplate kód, tedy nudný a opakující se kód, zvládnou za nás chatboti a různé pomocné softwarové nástroje. Z vlastní zkušenosti s tímto trendem částečně souhlasím. I když se to na první pohled zdá lákavé, realita je složitější.

Na rozdíl od jiných oborů umožňuje IT rychlou implementaci změn. Zatímco vyzkoušení nové plodiny může zemědělci trvat rok, otestování změny v softwaru zabere obvykle jen několik minut. Současná AI má schopnost vytvářet testy, generovat kód dle popisu a vylepšovat stávající. Z toho vyplývá, že není potřeba dělat práci, kterou zvládne automatizovaný nástroj. V extrémním případě by se dalo říci, že *[učení programování](https://www.techradar.com/pro/nvidia-ceo-predicts-the-death-of-coding-jensen-huang-says-ai-will-do-the-work-so-kids-dont-need-to-learn)* už není nutné a stačilo by se spolehnout na to, co připraví AI. S touto tezí ale osobně nesouhlasím. Určité porozumění stroji a kódu bude vždy nezbytné.

**Proč je pochopení kódu důležité i v době AI?**

I když AI dokáže generovat kód a automatizovat úkoly, stále je důležité, aby lidé rozuměli tomu, jak kód funguje. Zde je pár důvodů:

- Řešení problémů: AI se stále neobejde bez lidského dohledu. Je potřeba, aby člověk dokázal posoudit, zda je vygenerovaný kód správný a efektivní, a případně ho upravit. Otázka, jestli to bude chtít pokaždé, je samozřejmě jiná.
- Kreativita a inovace: AI je skvělá pro automatizaci úkolů, ale všechno ještě nedokáže. I když výsledky posledního *[ChatGPT4o](https://openai.com/index/hello-gpt-4o/)* jsou dechberoucí,  je to člověk, kdo vymýšlí nové nápady a koncepty v reálném světě, které pak AI může pomoci rychle uskutečňovat.
- Komunikace a spolupráce: Trochu s nadsázkou. V IT se bez kecání neudělá nic! I když roboti mluví, lidská konverzace je pořád k nezaplacení.

## Co na to firmy?
Postoj firem k tomuto tématu se liší v závislosti na prostředí. Co je v jedné firmě považováno za dobrý systém a kód, by v jiné firmě ani nepovolili nahrát na disk. Mnoho firem dělá zásadní chybu: podceňuje komplexní hodnotu softwaru.
Ta se neskládá pouze z užitné hodnoty, zahrnující základní funkčnost a bezpečnost. Důležitá je také rozšiřitelnost, škálovatelnost a otevřenost. Software by měl být otevřený změnám a přenositelný mezi platformami, ať už se jedná o software jako službu (SaaS), nebo vyvíjený na zakázku.

### Případ 1: Software jako nezbytný náklad firmy
Pro firmy zabývající se primárně něčím jiným, než je software, je jeho cena mnohdy nejasná.  Platí vždy, ať už jdou cestou vlastního vývoje, používáním softwaru jako služby (SaaS), vývojem na zakázku nebo nákupem tzv. krabicového řešení. Místo aby si firmy vybíraly nástroje na základě logiky, dělají to spíše podle toho, co se hodí šéfům a jaká je zrovna vnitrofiremní situace. Ani samotné IT firmy v tomto ohledu neprospívají, jelikož se neustále snaží prezentovat svá řešení jako jediné správné. V konečném důsledku je tedy software pro firmu nákladem a pokud se naskytne možnost ušetřit s pomocí AI, firmy se ji s velkou pravděpodobností chopí. Nákladem je v tomto kontextu myšlena i lidská práce.
Díky svým specifickým vlastnostem dokáže AI software důkladně analyzovat a provést jeho tzv. reverzní inženýrství. V tom totiž *[AI vyniká](https://en.wikipedia.org/wiki/AI-assisted_reverse_engineering)* a dosahuje vynikajících výsledků.

> Dobrou zprávou tedy je, že AI bezpochyby usnadní přechod ze starých systémů na nové platformy.

###  Případ 2: Software jako hodnota firmy.
U některých firem představuje software jejich hlavní, ne-li jedinou hodnotu. V takových případech je obvykle plně chápán celý proces vývoje softwaru. Kladou důraz na bezpečný kód, dodržování nejnovějších standardů, testování a zavádění principů kontinuálního dodávání a vývoje (Continuous Delivery/Continuous Development), neustálou refaktorizaci a údržbu. AI se zde již masivně testuje a zkouší, ale i v těchto firmách se bude AI využívat k optimalizaci nákladů.

> AI totiž přináší funkce, které posouvají některé dovednosti lidského vývojáře o úroveň níže, nebo výše, chcete-li.

Například:
V minulosti musel programátor znát do detailu algoritmus pro kódování MP4 videa. Dnes mu stačí knihovna, kterou jednoduše ověří a začlení do aplikace pro přehrávání. S nástupem AI se možnosti posouvají ještě dál. Knihovna se nejen sama vyhledá v nejvhodnější verzi, ale navrhne i její implementaci do existujícího kódu, připraví sadu testů a upraví celý kód v souladu s požadovaným standardem. Tím se eliminuje značná část rutinní práce, která postrádá kreativní prvek.
Podobně se zjednoduší i práce s infrastrukturou. AI sama navrhne nejvhodnější způsob a cílové umístění nasazení kódu v cloudovém prostředí. Příklady takového automatizovaného vývoje se množí a některé z nich existovaly v základní formě už před současnou vlnou AI.
**Samozřejmě zůstává otázka, co je kreativní, a kde zůstává ještě nějaký prostor pro člověka, vývojáře.**

## Vývojář a AI - jeden bez druhého ani ránu
Pozice softwarových vývojářů na trhu práce byla vždy specifická. V IT oboru se špičkoví vývojáři dokázali vypracovat k závratným výšinám, vytvářet produkty které měnily svět a zakládat firmy s miliardovou hodnotou.

**Zda tato éra končí a další vlna inovací bude patřit spíše AI, nebo s ní budou vývojáři úzce spolupracovat, se teprve ukáže.**

Jisté je, že kariéra v běžné IT firmě se bude i nadále ubírat stejnou cestou. Stále bude vyžadovat nejen základní odborné znalosti a dovednosti, ale i zodpovědnost, schopnost pracovat v týmu a sdílet znalosti s kolegy. V tomto prostředí, které zahrnuje nejen programování, ale i management, marketing, práci se zákazníky a další oblasti, se každoročně mění technologie bez ohledu na pokroky v oblasti umělé inteligence. Nové verze programovacích jazyků, frameworků, architektur a klíčových komponent, jako i nerealistické ambice, tlak na termíny a technologický dluh v některých firmách – to vše může vést k vyhoření. S AI nebo bez ní. Ale nezapomeňme na opačnou stranu mince.

**Hodnotou dynamického prostředí IT firem je schopnost adaptace a inovace.**

Zkušení matadoři, kteří v IT strávili desítky let, se můžou obávat, že jejich znalost detailů systému, platformy a domény je najednou k ničemu. Koneckonců, AI si s tím poradí lépe a rychleji. Na druhou stranu, mladí nadšenci, kteří teprve nastupují do světa IT, se můžou těšit na novou éru plnou inovací a možností. Pro ně je AI spíš přítelem než nepřítelem.
Některé pozice v IT se tedy skutečně můžou a budou radikálně změnit. Místo detailní znalosti systémů bude důležitější umět „postavit pilíře“ pro nástroje AI, podobně jako se budovala infrastruktura pro první chatboty. Na jiných pozicích bude nutné neustále kontrolovat a dohlížet na to, co AI dělá, jaká data sbírá a zda dodržuje specifické požadavky. Ačkoliv populární *[GitHub Copilot](https://github.com/features/copilot)* se prezentuje jako druhý pilot, ve skutečnosti se stává kapitánem.

> V podstatě se z mnohými nás stanou dozorci nad robotickými kolegy. Staneme se jejich průvodce na cestě do budoucnosti!

Pak pravděpodobně přijde některá další fáze.
Už se těším, až budu učit robota, jak se správně usmívat na klienty a jak se vyhýbat otázkám o platu. 

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/konstantin-evdokimov-TAyKlj_PZxk-unsplash.jpg){: .align-center}

Publikováno na *[Seznam Medium](https://medium.seznam.cz/clanek/premysl-hnevkovsky-vyvojar-a-ai-snatek-z-rozumu-64349)*  

