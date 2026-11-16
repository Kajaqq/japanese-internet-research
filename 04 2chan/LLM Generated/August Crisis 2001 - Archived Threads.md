---
type: ai-summary
language: pl
source_site: llm
source:
  - https://wiki3.jp/mona/page/24
  - https://seesaawiki.jp/w/battlewatcher/d/8%B7%EE%B4%ED%B5%A1%A1%A1%A1%C1%C5%C1%C0%E2%A4%CE%C6%FC%A1%C1
  - http://web.archive.org/web/20140306191835/http://cocoa.2ch.net/unix/kako/998/998695422.html
  - https://seesaawiki.jp/w/battlewatcher/d/8%b7%ee%b4%ed%b5%a1%a1%a1%a1%c1%bd%aa%a4%ef%a4%eb%c0%a4%b3%a6%a1%c1
  - http://web.archive.org/web/20010805190453/http://www.2ch.net/bbstable.html
topics:
  - "[[2channel Hub|2channel]]"
aliases:
  - 8月危機 - archiwalne wątki
  - August Crisis threads
  - 2ch閉鎖の危機なんだと
created: 2026-11-16
tags:
  - source/ai-generated
  - topic/2channel
  - graph-hidden
---
# August Crisis (8月危機), 2001 — archiwalne wątki

> [!info] O tej notatce
> Wykaz oryginalnych wątków 2ch z Kryzysu Sierpniowego (25–26 sierpnia 2001) i ich kopii w archiwach. Wątek główny i Part2.1 pobrano z Wayback Machine i sprawdzono (tytuł, daty, kluczowe posty). Tło wydarzeń: [[History of 2channel (Monapedia)]], [[History of 2channel]], [[Futaba Channel]].

## Wątek główny: „2ch閉鎖の危機なんだと” („Podobno 2ch grozi zamknięcie”)
- **Board:** UNIX板, serwer `cocoa.2ch.net`, key **998695422**
- **Pierwszy post:** 2001/08/25 (sob.) 08:23. Anonim linkuje w nim wątki o przeciążonych serwerach i o groźbie zamknięcia z boardów 批判要望, ラウンジ i ロビー.
- **Koniec:** post 1000 o 00:44 26 sierpnia, czyli wątek zapełnił się w ok. 16 godzin.
- **Kopie:**
  - [Wayback: wersja z archiwum (kako), 2014](http://web.archive.org/web/20140306191835/http://cocoa.2ch.net/unix/kako/998/998695422.html)
  - [Wayback: oryginalny URL read.cgi, 2016](http://web.archive.org/web/20160702020559/http://cocoa.2ch.net:80/test/read.cgi?bbs=unix&key=998695422)
  - [Wayback: kopia z mimizun.com, 2024](http://web.archive.org/web/20241011113547/http://mimizun.com/log/2ch/unix/998695422/)
  - Oficjalne archiwum 5ch: `https://kako.5ch.io/test/read.cgi/unix/998695422/` (niezweryfikowane — Cloudflare blokował dostęp z narzędzi)

### Kluczowe posty
- **#5, 16:48, Perler:** propozycja poprawek do read.cgi.
- **#18 i #21, 19:05–19:12, 夜勤★:** admin wchodzi do wątku i prosi, żeby ktoś to zakodował w C.
- **#61 i #68, 19:52–19:57, 夜勤★:** admin publikuje kod źródłowy `read.c` (link `http://piza.2ch.net/read4.txt`).
- Dalej Perler ◆GSi39OA6 i 名無し娘。◆vP.bOZFQ piszą obsługę gzip i Last-Modified.

## Kontynuacja: „2ch閉鎖の危機なんだと（Part2.1）”
- **Board:** UNIX板, key **998754174**, od 00:42 26 sierpnia, 940 postów
- [Kopia w Wayback](http://web.archive.org/web/20060303032325/http://cocoa.2ch.net:80/unix/kako/998/998754174.html)
- Wdrożenie krok po kroku (posty 夜勤★):
  - **#425, 02:00:** admin przychodzi sprawdzić nowy read.cgi.
  - **#574, 02:32:** read4.c.5 wgrany na serwer piza2.
  - **#711, 03:04:** „piza2 に read.cgi 5.01 入りました”.
  - **#801, 03:23:** wdrożenie na salad, najbardziej obciążony serwer.
  - **#866–#879, 03:35–03:38:** transfer chyba spadł, serwery „wyraźnie lżejsze”; dalsze testy zapowiedziane na natto.

> [!warning] Sprzeczność w źródłach
> Monapedia ([wiki3.jp/mona/page/24](https://wiki3.jp/mona/page/24)) podaje, że ulepszony read.cgi wdrożono „ok. 23:00” 25 sierpnia. Według samego wątku działo się to **między 02:30 a 03:40 26 sierpnia**. Zgadza się to z innymi wiki, które piszą o „ok. 3:00 26 sierpnia”.

## Wątki towarzyszące
| Wątek | Board | Key | Kopia |
|---|---|---|---|
| プログラマー応援スレ („wątek kibicowania programistom”) | UNIX (`cocoa`) | 998739347 | [Wayback](http://web.archive.org/web/20050502115727/http://cocoa.2ch.net:80/unix/kako/998/998739347.html) |
| プログラマが2chを救う！？ („programiści uratują 2ch!?”) | プログラム技術 (`piza2`, tech) | 998736516 | [Wayback](http://web.archive.org/web/20070206023222/http://piza2.2ch.net:80/tech/kako/998/998736516.html) |
| 転送量(料)の増加で2ch閉鎖の危機！ („2ch grozi zamknięcie przez rosnący transfer!”) | 批判要望 (`teri`, accuse) | 998704295 | [Wayback](http://web.archive.org/web/20100307051228/http://teri.2ch.net:80/accuse/kako/998/998704295.html) |
| 皆さん、２ちゃんねる存続の危機です („Wszyscy, 2ch walczy o przetrwanie”) | ラウンジ (`corn`, entrance) | 998677445 | [Wayback](http://web.archive.org/web/20070124145423/http://corn.2ch.net:80/entrance/kako/998/998677445.html) |
| ところでＵＮＩＸ板はなにをしたの？ („Co właściwie zrobił board UNIX?”), retrospektywa z 03:48 26 sierpnia | UNIX (`cocoa`) | 998765295 | [Wayback](http://web.archive.org/web/20110119040824/http://cocoa.2ch.net:80/unix/kako/998/998765295.html) |
| Wątek na News Flash (ニュース速報), tytuł nieznany | ニュース速報 (`kaba`, news) | 998752277 | brak kopii w Wayback |

## Preludium: seria „curry/ebi鯖重すぎます” na 批判要望
Wątek główny w pierwszym poście linkuje do Part3 i Part4 tej serii. To tutaj 夜勤★ przez cały sierpień raportował obciążenie serwerów i tu w nocy z 24 na 25 sierpnia ogłosił, że się poddaje. Wszystkie części są na boardzie 批判要望 (`teri.2ch.net`, bbs=accuse).

| Część | Key | Okres | Postów | Kopia |
|---|---|---|---|---|
| **Part1**: 【curry鯖重すぎます。】 | 996593101 | od 1.08.2001 00:25 | 554 | [Wayback](http://web.archive.org/web/20080829205244/http://teri.2ch.net/accuse/kako/996/996593101.html) |
| **Part2**: 【ebi＆curry鯖重過ぎます Part2】 | 997196349 | od 7.08 23:59 | 927 | [Wayback](http://web.archive.org/web/20050404140803/http://teri.2ch.net:80/accuse/kako/997/997196349.html) |
| **Part3** | 997804717 | 15.08 00:58 – 25.08 ok. 01:40 | 924 | [Wayback](http://web.archive.org/web/20050315172211/http://teri.2ch.net:80/accuse/kako/997/997804717.html) |
| **Part4** | 998670947 | od 25.08 01:35 | 1001 | [Wayback](http://web.archive.org/web/20050315193441/http://teri.2ch.net:80/accuse/kako/998/998670947.html) |

### Part1 (1–3 sierpnia)
Zwykłe skargi na wolne serwery. 夜勤★ restartuje maszyny i pisze, że przyczyną jest „chyba granica moich możliwości” (#213). O pieniądzach jeszcze nic.

### Part2 (8–13 sierpnia)
- 夜勤★ codziennie publikuje statystyki transferu: serwer curry 22–35 GB dziennie, ebi 5–11 GB.
- **#97:** admin odkrywa na nowo, że najwięcej da się zaoszczędzić na read.cgi — stąd później cała akcja z UNIX板.
- **#603:** read.cgi odpowiada za 33% transferu serwera curry.
- **#512:** admin przypuszcza, że wyświetlanie reklam kosztuje więcej, niż reklamy przynoszą.
- Większość postów „ひろゆき” w tym wątku to podszywacze (każdy ma inny tripkod).

### Part3: noc z 24 na 25 sierpnia
- **#826, 00:45:** „稲垣吾郎さんのせいで、破産しそうです。” („Przez Gorō Inagakiego chyba zbankrutuję”). Ruch po aresztowaniu członka SMAP zalał serwery boardów ニュース速報 i SMAP.
- **#841, 00:56:** to nie wina żadnego boardu, po prostu przyszedł „limit”.
- **#865, 01:11:** problemem jest cena za przepustowość; 2ch zużywał wtedy **160 Mbps**.
- **#869, 01:13:** na pytanie, czy przekroczono granicę tego, co hosting daje za darmo w zamian za reklamy: „そうですよん。… 単にお金の問題ですよー” („Tak jest… to po prostu kwestia pieniędzy”).

### Part4: 25 sierpnia od 01:35
- **#21, 01:48:** „単に、私が give up なだけですから” („po prostu to ja się poddaję”).
- **#24, 01:49:** „みんな　はさーん”. Zaraz potem zaczyna wyłączać kolejne boardy.
- **#141:** gdyby brał od 2ch pieniądze, stałoby się to zwykłym biznesem i musiałby zdjąć swoje reklamy.
- **#162 i #173:** boardy czatowe na jego serwerach zostaną pewnie zamknięte w przyszłym tygodniu. Chciałby zejść do 1/3 transferu, ale sam w to nie wierzy: ludzie z zamkniętych boardów przejdą na inne i w końcu „padną wszystkie”.
- **#241, 04:37:** proponuje **płatne narzędzie i boardy czatowe dostępne tylko przez nie**. Rok później (2002) z tego pomysłu wyrósł płatny ● (2channel Viewer); ostatecznie ● nigdy nie zamykał żadnego boardu, ale pomysł ograniczenia dostępu padł właśnie tutaj.

> [!warning] Uwagi do relacji na Seesaa Wiki
> - **„700万円 miesięcznie” nie pochodzi od administracji.** Policzyli to użytkownicy na podstawie 160 Mbps z #865 i cennika hostingu, do którego admin dał link w #837. Wyliczenia są w Part3 #880 i #909 oraz w wątku [転送量(料)の増加で2ch閉鎖の危機！](http://web.archive.org/web/20100307051228/http://teri.2ch.net:80/accuse/kako/998/998704295.html) („Big‐serverの料金計算では月に700万円にもなりそう”). [2ちゃんねる血風録 — 8月危機 〜終わる世界〜](https://seesaawiki.jp/w/battlewatcher/d/8%b7%ee%b4%ed%b5%a1%a1%a1%a1%c1%bd%aa%a4%ef%a4%eb%c0%a4%b3%a6%a1%c1) przedstawia to jak oficjalną kwotę.
> - **Postu 山本一郎＠切込隊長 ★ #53 z 21:50 25 sierpnia nie znaleziono** w żadnym z powyższych wątków ani w wątkach z UNIX板. Musi pochodzić z innego wątku (np. kolejnej części serii albo z ロビー).

## Serwery 2ch w sierpniu 2001
Źródło: [Wayback: www.2ch.net/bbstable.html, 5.08.2001](http://web.archive.org/web/20010805190453/http://www.2ch.net/bbstable.html). Każdy board był przypisany do konkretnego serwera o „jedzeniowej” nazwie (np. `http://curry.2ch.net/tv/`). Wszystkie należały do hostingu 夜勤★ w Sapporo (Big-Server / maido3), który dawał serwery w zamian za reklamy. Konwencja nazw jest tu tylko obserwacją — brak źródła, które by ją wyjaśniało.

### curry i ebi — jedna maszyna
夜勤★ w Part1 #10 (1.08.2001): „あのー　同じサーバなんですけど。 ebi&curry” („Eee… to jest ten sam serwer”). Dlatego restartowano je i raportowano razem, jako „ebi&curry”.

- **curry.2ch.net (12 boardów, głównie rozrywka):** `tv` テレビ番組, `tvd` テレビドラマ, `geinin` お笑い芸人, `smap` スマップ, `voice` 声優, `music` 音楽一般, `musicj` 邦楽, `musice` 洋楽, `occult` オカルト, `megane` めがね, `bicycle` 自転車, `jobs` Mac (ID od Steve'a Jobsa).
- **ebi.2ch.net (13 boardów, mieszanka):** `shar` シャア専用, `asong` アニソン等, `apple` 椎名林檎 (gra słów: ringo = jabłko), `owarai` お笑い小咄, `nohodame` のほほんダメ, `rikei` 理系全般, `chiri` 地理お国自慢, `sisou` 政治思想, `shihou` 司法試験, `regulate` 通信行政, `pav` ピュアAU, `kyozin` アンチ球団, `21oversea` 危ない海外.

Rozkład transferu curry (Part2 #603, 11.08): read.cgi 33%, dalej strony główne boardów `tv` 7,4%, `musicj` 7,3%, `tvd` 6,4%, `occult` 6,2%, **`smap` 5,5%**, `musice`, `music`, `geinin`, `voice`. Dlatego aresztowanie Inagakiego uderzyło dokładnie w ten serwer.

### Liczba boardów na serwerach
mentai 69 · yasai 33 · salad 33 · natto 29 · piza2 26 · ton 22 · cocoa 20 · cheese 17 · teri 15 · saki 13 · **ebi 13** · **curry 12** · salami 8 · kaba 8 · corn 3

### Gdzie stały boardy związane z kryzysem
| Board | ID | Serwer |
|---|---|---|
| ニュース速報 (News Flash) | `news` | kaba |
| ニュース議論 (News Discussion) | `news2` | kaba |
| スマップ (SMAP) | `smap` | curry |
| UNIX | `unix` | cocoa |
| 批判要望 (Criticism & Requests) | `accuse` | teri |
| ラウンジ (Lounge) | `entrance` | corn |
| 廃墟ロビー (Lobby) | `lobby` | saki |
| モ娘（狼） | `morning` | natto |
| パチンコ (Pachinko) | `pachi` | salami |

Boardy www, pachi i morning 夜勤★ wymieniał w Part3 #818 jako te, których ruch trzeba by zmniejszyć o połowę.

## Inne materiały
- **Kod read.cgi z tamtej nocy:** [nekoruri/readcgi](https://github.com/nekoruri/readcgi) — repozytorium CVS z 2001 r. przeniesione do Gita, z zachowanymi ówczesnymi lukami, jako materiał historyczny.
- **Opis wydarzeń z numerem wątku:** [2ちゃんねる血風録 — 8月危機 〜伝説の日〜 (Seesaa Wiki)](https://seesaawiki.jp/w/battlewatcher/d/8%B7%EE%B4%ED%B5%A1%A1%A1%A1%C1%C5%C1%C0%E2%A4%CE%C6%FC%A1%C1)
- **Kontekst:** [Monapedia — 8月危機](https://wiki3.jp/mona/page/24)

## Jak sprawdzić inne wątki z 2001 r.
Stare wątki 2ch mają adresy archiwalne w formacie `http://<serwer>.2ch.net/<board>/kako/<pierwsze 3 cyfry key>/<key>.html`. Key to uniksowy znacznik czasu założenia wątku, więc `998695422` = 2001-08-25 08:23:42 JST. Dostępność kopii można sprawdzić przez `https://archive.org/wayback/available?url=<adres>`.
