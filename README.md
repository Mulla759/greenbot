# Greenbot: RecruitMaxxing

> Greenbot is a specialized utility platform designed to optimize the internship recruitment process for students through community-driven data and automated outreach tools.

---

## Core Concepts

The platform centers on **RecruitMaxxing** — the practice of leveraging automation and collective intelligence to maximize internship placement probability.

| Pillar | Description |
|---|---|
| Collective Co-operation & Intelligence | Crowdsourcing recruiter data and interview processes to remove the "black box" of hiring |
| Outreach Automation | Reducing the friction of cold-emailing through templating and verified contact discovery |
| The "Blind" for Students | An exclusive, high-trust environment where students share real-time application status and W's |

---

## Privacy & Visibility Controls

Greenbot provides granular control over how user data and activity are shared with the community.

### Public Profile

Users can opt into a **Public Profile** state, which includes:

- **Global Feed Presence** — Activity and shared interview logs are visible on the main community feed.
- **Analytics Inclusion** — Data points contribute to platform-wide recruitment trends and success metrics.
- **Identity Toggle** — Users can choose to remain *Anonymous* or be *Attributed* (showing their handle/school).
- **Full Notification Suite** — Real-time alerts for interview updates, new recruiter leads, and chat mentions.

---

## User Auth & Invitation Process

To maintain high-quality data and prevent platform spam, Greenbot utilizes a **Secret Pipeline** authentication model.

1. **Invite-Only Access** — New accounts can only be created via a unique referral link from an existing verified user.
2. **Verification Layer** — Integration with student email domains or professional profiles to ensure a peer-to-peer environment.
3. **Tokenized Invites** — Each user is granted a limited number of invites to maintain controlled growth and community integrity.

---

## Technical Implementation

### System Architecture

| Layer | Stack |
|---|---|
| Frontend | React / Next.js + Tailwind CSS |
| Backend | Node.js / Express *or* Python / FastAPI |
| Database | PostgreSQL — relational mapping for recruiter and interview logs |
| Search | Indexed search for the recruiter database and `#process` history |
| Email Service | Resend / SendGrid via the Email Engine API |