# 404-Not-Founders
Team Members
​Dhruv: Backend & Sync Engineer  
​Prateek: AI Developer  
​Taksheel: Frontend UI/UX Designer  
​Namit: Cybersecurity Specialist  
​Yuvraj: Demo Lead  

Resilient AI LifeKeeper is an offline AI companion designed for both daily life productivity and disaster management. It acts as a personal journal in normal times and automatically transforms into a disaster assistant during emergencies helping individuals, communities, and relief agencies stay connected when the internet is down.

Resilient AI LifeKeeper: Everyday Journal. Blackout Lifeline
Track: Systems & Infrastructure
Sub Track: Decentralization & Protocols ; Core Systems & Data Engines
Overview:
Resilient AI LifeKeeper is an offline-first hybrid PWA that acts as a smart, encrypted personal journal during normal daily life. When cellular networks fail during emergencies, it automatically transitions into a decentralized crisis node, enabling local mesh chat, skill-based community formation, and AI-driven triage guidance entirely without internet access

Core Features
​Daily Life Mode: Encrypted journaling, idea capture, and automatic off-thread AI summaries.  
​Disaster Mode: Peer-to-peer offline chat, supply tracking, and emergency START triage processing. 
Decentralized Mesh Sync: Utilizes RxDB and Yjs with CRDTs to merge text logs and structured AI JSON payloads via WebRTC/BLE whenever devices come within range.  
​Local Edge AI: Runs quantized small language models (like Qwen2.5-0.5B-Instruct-q4f16_1-MLC) entirely in the browser via WebLLM inside a Web Worker, preventing UI freezing.  
​Security: Secures offline data using AES-256-GCM encryption and Role-Based Access Control (RBAC).

Tech Stack
​Frontend UI: Google demo API,Web API ,PWA Configuration  
​Offline AI Engine: WebLLM, Web Workers  
​Local DB & Sync: RxDB, Yjs (y-webrtc / y-indexeddb)  
​Security & Crypto: WebCrypto API  


   
