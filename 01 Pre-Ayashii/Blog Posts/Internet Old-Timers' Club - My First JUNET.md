---
type: translation
source_site: note.com
title: "Internet Old-Timers' Club: My First JUNET"
original_title: インターネット老人会 - はじめてのjunet
aliases:
  - はじめてのjunet
  - My First JUNET
author:
  - kzn
language: en
original_language: ja
translation_date: 2026-10-23
source: https://note.com/kazushinakamura/n/n7dafbef333f3
published: 2025-05-27
original_clipping: "[[Internet Old-Timers' Club - My First JUNET]]"
tags:
  - source/note-com
  - research/japanese-web-culture
  - history/early-internet
  - topic/junet
---
# Internet Old-Timers' Club: My First JUNET

Lately, a hashtag called "Internet Old-Timers' Club" has become conspicuous on social media here and there.[^tn-rojinkai] Because it is vague about which era and what kind of internet it refers to, the people who gather under it vary a great deal. Despite the "old-timers" label, on some platforms many of them are very young, so much so that I wonder whether I'll be pushed off into an Internet Hermits' Club, or rather the Underworld. (In a different sense, an Internet Burnouts' Club is also needed, isn't it ^^;)[^tn-puns]

In Japan, the "proper" internet probably began with commercialization in 1992, and I think most people first touched the internet after Windows 95, released in 1995, came into use.[^tn-1992] Even so, many people don't know the difference between the internet and *pasokon tsūshin* (PC communications),[^tn-pasotsu] and quite a few confuse their memories of PC communications with memories of the internet. One indirect cause may be that, during that period, Nifty-Serve and others were running interconnection experiments with the internet, so some functions, such as email, could be used from PC communications too.

I wrote about how I started using these services early on, back in the dawn of PC communications. This was at the height of grassroots BBSes,[^tn-kusanone] just as large companies were finally entering the PC communications business, and the article is below.

[**Modems and PC Communications**](https://note.com/embed/notes/n14db0e5fd9ec)

That said, my own "first internet" goes back a generation earlier, to the JUNET era.

 [**It Wasn't the Internet, It Was JUNET**](https://note.com/embed/notes/n40eef40cf72e)

Back then, email and news were delivered by exchanging data between servers with a mechanism called UUCP, which connected UNIX machines in distant places over telephone lines. Data sent to the distribution server on a LAN went out when the `uucico` command dialed a preset number and passed the data to the other server, then took back whatever was waiting.[^tn-uucico] Only a small number of sites were permanently connected.

**JUNET**

**Unix to Unix Copy Protocol**

This was also described as a "bucket brigade."[^tn-bucket] The same word is used to explain routing in the IP era, though, so take care not to confuse the two, even if the meaning is similar. The domain system was still being built, and specifying a destination sometimes meant listing every server the message would pass through, separated by "!".[^tn-bang] In any case, nothing was exchanged in real time. Data pooled until then was swapped when the connection was made at a fixed time each day, so depending on the destination it could take several days to reach the destination server. It truly was just like the postal service.

The servers at the top of JUNET were run by the University of Tokyo, Tokyo Institute of Technology (now Institute of Science Tokyo),[^tn-titech] Keio University and KDDI.[^tn-kdd] An organization that wanted to join the network contacted one of these servers, or an organization hanging off them, and asked to be connected. The steps and paperwork were collected in a document called *JUNET User's Guide*, and organizations that wanted to join did the setup and applied following the procedure written there.

***JUNET User's Guide* (1st edition)**[^tn-tebiki]

Apart from the top level, each server only had the choice of sending data upstream or downstream, so delivery routes weren't very complicated.

I, too, got access to JUNET at my part-time job and started exchanging email and posting to netnews.

**fj (newsgroups)**[^tn-fj]

I often hung around groups like fj.sys.pc98 and fj.os.msdos.[^tn-pc98] I wanted my posts to go out as soon as possible, so I would log in to the server as root and start `uucico` before the scheduled time came ^^;. Before long, that workplace also joined WIDE, got a leased line and moved to IP connectivity, so I no longer had to kick off `uucico`.[^tn-wide] However, JUNET hadn't yet reached the university I was attending then. Without meaning to, I ended up being the one who read that guide and asked the University of Tokyo to connect us via UUCP. At that point even the university had no LAN, so we used it by dialing up to the server over internal extension phone lines. Come to think of it, the dial-up server unit was attached to a Fujitsu-branded Sun,[^tn-fujitsu-sun] and its console was a PC-98LT.[^tn-pc98lt] It was that kind of era.

**WIDE Project**

In fact, I remember doing this setup while remotely logged in to the server at my workplace, checking its existing, working configuration. That one was already on IP, after all. Configuring it from scratch with nothing but the data on a floppy disk would have been far too hard, even back then. The University of Tokyo's connection line also only let you connect at fixed times, because it had to handle so many connection requests.

Which reminds me: later, when I was attending Tokyo Tech, I went to see the manhole famous from the legend of Professor Jun Murai's first JUNET connection.[^tn-manhole] In my time, Tokyo Tech's LAN had spread out into a real patchwork network, and its state was always changing. I wrote a script that fetched "today's internet" every morning and updated my settings. It would probe ports to find DNS servers, run a simple benchmark on them, and set the primary and secondary from the results. Routing was bizarrely complex too. Once the main router went down, yet routes were set automatically and we stayed connected to the outside through some mysterious path. It got a lot slower, but in the end the connection never dropped.

Either way, I was baptized by the internet (JUNET) before I seriously used PC communications. I had a university account (even an administrator account!!), but I couldn't log in remotely from home, so it came to the point where I really had to get a PC communications account as well.

The story from there will wait for another time.

---

*Added 2026.4.30*

![Image](https://assets.st-note.com/img/1777509541-DSg58nzyvPob2mZY7G4wuEWT.png?width=1200)

Infographic made with NotebookLM

**Slide material made with NotebookLM**

**Digest video**

![](https://www.youtube.com/watch?v=oioFcW--A_M)

**Explainer video made with NotebookLM**

![](https://www.youtube.com/watch?v=PYPtKmYcdDY)

**Audio commentary made with NotebookLM** ([embedded audio](https://note.com/embed/sounds/96b4fd5d2ebd798e7bfc4aca6ec1ec3b))

---

I couldn't find a good header image, so I had Grok draw one.

#InternetOldTimersClub #junet #WIDEProject #uucp #uucico #IPConnectivity #InternetUsersGuide #netnews #fj

> [!info] Cultural context and translator's notes
> This is a personal blog post by a Japanese engineer, published on note.com on 2025-05-27, and it should be read as memoir rather than reference history. The author never dates their own experiences, so the JUNET period described here can only be placed roughly in the late 1980s, before WIDE took over. Claims about who ran JUNET and the "manhole legend" are given as the author remembers them; see the notes for points that differ from other sources. The author's casual tone and kaomoji (^^;) are kept. note.com embeds have been turned into links, and the closing hashtags are rendered in English. The addendum dated 2026.4.30 refers to AI-generated summary media (NotebookLM, Grok) added later by the author; it is not part of the original memoir.

[^tn-rojinkai]: インターネット老人会 (*intānetto rōjinkai*, "Internet Old-Timers' Club / Internet Seniors' Association") is a Japanese social-media hashtag for nostalgia about the early web. Posters share things "only old-timers will remember". The author's complaint is that the tag has no fixed era, so people reminiscing about 2000s services use it alongside people who remember pre-commercial networks.
[^tn-puns]: Three wordplays on 老人会 (*rōjinkai*, old people's club): 仙人会 (*senninkai*, a club of hermit-sages or immortals, i.e. even older), 冥界 (*meikai*, the underworld, i.e. already dead), and 廃人会 (*haijinkai*). 廃人 (*haijin*, "a wreck, a burnout") is Japanese net slang for someone hopelessly addicted to the internet or games (cf. ネト廃 *neto-hai*), and it rhymes with *rōjin*. "In a different sense" means a club for addicts, not for the elderly.
[^tn-1992]: 1992 is the founding year of IIJ, Japan's first commercial ISP. Commercial IP service began in 1993, so "commercialized in 1992" is a common approximation. The Japanese release of Windows 95 was 23 November 1995, the date usually used to mark the internet going mainstream in Japan.
[^tn-pasotsu]: パソコン通信 (*pasokon tsūshin*, usually shortened to パソ通 *pasotsū*) means dial-up online services and BBS networks reached by modem, such as Nifty-Serve, PC-VAN and ASCII-NET. They were closed, centrally run systems, not part of the internet, though they later added email gateways to it. The author's point is that many self-described "internet old-timers" actually remember these services.
[^tn-kusanone]: 草の根BBS (*kusa-no-ne* BBS, "grassroots BBS") is the Japanese term for small hobbyist bulletin-board systems run by individuals on a single PC and phone line, as opposed to the big commercial services.
[^tn-uucico]: `uucico` ("UUCP copy in, copy out") is the UUCP daemon that actually places the call, logs in to the remote machine and transfers queued files in both directions. It was usually started by `cron` at fixed times to save on phone bills.
[^tn-bucket]: バケツリレー (*baketsu rirē*, "bucket relay/brigade") is the standard Japanese metaphor for store-and-forward networking, in which data is handed from one machine to the next like buckets in a fire-fighting chain. The same word is used loosely for hop-by-hop IP routing, hence the author's warning.
[^tn-bang]: These are UUCP "bang paths", e.g. `hostA!hostB!hostC!user`, which spell out every relay hop by hand. Domain-style addresses (`user@host.ac.jp`) replaced them as the JUNET domain system matured.
[^tn-titech]: Tokyo Institute of Technology (東工大 *Tōkōdai*) merged with Tokyo Medical and Dental University in October 2024 to form Institute of Science Tokyo (東京科学大学, shortened by the author to 科学大). The author adds the new name parenthetically.
[^tn-kdd]: This is probably an anachronism. In the JUNET era the company was KDD (Kokusai Denshin Denwa, the international telecom carrier), which became KDDI after its 2000 merger. Other accounts, including [[The Internet - Nicopedia]] in this vault, name only Keio, Tokyo Tech and the University of Tokyo as the founding JUNET sites in 1984. KDD's research labs are best remembered as an important node and the route for JUNET's international links, not as a founding member; verify before citing.
[^tn-tebiki]: JUNET利用の手引 (*JUNET riyō no tebiki*) was the official how-to-join document. The closing hashtag "#インターネット利用の手引" (Internet User's Guide) seems to refer to the same kind of document for the later IP internet.
[^tn-fj]: fj ("from Japan") was JUNET's Japanese-language netnews hierarchy, the Usenet-style newsgroup tree it shared with the wider network. fj was the main public discussion space of Japanese networking before the web. Its flame wars and culture are part of the prehistory of later Japanese anonymous BBSes.
[^tn-pc98]: fj.sys.pc98 was about NEC's PC-9800 series, the dominant Japanese personal computer of the 1980s–90s; fj.os.msdos was about MS-DOS.
[^tn-wide]: The WIDE Project, founded in 1988 under Jun Murai, built the IP research network that succeeded UUCP-based JUNET, using leased lines (専用線 *senyōsen*) for permanent connections. "Kick off `uucico`" translates 叩く (*tataku*, "to hit/bang on"), the usual Japanese slang for running a command by hand.
[^tn-fujitsu-sun]: "富士通のSUN" refers to Fujitsu's role as a Japanese OEM/distributor of Sun Microsystems workstations. The phrase means a Sun machine supplied by Fujitsu.
[^tn-pc98lt]: The NEC PC-98LT (1986) was an early laptop in the PC-98 family. Here it served as a dumb console terminal for the dial-up server.
[^tn-manhole]: The source does not explain the legend. It refers to the well-known JUNET origin story of Jun Murai, then at Tokyo Tech, linking machines between campuses at the start of JUNET in 1984. Versions differ: [[The Internet - Nicopedia]] (translated from Nicopedia) describes an unauthorized cable run between Tokyo Tech and Keio. The "manhole" detail comes only from the author's memory here, and the physical details of the first link are disputed, so treat it as folklore unless corroborated.
