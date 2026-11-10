---
type: translation
language: en
source_site: nicopedia
source: "https://dic.nicovideo.jp/a/%E3%83%8B%E3%82%B3%E3%83%8B%E3%82%B3%E3%83%A0%E3%83%BC%E3%83%93%E3%83%BC%E3%83%A1%E3%83%BC%E3%82%AB%E3%83%BC"
topics:
  - "[[Niconico Hub|Niconico]]"
aliases:
  - "ニコニコムービーメーカー"
created: 2026-10-09
tags:
  - source/nicopedia
  - topic/niconico
---
# [Nico Nico Movie Maker](https://dic.nicovideo.jp/a/%E3%83%8B%E3%82%B3%E3%83%8B%E3%82%B3%E3%83%A0%E3%83%BC%E3%83%93%E3%83%BC%E3%83%A1%E3%83%BC%E3%82%AB%E3%83%BC)

- [[#Overview]]
- [[#Specifications]]
- [[#You Dare Call It Merely "Paper Theater"?]]
- [[#Vulnerabilities in Niconico (The "Holes" in the System)]]
- [[#Related Videos]]
- [[#Related Communities]]
- [[#See Also]]
- [[#Related Links]]
- [[#Footnotes]]

---

**NMM.exe** — **Nico Nico Movie Maker** (abbreviated as **NMM**) refers to:

1. A freeware software utility developed and distributed for free by **Internet Co., Ltd.** *(Documented in this article).*
2. A commercial paid software suite sold by Internet Co., Ltd. → **Nico Nico Movie Maker (Douga)**.

---

## Overview

NMM was a software tool designed to easily produce "paper-theater" (*kamishibai* / slideshow) videos by combining still images with audio tracks. Completed projects could be uploaded directly to Niconico Douga from within the software interface. Videos uploaded via this method were assigned a unique **`nm`** prefix in their video ID URL, distinguishing them from standard video IDs (which begin with `sm` or the legacy `fz`).

Unlike ordinary uploads encoded in FLV or MP4 video container formats, files produced by NMM were uploaded as raw **`.swf` files (Flash animations)**. As of October 2008, NMM was celebrated as the single tool capable of publishing **the cleanest, highest-fidelity static images** to Niconico Douga without compression degradation.

Furthermore, due to the inherent technical characteristics of the SWF format, a slideshow-style video composed of vector or static images typically had a dramatically smaller file size than an equivalent MP4 or FLV video stream. Because the visual track consumed so little data, creators could allocate almost their entire upload bitrate budget to high-fidelity audio—making NMM an immensely popular choice for publishing original songs, Vocaloid tracks, and music podcasts.

On December 4, 2008, at *Nico Nico Daikaigi 2008 Winter*, a commercial paid edition called **"Nico Nico Movie Maker (Douga)"** was unveiled, adding support for actual video clips, custom *Nicowari* interstitial banners, and `@BGM` background audio layering.

Following a major platform specification update on June 18, 2015, Niconico permanently discontinued the submission of new videos in the `.swf` format. [1] In accordance with this change, public distribution of the free Nico Nico Movie Maker software ceased at the end of May 2015. [2]

*(Note: Starting in April 2018, all legacy `.swf` format videos hosted on Niconico Douga were automatically transcoded on the backend into standard `.mp4` video files).* [3]

---

## Specifications

- **Frame Limit:** Due to Adobe SWF engine constraints, the maximum duration of an animation was capped at **16,000 frames**.
  - Since Niconico's internal video backend (SMILEVIDEO) operated at 25 frames per second (fps), the maximum runtime was:  
    $$16,000 \div 25 = 640\text{ seconds} \approx 10\text{ minutes and } 40\text{ seconds}.$$
- **Platform Incompatibility:** Because videos were rendered as Flash SWF objects, they could not be played back on mobile feature phones (*Niconico Mobile*).
- **Download Restrictions:** Legacy Niconico browser extensions and downloader utilities could only save these files in their raw `.swf` format.  
  - For offline playback or conversion, the most reliable workaround was recording the screen using local capture software.

### Enhancements Introduced in Niconico Douga (Autumn)

With the release of the *Niconico Douga (Autumn)* platform update in October 2008, several key features were implemented: [4]
- Direct uploading of standalone `.swf` files via the Nico Nico Movie Maker gateway was officially enabled.
- Implemented compatibility with the new "User Nicowari" feature, allowing users to produce custom commercial/interstitial video banners in the dedicated 544×55 pixel banner format.
- An official dedicated "NMM Video Ranking" leaderboard was established on the Nico Nico Movie Maker website.

---

## You Dare Call It Merely "Paper Theater"?

> *"It's called 'Movie Maker,' yet all it can produce is a static picture slideshow!"*

*Oh, really?*

Do not underestimate the power of "paper theater." Seeing is believing.

### The True Potential of NMM
A single groundbreaking video revolutionized how the community viewed Nico Nico Movie Maker:

*[Embedded Content]*

Indeed. The ability to arrange sequential still images meant that creators could produce **fluid, hand-drawn animations using the mechanics of a traditional flipbook!** 

Furthermore, because the medium was raw SWF, there were zero video compression artifacts or pixelation blur. Because the video file size was virtually nonexistent, creators could maximize the audio bitrate to pristine, audiophile-grade levels. While the sheer manual labor made NMM ill-suited for full-length feature films, for short indie animations, NMM was not just viable—it actually offered a massive visual and acoustic advantage over conventional video codecs.

With that, creators demonstrated that boundless artistic possibilities existed through sheer ingenuity.

### Winning with Pure Wit and Direction
Flipbook animation was not the only way creators unlocked NMM's potential:

*[Embedded Content]*

If the tool allowed on-screen captions (*telop*), creators could triumph purely through comedic writing, witty storytelling, and clever kinetic typography!

### The Most-Viewed NMM Video of All Time (As of January 2013)

*[Embedded Content]*

Why choose between wit and technique when you can pour both into a single masterpiece?

---

## Vulnerabilities in Niconico (The "Holes" in the System)

### Monument #1: An Interactive Game Inside Niconico Douga
In early 2008, a clever uploader exploited an oversight between Nico Nico Movie Maker and Niconico's backend upload filter. Noticing that NMM uploaded raw `.swf` files, the uploader (*up-nushi*) injected custom interactive **ActionScript** code into an SWF and bypassed the validation checks.

The result was an **interactive Flash video game playable directly inside the Niconico Douga video player**.

Dwango's engineering team patched the security vulnerability immediately. However, recognizing it as a historic and monumental work demonstrating the untapped frontier of interactive video, management **chose not to delete the video**, preserving it permanently on the servers.

*[Embedded Content]*

This incident proved that Niconico Douga possessed the technical architecture to support embedded Flash gaming. *(For details, see the video commentary article for `nm2540850`).*

---

### Monument #2: The Total Collapse of Niconico Douga
When the *Niconico Douga (Autumn)* update officially permitted `.swf` uploads through NMM, an uploader discovered a method to execute external **JavaScript** calls from within the Flash container—a classic Cross-Site Scripting (XSS) exploit.

Dwango patched the critical security flaw instantly. Yet once again, because the upload brought genuine laughter, awe, and creative inspiration to both the community and the engineering staff, Dwango officially ruled to leave the video untouched as a beloved historical monument.

*[Embedded Content]*

Upon clicking the on-screen switch inside the video player, **the HTML components of the actual Niconico Douga webpage collapsed and crashed down with real-time 2D physics!** To make matters even more impressive, the fallen buttons, search bars, and logo fragments could be grabbed, dragged, and hurled across the browser window with the user's mouse cursor. *(For details, see the video commentary article for `nm4801333`).*

---

## Related Videos
*[Embedded Content]* *[Embedded Content]* *[Embedded Content]* *[Embedded Content]*

## Related Communities
*(Nicovideo Community services permanently ended in August 2024).*

---

## See Also

- Nico Nico Movie Maker (Douga)
- Kamishibai Creator
- SWF
- ActionScript

## Related Links
- [Official Nico Nico Movie Maker Product Page (Internet Co., Ltd.)](https://www.ssw.co.jp/)

---

## Footnotes

1. *Notice of Partial Feature Sunset: SWF Video Submissions, Nicoru, and Speed Checker Terminated* (June 18, 2015)
2. *Niconico Douga Official Video Authoring Tool: Nico Nico Movie Maker* – Internet Co., Ltd.
3. *[Updated 4/10] Transcoding Legacy Video Formats into Modern Standards to Expand Viewing Environments* (April 10, 2018)
4. *Niconico News: Major NMM Version Upgrade Adds Native SWF Support and Features* (October 2008)

---
- **Article ID:** 1252
- **First Created:** 08/05/15 23:00
- **Revision Number:** 3300170
- **Last Updated:** 24/09/05 04:48
- **Revision Comment:** Removed defunct related commercial merchandise link

---

## Cultural Context & Terminology Guide: Nico Nico Movie Maker (NMM)

- **Internet Co., Ltd. (株式会社インターネット):**  
  Vocaloid fans know Internet Co., Ltd. as the prominent developer of legendary Vocaloid voicebanks such as **Gackpoid (Kamui Gakupo)**, **Megpoid (GUMI)**, **Lily**, and **Otomachi Una**.  
  However, Internet Co., Ltd. was originally an established Japanese music and multimedia software company (creators of the *Singer Song Writer* DAW and the *Sound It!* audio editor). Because of their close technical relationship with Dwango and audio processing expertise, Dwango contracted them to develop the official freeware movie-making tool for Niconico users.
- **The Meaning of Video ID Prefixes (`sm`, `nm`, `so`):**  
  Every video on Niconico Douga is identified by a unique alphanumeric ID in its URL:
  - **`sm` (SMILEVIDEO):** Standard video files (FLV, MP4) uploaded through the main website. The vast majority of videos on Niconico carry an `sm` ID (e.g., `sm9`).
  - **`nm` (Nico Nico Movie Maker):** Videos uploaded directly through NMM as `.swf` files. Whenever users saw an `nm` ID, they immediately knew the video was either an audio-focused track, a podcast, or an illustrated slideshow.
  - **`so` (SMILE Official):** Official commercial uploads from corporate channels, anime licensors, or media partners.
- **"Kamishibai" (紙芝居 - Paper Theater / Picture Story):**  
  *Kamishibai* is a traditional form of Japanese street theater dating back centuries, popularized in the 1930s, where an itinerant narrator slid painted paper cards in and out of a wooden miniature stage while telling a story. On Niconico, "kamishibai" became the standard slang for videos consisting purely of static 2D illustrations accompanied by voice acting or music (the dominant format for early indie Vocaloid ballads and visual novel parodies).
- **Why Flash (.swf) Mattered for Early Audio Quality:**  
  In 2007–2009, server bandwidth was scarce. When users uploaded standard FLV or MP4 video files, Niconico's backend compression engine heavily re-encoded both video and audio, crushing sound quality into muffled low bitrates.  
  However, an NMM `.swf` file did not contain an encoded raster video stream; it only contained a lightweight static image and a raw, uncompressed audio file. Because Niconico did not re-encode `.swf` files, music producers and Vocaloid tuners could achieve crystal-clear 320 kbps audio quality, turning NMM into an unexpected weapon for music uploaders.
- **"Up-nushi" (うｐ主 / う主):**  
  Ubiquitous Japanese internet slang meaning **"the uploader"** or original poster (OP). When typing the English word "up" on a Japanese keyboard set to Hiragana input mode, the keys `u` and `p` output the characters **うｐ** (*upu*). Adding the kanji **主** (*nushi*, meaning master, host, or owner) created the slang *up-nushi*.
- **"Nicowari" (ニコ割):**  
  A built-in feature introduced during Niconico's early years where an interstitial video clip or a narrow bottom banner (544×55 pixels) would interrupt playback to display a public time chime, site announcement, or commercial. NMM allowed users to design their own "User Nicowari" banners to insert customized comedic gags or creator credits into their videos.
- **The "Historic Monument" (記念碑) Tradition:**  
  In Western web development, exploiting an upload filter to execute arbitrary ActionScript or inject malicious Cross-Site Scripting (XSS) would result in an immediate permanent ban, legal warnings, and the total scrubbing of the files.  
  Early Dwango culture, however, was run by eccentric, anti-authoritarian engineers. When uploaders discovered security holes to build a playable browser game (`nm2540850`) or make the entire Niconico website collapse into a physics sandbox (`nm4801333`), Dwango patched the code vulnerability but deliberately **left the infringing videos online permanently**. They officially designated them "Monuments" (記念碑) celebrating user ingenuity and hacker humor.
- **Telop (テロップ):**  
  A Japanese television broadcast loanword (derived from the *Television Optical Projector*) used to refer to on-screen text overlays, subtitles, captions, and kinetic typography. Many famous early Niconico comedy videos had no animation at all, relying entirely on rapid-fire, stylized *telop* text synced to music.