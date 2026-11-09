# Summary: what to do this week (checked 9 Nov 2026)

## Read this first: two big caveats

1. **I couldn't open any application pages.** This session's network policy blocked page fetching for every job site and company site (Gradcracker, Bright Network, TARGETjobs, LinkedIn, Greenhouse, company career pages). The test fetches all failed. Your rule says to open the application page for every role, so instead I verified "open" status through the **search index**: listing snippets with a future deadline, "still live"/"posted X" markers, or employer pages saying the window is open. Every row in `jobs.csv` is labelled this way. **Spend 10 seconds on each link before applying.** Nothing was invented. Where salary or a date was inferred, it says so.
2. **I'm well short of your targets: 10 engineering roles and 3 consulting roles in the main list, against 30+ and 25+.** The reasons:
   - Most 2027 graduate schemes closed between late September and 8 November. That includes Airbus, EDF, Centrica, SSE, UKAEA, Aurora, Capgemini Invent, LCP Delta, Rystad, Equinor and McLaren. They're in `closed_or_unverified.csv` so you don't waste time on them.
   - The £35k floor removes most engineering consultancies and defence primes: Rolls-Royce £31k, AtkinsRéalis £32–34.5k, Frazer-Nash £33k, BAE £34k, PA Consulting £32.5k.
   - Many specialist consultancies don't publish salary or deadlines. Without page access I couldn't confirm them, so they sit in the "UNVERIFIED" part of `closed_or_unverified.csv`. **Several of those are worth a 2-minute check**: Baringa, KPMG Power & Utilities Transactions, Octopus Energy Graduate Hardware, EY Infrastructure Advisory, Elixirr, d-fine.

## Closing within 14 days ⚠️

| Deadline | Role |
|---|---|
| **13 Nov** | Frontier Economics – 2027 Graduate Economic Analyst (London) |
| **18 Nov?** | Baringa – Graduate Analyst, Energy & Resources (deadline unclear: sources say either 19 Oct or 18 Nov, so check today) |
| **22 Nov** | Arm – Graduate Program, Engineering Pathways |
| **22 Nov** | Riverlane – Engineering Graduate Scheme 2027 |
| (29 Nov) | Graphcore 2027 graduate roles (20 days, so just outside the window) |

## The 10 best roles to apply to this week (newest and best fit first)

| # | Role | Published | Deadline | Salary | Why |
|---|---|---|---|---|---|
| 1 | **Sovereign AI Operations – Graduate Engineer (Power)**, London | 2 Nov 2026 | rolling | £33.4k–£46.1k (stated) | The newest role found. Grid connections and storage for AI data centres combine energy, infrastructure and finance. Negotiate into the upper half. |
| 2 | **Arm – Graduate Program, Engineering Pathways**, Cambridge/Bristol/Manchester/Sheffield | ~late Oct 2026 (inferred) | **22 Nov** ⚠️ | £42.5k–£57.5k | Top deep-tech employer. Last cycle closed after 16 days, so apply in the next 48 hours. |
| 3 | **RWE – Generation Engineering Graduate Programme**, UK/DE/NL | 19 Oct 2026 | 4 Jan 2027 | ~£40k + £2k (est.) | Renewables engineering with a European option. **One RWE application per cycle**: weigh it against #8. |
| 4 | **Graphcore – Graduate Manufacturing Operations / Hardware Engineer 2027**, Bristol | ~Oct 2026 (inferred) | 29 Nov | ~£45k (est. from sibling ads) | An AI-hardware scale-up. Manufacturing Ops uses your engineering plus your VPC strategy experience. |
| 5 | **Newton – Graduate Consultant (UK)** | ~Sep 2026 | 25 Dec | £48k + £2.5k | The best-paid open consulting role, and not on your applied list. A classic springboard into VC. |
| 6 | **Riverlane – Engineering Graduate Scheme 2027**, Cambridge | unknown | **22 Nov** ⚠️ | £40k | A VC-backed quantum deep-tech company with a 12-month rotation. Assessment day 14 Jan. |
| 7 | **TTP – Graduate Consultant, Mechanical Engineering 2027**, Cambridge | unknown | not shown | not published (est. ≥£35k) | Invents new products, with a commercial side. Very close to the Espzen founder profile. |
| 8 | **RWE Supply & Trading – Commercial Graduate Programme 2027**, Swindon/Essen | unknown | 1 Feb 2027 | ~£42k (2026 figure) | The purest engineering + energy + finance blend: trading, origination and asset optimisation. |
| 9 | **SP Energy Networks – Engineering Graduate Programme** | unknown | 3 Jan 2027 | £36k + £3k sign-on | Grid build-out with solid pay and a long deadline. A safe energy option. |
| 10 | **Frontier Economics – 2027 Graduate Economic Analyst**, London | unknown | **13 Nov** ⚠️ | not published (likely well above £35k) | A specialist boutique with a strong energy practice. It's a stretch, because it wants an economics-focused Master's, but it closes in 4 days. |

Also worth a 2-minute check: **Octopus Energy – Graduate Hardware Engineer (Slough)**. It's indexed as posted around 4 Nov, so it's very fresh, and it's a great fit, but the salary isn't published. Email the recruiter.

## The 5 most important VC actions

1. **Use UCL's own fund.** Email the AlbionVC / UCL Technology Fund team and UCL Business this month. Offer a dissertation-linked technical-diligence project for spring/summer 2027. AlbionVC has converted interns into analysts on this fund before.
2. **Apply now to rolling stints**: Speedinvest Visiting Analyst – Climate Tech, First Momentum Venture Scout, Earlybird DeepTech Analyst Intern, and Siemens Energy Ventures Analyst Intern (London). These 6-month visiting roles are the main way graduates get in.
3. **Publish a thesis and 2–3 deal memos** (for example, grid-connection bottlenecks for AI data centres, or long-duration storage economics). Send them to analysts and associates at the 25 target funds in `vc_report.md`. This is what turns cold emails into conversations.
4. **Secure a strong back-door job for Sept 2027 in parallel.** The best options are Newton, RWE, Riverlane, Graphcore or Arm. Climate VC fundraising is at a multi-year low and junior seats are scarce, so don't bet the year on a direct VC offer.
5. **Network systematically**: 5 coffee chats a week, UCL alumni first. Keep a tracker, and follow up every 6–8 weeks with something useful (a sourced deal or a memo).

## How I searched (for transparency)

- **About 110 web searches** across: big-employer graduate schemes (Rolls-Royce, Airbus, BAE, JLR, bp, Shell, EDF, Centrica, National Grid, NESO, SSE, ScottishPower, RWE, Ørsted, Vestas, Siemens Energy, Hitachi Energy, ABB/Schneider, ASML, GE Vernova, Equinor); deep tech and scale-ups (Arm, Graphcore, Riverlane, Cambridge Consultants, TTP, PA, Ocado, Dyson, McLaren, MAHPP, Helsing, Wayve, Tokamak Energy, UKAEA, Proxima Fusion, Isar Aerospace, Astroscale, Open Cosmos, quantum firms, Octopus Energy); and consulting beyond the big names.
- **Consulting search, in layers:** (a) energy/climate specialists (Baringa, Aurora, Cornwall Insight, LCP Delta, Afry, Sia, Guidehouse, Rystad, Wood Mackenzie, BNEF); (b) economics boutiques (Frontier, Oxera, CRA, Compass Lexecon, NERA, Cornerstone, BRG); (c) operations/turnaround (Newton, Efficio, A&M, AlixPartners, FTI); (d) engineering/infrastructure advisory (WSP, Arup, AtkinsRéalis, Mott MacDonald, EY Infrastructure Advisory, KPMG Power & Utilities Transactions); (e) tech/TMT boutiques (Elixirr, Analysys Mason, Altman Solon, Delta Partners, d-fine); (f) European boutiques (Arthur D. Little, Horváth, Porsche Consulting, Simon-Kucher, Capgemini Invent EU); (g) strategy/commercial teams inside energy firms (RWE Supply & Trading, Siemens Energy Graduate Program, Shell, bp, Centrica). Excluded as requested: McKinsey, BCG, Bain, OC&C, L.E.K., plus similar big names (EY-Parthenon, Strategy&, Roland Berger, Kearney, Oliver Wyman, Accenture Strategy).
- **Trackers used:** Intervyo and EP Advisory (both have "checked on" dates), and visa-sponsor aggregators that show "added/still live" dates.
- **Dates:** I used publish dates where the index showed them. Some are *inferred* (for example, Arm wasn't open on 18 Oct but is now; Graphcore's date is inferred from the Gradcracker listing ID sequence) and are marked "approx." Unknown dates are listed after the dated roles.

## To get a fully verified re-run

Allow these hosts in the cloud environment's network settings (environment menu → Edit → Network access → Allowed domains), then ask me to re-verify: `www.gradcracker.com`, `www.brightnetwork.co.uk`, `targetjobs.co.uk`, `www.linkedin.com`, `job-boards.eu.greenhouse.io`, `boards.greenhouse.io`, `jobs.lever.co`, `apply.workable.com`, `join.com`, plus employers' career domains. Setup steps: https://code.claude.com/docs/en/cloud-environments#network-access

## Files

- `jobs.csv`: 13 roles that look open, sorted newest-published first (dated, then approximate, then unknown), with a `type` column.
- `closed_or_unverified.csv`: 54 rows: unverified-but-promising, closed, open but below £35k, and a not-yet-open watchlist (bp, JLR, Ricardo, Vestas, ESA, Ørsted, National Grid, FTI).
- `vc_report.md`: the full VC research.
