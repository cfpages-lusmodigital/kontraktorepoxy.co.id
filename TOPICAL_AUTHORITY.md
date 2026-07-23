# Topical Authority — kontraktorepoxy.co.id

## Role and boundary

`kontraktorepoxy.co.id` should become an evidence-led guide to **planning, procuring, executing, accepting, and maintaining resin-flooring projects through a contractor in Indonesia**. Its primary readers are building owners, facility and maintenance managers, procurement teams, consultants, and project supervisors who need a defensible project result rather than a chemistry encyclopedia.

The domain may explain resin chemistry only far enough to support a project decision. Broad epoxy chemistry belongs to the independent editorial property `epoxy.co.id`; generic floor-material knowledge belongs to `lantai.id`. This is a cross-domain distinction, not a cannibalization restriction: each domain may independently cover useful questions. On this domain, neutral education must remain separate from the existing commercial service hubs such as `/epoxy-lantai/`, `/floor-hardener/`, and `/waterproofing/`.

Geographic scope is Indonesia, including hot-humid sites, monsoon moisture, coastal exposure, occupied buildings, industrial shutdown windows, local procurement, and Indonesian K3 obligations. A place name deserves a page only when real local evidence changes the scope, logistics, climate response, regulation, supply, or case study; swapping city names is not editorial coverage.

## Evidence audited

Audit performed against the `main` branch of `cfpages-lusmodigital/kontraktorepoxy.co.id` on 2026-07-23.

| Evidence | Observed count/detail | Editorial implication |
|---|---:|---|
| Tracked files | 2,479; 1,074 HTML files | Static WordPress export, not a modern content collection |
| `sitemap-complete.xml` | 1,074 URLs | Sitemap count matches the HTML-page count but overstates useful coverage |
| Repeated locality variants | 922 URLs | Seven stems repeat across roughly 131–133 locations each; do not count as 922 distinct subjects |
| Primary service/product hubs | 7 | `/cat-epoxy/`, `/epoxy-3d/`, `/epoxy-lantai/`, `/floor-hardener/`, `/injeksi-beton/`, `/polished-concrete/`, `/waterproofing/` |
| Non-location root pages | 21 | 18 facility/use-case pages plus contact/about and the `hello-world` placeholder |
| Category/archive URLs | 113 | Eight category roots and about 105 paginated archives; navigational, not editorial depth |
| Other author/manager/contact/feed/sandbox patterns | 10 | Includes archive-like manager/WhatsApp routes and a malformed sandbox URL |
| `video-sitemap.xml` entries | 1,088 | Requires manual verification that every video is unique, present, playable, and materially useful |
| Dedicated article collection | 0 observed | New knowledge pages need an intentional route family and templates |
| Representative metadata | Commercial and repetitive | Titles frequently use `#1`; descriptions are broad and sometimes conflate systems |

Seven locality families account for 922 URLs: `cat-epoxy-*` (132), `epoxy-3d-*` (132), `epoxy-lantai-*` (132), `floor-hardener-*` (131), `injeksi-beton-*` (131), `polished-concrete-*` (131), and `waterproofing-*` (133). Existing pages must be evaluated with Search Console, analytics, backlink, conversion, and content-difference evidence before consolidation; URL count alone is not a deletion rule.

Representative use-case routes include `/pabrik/`, `/pabrik-makanan/`, `/farmasi/`, `/gudang/`, `/rumah-sakit/`, `/loading-dock/`, `/bandara/`, `/basement/`, and `/lapangan-basket/`. They establish commercial demand but currently provide little proof that requirements, tests, or acceptance criteria differ by facility.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Broad contractor homepage; combines multiple services | expand | Homepage remains commercial overview and links to knowledge hub | Confirm live conversion goals and canonical |
| `/epoxy-lantai/` | Main commercial epoxy-floor service | keep | Commercial scope, quotation, proof, and contact | Rewrite only after preserving rankings/leads |
| `/cat-epoxy/` | Product-sale intent mixed with application advice | keep | Commercial product route; neutral system selection belongs to KEP-03 | Verify whether product sales are still fulfilled |
| `/epoxy-3d/` | Decorative service page | manual review | Commercial decorative route; suitability and lifecycle claims need evidence | Search demand, real portfolio, image rights |
| `/floor-hardener/`, `/polished-concrete/` | Adjacent flooring alternatives sometimes described as epoxy | keep | Separate commercial service routes; comparisons belong to KEP-16 | Correct terminology and verify actual capability |
| `/waterproofing/`, `/injeksi-beton/` | Adjacent building-repair services, broader than resin flooring | keep | Separate commercial routes; interfaces belong to KEP-16 and KEP-05 | Confirm service ownership and specialist competence |
| Seven `service-location` families (922 URLs) | Large-scale city swapping with near-identical intent | manual review | Keep only substantively distinct, evidenced service areas; consolidate others to relevant service hub | GSC clicks/impressions, backlinks, leads, local proof, copy similarity, redirect map |
| `/category/*/page/*` (about 105 URLs) | Paginated WordPress archives in sitemap | noindex | Useful category hubs may remain crawlable; pagination should not compete with articles | Live robots/meta/canonical behavior and internal links |
| `/category/uncategorized/` | Thin legacy taxonomy | remove | Redirect only if a relevant destination exists | Backlinks, traffic, content membership |
| `/hello-world/` | Default placeholder | remove | Return 410 or redirect only if there is a genuinely equivalent page | Confirm no links/traffic |
| `/3d/http_/foolish-lobster.w5.wpsandbox.pro/3d/` | Malformed migrated sandbox URL | remove | 410 preferred unless a true equivalent is demonstrated | Backlinks, indexation, origin of route |
| `/author/*`, `/manajer/*`, `/whatsapp/*` and feeds | Archive/contact artifacts with pagination | noindex | Keep functional contact endpoint only; remove from sitemap | Confirm no operational dependency |
| 18 facility/use-case pages | Commercial landing pages with overlapping generic copy | expand | Each route owns service conversion for that facility; KEP-14/15 articles own neutral requirements | Real project evidence, differentiated specifications, leads |
| `video-sitemap.xml` (1,088 entries) | More entries than HTML URLs | manual review | Include only eligible, unique, embedded videos | Playback, thumbnails, rights, transcript/value, current video markup rules |

Primary same-domain risks are: repetitive location pages; category archives competing with service pages; neutral and commercial intents mixed together; unsupported `#1`, “food grade,” chemical resistance, fire, slip, ESD, hygiene, or durability claims; and terminology that treats polished concrete, floor hardener, waterproofing, and epoxy as interchangeable systems.

## Coverage matrix

| Completeness lens | Topic owner(s) | Coverage note |
|---|---|---|
| Definition, vocabulary, taxonomy, anatomy | KEP-01, KEP-03 | Contractor-facing system and layer vocabulary; deep molecular chemistry is out of scope |
| Materials, mechanisms, measurement | KEP-03, KEP-06, KEP-08 | Explain only decision, application, and verification consequences |
| History and evolution | KEP-01 | One bounded article connects older coating practice to current project controls |
| Need recognition and no-action option | KEP-01, KEP-02 | Includes when coating is unsuitable or diagnosis must precede a quote |
| Survey and diagnosis | KEP-02 | Substrate, moisture, contamination, movement, prior coatings, environment |
| Requirements and design | KEP-03, KEP-05, KEP-15 | Performance schedule plus details and specialist functions |
| Comparison and selection | KEP-03, KEP-16 | Resin-system choice and non-resin alternatives have separate owners |
| Budget and procurement | KEP-09, KEP-11 | Tender comparability, quantities, cost drivers, lifecycle value |
| Preparation | KEP-04, KEP-05, KEP-10 | Surface, detail, site segregation, utilities, shutdown readiness |
| Installation/construction | KEP-06 | Mixing, sequencing, environmental controls, workmanship stop conditions |
| Commissioning/handover | KEP-08, KEP-09 | Test plan, punch list, records, warranty prerequisites |
| Use, inspection, maintenance | KEP-13 | Cleaning, inspection, localized repair, recoat, end-of-life |
| Troubleshooting and repair | KEP-12, KEP-13 | Symptom diagnosis is separate from intervention planning |
| Upgrade and replacement | KEP-13, KEP-16 | Recoat, overlay, removal, or alternative floor decision |
| Stakeholders and site types | KEP-09, KEP-10, KEP-14, KEP-15 | Owner, consultant, contractor, HSE, operator, food/pharma/electronics users |
| Geography and climate | KEP-02, KEP-06, KEP-10 | Humidity, rain, coast, heat, logistics; no city swapping |
| Scale, traffic, retrofit, quality level | KEP-03, KEP-10, KEP-11, KEP-14 | Performance and sequencing, not price-tier labels |
| DIY versus professional | KEP-02, KEP-04, KEP-07, KEP-12 | Safe owner observations plus explicit stop conditions |
| Safety and health | KEP-07 | SDS-led chemical controls, silica dust, ventilation, PPE, emergency response |
| Failure modes | KEP-02, KEP-12 | Causes, evidence, consequences, and escalation |
| Standards and regulation | KEP-07, KEP-08, KEP-15 | Verify current applicability and editions per project; never infer compliance from product marketing |
| Environmental impact | KEP-07, KEP-11, KEP-13 | Waste, packaging, solvents, removal, service life |
| Evidence quality and myths | KEP-08, KEP-17 | Test reports, substrate evidence, references, change control, case-study proof |
| Search formats | All topics | Hubs, checklists, decision tables, calculators, diagrams, defect atlases, test records, case studies |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KEP-01 | Project fundamentals and suitability | Decide whether a resin-flooring project is the right intervention and frame a useful brief | Terminology; layer anatomy; coating versus screed; new build versus retrofit; need signals; no-action/alternative option; stakeholder roles; historical change from “paint job” to managed system | Layer diagram; decision tree; glossary; sourced history | Does not teach resin chemistry (context: `epoxy.co.id`) or sell the service (`/epoxy-lantai/` owns conversion) | 6 |
| KEP-02 | Site survey and substrate diagnosis | Collect defensible site evidence before selecting or pricing a system | Concrete age/condition; moisture sources and test planning; strength/soundness; contamination; cracks/joints/movement; existing coating; flatness/slope; temperature/humidity/dew point; access and utilities; stop conditions | Survey checklist; annotated photos; test-location plan; diagnostic decision tree | Does not prescribe surface-preparation production (KEP-04) or diagnose a completed-floor failure (KEP-12) | 6 |
| KEP-03 | Performance specification and resin-system selection | Translate use conditions into a comparable, testable system specification | Traffic/load; thickness; mechanical and chemical exposure; thermal cycling; UV; texture; color; cure window; epoxy/PU/PU-cement/MMA decision; primer/body/topcoat; sample/mock-up; evidence hierarchy | Requirement matrix; system cross-section; exposure questionnaire; manufacturer-data comparison | Does not compare non-resin floor families (KEP-16) or provide a sales quote (`/epoxy-lantai/`) | 6 |
| KEP-04 | Concrete surface preparation | Specify and verify preparation that produces a clean, sound, profiled substrate | Laitance; oil/grease; old coatings; grinding/shot blasting/scarifying; edge work; dust collection; silica hazard; profile selection; cleaning; weak substrate; readiness inspection | Method-selection table; ICRI/standard references; visual profile guide; QC checklist | Does not design crack/joint repairs (KEP-05) or cover liquid-resin PPE (KEP-07) | 6 |
| KEP-05 | Repairs, joints, coves, drains, and transitions | Prevent predictable failures at substrate defects and interfaces | Crack classification; active versus dormant movement; construction/control/expansion joints; patching; edge termination; wall coves; drains and slopes; penetrations; doorways; equipment bases; waterproofing interfaces | Detail drawings; defect map; hold-point checklist; specialist review | Does not own structural crack engineering or broad waterproofing/injection services (`/injeksi-beton/`, `/waterproofing/`) | 6 |
| KEP-06 | Mixing, application, curing, and workmanship | Supervise the application sequence and recognize stop conditions | Storage/conditioning; batch control; ratio and mixing; pot life; primer; body coat; broadcast aggregate; topcoat; wet-edge; recoat window; temperature/humidity/dew point; curing protection; cold joints; workmanship records | Method-statement template; sequence diagram; batch log; environmental log | Does not choose the system (KEP-03), define worker controls (KEP-07), or accept final performance (KEP-08) | 6 |
| KEP-07 | K3, chemical safety, dust, and environmental controls | Build a product- and task-specific control plan before work starts | SDS/label review; resin/hardener exposure; sensitization; ventilation; glove compatibility; eye/skin protection; respiratory program; silica from grinding; ignition/solvents; confined/occupied areas; spill response; waste; take-home exposure | SDS worksheet; hierarchy-of-controls plan; PPE matrix requiring competent review; emergency checklist | Does not prescribe medical treatment or select PPE without SDS/exposure assessment; KEP-04 owns preparation quality | 6 |
| KEP-08 | QA/QC, testing, acceptance, and handover | Agree how compliance will be demonstrated and recorded | Inspection/test plan; substrate/moisture records; profile; batch/environment logs; wet/dry film or thickness; adhesion; cure; visual defects; color/gloss; slip/fire/chemical claims; ESD tests; punch list; O&M baseline | ITP template; test-register; acceptance matrix; calibrated-instrument record; handover dossier | Does not invent universal pass values; project specification, current standards, product data, and competent parties set criteria | 6 |
| KEP-09 | Tender, scope, contract, warranty, and change control | Compare offers on equivalent scope and reduce commercial ambiguity | Employer requirements; BOQ; inclusions/exclusions; quantity basis; brands/equivalency; qualifications; samples; substrate risk allocation; variation process; payment/retention; schedule; warranty conditions; exclusions; claims | Tender checklist; bid-normalization table; scope template; responsibility matrix | Does not calculate quantities/cost scenarios (KEP-11) or market one contractor (`/epoxy-lantai/`) | 6 |
| KEP-10 | Planning, logistics, and occupied-site delivery | Build an executable work plan around operations and site constraints | Area release; phasing; shutdown; pedestrian/forklift segregation; dust/odor control; ventilation; material storage; utilities; access; weather; coastal/remote logistics; adjacent trade interfaces; reopening criteria | Phasing diagram; readiness checklist; permit/interface matrix; communication plan | Does not define chemical controls (KEP-07) or technical curing limits (KEP-06) | 6 |
| KEP-11 | Quantity, price structure, and lifecycle value | Estimate scope transparently and understand why quotations differ | Measured area; wastage; thickness-to-volume logic; repair/detail allowances; preparation cost; mobilization; shutdown cost; testing; maintenance; recoat; removal; lifecycle comparison; sensitivity | Transparent worksheet/calculator specification; cost-component table; scenario model | Does not publish invented market prices or replace a measured contractor quotation; contract comparability belongs to KEP-09 | 6 |
| KEP-12 | Defect and failure diagnosis | Move from visible symptom to evidence-based cause hypotheses and safe next steps | Blistering; peeling/delamination; pinholes/bubbles; fisheyes/craters; soft/sticky cure; color/gloss variation; cracks/joint reflection; wear/scratches; chemical attack; tire pickup; slippery surface; sampling and escalation | Symptom atlas; cause tree; photo protocol; investigation plan | Does not recommend a repair before cause confirmation; repair/recoat choices belong to KEP-13 | 6 |
| KEP-13 | Cleaning, maintenance, repair, recoat, and end-of-life | Preserve performance and decide between local repair, recoat, removal, or replacement | Cleaning chemistry compatibility; routine inspection; stain/spill response; local repair; scratch/wear management; recoat readiness; adhesion between coats; line marking; records; removal hazards; waste and handover | Maintenance schedule; compatibility checklist; repair decision tree; asset log | Does not diagnose root cause (KEP-12) or compare alternative floor families for replacement (KEP-16) | 6 |
| KEP-14 | Industrial and high-traffic facility delivery | Adapt the contractor brief and sequencing to ordinary industrial operations | Factory production; warehouse/racking; forklift routes; workshop/oil; loading dock; parking/ramps; airport/station/public circulation; shutdown and reinstatement | Facility requirement cards; traffic maps; phased case-study template; stakeholder checklist | Existing facility routes own commercial conversion; these articles own neutral requirement differences and must not be location-swapped | 6 |
| KEP-15 | Food, pharma, healthcare, ESD, and specialist performance | Separate validated specialist requirements from vague marketing labels | Food hygiene and cleanability; coves/drains; pharma/cleanroom contamination control; healthcare operations; ESD control program; chemical containment; slip testing; fire classification; evidence and ongoing verification | Requirement matrix; regulator/standard links; lab-report interpretation; competent expert review | Does not claim “food grade,” ESD, fire, antimicrobial, or slip compliance from a product name alone; each project sets verified criteria | 6 |
| KEP-16 | Alternatives, interfaces, and intervention choice | Choose epoxy, another resin, a non-resin floor, or an adjacent repair scope without category confusion | PU/PU-cement/MMA; floor hardener; polished concrete; tile/vinyl; sealers; waterproofing; concrete injection; overlays; repair versus replacement; interface ownership | Multi-criteria decision table; lifecycle comparison; interface diagram | Commercial owners remain `/floor-hardener/`, `/polished-concrete/`, `/waterproofing/`, and `/injeksi-beton/`; no chemistry encyclopedia | 6 |
| KEP-17 | Contractor qualification, project evidence, and governance | Verify that people, methods, records, and claimed experience match the project risk | Prequalification; competence; manufacturer authorization; HSE record; equipment; sample/mock-up; references; case-study evidence; inspection authority; NCR/change control; daily reporting; closeout and lessons learned | Prequalification scorecard; evidence checklist; anonymized case-study template; governance workflow | Does not rank or endorse vendors without reproducible evidence; commercial company proof belongs on `/tentang-kami/` and service routes | 6 |

Total planned briefs: **102**.

## Related-domain opportunities

| Domain/route | Independent viewpoint | Useful collaboration without forced network footprints |
|---|---|---|
| `epoxy.co.id` | Epoxy entities, chemistry, resin/hardener behavior, and broader applications | Cite only when chemistry depth materially helps; this domain translates data into contractor controls |
| `lantai.id` | Generic flooring taxonomy, materials, user needs, and maintenance | Compare floor families while keeping project execution here |
| `/floor-hardener/` and `/polished-concrete/` | On-domain commercial alternatives | Link from KEP-16 comparisons to their service scopes, never disguise them as epoxy |
| `/waterproofing/` and `/injeksi-beton/` | On-domain adjacent repair services | Link only when moisture/cracks require a separate diagnostic or specialist scope |
| Safety/construction portfolio properties | Broad K3 and construction education | Reuse source research, but write each page for its domain’s audience and intent |

Cross-domain topic overlap is allowed. Cannibalization analysis in this plan applies only to pages on `kontraktorepoxy.co.id`.

## Consolidation plan

1. Export GSC performance, backlinks, analytics, and lead evidence for all 1,074 URLs before changing routes.
2. Cluster the 922 locality variants by service stem and compare normalized body copy, titles, links, local evidence, conversions, and backlinks.
3. Keep a locality page only when it contains verifiable service-area value such as logistics constraints, locally documented projects, coverage commitments, or materially different site conditions. Do not manufacture local facts.
4. Build an explicit redirect/canonical/noindex map; never mass-redirect unrelated pages to the homepage.
5. Remove archive pagination and technical artifacts from XML sitemaps. Keep useful category hubs only when they provide curated navigation.
6. Separate the new neutral knowledge family under one stable convention, recommended `/panduan/<slug>/`, from existing root commercial routes.
7. Reconcile facility pages with KEP-14/15: the existing route remains a commercial landing page; a knowledge brief handles requirements, tests, and decision support.
8. Validate internal links, canonicals, status codes, structured data, video eligibility, and sitemap counts after each bounded migration.

## Internal-link architecture

- Create `/panduan-kontraktor-epoxy/` as the central hub for KEP-01 through KEP-17. Each topic hub links to all six children; every child links back to its topic and central hub.
- Use a lifecycle path: suitability (KEP-01) → survey (KEP-02) → specification (KEP-03) → preparation/details (KEP-04/05) → application (KEP-06) → QA/handover (KEP-08) → maintenance/failure response (KEP-12/13).
- KEP-07 safety pages link contextually from preparation, mixing, occupied-site planning, and removal—not from an indiscriminate site-wide block.
- Diagnostic pages in KEP-12 link to the relevant survey/prevention page and to KEP-13 intervention decisions.
- KEP-14/15 facility guides link to requirement selection, logistics, K3, and QA, then to a commercial service route only where the reader is ready to procure.
- KEP-16 comparison pages link to each relevant on-domain service hub and back to KEP-01’s no-action/alternative decision.
- KEP-09/11/17 procurement tools link to technical criteria but do not turn neutral technical pages into sales copy.
- Related links are chosen per row in `ARTICLE_CATALOG.md`; a fixed repeated list is prohibited.

## Evidence and editorial standards

1. **Substrate moisture:** report method, instrument, calibration, locations, slab condition, date, and environmental conditions. ASTM F2170 notes that results describe the tested locations and time; never convert one reading into a universal guarantee. Acceptance limits come from the specified system and current project documents.
2. **Surface preparation:** connect substrate condition, selected system, site constraints, preparation method, target profile, and QC. ICRI 310.2R/CSP concepts or an applicable current equivalent may guide the specification, but the project must verify edition and suitability.
3. **Adhesion and other tests:** define method, instrument, cure state, sampling plan, failure mode, repair of destructive test points, and agreed criterion. ASTM D7234 is an example source for pull-off testing on concrete, not a universal pass value.
4. **Chemicals and K3:** review the actual product label and SDS. Current Indonesian sources to verify include [Permenaker 5/2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [Kepmenaker KEP.187/MEN/1999](https://jdih.kemnaker.go.id/peraturan/detail/2608/keputusan-menteri-nomor-187-tahun-1999), and [Permenaker 8/2010](https://jdih.kemnaker.go.id/peraturan/detail/158/peraturan-menteri-nomor-8-tahun-2010), all recorded as applicable by JDIH Kemnaker at audit time. Recheck status before publication.
5. **Health controls:** uncured resin components can be hazardous; odor is not a safety instrument. Use the hierarchy of controls and product/exposure-specific glove, ventilation, eye, skin, and respiratory decisions. NIOSH’s [epoxy and resin guidance](https://www.cdc.gov/niosh/reproductive-health/prevention/epoxies-resins.html) is a primary research-agency starting point.
6. **Grinding dust:** concrete grinding can generate respirable crystalline silica. Method statements need dust-control and exposure-control review; OSHA’s [silica overview](https://www.osha.gov/silica-crystalline) is supporting international evidence, not a substitute for Indonesian legal review.
7. **Food/pharma/healthcare claims:** “food grade,” “hygienic,” “antimicrobial,” or “cleanroom” must map to the facility’s regulator, risk assessment, cleaning regime, detail design, and test evidence. A marketing brochure is insufficient.
8. **ESD:** treat flooring as one element in an ESD control program. Specify product qualification and compliance verification separately; verify the current IEC 61340 series or project-selected equivalent before naming editions or limits.
9. **Slip, fire, chemical, and durability claims:** identify test method, specimen/system build-up, laboratory, classification/units, conditions, and applicability to the installed system. Do not infer a floor’s performance from resin type alone.
10. **Case studies:** use real scope, site condition, constraints, dated photos with rights, system build-up, tests, changes, results, and limitations. Never fabricate experience, measurements, savings, or failures.
11. Every high-stakes page receives competent technical/HSE review and a “verify current project requirements” note before publication.

## First bounded publication cluster

Start with 12 connected assets:

1. `KEP-01-A01` — project-suitability decision.
2. `KEP-02-A01` — pre-quote survey checklist.
3. `KEP-02-A02` — moisture source and test plan.
4. `KEP-03-A01` — performance requirement schedule.
5. `KEP-04-A01` — surface-preparation method selection.
6. `KEP-05-A01` — crack and joint classification.
7. `KEP-06-A01` — application sequence and hold points.
8. `KEP-07-A01` — SDS-led K3 plan.
9. `KEP-08-A01` — inspection and test plan.
10. `KEP-09-A01` — comparable tender scope.
11. `KEP-12-A01` — blistering diagnostic guide.
12. `KEP-17-A01` — contractor prequalification scorecard.

This cluster follows one project from decision through procurement, installation, acceptance, and a common failure investigation. It should launch only when each asset has its specified evidence, reciprocal lifecycle links, and a single primary intent.

Monitor: valid indexation and canonical selection; impressions/clicks grouped by intent; checklist/tool completion or downloads; navigation from educational to appropriate commercial pages; qualified inquiry rate and disclosed project type; assisted conversions; return visits; and GSC query/page pairs that reveal same-domain cannibalization. Ranking alone is not success.

## Definition of done

- All 17 parent topics have exactly six distinct briefs in `ARTICLE_CATALOG.md` (102 total).
- Titles, slugs, and IDs are unique; slugs do not collide with existing tracked routes.
- Every brief has one intent, an explicit named boundary, valid related IDs, evidence requirements, priority, and bounded wave.
- The same-domain anti-cannibalization register covers system selection, preparation, moisture, costs, defects, facilities, safety, QA, contractor evaluation, and commercial routes.
- High-stakes claims have product/SDS, test, current regulation/standard, competent-review, and applicability gates.
- No city-swapped brief, invented case, universal price, unsupported standard clause, or unverified performance promise is published.
- Legacy URLs receive an evidence-based keep/expand/merge/redirect/canonical/noindex/remove decision before migration.
- The skill validator passes, proposed slugs are checked against existing routes, and the Git diff contains only intended documentation.
