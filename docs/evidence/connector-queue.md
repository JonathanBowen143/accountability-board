# Connector Queue

Last updated: June 10, 2026.

This queue is the holding area between evidence ingestion and graph edits. It prevents the board from becoming either under-connected or over-claimed.

## Visual Encoding Notes

### Victim Anchor Node Size

Status: `implemented`.

Evidence: `index.html` draws nodes with `k:'victimAnchor'` as larger centered murdered-person anchors and uses regular `t:'victim'` nodes for smaller person-level victim/exoneree nodes.

Decision: Keep the larger Root, Birchmore, O'Keefe, Walshe, and Delgado-Garcia victim anchors as a style choice for navigation and moral focus. Do not let size imply blame, certainty, or evidence strength. The legend now names this as `Victim Anchor`.

## Current Norfolk Hot-Button Issues

### Read / O'Keefe Civil Suit

Status: `lead`.

Evidence: `WEB-READ-CIVIL-SUIT-2026-06`.

Current board state: The Read/O'Keefe lane already has direct links to Karen Read, John O'Keefe, MSP, Canton Police, Proctor, Goode, and Norfolk DA figures.

Decision: Do not add new claim-heavy connectors from the complaint alone. First localize the complaint PDF, then split adjudicated facts from allegations and decide whether the suit creates filing edges, oversight edges, or source notes.

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

### Local Police / DA Jurisdiction Backbone

Status: `graph-ready`.

Evidence: `WEB-LOCAL-POLICE-DA-JURISDICTION-2026-06`.

Current board state: Boston Police now connects to Suffolk County DA; Canton, Stoughton, and Brookline Police connect to Norfolk County DA; Lynn Police connects to Essex County DA; and Ayer Police connects to Middlesex County DA.

Decision: Keep these as `juris` edges only. They are structural prosecutorial-district connectors, not case-specific claims about conduct, discipline, or charging decisions.

### Edward Wright / Hampden / Springfield Wrongful-Conviction Lane

Status: `implemented`.

Evidence: `WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025`; `docs/evidence/murder-conviction-review-matrix.md`; `docs/evidence/overturned-murder-conviction-mining.md`.

Current board state: Edward Wright remains a small gold-ring wrongful-conviction node. Penny Anderson, Springfield Police Department, Hampden Superior Court, Det. Alfred Ingham, Judge Jeremy Bucci, and DA Anthony Gulluni now appear as narrow public-board connectors tied to Hampden County DA and the existing M.J. Ryan connector.

Decision: Keep this visible lane limited to the court/police/DA structure and the named detective tied to the false-testimony/crime-scene-preservation finding. Mark Grant, Judge Sarah Hamilton, defense counsel, third-party culprit names, witnesses, and additional historical actors remain internal unless a later pass shows a repeated public-actor pattern.

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

Status: `partly graph-ready; O'Malley / King lane internal-only pending video review`.

Evidence: `WEB-COX-BPD-ACCOUNTABILITY-LANES-1995-2026`.

Current board state: Cox has his original BPD employment connector, existing Cox/Conley/Williams 1995 beating connectors, existing oversight connectors to BPD actors already in the Read/O'Keefe lane, and a direct Read/O'Keefe public-accountability connector through the Dever dispute. The Stephenson King Jr. / Nicholas O'Malley fatal-police-shooting lane has been removed from the public board and retained only as an internal lead pending direct video and court-record review.

Decision: Cox remains board-relevant as both a past BPD victim of blue-wall conduct and a current commissioner tied to accountability disputes, but the next visible-board pass should not depend on the O'Malley arrest lane. Continue mining Cox only if official BPD, OPAT, court, POST, or City Council records create a direct accountability connector. Do not add generic biography edges merely because Cox held many commands, and do not connect him to John Mulligan unless a source directly ties Cox to the Mulligan / Sean Ellis lane.

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

Current board state: Fanning already connects to Root, Karen Read, Birchmore, MSP, Norfolk DA, Bukhenik, Broderick, Mattaliano, and Crawford.

Next action: locate or download the separate Fanning PDF, OCR it, and determine whether it supports a stronger Fanning-specific public-record connector, a Norfolk DA communication connector, or only a source note.

### Yuriy Bukhenik / Root Public-Records Correspondence

Status: `graph-ready`.

Evidence: `ROOT-BUKHENIK-FANNING-IMAGE-2020`; `ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020`; `_DRIVE_FULL_INDEX.tsv` lists `MSP- Yuri Bukhenik Brookline officers.png` and two indexed copies of `Tpr. Bukhenik Email Correspondence_redacted.pdf`.

Current board state: Bukhenik already connects to Root, Karen Read, MSP, Norfolk DA, Proctor, Tully, Guarino, Prince, DiCicco, Stoughton, Stoughton High context, Fanning, and Crawford.

Decision: The correspondence supports Bukhenik as a Root/Brookline communication and report/transcript-coordination connector. Do not use it as a misconduct source without a separate adjudicated or investigative record.

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

Evidence: `WEB-SUFFOLK-FOXWORTH-KAMARA-LARKIN-FLYNN-2021-2023`; `WEB-GAINES-OMALLEY-OVERTURNED-MURDER-CONVICTION-2024-2025`; `WEB-OMALLEY-SUFFOLK-WRONGFUL-CONVICTION-CLUSTER-2022-2026`; `WEB-LUCIEN-BRAZIL-SUFFOLK-BPD-2021-2024`; `WEB-RICCIUTI-ROSA-MCGEE-SUFFOLK-WRONGFUL-CONVICTION-2023-2026`; `WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025`; `WEB-PINA-DISAMBIGUATION-SUFFOLK-1999-2026`; `WEB-CARVER-ESSEX-BEVERLY-FIRE-2024-2026`; `docs/evidence/overturned-murder-conviction-mining.md`; `docs/evidence/murder-conviction-review-matrix.md`.

Current board state: Robert Foxworth, Barry Kamara, Raymond Gaines, Milton Jones, Floyd Hamilton, Joseph Jabir Pope, James Lucien, Rickey McGee, and Edward Wright are represented as small exonerated/wrongful-conviction nodes, not large victim anchors. Foxworth and Kamara connect to Suffolk DA, Boston Police, Suffolk Superior Court, former Suffolk ADA James Larkin, and former Boston Sgt. Det. Daniel Flynn. Gaines, Jones, Hamilton, and Pope connect narrowly to Suffolk DA, Boston Police, Suffolk Superior Court, and the existing Det. Peter O'Malley node. Lucien connects narrowly to Suffolk DA, Boston Police, Suffolk Superior Court, and the existing Det. John Brazil node. McGee connects narrowly to Suffolk DA, Boston Police, Suffolk Superior Court, and Judge Michael Ricciuti. Wright connects narrowly to Hampden DA, Springfield Police, Hampden Superior Court, Penny Anderson, Det. Alfred Ingham, Judge Jeremy Bucci, DA Anthony Gulluni, and DA M.J. Ryan Jr. Ricciuti also connects to Thomas Rosa Jr. and Suffolk Superior Court.

Decision: Keep the public board focused on repeated actor patterns and court/prosecution/police institutions. The matrix now separates visible small-node additions from internal holds. The O'Malley cluster is visible, but McConkey, Daley, Curran, Flynn, Goodale, witnesses, victims, and case-specific prosecutors remain internal pending stronger repeated-actor proof. The Ricciuti/Rosa/McGee pattern is visible, but individual detective, prosecutor, witness, investigator, counsel, and victim names remain internal pending stronger repeated-actor proof. The Wright/Hampden pattern is visible only as a narrow court/police/DA lane. Stephen Pina and Daniel Pina are now disambiguated but remain internal: Stephen because the reviewed sources show active Commonwealth appeal/retrial uncertainty, Daniel because the reviewed sources confirm exoneration posture but not actor-level public graph details. James Carver has now been refreshed through the Essex / Beverly fire lane, but remains internal because the Essex DA appeal and possible retrial posture remain live. Hold Michael Sullivan and Dewane Tse for additional actor-level or posture review before adding new visible nodes or edges. The next research pass should test Michael Sullivan first, then Dewane Tse or another recent Massachusetts overturned-murder-conviction lane using court-level sources.
