---
type: translation
language: en
source_site: nicopedia
source: "https://dic.nicovideo.jp/a/%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%8D%E3%83%83%E3%83%88"
topics:
  - "[[Niconico Hub|Niconico]]"
aliases:
  - "インターネット"
created: 2026-10-09
tags:
  - source/nicopedia
  - topic/niconico
---
# The Internet (インターネット)

- [[#The Global Internet]]
  - [[#Overview]]
  - [[#History]]
- [[#The Japanese Internet]]
  - [[#Summary in Three Lines]]
  - [[#Chronological History]]
  - [[#Internet Exchanges (IX)]]
  - [[#Physical Cable Infrastructure]]
  - [[#Root Name Servers]]
  - [[#The Future of the Japanese Internet]]
  - [[#Everyday Examples of Internet & IP Technology in Japan]]
  - [[#Media, Communication, and Regulatory Debates]]
- [[#Related Videos & Broadcasts]]
- [[#See Also]]
- [[#Related Links & Footnotes]]

---
## The Global Internet

### Overview

> *A nostalgic kindergartener: "What a boring world..."*

Etymologically, "internet" comes from *internetwork* (a network connecting networks together). In practice, it almost universally denotes **the Internet**—the world’s largest decentralized computer network. In other words, the "Internet" we use daily is a proper noun denoting a single, planetary-scale internetwork cooperatively managed by users across the globe.

Unlike early PC dial-up BBS networks (*pasokon tsūshin*), where a single central host computer served all users, the Internet is made possible by routers and servers operated independently by decentralized Autonomous Systems (AS) worldwide. Regional Internet Registries (NICs)—such as JPNIC in Japan—allocate and manage critical resources including IP addresses and Autonomous System Numbers. Today, communication relies predominantly on the standardized TCP/IP protocol suite, allowing connectivity from a vast spectrum of devices.

The submarine communications cables powering intercontinental traffic make landfall at only a handful of strategic coastal stations worldwide. In Japan, the vast majority of these undersea cables land along the coast of Chiba Prefecture. Tokyo serves as one of the world's premier traffic hubs, with the majority of trans-Pacific routing passing through Japan, making the country a vital node in global network topology.

### History

During the Cold War, the U.S. Air Force commissioned the RAND Corporation to study survivable command-and-control communications architectures capable of withstanding enemy nuclear strikes. In response, Paul Baran formulated the concept of distributed packet switching, where packets autonomously navigate decentralized routes to reach their destinations [1]. This architecture formed the foundation of **ARPANET**, developed by the Advanced Research Projects Agency (DARPA).

In 1986, **NSFNET** was established as an academic research backbone network, splitting off from ARPANET. Modeled after ARPANET, NSFNET operated over TCP/IP and associated protocols. Because it was funded by the U.S. government, it enforced an Acceptable Use Policy (AUP) prohibiting commercial use, preventing private corporations from freely leveraging it for profit.

Meanwhile, in Japan, 1984 marked the birth of **JUNET**—initially linking Keio University, Tokyo Institute of Technology, and the University of Tokyo—which gradually expanded to interconnect academic and corporate research labs nationwide, becoming the progenitor of the Japanese Internet.

In 1991, Tim Berners-Lee at CERN announced the **World Wide Web (WWW)** project, conceiving the fundamental building blocks of today's Web: HTTP, URIs, and HTML.

In its infancy, Internet access was strictly confined to participating universities and enterprise research labs; private residential access was nonexistent. That changed in 1993 with the advent of commercial Internet Service Providers (ISPs). By dialing into an ISP access point via telephone lines, ordinary households could access email, Usenet (NetNews), and the WWW.

Commercial Internet operations launched in earnest in Japan in November 1993 with the country's first commercial ISP. In the United States, commercialization also accelerated, culminating in 1995 when NSFNET decommissioned its public backbone, handing internet governance and infrastructure over to the private sector. The browser revolution arrived in 1993 with NCSA Mosaic, followed in 1994 by Netscape Navigator, the defining web browser of the 1990s.

Previously, getting online required complex manual TCP/IP stack configurations on platforms like Windows 3.1. The 1995 release of Microsoft **Windows 95**, which included native support for PPP dial-up networking out of the box, catalyzed mainstream explosive adoption.

Throughout the 1990s, dial-up via landline telephone circuits was the dominant connection method. However, users were billed by the minute for phone calls, and speeds were abysmally slow (topping out at 56 kbps on analog modems). This led to massive popularity for NTT’s **Telehodai** (*テレホーダイ*), a flat-rate service for dial-up calls placed during late-night hours. Every night at 11:00 PM, an enormous spike in network traffic caused severe congestion, often making it difficult to connect to the Internet or place standard phone calls.

Around the year 2000, broadband ADSL began rolling out, making always-on, high-speed, affordable connectivity standard. By 2001, fiber-optic services (FTTH) launched, kicking off Japan's modern gigabit era.

---

## The Japanese Internet

### Summary in Three Lines

- **Origin:** A mutual-aid network built by academic hobbyists.
- **Culture:** Highly anonymous, driven by the distinct Japanese pastime of *makaizou* (taking existing tech and radically modding/bastardizing it).
- **Vibe:** It was a chaotic mystery stew (*yaminabe*) in the past; it remains a chaotic mystery stew today.

---

### Chronological History

*(Honorifics omitted for historical figures.)*

- **September 1984:**  
  The birth of the Japanese Internet begins with **JUNET**. Operating on a UUCP store-and-forward "bucket brigade" mechanism, JUNET was founded when Jun Murai, then an assistant at Tokyo Institute of Technology, illicitly ran an underground communications cable between Tokyo Tech and his former workplace at Keio University without regulatory authorization.  
  The University of Tokyo joined in October 1984, transforming it into a full experimental research network.  
  *(Note: At the time, prior to the privatization of Nippon Telegraph and Telephone Public Corporation into NTT in April 1985, running private communications lines was strictly illegal under telecommunications monopoly laws. Murai was severely reprimanded by authorities on multiple fronts.)*

- **January 1986:**  
  JUNET connects to the American academic network CSNET via UUCP. International email transmission becomes possible, and eventually nearly 500 organizations link into JUNET.

- **August 2, 1988:**  
  After enlisting NTT engineers to repeatedly debug cross-Pacific TCP/IP transfers, **the first successful IP packet transmission between Japan and the United States is achieved on August 2, 1988.** This marks the official birthday of Japan’s connection to the international Internet.  
  During the testing phase, a major crisis occurred: endless packet routing experiments ran up an international phone bill exceeding **3,000,000 yen** in a single month (~$25,000 USD), triggering absolute panic among the academic admins. Data overage panics existed from day one.  
  To foot the bill, the team hurriedly enlisted private corporations to pool funds under the guise of "joint corporate research." This consortium was named the **WIDE Project**, and its network was christened the **WIDE Internet**. Traumatized by the astronomical phone bill, the team spearheaded efforts to lay a dedicated trans-Pacific leased line.

- **January 1989:**  
  The WIDE Project establishes a dedicated 64 kbps leased line connection to the U.S. via Hawaii.

- **April 1989:**  
  International Telecom Japan (ITJ, later absorbed into KDDI) launches commercial international leased-line services.

- **September 1989:**  
  The WIDE Internet initiates formal IP routing between Japan and the U.S., marking the official inauguration of Japan's internationally routable Internet.

- **1991:**  
  **JPNIC** is founded as a voluntary association (later incorporated), inheriting IP address and `.jp` domain registry management from JUNET.

- **October 1991:**  
  JUNET is formally dissolved, having fulfilled its role.

- **December 3, 1992:**  
  Members of the WIDE Project establish Internet Initiative Planning Co., Ltd. (later **IIJ**) to operate a commercial ISP.

- **November 1993:**  
  IIJ begins commercial Internet connectivity operations. The dawn of private, commercial ISP services in Japan begins.

- **March 1994:**  
  **NSPIXP-1**, Japan's first Internet Exchange (IX), is established by the WIDE Project in the basement of **Iwanami Shoten** (a venerable academic publishing house) in Jimbocho, Tokyo.  
  The IX was placed inside a book publisher because traditional university faculty vehemently resisted interconnecting academic networks directly with commercial entities. Jun Murai reportedly bypassed their objections with the brazen sophistry:  
  > *"Iwanami Shoten is totally fine! After all, they're academic!"*  
  NSPIXP-1 remained operational in the basement of Iwanami Shoten until it was decommissioned in 1999.

- **June 1994:**  
  Multiple ISPs (such as GOL and ASAHI Net) commence consumer operations. Early flat-rate dial-up options emerge, laying the groundwork for widespread household adoption.

- **October 1994:**  
  Netscape Navigator is released.

- **1995:**  
  Windows 95 goes on sale. Consumer internet adoption explodes. Dial-up PC networks (*pasokon tsūshin* like NIFTY-Serve), telcos, and internet backbones rapidly interconnect.

- **1995:**  
  The textboard BBS **Ayashii World** (*あやしいわーるど*, "Suspicious World") is established by administrator "Shiba." The platform sees explosive user growth following the Tokyo subway sarin attack carried out by the Aum Shinrikyo cult. Originating on NIFTY-Serve's closed "Home Party" service, it migrated to the open Internet using custom scripts like *Kuzuha Script*.  
  Ayashii World established core hallmarks of Japanese anonymous net culture: **ROMing** (*Read-Only Member* / lurking), posting without a handle (anonymous posting), and **Shift-JIS ASCII Art**. It remains the stylistic ancestor of all modern Japanese textboards.

- **August 5, 1997:**  
  The BBS **Amezou** (*あめぞう*) opens, introducing the "thread-floating" (bump) board architecture to Japan. Following the collapse and closure of original Ayashii World boards, refugee users migrated here.

- **April 1999:**  
  The WIDE Project establishes an **IPv6 Working Group**. Japan assumes an early, pioneering role in drafting, testing, and standardizing IPv6 specifications globally.

- **May 1999:**  
  Conceived originally as a backup mirror for Amezou, **2channel** (*2ちゃんねる*) is founded by **Hiroyuki Nishimura**.

- **March 2000:**  
  The WIDE Project completes IPv6 field verification, dissolving the working group upon finalizing core standards.

- **September 2000:**  
  The Japanese government announces the **e-Japan Strategy** and enacts the IT Basic Law (promoting high-speed broadband to public facilities, school IT education, e-government, telecommunications/broadcasting convergence, and national internet exhibitions).

- **December 31, 2000:**  
  The Economic Planning Agency launches **Inpaku** (*インターネット博覧会 / Internet Fair 2001*), a government-sponsored online fair that ran for an entire year.

- **August 2001:**  
  **Futaba Channel** (*ふたば☆ちゃんねる*) is launched as an imageboard spin-off refuge during major 2channel server crises.

- **October 2003:** *(Listed as August 2001 in original text)*  
  Adopting Futaba Channel's open-source PHP script (*Futaba Script / GazouBBS*), Christopher Poole ("moot") launches **4chan** as an English-language Futaba clone, giving birth to Western imageboard culture and Anonymous.

- **October 5, 2001:**  
  Outraged by the toxicity and sockpuppetry of 2channel, Kazuhiko Nishi (co-founder of ASCII Corporation) establishes **1ch.tv**, aiming to create a "kind, wholesome BBS free from self-staged manipulation." *(The experiment devolved into a spectacular flame-war disaster; see the dedicated 1ch.tv article for the full cautionary tale).*

- **April 2002:**  
  1ch.tv collapses and is downgraded to running on a personal home server.

- **December 12, 2006:**  
  **Nico Nico Douga (Kari)** begins experimental service. Its revolutionary hook is simple: overlaying user comments directly across the video canvas. Niwango, the operating subsidiary, names 2channel founder Hiroyuki Nishimura to its board of directors.

- **May 12, 2008:**  
  **Nico Nico Pedia** (*ニコニコ大百科*) launches.

- **March 11, 2011, 14:46:18 JST:**  
  **The Great East Japan Earthquake strikes.**  
  Seventeen minutes after the earthquake, a middle school student autonomously begins unofficially restreaming NHK’s television emergency broadcast over **Ustream**.  
  While Ustream Asia operators initially moved to shut down the unauthorized broadcast, they recognized that millions stranded without televisions desperately needed information and contacted NHK for retroactive permission. NHK promptly replied: *"Permission is granted via this email."* (At that moment, NHK's own web servers were crashing under load.)  
  Commercial networks (Fuji TV, TBS, TV Asahi) followed suit, and streaming portals—**Ustream, Yahoo! Japan, and Nico Nico Douga**—coordinated to relay emergency TV broadcasts nationwide in real time.  
  Ustream Asia CEO Tomotaka Nakagawa ordered staff to disregard operating costs entirely: *"Keep the stream online no matter what."*  
  This disaster marked the instant where the long-touted "convergence of the Internet and television" was realized out of sheer humanitarian necessity. People at their workplaces with access only to PC networks could follow live life-saving news. It also underscored the **innate physical disaster-resilience of the Internet**: despite catastrophic regional destruction, Japan's national Internet backbone stayed up right to the edge of IX saturation.

- **June 2012:**  
  Protesting Japan's new criminal penalties for copyright-infringing downloads, the hacktivist collective Anonymous launches distributed denial-of-service (DDoS) attacks knocking down the websites of the Ministry of Finance, the Liberal Democratic Party, and JASRAC.

- **July 2013:**  
  Revision of the Public Offices Election Act passes, legalizing digital and internet campaigning during elections.

- **April 2015:**  
  Meisei High School opens "Meisei Cyber Gakuen," Japan’s first accredited correspondence high school attended using 3D virtual avatars.

- **May 26, 2015:**  
  Revised Public Offices Election Act takes full effect for upcoming national parliamentary elections.

- **April 6, 2016:**  
  KADOKAWA-DWANGO establishes **N High School** (*N高等学校*), a fully accredited correspondence high school based in Uruma, Okinawa, leveraging digital platforms and Niconico's tech stack for distance learning.

- **April 14, 2016:**  
  The Kumamoto earthquakes occur. Japan's national internet backbone remains completely online, serving as an uninterrupted lifeline for emergency information.

- **April 1, 2016:**  
  Smart meters deploy across the national electrical power grid, operating over IP standards (Wi-SUN IP and ZigBee IP).

- **December 8, 2016:**  
  KDDI formally announces the acquisition of BIGLOBE, marking the corporate unification of a major mobile telco carrier with one of Japan’s foundational early dial-up PC network providers (PC-VAN).

---

### Internet Exchanges (IX)

An Internet Exchange (IX) is a physical interconnection facility where ISPs and content delivery networks exchange routing traffic—the crossroad intersections of the Internet. Major commercial IX facilities in Japan are heavily concentrated in **Tokyo and Osaka**. While government initiatives established regional IX points across provincial cities, network operators remain overwhelmingly concentrated in Tokyo, posing systemic continuity risks should a catastrophic disaster strike the capital.

### Physical Cable Infrastructure

To transmit data, physical lines must exist in the real world. Laying long-haul, high-capacity fiber cables requires dedicated rights-of-way. Consequently, Japan's backbones trace existing national infrastructure routes:

- **Terrestrial Telecom Networks:** The primary trunk routes of the former state monopoly, now NTT. They run along dedicated land easements and utility poles.
- **Expressway Rights-of-Way:** Fiber routes running along national expressways (operated by KDDI).
- **Coastal Undersea Fiber:** Submarine fiber lines circling the Japanese coastline (formerly NTT, now KDDI).
- **Railway Corridors (including Shinkansen routes):** Dedicated communications lines laid alongside Japan Railways tracks (originally owned by Japanese National Railways / Japan Telecom; now the primary backbone of SoftBank).
- **River and Highway Corridors:** Fiber lines laid along rivers and public roads by the Ministry of Land, Infrastructure, Transport and Tourism for civil management, progressively leased out to commercial carriers.

### Root Name Servers

The WIDE Project operates the **M-Root Server**, one of the world's 13 root DNS server clusters. Because an authoritative root server is hosted domestically, Japanese networks can technically resolve domain names internally even if all transoceanic international submarine cables were severed simultaneously. While primary M-Root operations are anchored in Tokyo, an active redundant mirror operates in Osaka, ensuring continuity even if the capital goes dark. This redundancy was critical in keeping domestic internet services functioning during the 2011 Tohoku earthquake.

---

### The Future of the Japanese Internet

Japan has contributed directly to foundational Internet architecture since its inception, as seen in its pioneering leadership in IPv6 deployment through the WIDE Project. Japan's extraordinarily dense population per square kilometer has also fueled exceptionally rapid technological penetration.

Japan entered severe demographic aging and population decline around 1989, coinciding with the collapse of the economic bubble. This timeline aligns closely with the spread of the commercial Internet and IP-based automation (e.g., automated redelivery scheduling for courier packages, migration from physical postal mail to email). In many ways, network technology and automation have cushioned the impact of a shrinking national workforce. As labor constraints intensify, the Internet will only grow in importance as a critical testbed for resilient, automated societal infrastructure.

### Everyday Examples of Internet & IP Technology in Japan

Below is an overview of systems operating over the Internet and IP protocols across Japanese society:

- Building automation and HVAC control
- Remote security and alarm management (SECOM, ALSOK)
- Remote elevator maintenance telemetry
- Landline VoIP networks
- Connected automated vending machines
- Corporate web portals & online banking
- Railway signaling and train dispatch control
- Smartphones & cellular core networks
- Regional telemedicine networks
- E-commerce and logistics routing
- Local Government Wide Area Network (LGWAN)
- Municipal and Kasumigaseki government LANs
- Automated courier package redelivery systems (Yamato Transport NEKO System)
- Smart electrical grid meters (Wi-SUN IP)
- Convenience store POS and inventory terminals
- PNET (Postal Integrated Information Network)
- Meteorological AMeDAS weather tracking
- Contactless smart transit cards (Suica, PASMO)
- Crowdfunding & IoT devices
- Japan Self-Defense Forces (JSDF) networks

*(Note: The JSDF Defense Information Infrastructure [DII] partitions open administrative systems—which connect to the public Internet—from classified operational combat systems, which operate on an air-gapped, isolated network).*

---

### Media, Communication, and Regulatory Debates

From illegal file sharing to the rise of clandestine middle/high school gossip boards (*gakkō ura-saito*), the Internet's evolution as a mass-communication medium has repeatedly triggered calls for state regulation.

However, the Internet's technical architecture is inherently resistant to centralized censorship. Under Japan's **Telecommunications Business Act (Article 4)**, the "Secrecy of Communications" (*tsūshin no himitsu*) is strictly protected; intercepting, inspecting, or tampering with user packet payloads is legally classified as unlawful wiretapping. Furthermore, government pre-screening of content violates constitutional bans on censorship. Any content moderation must therefore rely strictly on voluntary, terms-of-service compliance by private operators. 

Legal interpretations regarding the boundaries of telecom privacy have undergone continual renegotiation between the government, ISPs, and legal scholars—particularly concerning piracy blocking—demanding careful vigilance to prevent state overreach into digital speech.

---

## Related Videos & Broadcasts

*(Embedded Content)*

---

## See Also

### Core Networking & Infrastructure
- World Wide Web
- TCP/IP / IP Address / IPv6 / DNS
- Internet Service Provider (ISP) / Dial-up / Pasokon Tsūshin
- ISDN / ADSL / FTTH
- JUNET / WIDE Project / JPNIC
- Jun Murai (*The Father of Japan's Internet*)
- Internet Exchanges (IX) / Remote Host
- Telehodai (*NTT's late-night flat-rate dial-up service*)

### Japanese Message Boards & Culture
- BBS Culture
  - Ayashii World (*あやしいわーるど*)
  - Amezou (*あめぞう*)
  - 2channel (*2ちゃんねる*)
  - Futaba Channel (*ふたば☆ちゃんねる*)
  - 4chan / Anonymous
  - 1ch.tv
- Net Slang / ASCII Art / Internet Memes
- Net Literacy / Media Literacy
- Net de Shinjitsu (*"Finding the 'Truth' on the Internet"*)
- Inpaku (*Internet Fair 2001*)
- School Ura-Sites (*Unofficial student gossip boards*)
- Makaizou (*Radical modding / bastardization*)
- Yaminabe (*Mystery hotpot stew*)

### Society & Industry
- Internet Co., Ltd. *(Vocaloid engine developer)*
- Telecommunications Business Act
- Ministry of Internal Affairs and Communications (MIC)
- Ministry of Economy, Trade and Industry (METI)
- Great East Japan Earthquake (3/11)

---

## Related Links & Footnotes

- [WIDE Project Official Site](http://www.wide.ad.jp/)
- [JPNIC (Japan Network Information Center)](https://www.nic.ad.jp/)

---

## Cultural Context & Slang Guide

### 1. Jun Murai (村井純): The "Father of the Japanese Internet"
Jun Murai is universally recognized as the central architect of Japan's network infrastructure. In 1984, before state telecommunications monopoly laws were dismantled, he strung an unauthorized physical cable between Keio University and Tokyo Tech, launching **JUNET**. He subsequently founded the **WIDE Project** (which continues to manage Japan's M-Root DNS server today). Murai is celebrated for his pragmatic, slightly rebellious approach to early networking—exemplified by secretly installing Japan's first commercial Internet Exchange (NSPIXP-1) inside the basement of a prestigious Tokyo literary publisher (*Iwanami Shoten*) to bypass academic anti-commercialization rules.

### 2. "Telehodai" (テレホーダイ) & 1990s Dial-Up Culture
Before flat-rate broadband, Japanese residential dial-up was billed by the minute like regular telephone calls. In 1995, NTT launched **Telehodai**, a subscription service providing unmetered calls to two designated phone numbers between **11:00 PM and 8:00 AM**. 
This gave birth to a distinct nocturnal internet subculture: 
- Tens of thousands of users waited until exactly 11:00:01 PM to dial their ISPs, causing massive nationwide phone gridlock every single night.
- Early Japanese textboards, web novel sites, and chat rooms saw their traffic peak exclusively past midnight, fostering a community of sleep-deprived night owls.

### 3. The Lineage of Anonymous Japanese Textboards
The article charts the direct genealogical tree of modern textboards and anonymous online forums:
1. **Ayashii World (あやしいわーるど, *1995*):** The undisputed cradle of Japanese anonymous culture. It introduced posting without handles (nameless posting), Shift-JIS ASCII Art, and the concept of **"ROM"** (*Read-Only Member*, meaning to lurk quietly before daring to post).
2. **Amezou (あめぞう, *1997*):** Invented the "thread-floating" (bump) board mechanism, where active threads with new replies rise to the top of the index.
3. **2channel (2ちゃんねる, *1999*):** Created by Hiroyuki Nishimura as an alternate refuge when Amezou suffered server crashes. It grew into the largest forum in Japan and the definitive wellspring of 2000s Japanese internet slang.
4. **Futaba Channel (ふたば☆ちゃんねる, *2001*):** Created when 2channel faced catastrophic collapse; it combined anonymous posting with image uploads, pioneering the modern anime imageboard.
5. **4chan (*2003*):** Created when American teenager Christopher Poole ("moot") translated Futaba Channel’s open-source script into English.

### 4. "Makaizou" (魔改造) and "Yaminabe" (闇鍋)
- **Makaizou (魔改造):** Originally an otaku garage-kit term meaning "demonic modification" (taking a commercial anime figure and heavily kitbashing or altering it, often into an explicit or absurd state). In internet parlance, it refers to the Japanese cultural habit of taking foreign systems, technologies, or software, radically altering their internal mechanisms, and turning them into something eccentric, hyper-specialized, and completely distinct from the original design.
- **Yaminabe (闇鍋):** A traditional Japanese party game where guests sit in a pitch-black room and toss bizarre, mystery ingredients into a shared hot pot, forced to eat whatever they scoop out. It is a universal Japanese internet metaphor for a lawless, chaotic, uncurated digital space where high-brow academic discourse, vulgar shitposting, avant-garde art, and dangerous hoaxes simmer together in the same pot.

### 5. "Net de Shinjitsu" (ネットde真実)
Literally *"Finding the Truth via the Internet"*. A pervasive satirical meme on 2channel and Niconico used to mock naive users who read a single conspiracy blog, fringe forum post, or YouTube video and suddenly declare: *"The mainstream media is lying to us! I have discovered the real truth on the Internet!"* It serves as shorthand for online radicalization and media illiteracy.

### 6. "School Ura-Sites" (学校裏サイト)
Literally *"Unofficial School Back-Channels."* In the mid-2000s, with the rapid adoption of feature-phone web capabilities (i-mode) among teenagers, Japanese middle and high school students began creating thousands of mobile forums dedicated to specific schools. These unmoderated boards gained nationwide notoriety as notorious hotspots for vicious cyberbullying, teacher slander, and teen drama, sparking a moral panic and intense public debate over youth internet filtering and regulation.

### 7. Connection to Vocaloid: Internet Co., Ltd. (株式会社インターネット)
The disambiguation at the very beginning mentions **Internet Co., Ltd.** For Vocaloid enthusiasts, this company is legendary. Founded by Noboru Murakami in Osaka in 1988, they are the developer behind some of the most influential Vocaloid soundbanks in history, including:
- **Gackpoid (Camui Gackpo)** (voiced by visual kei icon GACKT)
- **Megpoid (GUMI)** (voiced by Megumi Nakajima, the voice behind *Macross Frontier's* Ranka Lee)
- **Otomachi Una**
- **Lily** and **CUL**