# ICIT Global Enterprise Procurement Directory Schema
### Anonymized High-Signal Talent Verification // The Iweology Project

To eliminate traditional hiring biases, systemic talent exploitation, and the administrative "noise" of unverified resumes, the ICIT Enterprise Procurement Directory enforces a Dual-State Identity Architecture. 

Personal identifying parameters are completely masked behind encrypted system tokens. Technical, operational, and ethical metrics are verified natively through continuous sandbox telemetry rather than arbitrary self-reporting. Full cryptographic deanonymization only occurs when an explicit handshake is authorized by the certified individual.

---

## 1. Core Profile Architecture & Mapping Matrix
The directory maps candidate profiles across eight foundational schema fields. The table below outlines how each metric is collected, masked, or exposed on the public enterprise search ledger:

*   **1. Name:** Covered by variable `user_legal_name` (String). Visibility is Encrypted / Masked. Verified via Paddle Account KYC.
*   **2. Picture:** Covered by variable `user_avatar_uri` (URI/Blob). Visibility is Completely Omitted. Replaced by an Immutable Alphanumeric System Token.
*   **3. ID:** Covered by variable `icit_block_id` (Alphanumeric). Visibility is Publicly Verifiable. Generated upon clearing the S_CIT threshold of 16 / 20 or higher.
*   **4. Age:** Covered by variable `user_birthdate` (Date/Timestamp). Visibility is Completely Omitted. Enforces backend validation for legal and Paddle transactional compliance.
*   **5. GitHub Handle:** Covered by variable `github_oauth_uid` (String/Object). Visibility is Restricted. Secure integration link authenticated at registration.
*   **6. Qualification:** Covered by variable `competency_track` (Object/Array). Visibility is Publicly Verifiable. Determined by passed Calibration Tracks and Language telemetry parameters.
*   **7. Country:** Covered by variable `iso_country_code` (String Alpha-2). Visibility is Publicly Verifiable. Evaluated via GeoIP and Localized Paddle regional routing verification.
*   **8. Work Status:** Covered by variable `availability_state` (Enum/State). Visibility is Publicly Verifiable. Candidate controlled dashboard initialization parameter.

---

## 2. Detailed Technical Field Implementations

### # Field 3: ICIT Cryptographic Identifier (icit_block_id)
Traditional user IDs are discarded. A candidate's public directory identity is tied strictly to their unique Autonomous Certification Grade (ACG) block. For example, a verified profile is rendered publicly on the directory index as:
*   `ICIT-ARCHITECT-8892`
*   `ICIT-PERIMETER-4412`

### # Field 6: Dynamic Qualifications & Track Verification
The qualification vector is divided into two distinct telemetry-driven data structures:

*   **A. Field Specialist Status (field_specialist_flag):** A strict binary indicator [Y/N] driven by whether the candidate has cleared a specialized competence pathway inside the assessment sandbox:
    *   Track 1 (C-ISA): Software Systems Architects.
    *   Track 2 (C-SME): Algorithmic Optimization Engineers.
    *   Track 3 (C-CCS): Crypto & Cyber Specialists (Elite Tier).
    *   Track 4 (C-TSD): Perimeter Defence Engineers.
*   **B. Coding Languages (verified_language_telemetry):** An array tracking the precise languages verified inside the containerized sandboxes. This captures real-world algorithmic execution speed, complexity scaling, and structural memory safety profiles natively.

### # Field 8: Workspace Mobility & Availability States
To accommodate borderless remote engineering procurement and protect currently engaged creators, the directory structures availability into a strict state machine model:

*   **State A: EMPLOYED_BUT_FLEXIBLE**
    *   *Definition:* The individual is currently under contract or fully employed but actively monitors the registry. They are open to automated enterprise programmatic invitations without advertising their job search publicly.
*   **State B: AVAILABLE_TO_WORK**
    *   *Sub-states:*
        1.  `FULL_TIME`: Available for permanent human-first systemic architecture placement.
        2.  `CONTRACT`: Available for specific, scoped corporate infrastructure deployments.
        3.  `FREELANCE`: Available for fractional, short-term algorithmic calibration tasks.

---

## 3. The Cryptographic Handshake & Enterprise Access Flow
By decoupling an engineer's technical and ethical capability from their personal identity markers, the ICIT Directory forces corporate procurement teams to evaluate talent purely on systemic cohesion. This protects high-capacity creators from traditional hiring noise and talent devaluation, while ensuring enterprises procure architects whose minds are fully aligned with technological excellence and collective wellbeing.

### Automated Baseline Interaction Sequence:
1. Enterprise Searches Directory on the procurement portal.
2. Only Masked Tokens and Verified P3 / MRE Metrics are exposed to the search interface.
3. Enterprise Triggers an Automated Interaction Request parameter block.
4. Candidate Reviews Enterprise Profile securely within their private dashboard dashboard state.
5. Core Logic Split executes automatically based on Candidate Response:
    *   **If Request is Rejected:** The interaction sequence is anonymously dissolved. No personal identifiers are recorded or passed.
    *   **If Handshake is Authorized:** A cryptographic public/private key exchange is initiated natively. Legal name, GitHub history, and active contact routines are safely deanonymized for that specific enterprise entity.

