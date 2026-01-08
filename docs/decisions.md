This document records key technical and product decisions made during development to keep the team aligned.

---

#1 MVP Scope Decisions
- Student-only access using `@umass.edu` email verification
- Manual cost splitting (no in-app payments)
- Privacy-first design (contact info hidden until ride confirmation)

---

#2 Architecture Decisions
- REST-based API architecture
- Frontend and backend separated (`client/` and `server/`)
- PostgreSQL as the primary database

---

#3 Matching Logic (Initial)
- Match rides based on destination
- Time window tolerance of ±2 hours
- Seat availability enforced at acceptance time

---

#4 Deferred (Phase 2)
- Real-time GPS tracking
- Payment integrations
- Gamification and rewards
