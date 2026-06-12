# Connector Queue

Last updated: June 11, 2026.

This queue is the holding area between evidence ingestion and graph edits. It prevents the board from becoming either under-connected or over-claimed.

## Visual Encoding Notes

### Victim Anchor Node Size

Status: `implemented`.

Evidence: `index.html` draws nodes with `k:'victimAnchor'` as larger centered murdered-person anchors and uses regular `t:'victim'` nodes for smaller person-level victim/exoneree nodes.

Decision: Keep the larger Root, Birchmore, O'Keefe, Walshe, and Delgado-Garcia victim anchors as a style choice for navigation and moral focus. Do not let size imply blame, certainty, or evidence strength. The legend now names this as `Victim Anchor`.

### Public-Role Label Normalization

Status: `active audit`.

Evidence: Current graph labels; `WEB-SUFFOLK-FOXWORTH-KAMARA-2021-2023`; Root local records using `Sergeant Detective` / `Sgt. Det.` phrasing.

Decision: Keep source status words like `former`, `retired`, and `now` out of visible node labels unless the status is the accountability fact itself. Use the public role or rank that identifies the person in the source. For Boston Police detective titles, preserve the rank/detective distinction when the source provides it: `Sgt. Det.` and `Det. Lt.` are different from plain `Det.`. Daniel Flynn is now displayed as `Sgt. Det. Daniel Flynn`, while his former status remains in the evidence notes.

For prosecutor labels, use compact board forms: `DA`, `ADA`, `First ADA`, `Sp. ADA`, `AAG`, `SAAG`, and `SADA`. Do not use visible labels such as `Assistant DA`, `Assistant District Attorney`, or `Assistant Attorney General` when the role is attached to a proper name. Preserve the expanded wording in evidence prose when quoting or closely paraphrasing a source.

## Current Norfolk Hot-Button Issues

### Read / O'Keefe Civil Suit

Status: `lead`.

Evidence: `WEB-READ-CIVIL-SUIT-2026-06`.

Current board state: The Read/O'Keefe lane already has direct links to Karen Read, John O'Keefe, MSP, Canton Police, Proctor, Goode, and Norfolk DA figures.

Decision: Do not add new claim-heavy connectors from the complaint alone. First localize the complaint PDF, then split adjudicated facts from allegations and decide whether the suit creates filing edges, oversight edges, or source notes.

### Read / O'Keefe Relationship and Institutional Context

Status: `graph-ready`.

Evidence: `WEB-READ-MCLAUGHLIN-ALBERT-2025`; `WEB-READ-HIGGINS-CANTON-PD-2024`.

Current board state: Added a McLaughlin-to-Caitlin Albert personal/acquaintance connector, a Caitlin-to-Nicole Albert family connector, a Higgins-to-Canton Police professional connector, and a Higgins-to-Berkowitz communication/contact connector. These are all existing nodes in the Read/O'Keefe lane.

Decision: Keep these as context connectors only. The McLaughlin/Caitlin edge documents a litigated acquaintance and social-overlap issue, not a close-friendship or misconduct finding. The Higgins/Canton Police edge documents a satellite-office and vehicle-storage/work-vehicle connection, not Canton Police employment and not a federal-lane expansion. The Higgins/Berkowitz edge documents reported call/contact testimony and cross-examination context only.

### Read / O'Keefe Phone, Text, and Digital-Evidence Context

Status: `graph-ready`.

Evidence: `WEB-READ-GUARINO-PHONE-DATA-2024-2025`; `WEB-READ-HIGGINS-CANTON-PD-2024`.

Current board state: Added Guarino-to-O'Keefe, Guarino-to-Jennifer McCabe, and Guarino-to-Kerry Roberts case/evidence-handling connectors. Guarino-to-Karen Read already exists through the case lane.

Decision: Keep these as phone-data extraction, review, and testimony connectors only. Do not treat them as findings about the accuracy of the digital evidence or as misconduct findings. Do not add a separate Higgins-to-Brian Albert communication edge until a cleaner source supports something more durable than the existing personal/friendship edge.

### Sandra Birchmore Federal Superseding Indictment

Status: `graph-ready`.

Evidence: `WEB-BIRCHMORE-FARWELL-SUPERSEDING-2025`; `WEB-BIRCHMORE-FARWELL-DETENTION-AFFIDAVIT-2024`.

Current board state: Birchmore already functions as a victim anchor tied to Stoughton Police, Matthew Farwell, MSP/POST context, Canton, OCME, and related Norfolk/Canton institutions. The Stoughton Police Explorers program is documented as Stoughton Police context, not as a standalone public graph node.

Decision: Use the federal indictment and detention affidavit to harden existing Birchmore and Stoughton Police connectors. Preserve allegation language until adjudication.

### Stoughton Police Explorers / Birchmore / Farwell

Status: `folded back into Stoughton Police`.

Evidence: `WEB-BIRCHMORE-FARWELL-SUPERSEDING-2025`; `WEB-BIRCHMORE-FARWELL-DETENTION-AFFIDAVIT-2024`.

Current board state: Removed the standalone `Stoughton Police Explorers` institution/program node from the public graph. The program remains documented as Stoughton Police context in the evidence files.

Decision: Do not keep a separate Explorers graph node in the current victim/public-official view. Treat it as an offshoot/program of the Stoughton Police Department unless the project later opens a dedicated youth-program or departmental-program layer.

### Birchmore Federal Lane / Internal-Only Actors

Status: `internal-only`.

Evidence: `WEB-BIRCHMORE-FEDERAL-LANE-ACTORS-2025`; `WEB-BIRCHMORE-FARWELL-PRETRIAL-STATUS-2026`.

Current board state: The federal prosecutors, FBI federal actor, federal judge, and federal procedural actors are not represented as graph nodes.

Decision: Keep the federal lane out of the public chart for now. Document Leah B. Foley, Ted E. Docks, Elizabeth Riley, Torey B. Cummings, Brian A. Fogerty, Magistrate Judge M. Page Kelley, and Pam Bondi in the evidence files as federal-lane or procedural actors only. They may become public graph nodes later if the project scope shifts from Massachusetts accountability connectors to the federal prosecution lane.

### Delgado-Garcia Academy Charges and Reforms

Status: `graph-ready`.

Evidence: `WEB-DELGADO-GARCIA-INDICTMENTS-2026`; `WEB-MSP-ACADEMY-REVIEW-2026`.

Current board state: Delgado-Garcia is already a victim anchor, with MSP Academy-related nodes and several charged staff represented.

Decision: Keep the charged academy staff connected to Delgado-Garcia with charge/status language and add reform context as institutional evidence, not as individual culpability expansion.

### Norfolk County Public-Trust Cluster

Status: `lead`.

Evidence: `WEB-NORFOLK-CONFIDENTIAL-2024`; `WEB-NORFOLK-DA-FALLOUT-2025`.

Current board state: Root, Birchmore, and O'Keefe already share Norfolk DA, MSP, Canton/Stoughton/Brookline/Boston, and investigator-overlap lanes.

Decision: Treat these sources as prioritization evidence for a Norfolk-specialized pass. They justify focused ingestion across Root, Birchmore, O'Keefe, and related MSP/Norfolk DA figures, but individual connectors still need primary records, court filings, official reports, or direct quoted source material.

### Ana Walshe / County and State Actors

Status: `graph-ready`.

Evidence: `WEB-WALSHE-CASE-STATUS-2025`; `WEB-WALSHE-COHASSET-PUBLIC-OFFICIALS-2025`.

Current board state: Removed Cohasset Police Department, Chief William Quigley, Sgt. Harrison Schmidt, and Detective Commander Michael Lopes from the public graph. Brian Walshe remains styled as `Convicted`, and the visible Walshe lane is connected to Norfolk Superior Court, the Norfolk DA's office, MSP/investigator overlap, ADA Gregory Connor, and Judge Diane Freniere.

Decision: Keep the Walshe lane focused on county-level and state-level actors. Cohasset local police names stay documented internally as chronology, but they do not belong on the visible board for this pass because the conviction itself is not contested. Do not add private attorneys, private family/friend witnesses, or Brian Walshe's unrelated federal art-fraud actors to the public chart.

## Ready or Mostly Ready

### Historical Connector Tightening

Status: `implemented`.

Evidence: `WEB-HISTORICAL-CONNECTOR-TIGHTENING-1921-2022`.

Current board state: The historical layer now has four additional existing-node edges: Katzmann to Thayer in the Sacco/Vanzetti trial lane, Tufts to the SJC, Pelletier to the SJC, and Harshbarger to Coakley as a Middlesex DA professional-lineage connector. Coakley's Middlesex DA office edge was already present.

Decision: Continue using historical connectors when they explain a recurring Massachusetts institution, office, court, or public-accountability mechanism. Do not widen the historical layer into extra biographical names unless the source creates a clear board-relevant relationship between existing institutions, public officials, or accountability cases.

### Deegan / FBI Informant Murder-Conviction Lane

Status: `high-priority historical candidate; internal until federal-lane rule is decided`.

Evidence: `WEB-DEEGAN-FBI-INFORMANT-MURDER-CONVICTIONS-1965-2009`.

Current board state: The public board has Sacco/Vanzetti, Boston Strangler / DeSalvo, Bridgewater/SJC, Watch and Ward/Pelletier, and several recent wrongful-conviction lanes, but it does not yet represent the 1965 Edward "Teddy" Deegan murder convictions or the later Limone / Greco / Tameleo / Salvati exoneration and FBI-informant misconduct findings.

Decision: Treat Deegan as the obvious mid-20th-century murder-corruption coverage gap. Hold visible graph changes for one scope decision: whether the board allows a historical federal-lane exception for FBI Boston because the misconduct center is federal, even though the prosecution and conviction posture are Massachusetts/Suffolk County. If approved later, add only a small minimal structure first: Deegan as the underlying murdered person; Limone, Greco, Tameleo, and Salvati as small wrongful-conviction victims; Suffolk DA and Suffolk Superior Court as state institutions; and a restrained FBI Boston / federal-informant institution connector. Keep named FBI agents, Barboza, Flemmi, Patriarca, Durham, Hinkle, prosecutors, detectives, and civil-litigation family actors internal until the public graph can carry that complexity without over-expanding.

### Watch and Ward / Pelletier Historical Lane

Status: `implemented`.

Evidence: `WEB-WATCH-WARD-PELLETIER-ALLEN-SJC-1913-1975`; `WEB-CURLEY-COMMUTATION-AND-COAKLEY-1903-1950`.

Current board state: Watch and Ward Society now connects to DA Joseph Pelletier and to the Massachusetts Supreme Judicial Court, in addition to its existing Suffolk, Essex, Bristol, and court-context connectors.

Decision: Keep this visible lane narrow for now. The source trail supports Watch and Ward as private political-influence/accountability-pressure context around the Pelletier removal lane, but Godfrey Lowell Cabot, Daniel H. Coakley, William J. Corcoran, Boston Bar Association actors, booksellers, censorship-specific actors, and James Michael Curley should remain internal until the board intentionally opens a private-influence, Boston municipal-corruption, and censorship subnetwork. Curley's Truman commutation is documented, but it should not become a visible node unless a later pass adds the Coakley/Pelletier/Corcoran/Tufts bridge or another clear existing-node connector.

### Bridgewater / SJC Suppression Lane

Status: `implemented`.

Evidence: `WEB-TITICUT-FOLLIES-BRIDGEWATER-SJC-1966-1993`.

Current board state: `Titicut Follies (1967)` has been kept out of the public board. Bridgewater State Hospital now connects directly to the Massachusetts Supreme Judicial Court through a `filing` edge supported by the `Commonwealth v. Wiseman` litigation record and the related source trail. The `show` legend key remains generalized to `Documentary / Media` for existing media/public-record connectors such as `Boston's Finest (2013)`.

Decision: Keep this as an institutional-suppression lane, not a filmography lane. Do not add `Titicut Follies (1967)`, Frederick Wiseman, Elliot Richardson, Judge Harry Kalus, Judge Andrew Gill Meyer, Grove Press, individual Bridgewater staff, inmates, or later patient-death actors unless a later pass identifies a repeated public actor, court mechanism, or institution-level accountability connector.

### Local Police / DA Jurisdiction Backbone

Status: `graph-ready`.

Evidence: `WEB-LOCAL-POLICE-DA-JURISDICTION-2026-06`.

Current board state: Boston Police now connects to Suffolk County DA; Canton, Stoughton, and Brookline Police connect to Norfolk County DA; Lynn Police connects to Essex County DA; and Ayer Police connects to Middlesex County DA.

Decision: Keep these as `juris` edges only. They are structural prosecutorial-district connectors, not case-specific claims about conduct, discipline, or charging decisions.

### Victor Rosario / Lowell Regional Connector

Status: `graph-ready`.

Evidence: `WEB-ROSARIO-LOWELL-MIDDLESEX-ARSON-MURDER-WRONGFUL-CONVICTION-1982-2023`.

Current board state: Victor Rosario is already visible as a small wrongful-conviction victim node, but his lane is under-connected. Before this pass, he connected to Middlesex DA and DA John J. Droney, without a Lowell city institution or Middlesex Superior Court context.

Decision: Add Lowell Police Department as a visible institution. Connect Lowell Police to Middlesex DA with a `juris` edge, connect Rosario to Lowell Police with a narrow case connector, and connect Rosario to Middlesex Superior Court. This makes Lowell visible as the next non-Boston regional lane without adding every officer, fire investigator, civil-rights defendant, settlement actor, or fire victim from the Rosario case.

### Edward Wright / Hampden / Springfield Wrongful-Conviction Lane

Status: `implemented`.

Evidence: `WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025`; `docs/evidence/murder-conviction-review-matrix.md`; `docs/evidence/overturned-murder-conviction-mining.md`.

Current board state: Edward Wright remains a small gold-ring wrongful-conviction node. Penny Anderson, Springfield Police Department, Hampden Superior Court, Det. Alfred Ingham, Judge Jeremy Bucci, and DA Anthony Gulluni now appear as narrow public-board connectors tied to Hampden County DA and the existing M.J. Ryan connector.

Decision: Keep this visible lane limited to the court/police/DA structure and the named detective tied to the false-testimony/crime-scene-preservation finding. Mark Grant, Judge Sarah Hamilton, defense counsel, third-party culprit names, witnesses, and additional historical actors remain internal unless a later pass shows a repeated public-actor pattern.

### Schand / Wilhite / Springfield Wrongful-Conviction Expansion

Status: `implemented`.

Evidence: `WEB-SCHAND-WILHITE-SPRINGFIELD-HAMPDEN-WRONGFUL-CONVICTIONS-1986-2020`; `WEB-REGIONAL-CITY-MURDER-CANDIDATE-SCAN-1979-2026`; `docs/evidence/murder-conviction-review-matrix.md`; `docs/evidence/overturned-murder-conviction-mining.md`.

Current board state: Mark Schand and Charles Wilhite now appear as small gold-ring wrongful-conviction nodes in the Springfield / Hampden lane. Victoria Seymour and Alberto Rodriguez appear as the underlying homicide-victim nodes, not large anchors. Schand and Wilhite connect narrowly to Springfield Police Department, Hampden County DA, and Hampden Superior Court. Wilhite also connects to the existing Judge Peter Velis node because the reviewed sources document Velis's new-trial role.

Decision: Keep this visible layer institutional and court-anchored. Mark Mastroianni, Judge C. Jeffrey Kinder, City of Springfield, Anthony Pioggia, Steven Tatro, the named Schand civil defendants, witnesses, counsel, and settlement actors remain internal unless a later repeated-actor review supports public-board use.

### David DiCicco / Norfolk Assignment and Cross-Case Investigator Lane

Status: `graph-ready`.

Evidence: `WEB-DICICCO-NORFOLK-OVERLAP-2025-2026`; `WEB-WALSHE-COHASSET-PUBLIC-OFFICIALS-2025`.

Current board state: DiCicco now connects to Massachusetts State Police, Norfolk County DA, Birchmore, O'Keefe/Read, Walshe, and the existing MSP investigator-overlap cluster. The new graph change is the Norfolk DA assignment edge; the O'Keefe/Read and Walshe relationships remain on the existing `spine` connectors.

Decision: Treat these as investigator/assignment connectors only. The visible board should show the overlap, but misconduct or disciplinary conclusions require separate adjudicated or official disciplinary sources.

### Velis / Merrigan / L'Italien / Coughlin Farak Inquiry

Status: `graph-ready`.

Evidence: `WEB-FARAK-VELIS-MERRIGAN-LITALIEN-COUGHLIN-2016`.

Current board state: Judge Peter Velis and Judge Thomas Merrigan now connect directly to Det. Capt. Paul L'Italien and Capt. James Coughlin using `oversee` connectors.

Decision: Keep these as investigation-assignment connectors. The source describes the two State Police officers as assigned to provide investigative support and prepare a report for Velis and Merrigan; it does not make the officers case defendants or misconduct subjects.

### Commissioner Michael Cox / BPD Accountability Lanes

Status: `implemented for Cox/BPD context; OPAT and O'Malley / King lanes internal-only pending stronger review`.

Evidence: `WEB-COX-BPD-ACCOUNTABILITY-LANES-1995-2026`; `WEB-COX-OPAT-CRB-OVERSIGHT-2025-2026`.

Current board state: Cox has his original BPD employment connector, existing Cox/Conley/Williams 1995 beating connectors, existing oversight connectors to BPD actors already in the Read/O'Keefe lane, and a direct Read/O'Keefe public-accountability connector through the Dever dispute. Boston OPAT has been removed from the public graph after scope review; OPAT/CRB material remains documented as Cox/BPD accountability context because OPAT is officially separate from BPD but does not need its own visible node in the current victim/public-official layer. The Stephenson King Jr. / Nicholas O'Malley fatal-police-shooting lane has been removed from the public board and retained only as an internal lead pending direct video and court-record review.

Decision: Cox remains board-relevant as both a past BPD victim of blue-wall conduct and a current commissioner tied to accountability disputes, but further visible-board expansion should not depend on the O'Malley arrest lane unless direct video and court records are reviewed. Continue mining Cox only if official BPD, OPAT, court, POST, or City Council records create a direct accountability connector. Do not add generic biography edges merely because Cox held many commands, and do not connect him to John Mulligan unless a source directly ties Cox to the Mulligan / Sean Ellis lane.

### Steve Nelson / Norfolk Victim Witness Advocate

Status: `internal-only after scope review`.

Evidence: `WEB-READ-RETRIAL-NORFOLK-STAFF-2025`.

Current board state: Steve Nelson has been removed from the public graph but remains documented in the witness/evidence files.

Decision: A possible witness-list role is not strong enough for the visible public board unless a later source shows a more direct accountability function. Keep Nelson internal for completeness.

### Norfolk County DA / Juston Root

Status: `graph-ready`.

Evidence: `ROOT-NDAO-2020-REPORT`; `ROOT-FIRST-CIRCUIT-2024`.

Current board state: Root is already connected to `INORFOLK`, `morrissey`, the main shooting-officer cluster, Brookline, Boston Police, Massachusetts State Police, OCME, and related investigative/personnel nodes.

Decision: Keep the current graph connectors. The evidence supports institutional review and no further action; it does not, by itself, support stronger misconduct language.

### David Godin / Root Body-Worn Camera Lane

Status: `graph-ready`.

Evidence: `ROOT-GODIN-IAD-2022-0053`; `ROOT-GODIN-BWC-MOTION-2021`; `ROOT-FIRST-CIRCUIT-2024`.

Current board state: Godin is connected to Root and Boston Police. William Doogan and Marc Sullivan have been added as separate Root/BPD handling connectors.

Decision: Keep the connectors role-based. These sources support the BWC-handling lane, but they do not turn every BWC assertion into adjudicated misconduct language.

### Root Federal Civil Action / Shooting Officer Cluster

Status: `graph-ready`.

Evidence: `ROOT-BANNON-COMPLAINT-2020`; `ROOT-FIRST-CIRCUIT-2024`; `ROOT-NDAO-2020-REPORT`.

Current board state: David Godin, Joseph McMenamy, Leroy Fernandes, Brenda Figueroa, Corey Thomas, and Paul Conneely already connect to Root. Michael St. Peter, John Broderick, Christopher Elcock, David Wagner, and Brookline/Boston institutional connectors are also present.

Decision: Preserve the existing officer-cluster connectors. Use the First Circuit opinion as the primary adjudicated source for outcome language and use the complaint as a filing/claim source only.

### Justin Desmarais / Valet Collision

Status: `corrected`.

Evidence: `ROOT-BANNON-COMPLAINT-2020`.

Current board state: Justin Desmarais remains connected to David Godin and Michael St. Peter, but the direct Desmarais-to-Juston Root edge has been removed. His node category has also been changed from `Victim` to `Connected` so the board does not imply that he was a victim of Juston Root.

Decision: Do not connect Desmarais directly to Root. Godin and St. Peter are tied directly to Root because they shot at Root. Desmarais is tied to Godin and St. Peter because of the separate valet encounter involving those officers. The current evidence note does not resolve which officer shot Desmarais, so the graph should keep Desmarais connected to both officers without drawing a Root edge or assigning a shooter.

### Brian Walshe / Ana Walshe Direct Connector

Status: `corrected`.

Evidence: current graph source state; Walshe source-ledger entry still needed.

Current board state: The direct Brian Walshe-to-Ana Walshe edge is now a family connector, not a generic case connector. Brian Walshe is now a convicted node, and Ana Walshe remains a victim anchor.

Decision: Keep the direct relationship visually distinct from the investigative/prosecution connectors. Do not let the family connector soften or replace the separate criminal-case status language attached to Brian Walshe.

### Marc Sullivan / Root FDIT Connector

Status: `graph-ready`.

Evidence: `ROOT-FIRST-CIRCUIT-2024`; `ROOT-GODIN-IAD-2022-0053`.

Current board state: Added `Sgt. Det. Marc Sullivan` as a separate node connected to Root, Boston Police, and Godin.

Decision: Keep this separate from the existing `Sgt. Michael Sullivan` node. The Root archive contains a Michael Sullivan Form 26 trail and a Marc/Mark Sullivan FDIT trail; merging them would create a name error.

### William Doogan / Godin BWC Handling

Status: `graph-ready`.

Evidence: `ROOT-GODIN-BWC-MOTION-2021`.

Current board state: Added `Sgt. Det. William Doogan` as a Root/BPD connector tied to Godin.

Decision: Treat Doogan as a chain-of-handling/source-note connector, not as a blame connector.

## Priority Holds

### John Fanning / Root Public-Records Email

Status: `graph-ready for Root/Brookline correspondence; separate Fanning public-records PDF still hold`.

Evidence: `ROOT-BUKHENIK-FANNING-IMAGE-2020`; `ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020`; `_DRIVE_FULL_INDEX.tsv` lists `8 BULLETS 02-06-20 FANNING Email from Public Records Request Norfolk DA.pdf`; `_CAREER_INVENTORY_NorfolkCounty.md` flags the separate Fanning PDF as a priority retrieval item.

Current board state: Fanning already connects to Root, Karen Read, Birchmore, MSP, Norfolk DA, Bukhenik, Broderick, Mattaliano, and Crawford. The Root/Brookline correspondence now includes a direct Fanning-to-Broderick communication connector in addition to their professional connector.

Next action: locate or download the separate Fanning PDF, OCR it, and determine whether it supports a stronger Fanning-specific public-record connector, a Norfolk DA communication connector, or only a source note. Do not infer that stronger connector from the Drive filename alone.

### Yuriy Bukhenik / Root Public-Records Correspondence

Status: `graph-ready`.

Evidence: `ROOT-BUKHENIK-FANNING-IMAGE-2020`; `ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020`; `_DRIVE_FULL_INDEX.tsv` lists `MSP- Yuri Bukhenik Brookline officers.png` and two indexed copies of `Tpr. Bukhenik Email Correspondence_redacted.pdf`.

Current board state: Bukhenik already connects to Root, Karen Read, MSP, Norfolk DA, Proctor, Tully, Guarino, Prince, DiCicco, Stoughton, Stoughton High context, Fanning, Crawford, Elcock, and Wagner.

Decision: The correspondence supports Bukhenik as a Root/Brookline communication, interview-handling, and report/transcript-coordination connector. The Elcock and Wagner connectors are case-handling links, not blame connectors. Do not use the Guarino/Brookline interview reference as a public board edge until a reviewed transcript or named-subject record supports a narrower connector. Do not use any of this correspondence as a misconduct source without a separate adjudicated or investigative record.

### David DiCicco

Status: `lead`.

Evidence: `_CAREER_INVENTORY_NorfolkCounty.md` says DiCicco overlaps Root, Read, and Walshe, but the first local Root-mirror text search only found that inventory entry.

Current board state: DiCicco already has Root and Read spine edges and a Walshe edge.

Decision: Do not strengthen or expand DiCicco until the Root-specific source is identified. Treat the existing edge as inherited from prior documented work, not freshly proven by this pass.

## Needs Primary Source

### William Farwell / Robert Devine / Joshua Heal

Status: `lead`.

Evidence found this pass: the DOJ indictment and detention affidavit support Matthew Farwell, Stoughton Police, Police Explorers, Canton, and OCME. The detention-affidavit text search did not surface William Farwell, Robert Devine, or Joshua Heal by name.

Current board state: William Farwell, Robert Devine, and Joshua Heal already have Birchmore graph edges inherited from prior work.

Next action: recover the civil-case filings, POST materials, internal-affairs findings, or other primary documents that directly support each edge before strengthening their labels, adding new edges, or treating them as federal-case evidence.

### Kathleen Prince

Status: `partial graph-ready; remaining communication edge still needs verification`.

Evidence: `WEB-READ-RETRIAL-NORFOLK-STAFF-2025`; `WEB-PRINCE-OCONNELL-SJC-2012`. No direct Root-mirror text/OCR hit was found in the searched OCR, index, or inventory files.

Current board state: Prince is represented as MSP, Read/O'Keefe case, O'Connell/SJC court-record context, and a communication connector to Jennifer McCabe.

Decision: The MSP, Read/O'Keefe, O'Connell, and SJC connectors are supported enough to keep. Do not add Root connectors for Prince without a direct source. The Prince-to-McCabe communication connector should remain a verification target until a transcript, filing, or stable source for the precise statement/interview relationship is recovered.

### Coleen Crawford

Status: `graph-ready for Root/Fanning/Bukhenik digital-evidence connectors; discovery-motion expansion still needs docket-copy verification`.

Evidence: `WEB-READ-RETRIAL-NORFOLK-STAFF-2025`; `WEB-READ-BIRCHMORE-DISCOVERY-MOTION-2025`; `WEB-NDAO-CRAWFORD-TULLY-DIGITAL-EVIDENCE-2019`; `ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020`.

Current board state: Crawford is represented in the Read/O'Keefe lane, Norfolk DA employment context, Root context, a Fanning business/community connector, a Bukhenik communication connector, and a narrow Tully professional-training connector.

Decision: The Read/O'Keefe and Norfolk DA connectors are supported by witness-list reporting. The Root, Fanning, and Bukhenik connectors are supported by the Root/Brookline correspondence packet as digital-evidence handling and communication connectors. The Tully connector is supported only as a professional/training overlap from the Norfolk DA homicide-conference release. The Read/Birchmore discovery motion is a lead for broader cross-case work, but it needs an official docket copy before public graph expansion.

### Norfolk County DA Staff Beyond Morrissey

Status: `partly graph-ready; active lead for additional office staff`.

Evidence: `ROOT-NDAO-2020-REPORT` supports Morrissey and the office-level Root review. `WEB-READ-RETRIAL-NORFOLK-STAFF-2025` documents Steve Nelson internally as a Read/O'Keefe/Norfolk DA office witness-list actor. `WEB-BELAND-NORFOLK-WALSHE-READ-2023-2024` supports Beland's visible Norfolk DA, Walshe, and Read/O'Keefe correspondence connectors. `WEB-READ-BIRCHMORE-DISCOVERY-MOTION-2025` remains only a lead for Beland and other Read/Birchmore crossover names, pending official court-copy verification. `_DRIVE_FULL_INDEX.tsv` lists NDAO public-record and Axon audit items that may identify additional office staff. `_CAREER_INVENTORY_NorfolkCounty.md` lists David Traub and Hank Brennan, but those entries are Read-prosecution context rather than Root-specific evidence.

Current board state: Beland is represented as a Norfolk DA prosecutor connected to the Walshe lane and to the Read/O'Keefe correspondence/filing lane. She is not connected to Birchmore on the public board.

Next action: ingest NDAO public-record files and identify staff names from primary records before adding office-wide connectors. The Drive file `34 Digital Evidence Report.pdf` is present but image-only through the connector, so it should be OCR'd before any claims are drawn from it. Do not add every DA employee from a witness list; add only role-based connectors that clarify the public-accountability structure.

### Recent Overturned Murder Conviction Mining

Status: `partly graph-ready; active lead list`.

Evidence: `WEB-SUFFOLK-FOXWORTH-KAMARA-LARKIN-FLYNN-2021-2023`; `WEB-GAINES-OMALLEY-OVERTURNED-MURDER-CONVICTION-2024-2025`; `WEB-OMALLEY-SUFFOLK-WRONGFUL-CONVICTION-CLUSTER-2022-2026`; `WEB-LUCIEN-BRAZIL-SUFFOLK-BPD-2021-2024`; `WEB-RICCIUTI-ROSA-MCGEE-SUFFOLK-WRONGFUL-CONVICTION-2023-2026`; `WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025`; `WEB-SCHAND-WILHITE-SPRINGFIELD-HAMPDEN-WRONGFUL-CONVICTIONS-1986-2020`; `WEB-CIFIZZARI-WORCESTER-MILFORD-WRONGFUL-CONVICTION-1979-2019`; `WEB-TANNER-BRISTOL-DARTMOUTH-POSTHUMOUS-DNA-TESTING-1988-2026`; `WEB-PINA-DISAMBIGUATION-SUFFOLK-1999-2026`; `WEB-CARVER-ESSEX-BEVERLY-FIRE-2024-2026`; `WEB-TSE-SUFFOLK-LEGAL-INSUFFICIENCY-2024`; `WEB-MICHAEL-J-SULLIVAN-MIDDLESEX-WRONGFUL-CONVICTION-2014-2024`; `WEB-PINO-STATE-POLICE-CRIME-LAB-2007-2024`; `docs/evidence/overturned-murder-conviction-mining.md`; `docs/evidence/murder-conviction-review-matrix.md`.

Current board state: Robert Foxworth, Barry Kamara, Raymond Gaines, Milton Jones, Floyd Hamilton, Joseph Jabir Pope, James Lucien, Rickey McGee, Edward Wright, Mark Schand, Charles Wilhite, Gary Cifizzari, Dewane Tse, and Michael J. Sullivan are represented as small exonerated/wrongful-conviction or legal-invalid-conviction nodes, not large victim anchors. Foxworth and Kamara connect to Suffolk DA, Boston Police, Suffolk Superior Court, former Suffolk ADA James Larkin, and former Boston Sgt. Det. Daniel Flynn. Gaines, Jones, Hamilton, and Pope connect narrowly to Suffolk DA, Boston Police, Suffolk Superior Court, and the existing Det. Peter O'Malley node. Lucien connects narrowly to Suffolk DA, Boston Police, Suffolk Superior Court, and the existing Det. John Brazil node. McGee connects narrowly to Suffolk DA, Boston Police, Suffolk Superior Court, and Judge Michael Ricciuti. Wright connects narrowly to Hampden DA, Springfield Police, Hampden Superior Court, Penny Anderson, Det. Alfred Ingham, Judge Jeremy Bucci, DA Anthony Gulluni, and DA M.J. Ryan Jr. Schand and Wilhite connect narrowly to Springfield Police, Hampden DA, Hampden Superior Court, and their underlying homicide-victim nodes, with Wilhite also connected to Judge Peter Velis. Cifizzari connects narrowly to Worcester County DA, Worcester Superior Court, Milford Police, Concetta Schiappa, and the existing DA Joseph D. Early Jr. node for the 2019 dismissal role. Ricciuti also connects to Thomas Rosa Jr. and Suffolk Superior Court. Tse connects narrowly to Suffolk DA, Suffolk Superior Court, and the SJC. Michael J. Sullivan connects narrowly to Middlesex DA, Middlesex Superior Court, Massachusetts State Police, and Chemist Robert Pino. Pino connects to Massachusetts State Police and the existing State Police Crime Laboratory node.

Decision: Keep the public board focused on repeated actor patterns and court/prosecution/police institutions. The matrix now separates visible small-node additions from internal holds. The O'Malley cluster is visible, but McConkey, Daley, Curran, Flynn, Goodale, witnesses, victims, and case-specific prosecutors remain internal pending stronger repeated-actor proof. The Ricciuti/Rosa/McGee pattern is visible, but individual detective, prosecutor, witness, investigator, counsel, and victim names remain internal pending stronger repeated-actor proof. The Wright/Schand/Wilhite Hampden pattern is visible only as a narrow court/police/DA lane plus underlying homicide victims. The Cifizzari Worcester County / Milford pattern is visible only as a narrow court/police/DA lane plus Concetta Schiappa, and it should not be described as a Worcester city-police lane. Tanner is now documented as a Bristol / Dartmouth-New Bedford internal watch lane, not a public-board node, because the reviewed sources support continued DNA testing but not a DNA result, posthumous exoneration, or prosecution-ending posture. Stephen Pina and Daniel Pina are now disambiguated but remain internal: Stephen because the reviewed sources show active Commonwealth appeal/retrial uncertainty, Daniel because the reviewed sources confirm exoneration posture but not actor-level public graph details. James Carver has now been refreshed through the Essex / Beverly fire lane and should be treated as wrongfully convicted in the project evidence, but remains internal because the Essex DA appeal and possible retrial posture remains live after the June 10 post-argument check. Dewane Tse is visible as a legal-invalid-conviction victim after the SJC ordered required findings of not guilty for insufficient evidence. Michael J. Sullivan is visible as a wrongful-conviction victim after the SJC new-trial decision, 2019 no-retrial posture, and 2024 civil innocence verdict; use `mjsullivan` only, not any existing Sullivan node. Robert Pino is visible as a narrow exposed State Police crime-lab connector because Boston.com's 2024 Sullivan account ties him directly to the physical evidence that implicated Sullivan and the SouthCoastToday / Standard-Times 2007 article page supports the lab-level DNA database role. The next research pass should either revisit Carver after more time has passed for an Appeals Court decision or test another regional Massachusetts murder-conviction lane using court-level sources.

### Non-Boston Regional City Expansion

Status: `active regional queue`.

Evidence: `WEB-REGIONAL-CITY-MURDER-CANDIDATE-SCAN-1979-2026`; `WEB-ROSARIO-LOWELL-MIDDLESEX-ARSON-MURDER-WRONGFUL-CONVICTION-1982-2023`; `WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025`; `WEB-SCHAND-WILHITE-SPRINGFIELD-HAMPDEN-WRONGFUL-CONVICTIONS-1986-2020`; `WEB-CIFIZZARI-WORCESTER-MILFORD-WRONGFUL-CONVICTION-1979-2019`; `WEB-TANNER-BRISTOL-DARTMOUTH-POSTHUMOUS-DNA-TESTING-1988-2026`.

Current board state: Lowell / Middlesex, Springfield / Hampden, Worcester County, Essex / Beverly, Plymouth, Bristol, and Ayer/Middlesex now exist in different strengths. Boston remains the densest cluster, but it should no longer be the default mining path.

Decision: Shift the next research lane away from Boston. Lowell / Rosario, Springfield / Hampden, and Worcester County / Cifizzari have been tightened. Bristol / New Bedford-Dartmouth has now been documented as an internal Tanner watch lane, but it is not graph-ready because the reviewed sources support testing access rather than resolved exoneration. Next priority order: Carver refresh after the Essex appeal posture changes, then another resolved regional lane with a repeated actor or court-level source set. Do not add Dana Gaul as a public node from this pass because the reviewed posture is wrongful arrest / dismissed charge rather than overturned murder conviction or final exoneration.

### Tanner / Bristol / Dartmouth Posthumous DNA Testing Lane

Status: `internal watch`.

Evidence: `WEB-TANNER-BRISTOL-DARTMOUTH-POSTHUMOUS-DNA-TESTING-1988-2026`; `docs/evidence/murder-conviction-review-matrix.md`; `docs/evidence/overturned-murder-conviction-mining.md`.

Current board state: Bristol County DA and Bristol Superior Court already exist as institutional nodes. Shawn Tanner and Mary Harris do not appear on the public board.

Decision: Keep this lane internal until a DNA result, posthumous-exoneration posture, or official prosecution-position change supports graph use. If that threshold is met, consider a narrow small-node treatment for Tanner, a Mary Harris underlying homicide-victim node, and connectors to Bristol County DA, Bristol Superior Court, and any officially identified evidence-transfer, lab, or regional investigation actors. Do not add a New Bedford Highway Killer lane or its victims from the current evidence.

### Cifizzari / Worcester County / Milford Wrongful-Conviction Lane

Status: `implemented`.

Evidence: `WEB-CIFIZZARI-WORCESTER-MILFORD-WRONGFUL-CONVICTION-1979-2019`; `WEB-REGIONAL-CITY-MURDER-CANDIDATE-SCAN-1979-2026`; `docs/evidence/murder-conviction-review-matrix.md`; `docs/evidence/overturned-murder-conviction-mining.md`.

Current board state: Gary Cifizzari now appears as a small gold-ring wrongful-conviction node. Concetta Schiappa appears as the underlying homicide-victim node, not a large anchor. Milford Police Department and Worcester Superior Court now appear as institution nodes connected to the existing Worcester County DA lane. DA Joseph D. Early Jr. connects to Cifizzari only for the documented 2019 dismissal/nolle role.

Decision: Keep this lane narrow and geographically precise. It is a Worcester County / Milford lane, not a Worcester city-police lane. Michael Giroux, Dr. Richard Souviron, other bite-mark experts, trial prosecutors, counsel, family/witnesses, and civil-litigation actors remain internal unless a later forensic-science or repeated-actor pass supports public-board use.

### Robert Pino / State Police Crime-Lab Lead

Status: `ingested`, `graph-ready; added narrow connector`.

Evidence: `WEB-PINO-STATE-POLICE-CRIME-LAB-2007-2024`; `WEB-MICHAEL-J-SULLIVAN-MIDDLESEX-WRONGFUL-CONVICTION-2014-2024`.

Current board state: Chemist Robert Pino is visible and connected narrowly to Michael J. Sullivan, Massachusetts State Police, and the existing State Police Crime Laboratory institution node.

Decision: Keep Robert Pino visible but narrow. Do not create a duplicate State Police Crime Lab institution, Pinero connector, Mark Delaney, Carl Selavka, or other case links unless a future source-ledger pass opens that broader lane.
