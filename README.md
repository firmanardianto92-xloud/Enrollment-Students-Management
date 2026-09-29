# Enrollment Students Management

Interactive mock-up of an admissions dashboard for a school's **acceleration program** (SD / SMP / SMA). Every source of prospective students is tracked as a **lead**.

## Open it

Open `index.html` in a browser. There is no build step and no server.

## Demo accounts

| Email | Password | Role |
|---|---|---|
| kepala.admisi@cendekia.sch.id | Admisi2026! | Head of Admissions |
| dimas@cendekia.sch.id | Leads2026! | Admissions Officer |
| principal@cendekia.sch.id | Viewer2026! | Principal (view only) |

## What's inside

- **Login** for the management team.
- **Dashboard**:
  - KPIs.
  - A 7-stage funnel that flags the biggest drop-off.
  - Leads by source: Social Media (Instagram, TikTok, Facebook, Threads, X), Open House, and Event & Others (Education Expo, School Roadshow, Parent Referral, Website).
  - The current stage of each source's leads.
  - Follow-ups due today.
  - Team workload.
- **Pipeline board** showing each student card by current stage.
- **Leads table** with search, filters, sorting and a "Copy as CSV" button.
- **Student detail**:
  - Stage timeline.
  - Student data, parents, siblings and previous school.
  - Lead source and activity log.
  - Buttons to advance the stage, log a follow-up, or mark the lead as dropped.

Theme: soft green and white. Each lead source has its own color (Instagram pink, TikTok cyan, Facebook blue, Threads violet, X black, Open House green, Education Expo gold, School Roadshow orange, Parent Referral brown, Website slate).

Tracked stages: Open House Registration → Form Purchase → Assessment (Test) → Accepted → Payment → New Student Application Form → Enrolled.

## Sample data

There are 100 generated leads covering every stage, plus some dropped leads. The data is seeded, so it is the same on every load. All names, contacts and numbers are fictional. Changes made in the UI reset when the page reloads.

## System diagrams

Open `diagram.html` in a browser for the interactive version. All diagrams in one high-resolution image: [enrollment-system-diagram-HD.png](docs/diagrams/enrollment-system-diagram-HD.png) (3300 × 10350 px).

Each diagram as a separate PNG (3120 px wide) in `docs/diagrams/`:

- [1-gambaran-sistem.png](docs/diagrams/1-gambaran-sistem.png): system overview (sources → lead record → screens)
- [2-alur-pendaftaran.png](docs/diagrams/2-alur-pendaftaran.png): enrollment flowchart with follow-up and dropped paths
- [3-login-hak-akses.png](docs/diagrams/3-login-hak-akses.png): login and role access
- [4-data-per-tahap.png](docs/diagrams/4-data-per-tahap.png): data recorded at each stage

## Family ID Blueprint

An architecture proposal for growing the Enrollment Desk into a school-wide family lifecycle system: the Attract → Enroll → Grow → Continue → Advocate lifecycle, a layered architecture, the Family ID concept, the experience for each role, Home Portal content, CX principles, a phased roadmap and a Phase 1 cost estimate (setup to training).

- [Family-ID-Blueprint.html](docs/blueprint/Family-ID-Blueprint.html): open in a browser
- [Family-ID-Blueprint.pdf](docs/blueprint/Family-ID-Blueprint.pdf): A4 PDF
- [Family-ID-Blueprint.png](docs/blueprint/Family-ID-Blueprint.png): full page as one image
