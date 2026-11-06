## Ting-Kai Chang

Software engineer working on a SaaS platform for aesthetic medicine clinics, mostly on the backend with Node.js and PostgreSQL. I like turning messy front-desk workflows into systems that hold up on a busy day, and I build side projects to try out ideas around self-hosting, local LLMs and real-time tools.

### What I work on

- **Clinic operations** — booking, membership and checkout APIs with Express and PostgreSQL, e-invoice integration, daily and monthly reconciliation reports.
- **Digital consent forms** — template-driven forms and signatures that replace paper, rendered to PDF with Puppeteer and pdf-lib, stored on S3 behind presigned URLs, with a concurrency queue to keep PDF generation from slowing the service at peak hours.
- **Access control** — multi-brand, multi-branch RBAC, with sessions revoked as soon as an account is archived or its role changes.
- **Performance and data safety** — PostgreSQL index and query tuning, load testing, and production data migrations run as pre-check, dry run and verification steps.

### Projects

<table>
  <tr>
    <td width="72" valign="top"><img src="https://raw.githubusercontent.com/jeje898281/personal-website/main/site/assets/projects/commucloud.svg" width="56" alt="CommuCloud"></td>
    <td valign="top">
      <b>CommuCloud</b><br>
      Runs condominium owners' meetings: QR check-in, QR ballots and live quorum tracking by headcount and floor area. Multi-tenant, role-based, with email notices sent through a job queue.<br>
      <sub>Express · PostgreSQL · Prisma · Redis · BullMQ · React · Docker</sub><br>
      <sub><a href="https://github.com/jeje898281/community-app-backend">backend</a> · <a href="https://github.com/jeje898281/community-app-frontend">frontend</a> · <a href="https://github.com/jeje898281/community-app-infra">infra</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="https://raw.githubusercontent.com/jeje898281/personal-website/main/site/assets/projects/streamgloss.svg" width="56" alt="StreamGloss"></td>
    <td valign="top">
      <b>StreamGloss</b><br>
      Live Traditional Chinese subtitles for English streams, fully offline: voice activity detection, Whisper transcription and LLM translation in a threaded pipeline.<br>
      <sub>Python · faster-whisper · Silero VAD · Ollama</sub><br>
      <sub><a href="https://github.com/jeje898281/StreamGloss">source</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="https://raw.githubusercontent.com/jeje898281/personal-website/main/site/assets/projects/trip.svg" width="56" alt="TripMate"></td>
    <td valign="top">
      <b>TripMate</b><br>
      A LINE group bot that answers questions about a shared trip — next stop, transport, reservations — grounded in a verified itinerary.<br>
      <sub>Cloudflare Workers · Gemini · RAG · private</sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="https://raw.githubusercontent.com/jeje898281/personal-website/main/site/assets/projects/tamori.png" width="56" alt="Tamori"></td>
    <td valign="top">
      <b>Tamori</b><br>
      A spaced-repetition vocabulary app that imports Anki decks and runs as a PWA on the phone.<br>
      <sub>React · NestJS · PostgreSQL · private</sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="https://raw.githubusercontent.com/jeje898281/personal-website/main/site/assets/projects/ptt.svg" width="56" alt="PTT Danmaku"></td>
    <td valign="top">
      <b>PTT Danmaku</b><br>
      Shows the latest PTT comments as scrolling overlays on top of a live stream.<br>
      <sub>Electron · Python · WebSocket · private</sub>
    </td>
  </tr>
</table>

### Stack

Node.js · TypeScript · PostgreSQL · Redis · React · Python · Docker · AWS

### Background

Software engineer since 2024. Studied Political Science and Social Work at National Taiwan University (2017–2022).

<sub>jeje898281@gmail.com</sub>
