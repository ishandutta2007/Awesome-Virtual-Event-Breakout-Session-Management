# Awesome-Virtual-Event-Breakout-Session-Management

# Awesome Virtual Event & Breakout Session Management

> A curated list of top Virtual Event and Breakout Session Management platforms — both SaaS/Hosted commercial solutions and open-source alternatives for hosting online conferences, managing breakout rooms, and facilitating interactive sessions.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Zoom Events](#zoom-events)
  - [Hopin](#hopin)
  - [Bizzabo](#bizzabo)
  - [vFairs](#vfairs)
  - [Airmeet](#airmeet)
  - [Cisco Webex Events](#cisco-webex-events)
  - [Cvent Attendee Hub](#cvent-attendee-hub)
  - [ON24](#on24)
  - [Hubilo](#hubilo)
- [Open-Source Software](#-open-source-software)
  - [BigBlueButton](#bigbluebutton)
  - [PILOS](#pilos)
  - [plugNmeet](#plugnmeet)
  - [venueless](#venueless)
  - [eduMEET](#edumeet)
  - [Telehack](#telehack)
  - [Open Meet](#open-meet)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Virtual Event and Breakout Session Management platforms. These are not open-source but are included as reference points for feature comparison.

### Zoom Events
**Type:** Virtual event platform within Zoom ecosystem  
Zoom Events builds on Zoom's meeting infrastructure to support multi-session virtual events with breakout rooms, networking, and ticketing. Suited for organizations already using Zoom for meetings who want to extend into event hosting without adopting a separate platform.

### Hopin
**Type:** Virtual and hybrid event platform  
Hopin was a category-defining virtual event platform featuring multi-stage streaming, networking, expo booths, and breakout sessions. Acquired by RingCentral in 2023, with the events platform subsequently wound down. Included here as a historical reference point for the virtual event category.

### Bizzabo
**Type:** Event experience operating system  
Bizzabo combines registration, agenda management, networking, and attendee engagement with support for in-person, virtual, and hybrid events. Breakout sessions and multi-track agendas are core features. Pricing is quote-based.

### vFairs
**Type:** Virtual event and trade show platform  
vFairs specializes in immersive virtual events with virtual booths, auditoriums, networking lounges, and breakout rooms. Often used for career fairs, trade shows, and large conferences requiring an expo-like experience.

### Airmeet
**Type:** Virtual and hybrid event platform  
Airmeet offers virtual conferences, webinars, and meetups with networking lounges, breakout sessions, and audience engagement tools. Includes a free tier for smaller events, making it accessible for community gatherings and workshops.

### Cisco Webex Events
**Type:** Webex-integrated event platform  
Webex Events provides webinar and event hosting within the Cisco Webex ecosystem. Supports breakout sessions, registration, and analytics. Suited for enterprises already standardized on Webex for collaboration.

### Cvent Attendee Hub
**Type:** Enterprise event experience platform  
Cvent Attendee Hub provides a unified attendee experience across in-person, virtual, and hybrid events, with session management, networking, and content delivery. Part of the broader Cvent enterprise event management suite.

### ON24
**Type:** Webinar and digital experience platform  
ON24 focuses on engagement analytics and on-demand webinar experiences. While not a full virtual event platform, it supports multi-session webinar series with breakout-style interactions and detailed attendee engagement scoring.

### Hubilo
**Type:** Virtual and hybrid event platform  
Hubilo provides virtual event hosting with networking, breakout sessions, and engagement features. Positioned for organizations wanting a modern virtual event experience with strong attendee interaction capabilities.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Virtual Event and Breakout Session Management tools. The open-source ecosystem is stronger for video conferencing with breakout support than for full event management suites.

### BigBlueButton
**Stack:** Java / JavaScript / WebRTC | **License:** LGPL-3.0  
A leading open-source web conferencing platform explicitly designed for online learning, with **breakout rooms** as a core built-in feature [citation:4][citation:10]. Supports group and individual breakout rooms, real-time audio/video sharing, multi-user whiteboard, polling, shared notes, and session recording. Moderators can create breakout rooms, assign participants, and manage sessions. Widely deployed in educational institutions and increasingly used for workshops and training events.  
**Best for:** Educational institutions and organizations needing robust, self-hosted breakout rooms with strong collaboration tools and recording.

### PILOS
**Stack:** (Check repository) | **License:** LGPL-2.1-only  
An open-source front-end for BigBlueButton servers with a built-in load balancer [citation:2]. Designed with education at its core, PILOS offers video/audio, screen sharing, multi-user whiteboard, **breakout rooms**, chat, surveys, recording, and live streaming to RTMP endpoints. Manages BigBlueButton server pools, users, and roles. Deployed by several European universities.  
**Best for:** Organizations already running BigBlueButton that want a more polished management layer with load balancing and additional features.

### plugNmeet
**Stack:** Go / React / WebRTC | **License:** Open Source (per project)  
A full-featured open-source video conferencing and webinar solution with **breakout rooms** for splitting participants into smaller groups [citation:14]. Includes HD audio/video, interactive whiteboard, polls, public/private chat, waiting room, and end-to-end encryption. Supports MP4 recording, live broadcasting to YouTube via RTMP, and an AI meeting agent for translation, summaries, and transcriptions. Can be self-hosted for full data control.  
**Best for:** Teams wanting a complete, self-hostable webinar and meeting platform with breakout rooms, recording, and AI features.

### venueless
**Stack:** Python / Django / JavaScript | **License:** Business Source License 1.1 (converts to Apache 2.0)  
An open-source platform for running fully online events, including live video streams, interactive video calls, group chats, and networking [citation:12]. Built by the teams behind pretix and pretalx for conferences and larger virtual gatherings. **Important licensing note:** The BSL is not OSI-approved open source, but converts to Apache 2.0 24 months after each release. You can self-host for your own events for free, but **cannot offer it as a hosted service** to other organizations.  
**Best for:** Conference organizers wanting a comprehensive virtual event platform, with awareness of the BSL licensing terms.

### eduMEET
**Stack:** WebRTC / JavaScript | **License:** Open Source (per project)  
A WebRTC web-conferencing platform originally developed within the GÉANT project for research and education [citation:8]. Version 4.0 (January 2024) added **breakout rooms**, transcription engines, background blur, and support for up to 49 visible participants. Completely rebuilt for scalability, with a refreshed UI and simplified configuration. Transitioned to community-managed open-source governance.  
**Best for:** Research and education communities in Europe needing a scalable, self-hosted conferencing platform with breakout support.

### Telehack
**Stack:** FastAPI / LiveKit / Docker | **License:** Open Source (per GitHub)  
A self-hosted web-based system for running hackathons, with **automatic breakout room creation** for each team [citation:1]. Features include passwordless email authentication against a participant roster, video conferencing with camera/mic/screen share, automatic recording of every room, organizer controls (broadcast announcements, stage streaming, summon/dispatch participants), presentation mode with timed slots, and voting/awards ceremony.  
**Best for:** Hackathon organizers and event facilitators needing team-based breakout rooms with recording and structured presentation workflows.

### Open Meet
**Stack:** TypeScript / Next.js / NestJS / LiveKit | **License:** Open Source (per GitHub)  
A self-hostable team collaboration platform combining video meetings with persistent team chat [citation:3]. Supports instant rooms, scheduled/recurring meetings, screen sharing, reactions, in-meeting chat, and host controls. **Note:** The current feature set does not explicitly list breakout rooms, though the LiveKit foundation could support them. Positioned as a privacy-friendly alternative to Google Meet and Zoom with integrated messaging.  
**Best for:** Teams wanting a combined meeting and persistent chat workspace they control, without native breakout rooms.

---

## 📊 Comparison at a Glance

| Software | License | Type | Breakout Rooms | Self-Hosted | Recording | Best For |
|----------|---------|------|----------------|-------------|-----------|----------|
| **Zoom Events** | Proprietary | Virtual events | ✅ | ❌ | ✅ | Zoom ecosystem users |
| **Hopin** | Proprietary | Virtual events | ✅ | ❌ | ✅ | (Wound down) |
| **Bizzabo** | Proprietary | Event experience | ✅ | ❌ | ✅ | Hybrid event programs |
| **vFairs** | Proprietary | Virtual trade shows | ✅ | ❌ | ✅ | Expo-style events |
| **Airmeet** | Proprietary | Virtual events | ✅ | ❌ | ✅ | Community events (free tier) |
| **Webex Events** | Proprietary | Webex events | ✅ | ❌ | ✅ | Cisco ecosystem |
| **Cvent Attendee Hub** | Proprietary | Enterprise events | ✅ | ❌ | ✅ | Large enterprise conferences |
| **BigBlueButton** | LGPL-3.0 | Web conferencing | ✅ | ✅ | ✅ | Education + workshops |
| **PILOS** | LGPL-2.1 | BBB front-end | ✅ | ✅ | ✅ | Managed BBB with load balancing |
| **plugNmeet** | Open Source | Webinar suite | ✅ | ✅ | ✅ | Full webinar + AI features |
| **venueless** | BSL → Apache | Virtual event platform | (Check) | ✅ (with limits) | ✅ | Conferences (check license) |
| **eduMEET** | Open Source | Web conferencing | ✅ | ✅ | ✅ (local) | European research/education |
| **Telehack** | Open Source | Hackathon system | ✅ (auto team rooms) | ✅ | ✅ (auto) | Hackathons + team presentations |
| **Open Meet** | Open Source | Meetings + chat | ❌ (not listed) | ✅ | ✅ (host) | Combined meetings + messaging |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Virtual Event or Breakout Session Management tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source (or clearly note the license if source-available but not OSI-approved, as with venueless's BSL).

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
