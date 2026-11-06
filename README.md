## Ting-Kai Chang 張定楷

[English](#english) · [中文](#中文)

### English

Software engineer working on a SaaS platform for aesthetic medicine clinics, mostly on the backend with Node.js and PostgreSQL. I turn front-desk workflows into systems that hold up at peak hours, and build side projects around self-hosting, local LLMs and real-time tools.

**What I work on**

- **Clinic operations** — booking, membership and checkout APIs with Express and PostgreSQL, e-invoice integration, daily and monthly reconciliation reports.
- **Digital consent forms** — template-driven forms and signatures that replace paper, rendered to PDF with Puppeteer and pdf-lib, stored on S3 behind presigned URLs, with a concurrency queue so PDF generation does not slow the service at peak hours.
- **Access control** — multi-brand, multi-branch RBAC, with sessions revoked as soon as an account is archived or its role changes.
- **Performance and data safety** — PostgreSQL index and query tuning, load testing, and production data migrations run as pre-check, dry run and verification steps.

**Projects**

<table>
  <tr>
    <td width="72" valign="top"><img src="assets/commucloud.svg" width="56" alt="CommuCloud"></td>
    <td valign="top">
      <b>CommuCloud</b><br>
      Runs condominium owners' meetings: QR check-in, QR ballots and live quorum tracking by headcount and floor area. Multi-tenant and role-based, with email notices sent through a job queue.<br>
      <sub>Express · PostgreSQL · Prisma · Redis · BullMQ · React · Docker</sub><br>
      <sub><a href="https://github.com/jeje898281/commucloud">source</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/streamgloss.svg" width="56" alt="StreamGloss"></td>
    <td valign="top">
      <b>StreamGloss</b><br>
      Live Traditional Chinese subtitles for English streams, fully offline: voice activity detection, Whisper transcription and LLM translation in a threaded pipeline.<br>
      <sub>Python · faster-whisper · Silero VAD · Ollama</sub><br>
      <sub><a href="https://github.com/jeje898281/StreamGloss">source</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/trip.svg" width="56" alt="TripMate"></td>
    <td valign="top">
      <b>TripMate</b><br>
      A LINE group bot that answers questions about a shared trip — next stop, transport, reservations — grounded in a verified itinerary.<br>
      <sub>Cloudflare Workers · Gemini · RAG · private</sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/tamori.png" width="56" alt="Tamori"></td>
    <td valign="top">
      <b>Tamori</b><br>
      A spaced-repetition vocabulary app that imports Anki decks and runs as a PWA on the phone.<br>
      <sub>React · NestJS · PostgreSQL · private</sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/ptt.svg" width="56" alt="PTT Danmaku"></td>
    <td valign="top">
      <b>PTT Danmaku</b><br>
      Shows the latest PTT comments as scrolling overlays on top of a live stream.<br>
      <sub>Electron · Python · WebSocket · private</sub>
    </td>
  </tr>
</table>

**Stack** — Node.js · TypeScript · PostgreSQL · Redis · React · Python · Docker · AWS

**Background** — Software engineer since 2024. Studied Political Science and Social Work at National Taiwan University (2017–2022).

---

### 中文

軟體工程師，參與醫美診所 SaaS 平台開發，以 Node.js 與 PostgreSQL 的後端開發為主。專注於將櫃檯現場流程轉化為可在尖峰時段穩定運作的系統，並透過個人專案實作自架服務、本地 LLM 與即時處理等主題。

**工作內容**

- **診所營運** — 以 Express 與 PostgreSQL 建置預約、會員與結帳 API，串接電子發票，開發日結、月結對帳報表。
- **醫療文件數位化** — 以範本管理的線上表單與簽署取代紙本，透過 Puppeteer 與 pdf-lib 產生 PDF、存放於 S3 並以 presigned URL 控管下載，搭配併發佇列避免尖峰時段拖慢服務。
- **權限控管** — 多品牌、多分店的 RBAC 角色權限，帳號封存或權限異動時即時登出受影響帳號。
- **效能與資料安全** — PostgreSQL 索引與查詢調校、壓力測試，正式環境資料異動以預檢、試跑與驗證分步執行。

**專案**

<table>
  <tr>
    <td width="72" valign="top"><img src="assets/commucloud.svg" width="56" alt="CommuCloud"></td>
    <td valign="top">
      <b>CommuCloud</b><br>
      社區區分所有權人會議系統：QR Code 報到、QR 選票表決，並依出席戶數與坪數比例即時計算是否達法定門檻。支援多社區與角色權限，會議通知透過工作佇列寄送。<br>
      <sub>Express · PostgreSQL · Prisma · Redis · BullMQ · React · Docker</sub><br>
      <sub><a href="https://github.com/jeje898281/commucloud">原始碼</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/streamgloss.svg" width="56" alt="StreamGloss"></td>
    <td valign="top">
      <b>StreamGloss</b><br>
      英文直播即時中文字幕，全程離線執行：語音偵測、Whisper 語音辨識與 LLM 翻譯以多執行緒管線串接。<br>
      <sub>Python · faster-whisper · Silero VAD · Ollama</sub><br>
      <sub><a href="https://github.com/jeje898281/StreamGloss">原始碼</a></sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/trip.svg" width="56" alt="TripMate"></td>
    <td valign="top">
      <b>TripMate</b><br>
      LINE 群組旅遊助理，依查證過的行程資料回答下一站、交通與預約時間等問題。<br>
      <sub>Cloudflare Workers · Gemini · RAG · 未公開</sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/tamori.png" width="56" alt="Tamori"></td>
    <td valign="top">
      <b>Tamori</b><br>
      依遺忘曲線安排複習的背單字 PWA，支援匯入 Anki 牌組。<br>
      <sub>React · NestJS · PostgreSQL · 未公開</sub>
    </td>
  </tr>
  <tr>
    <td valign="top"><img src="assets/ptt.svg" width="56" alt="PTT 彈幕"></td>
    <td valign="top">
      <b>PTT 彈幕</b><br>
      將 PTT 文章最新推文以彈幕形式疊加於直播畫面。<br>
      <sub>Electron · Python · WebSocket · 未公開</sub>
    </td>
  </tr>
</table>

**技術** — Node.js · TypeScript · PostgreSQL · Redis · React · Python · Docker · AWS

**背景** — 2024 年起擔任軟體工程師。國立臺灣大學政治學系、社會工作學系（2017–2022）。

---

<sub>jeje898281@gmail.com</sub>
