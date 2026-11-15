# 🌍 Melix Edu – Global Non-Profit Peer-to-Peer Learning Platform

**Melix Edu** is a free, open-source, global peer-to-peer (P2P) learning platform connecting volunteer student tutors with underserved students worldwide—with a special focus on supporting education in under-resourced regions such as **Cambodia and Laos**.

By automatically tracking verified tutoring hours and issuing **LinkedIn-verifiable certificates**, Melix creates a win-win ecosystem: students receive free, high-quality academic support, while peer tutors earn recognized credentials for their university and career applications.

---

## 🎯 The Vision & Core Idea
Millions of motivated students in under-resourced regions lack access to tutoring, while privileged students around the world want to help and build meaningful volunteer experience. Melix bridges this gap with a minimalist, safe, and automated matching platform.

---

## 🚀 Roadmap: MVP (Version 1) vs. Full Vision (Version 2)
To make development fast, modular, and achievable on a 100% Free-Tier stack, the platform is structured into two clear phases:

### Phase 1: MVP Features (Launch Version)
1. **Smart Matching & Built-in Child Safety**
   * **Flexible Roles:** Users can register as a **Student**, a **Peer Tutor**, or **both** (either subject list can be left blank).
   * **Automated Matching:** Connects learners and tutors based on **Language**, **Subject**, and **Grade Level**.
   * **Age-Gap Protection:** Birthdate verification at sign-up ensures tutors are always at least **1 year older** than the student they are matched with.
   * **Instant Video Rooms:** Once matched, the system automatically generates a unique **Jitsi Meet URL** (`https://jit.si[randomID]`)—requiring zero video server costs.

2. **Automated Hour Tracking & LinkedIn Merit Certificates**
   * **Session Logging:** After a session, both participants confirm completion to log tutoring hours automatically.
   * **Verifiable PDF Certificates:** Reaching milestones unlocks an auto-generated PDF certificate with a unique verification ID and public verification URL (`melix-edu.org/verify/[ID]`) for one-click **LinkedIn integration**:
     * *Starter Milestone:* **10 Hours** – Certificate of Community Tutoring *(for early adopter motivation)*
     * *Level 1:* **40 Hours** – Certificate of Teaching Practice
     * *Level 2:* **100 Hours** – Certificate of Teaching Competence
     * *Level 3:* **300 Hours** – Certificate of Teaching Expertise
     * *Level 4:* **500 Hours** – Certificate of Teaching Excellence

3. **Community Safety & Reporting**
   * **Screen-Share First Guidance:** Clear UI reminders encouraging camera-off, screen-share-focused study sessions.
   * **Safety Hotline / Report Button:** One-click reporting on profiles and sessions to flag inappropriate behavior immediately.

### Phase 2: Post-MVP Expansion
* **Quality Feedback Loops:** Automated quality check-in surveys triggered after every **5 completed lessons**.
* **Tutor Verification Workflow:** Admin dashboard (`applied` / `verified` / `rejected`) for optional academic credential review once adult/non-profit governance is established.
* **Multilingual UI Localization:** Full interface translations tailored for students in Southeast Asia and beyond.

---

## 🎨 Design Direction & Aesthetic
* **Style:** Minimalist, high-trust academic aesthetic with generous white space and crisp hairline borders.
* **Color Palette:**
  * Primary Deep Navy Blue: **`#0D274D`**
  * Background: Soft Off-White / Pure White (`#FAFAFA` / `#FFFFFF`)
  * Accents: Subtle emerald/gold highlights for verified milestones
* **Figma Wireframes:** `[Insert your Figma link here – coming soon]`

---

## 🛠️ Technical Architecture (100% Free-Tier Ready)
* **Frontend:** Next.js (App Router), TypeScript, Tailwind CSS
* **Backend & Database:** Supabase (PostgreSQL, Auth, Row-Level Security)
* **Hosting:** Vercel (Free Tier, Serverless)
* **Video Rooms:** Jitsi Meet (randomized room URLs)
* **Certificates:** Server-side PDF generation (`@react-pdf/renderer` or `pdf-lib`) + public verification route
* **Security:** All API keys and secrets managed strictly via `.env` environment variables.

---

## 🤝 Looking for a Technical Co-Builder / Lead Full-Stack Developer!
I am a **14-year-old student founder** looking for **one dedicated Full-Stack Developer** to build the Melix MVP together as equal open-source partners. Because this is a non-profit passion project without funding or legal contracts, it is an ideal opportunity for a student or junior developer who wants to build a standout, high-impact full-stack application for their portfolio from scratch.

* **What I bring to the table:** Complete functional specification, minimalist UI/UX wireframes (Figma), all copywriting, user testing, and global student outreach to onboard our first tutors and learners.
* **What you bring:** Full-stack Next.js/Supabase development, clean architecture, and passion for educational equity.

### 📬 How to Get Involved
1. Explore the **[Issues](../../issues)** tab to view the initial MVP tasks.
2. Start a conversation in **[GitHub Discussions](../../discussions)**.
3. Or reach out directly via email: **`Melix-Edu@protonmail.com`**

---

## 📄 License
This project is open-source under the **MIT License** – see the [LICENSE](LICENSE) file for details.
