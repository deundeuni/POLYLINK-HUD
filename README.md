> **Multilingual Publication Notice:** This document is published in dual Korean/English versions. v1.3.1 2026-09-12 (Korean version: [README.ko.md](README.ko.md))  
> **Original Authority Notice:** The authoritative legal and technical reference for this specification belongs to the Korean original (`README.ko.md`). The English version serves solely as an auxiliary reference. (`README.ko.md` is authoritative original)

# POLYLINK-HUD (formerly CWP-AR-HUD) — Technical Specification for Multilingual Legacy Industrial Equipment Non-invasive Optical Vision OCR/LLM Overlay and Multisensory AR Glass HUD Spatial HMI Gateway
## Subtitle: Human-Centric Auxiliary AI Safety First Principle, Zero-Modification Principle for Firmware/PLC Controllers, Base Lightweight Implementation & Extended Fusion Hardware Combinations, Error Lifecycle Blackbox Logging & RAG Solution Search Linkage, Enterprise Storage Routing (NAS/S3/MES) Automated Documentation, Privacy by Design 4 Human Rights Protection Mechanisms & BYOD Private Space Blurring, Legacy Media Zero-Modification Overlay & Game UI/Dialogue and Venue Standard Subtitle Application Extensibility, Target Language (Native Language) Spatial Overlay for Multilingual/Multinational Sites, 1ms-class MIPI Switching & Cognitive Buffer Resource Control, FIRST-LIGHT/LAST-LIGHT Wide-Area Mesh L0 Anchor Lineage, 3 Sub-categories (Enterprise/Everyday/Personal BYOD), Pure Conceptual White Paper Author Zero-Liability Declaration, and soma-moa L3 Social Auxiliary Governance Defensive Publication (Ver. 1.3.1)

* **Official Classification:** Defensive Publication / Prior Art White Paper
* **Initial Conception Date:** 2026-08-28 / **Final Revision Date (v1.3.1):** 2026-09-12
* **Original Intellectual Property Owner:** soma-moa (Conceiver: deundeuni)
* **Official Repositories:** github.com/soma-moa | github.com/deundeuni | **Official Domain:** somamoa.ai.kr
* **Applicable Licenses:** Creative Commons Attribution 4.0 (CC BY 4.0) & DPL v1.0 (Defensive Patent License)
* **Keywords:** POLYLINK-HUD, CWP-AR-HUD, Polyglot Link HUD, AR Glass HUD, Human-Centric Auxiliary AI Safety, Non-invasive HMI, Vision OCR, On-Device VLM, Error Lifecycle Blackbox Logging, RAG Solution Search, Enterprise Routing, NAS S3 MES Auto-Documentation, Legacy Equipment Language Barrier, Multilingual Control Panel, Target Language Agnostic, Native Language Translation, Extended Fusion, Privacy by Design, 4 Human Rights Protection Mechanisms, Human-in-the-Loop, PIPA, EU AI Act Compliance, World-Locked Anchoring, Cybersickness Mitigation, Cognitive Read Window, Non-contact Wire Break Detection, 1ms-class Visual Response, MIPI High-Z, Overload Resource Control, Downtime Loss Mitigation, Hands-Free Maintenance, BYOD Personal AR Glasses, Legacy Media Zero-Modification Overlay, Game UI Subtitles, Venue Standard Subtitle Application, FIRST-LIGHT, LAST-LIGHT, Seamless Transition, First Light Last Light Link, Auxiliary Governance, Axiom 0, Author Zero Liability, soma-moa L3 Social, Tri-State Isolation, deundeuni, Prior Art

---

## 0. Author Declaration & Motivation

### 0.1 Field-Driven Motivation, Human-Centric Auxiliary AI Safety & Auxiliary Governance
This architecture originated from a practical pain point observed in industrial environments: "At sites operating imported and legacy precision processing and control equipment for over 10 to 20 years, inability to comprehend control panel displays and manuals written in foreign languages causes simple one-line errors to halt operations for days, leading to massive Downtime Loss."

The primary premise of this specification is **"Human-Centric Auxiliary Safety First and Compliant Safe Operation of AI Systems Assisting Human Operators."** High-value and precision numerical control (NC/PLC) equipment tightly integrates precision calibration parameters with control logic. Arbitrarily modifying control panel software or reinstalling translation programs into internal systems introduces severe risks of bricking the entire control panel or losing calibration values. Furthermore, in environments contaminated with oil and dust, holding a smartphone to run camera translation applications compromises hands-free maintenance operations and distracts worker attention, increasing safety accident risks.

Addressing these challenges, this framework introduces **'POLYLINK-HUD (Polyglot Link HUD) Non-invasive Spatial HMI Gateway'**. Without modifying internal code or circuitry by even 1 Bit (Zero-Modification), it captures external display pixel streams and audio feeds via cameras and microphones, projecting real-time target language (customized to the worker's native language) subtitles and manual guidelines onto AR glass HUD lenses as spatial overlays.

The core identity `moa` transcends simple data gathering/collecting, embodying human warmth aimed at "embracing and gathering fragmented error logs and distributed terminals into one system." The vowel symmetry in `S O M A` - `m o a` and the lowercase hyphenated form `soma-moa` represent the open-source community identity.

This serves as a practical implementation of `soma-moa` Charter 0 (Axiom 0) and the Human-in-the-Loop philosophy: "Robots and AI are Subordinate, System Governance is Main, but even Governance must remain Auxiliary to primary human tasks." It maintains original equipment safety while aiming to improve first-line response capabilities of field technicians.

Identical language barriers extend beyond industrial sites into daily life (menus, signboards, textbooks, imported appliance manuals). This framework aims to mitigate entry barriers when playing console or PC games where dialogues and UIs are provided only in English, experiencing difficulties enjoying foreign-language subtitles on legacy media such as VHS, LD, DVD, and archival films without modifying the original media, or attending live theater, plays, and operas where the absence of subtitles hinders comprehension, forcing reliance solely on native-translated performances.

### 0.2 Wide-Area Survival Mesh Lineage & Privacy by Design
POLYLINK-HUD inherits L0 anchoring, Tri-State Isolation, Co-Survival Bridge, and H-INDICATOR mechanisms from master specifications `LAST-LIGHT` (Indoor/Underground L0 Anchor: Fire Extinguisher Cabinet) and `FIRST-LIGHT` (Outdoor Wide-Area L0 Anchor: Marine Buoy, Mountain Repeater). It expands industrial control panels into a new L0 anchor type, functioning as an L2 translation overlay module providing an uninterrupted translation link (Seamless Transition Link) from First Light (equipment signal) to Last Light (worker field of view).

This system prioritizes individual human rights and privacy protection. Adhering to Privacy by Design principles, it excludes functions that collect or analyze worker eye movement, facial expressions, or emotional states for evaluation purposes, maintaining strict compliance with applicable regulations (PIPA, EU AI Act, etc.).

### 0.3 Base Model & AI Scalability Definitions (Base vs Extended Fusion)
The optical vision OCR, speech STT, VLM/LLM contextual interpretation, and AR HUD spatial overlay projection mechanisms disclosed herein serve as the Master Reference Framework for spatial HMI gateways.

The Base model of POLYLINK-HUD operates using standard built-in sensors (RGB camera and 6DoF IMU) on AR glasses and edge terminals, adhering to the ultra-lightweight non-invasive auxiliary structure to minimize compute resource usage. Extended Fusion configurations that combine external non-contact sensors (IR/thermal cameras, non-contact EMF sensors, microphone arrays, smart rings, haptic modules, BLE/Wi-Fi/UWB modules, edge NPUs) or large-scale AI agents preserve and fully encompass technical rights under this prior art framework. By securing flexibility in hardware coupling, it proactively aims to maintain computational stability and processor overload protection even when modules are combined.

* **1ms-class Switching & Flexible Range Rule —** Visual overlay control, frame synchronization, and HUD layer disconnection (High-Z) timescales operate at a 1ms-class reference point (0.1ms to 10ms variable range) at the MIPI switch stage, encompassing complete display blackout within 1 frame (16.6ms) to cover hardware switching to display panel response domains.
* **Target-Language Agnostic Rule —** In multinational site environments where equipment default displays or standards are fixed in English or foreign languages, spatial subtitle and guidance layers are translated and projected 1:1 into the target language configured by individual non-native workers.
* **Non-Invasive Zero-Modification Principle —** Electrical or software modifications to internal PLCs, NC controllers, bus lines, and ROM firmware are excluded, operating strictly as an auxiliary system receiving external optical pixels and audio signals.
* **Hands-Free Spatial Alignment —** Head pose tracking and control panel UI coordinate anchoring allow workers to view native target language translation overlays directly above foreign display areas without shifting eye focus during hands-free tool operation.
* **Form-Factor Agnostic Rule —** Receiving and projecting devices are not limited to specific AR glasses, encompassing enterprise-issued units as well as personal consumer smart glasses purchased at the user's expense (BYOD, Bring Your Own Device) running software-level overlays.

### 0.4 Zero-Downtime & Offline Independence
During network disconnections or edge processing overloads, the system maintains offline independent operation via minimal OCR functionality and cached alarm code libraries, aiming to avoid operational delays or stoppages to equipment.

### 0.5 Non-Exclusive Interoperability
This architecture avoids lock-in to specific optical vision sensors or translation engines, functioning as an open public standard compatible with industrial vision standards, UVC specs, open-source VLM/LLM models, and common HMI protocols.

### 0.6 Operational Priority
During equipment emergencies or alarms, vision OCR and critical error code target language overlays take top execution priority, throttling high-resolution graphic rendering to maintain 1ms-class response continuity.

### 0.7 Universal Scope, 3 Sub-categories & Enterprise Storage Routing
This specification applies universally to legacy numerical control machine tools, foreign measuring instruments, imported automated control panels, precision terminal boxes, marine control panels, video conference translation, and consumer smart glass translation overlays. It defines three distinct operational sub-categories and enterprise auto-documentation routing structures:

* **Enterprise Sub-category & Storage Routing —** Focuses on operational continuity via L0 0.1ms E-Stop, L1 Many as One, and L2 physical isolation hardware execution. Maintenance logs and action results extracted from the non-invasive pipeline automatically route to enterprise-designated remote infrastructure (NAS, S3, MES, ERP systems) to assist in maintenance record documentation.
* **Everyday Sub-category —** Automatically suppresses speculative output when Vibe Search inference confidence falls below 90%. Covers menus, signs, books, manuals, video call captions, legacy media (archival films, VHS, LD, DVD) and console/PC game UI/dialogue subtitles, and live theater/play/opera subtitles. Restricted to temporary personal viewing; excludes recording, distribution, or derivative works.
* **Personal Sub-category —** Implements PII 10-second flush, 1x/2x haptic notifications, minimal logging, and Quiet Assist for personal consumer smart glasses (BYOD). Automatically excludes and blurs third-party faces and voices without external transmission. Legal liability for public space recording rests with the device owner.

### 0.8 Pure Conceptual White Paper & Zero Liability Notice
This document is a conceptual white paper published as defensive prior art based on personal field experience to prevent private patent monopolization by third parties and suggest technological development directions. This document contains no product quality warranties or repair guarantees. All operational outcomes and legal liabilities arising from referencing, implementing, or applying these concepts belong to the user, and the author (`deundeuni` / `soma-moa`) assumes zero civil or criminal liability.

### 0.9 Acknowledgement of Independent Prior Research
This architecture was independently conceived by the author; however, the possibility of similar independent research by other parties is acknowledged. The objective of this publication is to prevent private monopolization and open the concepts as public prior art.

---

## 1. Version History

* **v1.0 (2026-09-11) —** Initial release of `soma-moa` L3 Social HMI extension module `CWP-AR-HUD` v1.0.
* **v1.1 (2026-09-11) —** Renamed to `POLYLINK-HUD`, established `FIRST/LAST-LIGHT` lineage, clarified Extended Fusion, and defined dual licensing structure.
* **v1.2 (2026-09-11) —** Removed brand names, established game/venue subtitle extensibility, and defined BYOD private space blurring protections.
* **v1.3 (2026-09-11) —** Established Human-Centric Auxiliary AI Safety First, Error Lifecycle Blackbox Logging, RAG linkage, enterprise routing, and trade secret separation.
* **v1.3.1 (2026-09-12) —** **[Legacy Media & Zero-Modification Preservation Revision]** Defined non-invasive spatial overlays for legacy media (Archival Film, VHS, LD, DVD) and game UI/dialogue without modifying or damaging original physical media.

---

## 2. 3-Tier Applied Architecture

* **[L2] Auxiliary HMI & User Interface Layer**
  * AR Glass Spatial HUD — Projects target language (native language) subtitle overlays, 3D action guides, and wire break arrows directly over foreign control panel UIs.
  * Co-Survival Bridge / Smart Ring / Haptic Module — Delivers localized haptic feedback (1x/2x) during critical error events.
  * Monitoring & Enterprise Routing — Auto-routes maintenance history, pinout diagrams, and RAG resolution guides to enterprise NAS/S3/MES systems.
* **[L1] Perception & Inference Fabric**
  * Pixel Stream OCR/VLM Pipeline — Performs real-time segmentation and text extraction from control panel display areas.
  * RAG Solution Search & Edge LLM Engine — Analyzes error codes to perform real-time target translation and query on-device/remote RAG knowledge bases.
  * Spatial Anchoring & Tracking — Maintains world-locked subtitle positioning over physical panel coordinates using 6DoF IMU deadband filtering.
  * Extended Fusion Signal Module — Processes extended EMF and thermal camera signals to convert wire break coordinates.
* **[L0] Equipment & Hardware Layer**
  * Legacy Control Panels (CRT/LCD/LED displays), error indicator lights, foreign physical manuals, cable trays (Industrial L0 Anchor).
  * [Base Model] AR glass built-in RGB camera, 6DoF IMU, microphone array, see-through display (ultra-lightweight execution).
  * [Extended Fusion] Detachable EMF/thermal sensors, auxiliary emergency power, edge NPU processing unit.

---

## 2.5 AI Governance & Safety-First (4 Protection Mechanisms)

* **Abstract AI Engine & RAG Linkage Definition —** The AI processing layer encompasses on-device edge AI, lightweight VLMs, sLLMs, RAG knowledge retrievers, and server/cloud-linked models as an abstract cognitive/inference entity.
* **Privacy by Design & Human-Centric Auxiliary AI Safety 4 Protection Mechanisms —**
  * Systems are designed with human-centric AI assistance and safety as top priorities, excluding eye-tracking, face analysis, or emotional evaluation functions in compliance with PIPA, EU AI Act, and applicable privacy laws.
  * **1. Anonymized Delta Logging, PII 10-Second Flush & Private Space Blurring —** All frame data and PII are flushed from RAM within 10 seconds, retaining only CBOR 24B anonymized logs. When personal AR glasses scan private spaces, non-consenting faces and voices are immediately excluded/blurred and never transmitted externally.
  * **2. Quiet Assist —** Replaces intrusive audible alarms with 1x/2x localized haptic feedback, minimizing non-essential logging.
  * **3. Technician Dignity & Auxiliary Status Locking —** Ensures AI functions strictly as an auxiliary helper rather than a worker surveillance tool, reserving final decision authority exclusively for humans (Human-in-the-Loop).
  * **4. Just Culture & Overload Mitigation —** Avoids penalizing worker errors, actively establishing overload mitigation buffers.

---

## 3. Core System Blocks & Mechanisms

### A. Non-invasive Frame Capture & OCR/VLM Pipeline
* Scans control panel displays without physical contact using external vision cameras to receive pixel frames.
* Filters pixel moiré and reflection noise via asynchronous random sampling.

### B. Edge LLM Contextual Translation & RAG Solution Search Linkage
* Analyzes extracted foreign text to convert it into the user-configured target language in real time.
* Connects with on-device or remote RAG knowledge bases immediately upon capturing error codes to retrieve root causes and manual action guidelines.

### C. World-Locked Anchoring & Cybersickness Mitigation
* Locks subtitles and RAG action guides onto physical 3D control panel coordinates using 6DoF IMU data (World-Locked).
* Integrates with human Vestibulo-Ocular Reflex (VOR) mechanisms to mitigate visual-vestibular conflict during head movement, applying deadband filters to prevent text swimming.

### D. Cognitive Read-Time Window 2-Stage Resource Control
* **Stage 1 (Initial Capture, VLM Inference & RAG Search) —** Triggers NPU execution at 1ms-class low latency upon detecting new error text to generate target subtitles and RAG guidelines.
* **Stage 2 (Spatial Anchoring & Read Window) —** Once subtitles lock onto panel coordinates and the worker scans the text during the Cognitive Read Window, high-overhead VLM/LLM inference throttles down (Pause/Dormant), maintaining coordinates via lightweight IMU tracking.
* Aims to mitigate processor overheating, processing bottlenecks, and rendering jitter during continuous operation.

### E. Non-contact EMF / Thermal Extended Fusion Wire Break Detection
* Scans external magnetic field disconnections using extended non-contact EMF sensors or thermal cameras without stripping wires or making circuit contact.
* Projects estimated wire break locations directly onto physical cable trays or terminal blocks using AR HUD spatial overlays (colored layers and directional arrows).

### F. Hands-Free AR HUD Rendering & Haptic Assistance
* Enables technicians to review native language guides, wire break locations, and terminal pinouts hands-free while holding tools.
* Delivers 1x/2x localized haptic alerts during critical system warnings to alleviate visual fatigue.

### G. Axiom 0 Non-invasive Governance
* Operates as an external visual/auditory/haptic auxiliary layer without interfering with primary machine control systems, aiming to mitigate firmware bricking risks.

### H. Downtime Loss Mitigation & Self-First-Action Guide
* Guides field technicians through immediate first-line resolution of simple alarms and wire breaks, aiming to reduce line stoppages caused by waiting for external service engineers.

### I. Error Lifecycle Blackbox Logging & Enterprise Routing
* Automatically logs the complete process—from error detection and translation to RAG guide presentation, physical action completion, and error clearance—in a non-invasive blackbox format.
* Anonymized structured logs stripped of PII automatically route to enterprise-designated remote infrastructure (NAS, S3, MES), assisting in the automated documentation of maintenance history and AI training data.

### J. Human-in-the-Loop Auxiliary Governance & Trade Secret Separation
* Human-in-the-Loop execution operates as an auxiliary governance procedure ensuring that physical control actions are never executed without explicit operator approval or manual override. Specific pipeline control source code, OCR/VLM model weights, and algorithm parameters are maintained as proprietary Trade Secrets pursuant to Korean Patent Act Article 103 and 35 U.S.C. §273.

---

## 4. 4-Layer Survival Architecture Specs, Safety Philosophy & Dynamic Control

### 4.1 4-Layer Survival Architecture Quantitative Specs
* **L0 (Hardware/Switching) —** 0.1ms E-Stop cutoff, V-Home ±5mm 3D zero calibration, HMAC HW Bypass control.
* **L1 (Network/Communication) —** Many as One dual-redundant mesh, Raft consensus threshold 70% / 100ms latency control, CBOR packet spec (L0 24B + L1 33B, total < 50B), SDK size 35.2KB (< 42KB limit), base RAM usage 3.2KB (< 10MB limit).
* **L2 (Governance/Inference) —** Physical isolation between compute Brain and Governance, eFPGA validation < 0.02ms, PRELOCK 80% safety margin, E_STOP_LATCH < 0.1ms, RECOVERY requires Ed25519 signature.
* **L3 (User/HMI) —** Quiet Assist 1x/2x haptic notifications, PII memory flush within 10 seconds.

### 4.2 Safety Philosophy Inheritance & International Standards
Heinrich 300:29:1 ratio serves solely as philosophical motivation; physical engineering implementations reference international safety standards:
* Active implementation of Safety-II and Just Culture principles
* ISO 13849-1 Category 4 Performance Level e (PL e) compliance
* IEC 61508 SIL3 safety integrity level integration
* GDPR Article 5(1)(e) data minimization and storage limitation principles

### 4.3 Dynamic Resource Management & Defense Control
* **Rate Limiter —** Normalizes camera input frame rates and OCR processing cycles to mitigate processor overload and frame flooding.
* **T-Reg Suppressor —** Hardware-throttles execution cycles when terminal power or thermal metrics exceed threshold limits, aiming to prevent device crashes during extended wear.
* **Tri-State Isolation —** Triggers a 1ms-class (0.1ms to 10ms variable range) High-Z state at the MIPI switch stage during compute errors or NPU overloads, completing display blackout within 1 frame (< 16.6ms) to mitigate blocking the technician's view of physical equipment.

---

## 5. Standard Utilization & Legal Boundaries

* **Standard Compliance —** References ISO/IEC 14496, Bluetooth SIG, USB UVC, and industrial vision standards.
* **OEM Warranty Preservation —** Maintains non-invasive operation without altering physical or electrical states of target equipment, preserving original manufacturer warranties.

---

## 6. Future Applications, Industry Expansion & Standard Subtitle App Extensibility

Applies to legacy CNC AR maintenance, foreign meter retrofits, everyday consumer AR guides (signs, menus, manuals), legacy media (archival films, VHS, LD, DVD) and console/PC game UI/dialogue subtitles under zero-modification overlays, live theater/play/opera subtitles, and underground-industry-outdoor wide-area seamless transition links. Extensible to a Venue Standard Subtitle Application Platform where personal AR glasses receive and display real-time native subtitles based on venue spatial anchors and public subtitle feeds. First inventor prior art rights for all extension concepts—including error lifecycle blackbox logging and RAG linkage routing—belong solely to the author (`deundeuni` / `soma-moa`).

---

## 7. Practical Protection, Brand Rights & Legal Framework

* **Authoritative Original Notice —** Legal and technical interpretation relies primarily on the Korean original (`README.ko.md`). The English version serves solely as an auxiliary reference.
* **Brand & Domain Defense —** Maintains exclusive rights to open-source code name `soma-moa`, brand name `Somamoa`, and canonical domain `somamoa.ai.kr`, mitigating unauthorized trademark appropriation or patent privatization by third parties.
* **Dual Licensing Structure —** The white paper text is licensed under Creative Commons Attribution 4.0 (CC BY 4.0) for public open access. However, if a third party attempts to enforce patent rights derived from this concept against the author or ecosystem participants, DPL v1.0 (Defensive Patent License) terms trigger automatic retroactive revocation of their license.
* **Broad Scope Encompassment —** Prior art protections broadly encompass non-invasive frame capture, OCR/VLM overlays, RAG solution search linkage, error lifecycle blackbox logging, enterprise storage auto-documentation routing, target language independence, native language conversion, Base model lightweight execution, Extended Fusion, Privacy by Design human rights protections, 3 sub-categories (Enterprise/Everyday/Personal BYOD), World-Locked anchoring, Cognitive Read Window resource control, non-contact wire break detection, 1ms-class MIPI switching, FIRST-LIGHT/LAST-LIGHT links, soma-moa L3 Social integration, Tri-State Isolation, legacy media (VHS, LD, DVD, archival films) zero-modification overlays, game UI subtitles, venue standard subtitle applications, and BYOD personal AR glasses.
* **Commercialization Separation —** White paper originals contain pure open-source and prior art disclosures; commercialization roadmaps are managed in separate documentation.
* **Prior Use Rights & Trade Secrets —** Preserves prior use rights under Korean Patent Act Article 103 and 35 U.S.C. §273. Specific OCR model weights and AI parameters are protected as Trade Secrets.
* **Legal Counsel Recommendation —** Professional patent attorney review is recommended for formal defensive strategies.

---

## 8. Sources, Zenodo DOIs & Document Completeness

* **Master Governance Architecture:** GitHub - `soma-moa / soma-moa`
* **Master Survival Architecture:** GitHub - `deundeuni / chiplet-apu-multi-system-survival-architecture`
* **Architecture Strategy:** GitHub - `soma-moa / ARCHITECTURE_STRATEGY.md`
* **Indoor/Underground L0 Anchor Master:** GitHub - `soma-moa / LAST-LIGHT`
* **Outdoor Wide-Area L0 Anchor Master:** GitHub - `soma-moa / FIRST-LIGHT`
* **Master Uncertainty Evaluation Layer:** GitHub - `soma-moa / FIRST-LIGHT / H-INDICATOR`
* **CERN Zenodo Official Registries (6 DOIs):**
  * Zenodo DOI 10.5281/zenodo.22373538
  * Zenodo DOI 10.5281/zenodo.22373722
  * Zenodo DOI 10.5281/zenodo.22373704
  * Zenodo DOI 10.5281/zenodo.22373189
  * Zenodo DOI 10.5281/zenodo.22373686
  * Zenodo DOI 10.5281/zenodo.22374987
* **Canonical Gateway:** `somamoa.ai.kr`
* **Legal Precedents:** Korean Patent Act Article 103, US Patent Code 35 U.S.C. §273.
* **Version-Agnostic Citation Statement —** Version numbers of referenced repositories and documents are subject to ongoing updates. Prior art protections and core technical concepts disclosed herein are not restricted to specific version numbers, applying independently across all past, present, and future revisions of cited sources.
* **Document Completeness:** This specification possesses complete independent technical authority as a standalone document.

---

## Appendix A: Inventorship, Background & Legal Precedents
* **System Architect & Sole Inventor —** deundeuni (soma-moa) — Conceived independently from field experience as a factory sample worker and daily semiconductor construction site laborer. Sole intellectual authority for overall system architecture, non-invasive overlay circuits, and technical decisions.
* **Legal Precedents for Inventorship —** AI models functioned strictly as text editing tools. Sole inventorship belongs to human author `deundeuni` under US Supreme Court / Federal Circuit precedents (Thaler v. Vidal), USPTO February 2024 AI Inventorship Guidance, and European Patent Office Guidelines (EPO G-II 3.3.1).
* **Source Rights Attribution —** All intellectual property rights, vision overlay algorithms, and infrastructure anchoring mechanisms belong exclusively to the author (`deundeuni`) and official repositories (`soma-moa` / `deundeuni`).

---

## Appendix B: Version History
▶ Refer to Section 1 (Version History) in main text.

---

## Appendix C: AI Assistance Disclosure & Tool Operational Rules
* **Original Architecture & Concepts —** deundeuni (Human) — Sole Inventor, responsible for overall architecture, field motivation, and technical design decisions.
* **Auxiliary Text Editing Tools —** AI tools were utilized strictly under the human author's direction for grammar editing, text refinement, and document formatting (Auxiliary Text Editing Tools), taking no part in conceiving core inventive concepts.

---

## Appendix D: Legal Disclaimer & Responsibility Limitation
* **White Paper Nature & Auxiliary Notice —** Disclosed technologies (POLYLINK-HUD v1.3.1) constitute a pure conceptual white paper published to prevent private patent monopolization. It provides no operational guarantees for commercial production and functions strictly as an auxiliary reference.
* **Author Zero-Liability Declaration —** The author (`deundeuni` / `soma-moa`) assumes zero civil or criminal liability for equipment failures, maintenance errors, line stoppages, property damage, or legal disputes resulting from implementing or referencing this document. All operational responsibilities belong to the implementing entity.
* **Trademark Disclaimer —** Technical terms and standards referenced herein serve as field examples and imply no infringement of third-party trademarks.
