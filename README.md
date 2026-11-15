# 🌍 Melix – Free Global Peer-to-Peer Learning Platform

**Melix** is a global, non-profit, open-source peer-to-peer (P2P) learning platform designed to make quality education accessible to students everywhere—completely free of charge. 

Instead of expensive tutoring, students connect directly with peers around the world to help each other succeed in school and beyond.

---

## 🎯 The Vision & Problem
Millions of students struggle with school subjects without access to affordable tutoring, while many other students love explaining topics and want to help. As a **14-year-old student** myself, I see this gap every day. Melix is built to solve this with a simple, safe, and distraction-free matching platform created by students, for students.

---

## 🚀 MVP Features (Version 1)
To keep the first version fast, lightweight, and easy to build, we are focusing on **4 core features**:

1. **Flexible User Profiles & Role Selection**
   * Sign up via Email/Password or Google Auth.
   * Users create a profile with their name, languages spoken, and timezone.
   * **Flexible Learning Roles:** Users can select subjects they need help with, subjects they can teach, **or leave either one blank**. This allows users to join purely as a learner, purely as a peer tutor, or do both.

2. **Peer-Matching & Subject Search**
   * A clean directory of active learners and peer tutors.
   * Simple filtering by **Subject** (e.g., Math, English, Biology, Coding) and **Language** to quickly find the right study partner.

3. **Session Requests & Automatic Jitsi Link Generation**
   * Learners can send a session request with a short note (e.g., *"Need help with fractions, free tomorrow at 4 PM UTC?"*).
   * Once accepted, the app automatically generates a unique, random **Jitsi Meet URL** (e.g., `https://jit.si`)—requiring zero video infrastructure or hosting costs.

4. **Simple User Dashboard ("My Sessions")**
   * View incoming/outgoing session requests (Accept/Decline).
   * Access scheduled study sessions with a one-click **"Join Jitsi Room"** button.

### 🛡️ Built-in Safety Principles (MVP)
* **Screen-Share First:** Clear UI guidance encouraging users to keep cameras off and use screen-sharing/whiteboards during Jitsi sessions.
* **Report Button:** A simple one-click report option on user profiles and sessions to keep the community safe.

---

## 🎨 Design & Wireframes
* **Figma Prototype:** `[Insert your Figma link here – coming soon]`
* **Website Copy & Content:** Check the `/docs` folder for pre-written UI texts and the community launch plan.

---

## 🛠️ Suggested Tech Stack
*(Open to discussion – the technical lead has full freedom over the final architecture)*
* **Frontend:** Next.js, TypeScript, Tailwind CSS
* **Backend & Auth:** Supabase or Firebase (Free Tier)
* **Video Rooms:** Jitsi Meet (via randomized URL generation)
* **Hosting:** Vercel or Netlify (Free Tier)

---

## 🤝 Looking for a Technical Co-Builder / Lead Developer!
I am a **14-year-old founder and product creator** looking for **one motivated Full-Stack Developer** (or a small core team) to build this MVP together as equal partners in an open-source spirit. Because this is a non-profit passion project without funding or legal contracts, it is ideal for a student or junior developer who wants to build a real-world, high-impact platform for their portfolio from scratch.

* **What I bring to the table:** Full product concept, UI/UX wireframes (Figma), all website copywriting, user testing, and community marketing to onboard our first 100+ students.
* **What you bring:** Full-stack development, technical architecture decisions, and excitement for open education.

### 📬 How to Get Involved
1. Check out the **[Issues](../../issues)** tab to see the planned MVP tasks.
2. Start or reply to a thread in our **[GitHub Discussions](../../discussions)** tab.
3. Or send me an email directly at: **`Melix-Edu@protonmail.com`**

---

## 📄 License
This project is open-source and licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
