# Hello, Guys! I'm Lucas Marchi :metal: 

💻 **Senior Software Engineer (Rust)**  
💬 [LinkedIn](https://www.linkedin.com/in/lgmarchi-software-engineer/)  
📫 lucasgmarchi@gmail.com  
💻 [GitHub](https://github.com/lgmarchi)

## 😀 Summary
 Software Engineer with 8 years of experience across data analysis, mobile development, and backend systems. Over the last 3 years focused on Rust, building APIs and async services using technologies such as Tokio, Axum, and PostgreSQL. Experience working with AWS infrastructure, real-time applications, and AI integrations.

- **Core Languages**: Rust · Flutter  
- **Rust Ecosystem**: Tokio · Axum · SQLx · Serde · Tower · Barnacle-rs · Utoipa (API Documentation) · SeaORM · CodeLLDB (Debug)  
- **Databases**: PostgreSQL · Firebase · Supabase · Redis  
- **AI Integration**: LLM Integration · Rig · Prompt Pipelines · AWS Rekogntion  
- **AWS**: S3 · Rekognition · SNS · SQS  
- **Backend & Systems**: Async Systems · REST APIs · Background Jobs · Rate Limiting · API Authentication  
- **Frontend & Mobile**: Flutter · Dioxus  
- **Tools**: Git · GitHub · Linear · Postman · DBeaver · Cursor · Opencode · Slack · Discord

## 🔥 Open-source Projects

### barnacle-rs
Rate limiting and API key validation middleware for Axum with Redis backend.
- [crate](https://crates.io/crates/barnacle-rs)
- [github repo](https://github.com/zyphelabs/barnacle-rs.git)

### Uplink Desktop  
Privacy-first, modular, P2P messaging client built atop Warp.  
UI written entirely in Dioxus (Rust). Hyper-customizable & multi-platform.
- [github repo](https://github.com/Satellite-im/Uplink)

## 📂 Latest Projects

### **[Zyphe](https://www.zyphe.com/)** (Senior Backend Rust Engineer)
_Zyphe is a trusted, modern compliance platform that's transforming how businesses handle KYC (Know Your Customer), AML (Anti-Money Laundering), and KYB (Know Your Business) verification across the US, EU, and other global markets. We offer decentralized identity solutions that make onboarding faster with enterprise-grade security, all while keeping user privacy at the forefront._

• 𝗖𝘂𝘁 𝗶𝗻𝗳𝗿𝗮𝘀𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲 𝗰𝗼𝘀𝘁𝘀 𝗯𝘆 𝟰𝟬% by redesigning background job processing — replaced Apalis's default 100ms blind polling (230 queries/sec across 23 job queues) with PostgreSQL LISTEN/NOTIFY and tiered poll intervals (1s–60s based on job urgency), reducing polling overhead by ~𝟵𝟴%.  
• 𝗔𝗿𝗰𝗵𝗶𝘁𝗲𝗰𝘁𝗲𝗱 𝗮𝗻𝗱 𝗯𝘂𝗶𝗹𝘁 𝘁𝗵𝗲 𝗲𝗻𝘁𝗶𝗿𝗲 𝗯𝗶𝗼𝗺𝗲𝘁𝗿𝗶𝗰 𝘃𝗲𝗿𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻 𝘀𝘆𝘀𝘁𝗲𝗺 — liveness detection, anti-spoofing (occlusion, face consistency), and face matching. Migrated from a third-party provider to an in-house pipeline using ONNX Runtime and AWS Rekognition, reducing liveness detection costs by 20%+ and later extracting it as an independent microservice.  
• 𝗕𝘂𝗶𝗹𝘁 𝗮𝗻 𝗔𝗜 𝗼𝗿𝗰𝗵𝗲𝘀𝘁𝗿𝗮𝘁𝗶𝗼𝗻 𝗹𝗮𝘆𝗲𝗿 serving multiple LLM providers (Amazon Bedrock, OpenAI) through Rig, enabling image and document analysis with structured prompt pipelines  
• 𝗖𝗿𝗲𝗮𝘁𝗲𝗱 𝗮𝗻𝗱 𝗼𝗽𝗲𝗻-𝘀𝗼𝘂𝗿𝗰𝗲𝗱 𝗯𝗮𝗿𝗻𝗮𝗰𝗹𝗲-𝗿𝘀 (published on crates.io), a Rust middleware for Axum that extends Tower Governor with API key authentication and per-user/email/UUID rate limiting — used in production to protect all customer-facing APIs.  

𝗦𝘁𝗮𝗰𝗸: Rust · Axum · Tokio · PostgreSQL · SQLx · Redis · AWS (S3, SQS, SNS, Rekognition, Bedrock) · Apalis · Rig · Tower

### **[Satellite.im - Open Source project](https://github.com/Satellite-im)** (Senior Software Engineer - Rust, Flutter, and Svelte)
_Overall, Satellite IM's combination of privacy, security, high-quality communication, flexibility, and community focus makes it a compelling choice for users seeking a secure and decentralized messaging platform._

• 𝗗𝗲𝗹𝗶𝘃𝗲𝗿𝗲𝗱 𝗮 𝗽𝗿𝗼𝗱𝘂𝗰𝘁𝗶𝗼𝗻-𝗿𝗲𝗮𝗱𝘆 𝗺𝗼𝗯𝗶𝗹𝗲 𝗠𝗩𝗣 𝗶𝗻 𝟯 𝗺𝗼𝗻𝘁𝗵𝘀, leading development from architecture to release — establishing QA processes that reduced production bugs by 15%.  
• 𝗥𝗲𝗱𝘂𝗰𝗲𝗱 𝘀𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲𝗱 𝗱𝗮𝘁𝗮 𝗲𝗿𝗿𝗼𝗿𝘀 𝗯𝘆 𝟮𝟬% by diagnosing and fixing serialization/deserialization issues across the Serde pipeline, improving data reliability across all platforms.  
• 𝗕𝘂𝗶𝗹𝘁 𝗿𝗲𝗮𝗹-𝘁𝗶𝗺𝗲 𝗰𝗵𝗮𝘁 𝗮𝗻𝗱 𝗪𝗲𝗯𝗥𝗧𝗖 𝘀𝘆𝘀𝘁𝗲𝗺𝘀 supporting group calls, screen sharing, and per-character input processing (emoji parsing, typing indicators).  
• 𝗦𝗵𝗶𝗽𝗽𝗲𝗱 𝗰𝗿𝗼𝘀𝘀-𝗽𝗹𝗮𝘁𝗳𝗼𝗿𝗺 𝗳𝗲𝗮𝘁𝘂𝗿𝗲𝘀 𝗮𝗰𝗿𝗼𝘀𝘀 𝟲 𝘁𝗮𝗿𝗴𝗲𝘁𝘀 (Windows, macOS, Linux, Web, iOS, Android), including OS-specific multi-threaded solutions for clipboard handling that eliminated UI freezes during heavy media operations.  
• 𝗜𝗺𝗽𝗹𝗲𝗺𝗲𝗻𝘁𝗲𝗱 𝗵𝗶𝗴𝗵-𝗰𝗼𝗻𝗰𝘂𝗿𝗿𝗲𝗻𝗰𝘆 𝗳𝗶𝗹𝗲 𝘁𝗿𝗮𝗻𝘀𝗳𝗲𝗿 𝘄𝗼𝗿𝗸𝗳𝗹𝗼𝘄𝘀 𝘂𝘀𝗶𝗻𝗴 𝗧𝗼𝗸𝗶𝗼, enabling simultaneous uploads, downloads, and background processing while maintaining responsive UI across all platforms.  

𝗦𝘁𝗮𝗰𝗸: Rust · Tokio · Dioxus · Serde · WebRTC · Svelte · TypeScript · Flutter


### **Xports App** (Co-founder | Senior Flutter Developer)

• 𝗖𝗼-𝗳𝗼𝘂𝗻𝗱𝗲𝗱 𝗮𝗻𝗱 𝘀𝗵𝗶𝗽𝗽𝗲𝗱 𝗮 𝘀𝗽𝗼𝗿𝘁𝘀 𝘁𝗼𝘂𝗿𝗻𝗮𝗺𝗲𝗻𝘁 𝗽𝗹𝗮𝘁𝗳𝗼𝗿𝗺 𝘁𝗼 𝗔𝗽𝗽 𝗦𝘁𝗼𝗿𝗲 𝗮𝗻𝗱 𝗣𝗹𝗮𝘆 𝗦𝘁𝗼𝗿𝗲 — 1,000+ downloads, 300+ active users across 3 applications built from scratch.  
• 𝗥𝗲𝘀𝗼𝗹𝘃𝗲𝗱 𝟮 𝗰𝗿𝗶𝘁𝗶𝗰𝗮𝗹 𝗽𝗿𝗼𝗱𝘂𝗰𝘁𝗶𝗼𝗻-𝗯𝗹𝗼𝗰𝗸𝗶𝗻𝗴 𝗯𝘂𝗴𝘀 that were preventing release, increasing application stability by 80% and unblocking the production launch.  
• 𝗥𝗲𝘀𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲𝗱 𝗙𝗶𝗿𝗲𝘀𝘁𝗼𝗿𝗲 𝗱𝗮𝘁𝗮𝗯𝗮𝘀𝗲 𝘀𝗰𝗵𝗲𝗺𝗮 𝘁𝗼 𝗼𝗽𝘁𝗶𝗺𝗶𝘇𝗲 𝗿𝗲𝗮𝗱/𝘄𝗿𝗶𝘁𝗲 𝗽𝗮𝘁𝘁𝗲𝗿𝗻𝘀, reducing redundant document reads and lowering Firebase costs through denormalization and efficient query design.  
• 𝗘𝗹𝗶𝗺𝗶𝗻𝗮𝘁𝗲𝗱 𝘃𝗶𝗱𝗲𝗼 𝗰𝗼𝗿𝗿𝘂𝗽𝘁𝗶𝗼𝗻 𝗶𝘀𝘀𝘂𝗲𝘀 𝗯𝘆 𝗺𝗶𝗴𝗿𝗮𝘁𝗶𝗻𝗴 𝘃𝗶𝗱𝗲𝗼 𝗲𝗱𝗶𝘁𝗶𝗻𝗴 𝗳𝗿𝗼𝗺 𝗙𝗹𝘂𝘁𝘁𝗲𝗿 𝘁𝗼 𝗻𝗮𝘁𝗶𝘃𝗲 𝗦𝘄𝗶𝗳 𝗮𝗻𝗱 𝗞𝗼𝘁𝗹𝗶𝗻, solving a cross-platform limitation that was breaking user-generated content.  
• 𝗔𝘂𝘁𝗼𝗺𝗮𝘁𝗲𝗱 𝟰𝟬% 𝗼𝗳 𝗺𝗮𝗻𝘂𝗮𝗹 𝗼𝗽𝗲𝗿𝗮𝘁𝗶𝗼𝗻𝘀 𝗯𝘆 𝗯𝘂𝗶𝗹𝗱𝗶𝗻𝗴 𝗖𝗹𝗼𝘂𝗱 𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻𝘀 for real-time data processing, event triggers, and background tasks — reducing the need for manual intervention in tournament management.  

𝗦𝘁𝗮𝗰𝗸: Flutter · Dart · Firebase · Firestore · Cloud Functions · Swift · Kotlin · App Store · Play Store

## 🎓 Education

**BSc in Mechanical Engineering**  
São Bernardo do Campo, Brazil  
*Technical research in mobile Java for engineering problems*

## 🌎 Languages

🇧🇷 Portuguese: Native  
🇺🇸 English: Proficient

---

## ⚙️ Technologies and Tools

![](https://img.shields.io/badge/Code-Rust-informational?style=flat&logo=rust&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Flutter-informational?style=flat&logo=flutter&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Dioxus-informational?style=flat&logo=rust&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Svelte-informational?style=flat&logo=svelte&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Javascript-informational?style=flat&logo=javascript&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Typescript-informational?style=flat&logo=typescript&logoColor=white&color=2bbc8a)
