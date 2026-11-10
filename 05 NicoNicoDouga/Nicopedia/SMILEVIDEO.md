---
type: translation
language: en
source_site: nicopedia
source: "https://dic.nicovideo.jp/a/smilevideo"
topics:
  - "[[Niconico Hub|Niconico]]"
created: 2026-10-09
tags:
  - source/nicopedia
  - topic/niconico
---
# SMILEVIDEO

> Original Source: [SMILEVIDEO - ニコニコ大百科 (Nico Nico Pedia)](https://dic.nicovideo.jp/a/smilevideo)

- [[#Overview]]
- [[#Development History]]
- [[#Service Timeline]]
- [[#Deletion & Moderation Status]]

**SMILEVIDEO** was a dedicated video hosting and upload platform formerly operated by Niwango, Inc. specifically for Nico Nico Douga. 
The service has since been fully integrated into the main Nico Nico Douga platform, and SMILEVIDEO as a standalone entity has ceased operation.  

---

## Overview

During Nico Nico Douga’s early Beta era, the service relied on YouTube as its video delivery infrastructure. 
After YouTube banned Nico Nico Douga from accessing its servers, SMILEVIDEO was hastily constructed immediately prior to the launch of Nico Nico Douga (γ).  
Legend has it that the system was brought online in an astonishingly short development window because it was built directly on top of a personal hobby project that a Dwango engineer happened to be tinkering with at the time.

---

## Development History

On February 23, 2007, because Nico Nico Douga was generating immense traffic and straining YouTube's servers, YouTube blocked all incoming requests from Nico Nico via HTTP referrer, rendering nearly every video on the platform instantly unplayable. 
While Dwango’s management had anticipated that an access block would happen eventually, it arrived far sooner than expected.
On the very day the block took effect, an emergency meeting titled the *"Let’s Build a Video Upload Site in One Week Kickoff"* was convened. 
Naturally, building a full-fledged video hosting site capable of matching YouTube’s scale in a mere seven days seemed virtually impossible.
However, a Dwango contract engineer happened to be building his own video-sharing platform purely for fun—with immaculate timing. 
The team resolved to use his personal prototype as the foundation for their new hosting service. The name "SMILEVIDEO" was chosen entirely on a whim during the meeting, much like the name "Nico Nico Douga" itself.
Ultimately, SMILEVIDEO was completed in roughly four days—comfortably beating the one-week deadline—and Nico Nico Douga made its triumphant revival.

### Site Integration

With the release of the "Nico Nico Douga (Harajuku)" version update, SMILEVIDEO’s standalone operations came to an end after 3 years, 8 months, and 9 days, as it was fully merged into the main Nico Nico Douga site.
Originally, the two platforms were kept as separate entities for several strategic reasons: it provided legal insulation against copyright lawsuits (separating the comment overlay system from the video host itself), and it kept the door open for Nico Nico to potentially piggyback on other third-party video hosts if needed.
The eventual decision to unify the sites was driven by major shifts in the ecosystem surrounding Nico Nico Douga:

- Dwango had successfully built one of Japan's largest domestic content delivery networks (CDNs), eliminating the need to rely on external infrastructure.
- The platform’s user base and library of user-uploaded videos had grown to a scale where outside hosting was no longer necessary.
- The company had established cooperative agreements with copyright collectives such as JASRAC, allowing them to handle rights clearance through proper legal frameworks rather than relying on loopholes to dodge litigation. (Put another way: the platform had grown too prominent for legal workarounds to remain socially acceptable.)
- The community's dominant content had transitioned away from high-liability *maruage* (raw, pirated television re-uploads) toward original user-created works and MAD remixes; furthermore, full anime series began receiving official, licensed distribution on the platform.

...Or so the theory goes. Then again, maybe none of that was the reason at all.

---

## Service Timeline

| Date | Milestone |
| :--- | :--- |
| **Feb 24, 2007** | Announced commitment to build an in-house video upload system, codenamed "SMILE (provisional)", within one week. |
| **Feb 28, 2007** | Acquired domain name, licenses, etc. |
| **Mar 6, 2007** | Launched alongside Nico Nico Douga (γ). Storage quota: 100 MB; no bitrate limit. |
| **Mar 8, 2007** | Storage quota increased to 200 MB; FLV files capped at 40 MB per upload. |
| **Mar 9, 2007** | Introduced a 600 kbps bitrate cap on FLV files. |
| **Mar 16, 2007**| Video delivery backend upgraded. |
| **Mar 28, 2007**| Server infrastructure expanded. |
| **?** | Added custom thumbnail frame-selection feature. |
| **?** | User storage quota expanded to 2 GB. |
| **Jun 18, 2007**| Premium Membership launched; Premium users received an upgraded 4 GB quota. |
| **?** | Various other changes (forgot what they were). |
| **Mar 5, 2008** | Storage quota raised to 8 GB. Added support for MP4 (AVC/H.264) video. Bitrate cap for FLV and MP4 raised to 800 kbps (Premium members only). |
| **Jul 5, 2008** | Ver. 1.2.1: Free users gained H.264 upload support (capped at 600 kbps). |
| **?** | Various odds and ends (forgot). |
| **Aug 1, 2008** | Ver. 1.3.1: Added integration with Nico Ni Commons. |
| **Dec 12, 2008**| Ver. 1.4.0: Premium upload cap raised to 1,000 kbps / 100 MB for FLV and MP4. Visual redesign rolled out for improved usability. |
| **Dec 22, 2008**| Ver. 1.4.1: Added video sorting features. |
| **Oct 29, 2009**| Ver. 1.4.2: Bitrate and resolution limits removed entirely for Premium member uploads. |
| **Feb 4, 2010** | Ver. 1.9.1: Allowed users to fill in title/video details prior to server-side encoding. |
| **Apr 21, 2010**| Ver. 1.9.2: Maintained Premium subscriptions now granted effectively unlimited storage. |
| **Jul XX, 2010**| Ver. 2.0.0: Major overhaul of UI and site design. |
| **Oct 29, 2010**| Service formally retired and absorbed following the Nico Nico Douga (Harajuku) update. |

---

## Deletion & Moderation Status

Several deleted videos have been spotted displaying the unique notice:  
**"This video was deleted because it was deemed to be a broadcast television program based on a petition submitted to SMILE Development TEST."**  
This is believed to have been an internal test conducted by SMILEVIDEO's development team rather than a response to an actual copyright holder complaint.

Other videos have historically been logged as deleted under the administrative accounts **"SMILEVIDEO Development"** and **"SMILEVIDEO Support."**

---

## Cultural Context & Slang Guide

### 1. Why Every Vocaloid Video Starts with "sm": The Legacy of SMILEVIDEO
If you have ever pasted or linked a classic Vocaloid song on Nico Nico Douga you will recognize that almost all video identifiers start with **`sm`**.

Those two letters stand directly for **SMILEVIDEO**. 
When Dwango launched SMILEVIDEO to host videos, every video uploaded through its backend was assigned an incremental integer preceded by `sm`. Even though the SMILEVIDEO brand was retired in 2010, the `sm` prefix remains the universal standard ID format across Niconico to this day. 
Other historical prefixes you might encounter include:
- **`so`**: "Smile Official" (official channel uploads, anime broadcasts, corporate media).
- **`nm`**: "Nico Nico Movie Maker" (videos authored using Dwango's lightweight flash-slideshow tool, popular among early Vocaloid producers who only had static illustrations).

### 2. Niconico’s Origin as a "Parasite" on YouTube
When Nico Nico Douga originally debuted on December 12, 2006, as a test release (*Nico Nico Douga (Kari)* / ニコニコ動画（仮）), **it had no video servers of its own**. 

Instead, it was simply an interface layer that embedded videos hosted on YouTube and displayed scrolling user comments on top of them. Because the Japanese user base exploded overnight, Niconico users began flooding YouTube with re-uploads of Japanese media just to comment on them. On February 23, 2007, YouTube blocked Niconico's HTTP referrer traffic, completely bricking the site. 

The creation of SMILEVIDEO over four sleepless days was the do-or-die engineering feat that allowed Niconico to survive and become an independent platform.

### 3. Niconico Version Names: (β), (γ), and (Harajuku)
Instead of traditional software version numbers like 1.0 or 2.0, Nico Nico Douga historically branded each major redesign or era with unique titles:
- **(仮) (*Kari* / Provisional):** The initial experimental launch (Dec 2006 – Jan 2007).
- **(β) (*Beta*):** The peak of the YouTube-dependent era (Jan – Feb 2007).
- **(γ) (*Gamma*):** The revival era hosted on SMILEVIDEO (March 2007).
- **(RC) / (RC2) / (SP1) / (Summer) / (Autumn):** Rapid incremental eras through 2007–2009 during the golden age of Vocaloid's birth.
- **(Harajuku / 原宿):** Launched in October 2010, named after Dwango's high-tech studio in Tokyo's Harajuku district. This update modernized the site player and completely folded SMILEVIDEO into the core domain.

### 4. "Maruage" (丸上げ) vs. Original User Culture
*Maruage* (丸上げ, literally "uploading whole/intact") is Japanese internet slang for ripping an entire television broadcast, movie, or anime episode and uploading it without edits. 

In early 2007, like early YouTube, Niconico was rife with *maruage* piracy. To avoid being sued into oblivion, Dwango initially separated the video-hosting platform (SMILEVIDEO) from the community platform (Niwango / Nico Nico Douga). However, as 2007 progressed, the explosion of original user-generated content—spearheaded by the release of **Hatsune Miku** in August 2007, along with Touhou remixes and Idolmaster MADs—shifted Niconico’s identity from a pirate hub to a creative creative hotbed. This cultural shift, paired with legal agreements with music rights managers like **JASRAC** (allowing users to freely upload vocal/instrumental covers), made legal unification of the sites possible.

### 5. "Sumire Video" (スミレビデオ)
The disclaimer in the opening paragraph notes that the name is *Smile Video*, not *Sumire Video*. 
*Sumire* (菫 / スミレ) is the Japanese word for the violet flower. Because Japanese netizens often skim Katakana rapidly or invent deliberate pun misreadings on 2channel boards, users frequently joked that the platform was named "Sumire Video." It became a long-running inside joke and tagging meme on the platform.