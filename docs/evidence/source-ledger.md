# Source Ledger

Last updated: June 9, 2026.

This ledger records source surfaces reviewed or identified for the board. It is intentionally separate from `index.html`; evidence belongs here first, graph edges second.

## WEB-LOCAL-POLICE-DA-JURISDICTION-2026-06

Status: `ingested`, `graph-ready for jurisdiction backbone`.

Source titles:

Suffolk County District Attorney's Office, `Bureaus of the Suffolk DA's Office`: `https://www.suffolkdistrictattorney.com/about-the-office/bureaus-of-the-suffolk-das-office`.

Mass.gov, `Norfolk District Attorney's Office`: `https://www.mass.gov/orgs/norfolk-district-attorneys-office`.

Norfolk County, `Communities`: `https://www.norfolkcounty.org/county_commission/communities.php`.

Town of Brookline, `Norfolk County`: `https://www.brooklinema.gov/878/Norfolk-County`.

Office of Essex County District Attorney Paul F. Tucker, `Home` and `Locations`: `https://www.essexcountyda.com/`; `https://www.essexcountyda.com/locations`.

Middlesex District Attorney's Office, `District Court Locations`: `https://www.middlesexda.com/about-us/pages/district-court-locations`.

U.S. Census Bureau QuickFacts, `Ayer town, Middlesex County, Massachusetts`; `Canton town, Norfolk County, Massachusetts`; `Stoughton town, Norfolk County, Massachusetts`: `https://www.census.gov/quickfacts/fact/table/ayertownmiddlesexcountymassachusetts/PST040224`; `https://www.census.gov/quickfacts/fact/table/cantontownnorfolkcountymassachusetts/PST040224`; `https://www.census.gov/quickfacts/fact/table/stoughtontownnorfolkcountymassachusetts/PST040224`.

Extracted facts:

The Suffolk DA page states that the Suffolk County DA's Office serves Boston, Chelsea, Revere, and Winthrop and that Boston is served by municipal courts in Suffolk County. The Norfolk materials place Brookline, Canton, and Stoughton in Norfolk County and identify the Norfolk DA as the relevant county prosecutorial office. Essex DA materials state that the office serves Essex County's cities and towns and maintains Lynn offices, including the Lynn District Court Office. The Middlesex DA page states that the Ayer District Court region serves Ayer and related Middlesex County communities.

Board implications:

Add local police-to-DA-office jurisdiction connectors using the existing `juris` edge type: `IBPD` to `ISUFFOLK`; `ICANTON`, `ISTOUGHTON`, and `IBROOKLINE` to `INORFOLK`; `ILYNN` to `IESSEX`; and `IAYER` to `IMIDDLESEX`. These edges are structural jurisdiction context only. They do not assert case-specific action or misconduct by a DA office.

## WEB-DICICCO-NORFOLK-OVERLAP-2025-2026

Status: `ingested`, `graph-ready`.

Source titles:

NBC10 Boston, `Michael Proctor's appeal over state police termination moves forward with hearing`, published July 8, 2025: `https://www.nbcboston.com/news/local/michael-proctor-mass-state-police-appeal-hearing/3761846/`.

Boston.com, `Here's what happened on the first day of the Brian Walshe murder trial`, updated December 1, 2025: `https://www.boston.com/news/crime/2025/12/01/brian-walshe-murder-trial-opening-statements/`.

Vanity Fair, `Beyond the Karen Read Verdict: DA Michael Morrissey and the Scandal Still Haunting Massachusetts`, published July 2025: `https://www.vanityfair.com/style/story/karen-read-verdict-norfolk-county-da`.

Extracted facts:

NBC10 Boston reports that State Police confirmed David DiCicco, described as another trooper involved in the Karen Read case, was moved out of the Norfolk County District Attorney's Office. Boston.com reports that State Police investigators Michael Proctor and David DiCicco were included in a January 7 Brian Walshe interview recording and that both worked on the Karen Read case. Vanity Fair also reports that DiCicco was moved out of Morrissey's office.

Board implications:

Add `dicicco` to `INORFOLK` as an employment/assignment connector and use these sources to support the existing cross-case `spine` connectors from `dicicco` to `CREAD` and `CWALSHE`. Do not add parallel `case` edges for the same relationship unless a later graph grammar change separates investigative participation from recurring-cross-case status. These are investigator/assignment links. They should not be framed as misconduct findings without separate adjudicated or official disciplinary evidence.

## WEB-FARAK-VELIS-MERRIGAN-LITALIEN-COUGHLIN-2016

Status: `ingested`, `graph-ready`.

Source titles:

Velis / Merrigan report mirror hosted by ACLU of Massachusetts, `Investigation of the Attorney Luke Ryan affidavit`: `https://www.aclum.org/app/uploads/drupal/sites/default/files/wp-content/uploads/2016/05/VelisMerriganReporttoAGHealey-reduced-file-size.pdf`.

Hampden Superior Court, Judge Richard J. Carey order mirror hosted by ACLU of Massachusetts, May 3, 2016: `https://www.aclum.org/app/uploads/drupal/sites/default/files/wp-content/uploads/2016/05/Carey-Order-2016_5_3.pdf`.

Extracted facts:

The Velis / Merrigan report states that Attorney General Healey's office requested investigators and that Massachusetts State Police assigned Detective Captain Paul J. L'Italien and Captain James F. Coughlin to assist the investigation being conducted by Judge Peter Velis and Judge Thomas Merrigan. The statement of facts says L'Italien and Coughlin were assigned to provide investigative support to the Attorney General and Northwestern District Attorney offices, and specifically to assist Velis and Merrigan in an investigation involving allegations of misconduct by sworn members and prosecutors assigned to the Attorney General's Office in the Sonja Farak matter. Judge Carey's order likewise states that L'Italien and Coughlin were assigned to conduct the investigation for SAAG Velis and SADA Merrigan and to prepare a report.

Board implications:

Add direct oversight/investigative-support connectors from Velis and Merrigan to L'Italien and Coughlin. Use `oversee` rather than a generic case edge because the source describes assignment, assistance, and report preparation for the Velis/Merrigan inquiry.

## WEB-COX-BPD-ACCOUNTABILITY-LANES-1995-2026

Status: `ingested`, `partly graph-ready; O'Malley / King lane internal-only pending video review`.

Source titles:

Boston.gov, `Michael Cox`: `https://www.boston.gov/departments/police/michael-cox`.

Justia, `United States v. Kenneth M. Conley`, 186 F.3d 7 (1st Cir. 1999): `https://law.justia.com/cases/federal/appellate-courts/F3/186/7/569286/`.

Justia, `United States v. Kenneth M. Conley`, 249 F.3d 38 (1st Cir. 2001): `https://law.justia.com/cases/federal/appellate-courts/F3/249/38/603323/`.

Boston.com, `Reddit rediscovers 'Boston's Rodney King' - here's what he's doing now`, published September 2, 2015: `https://www.boston.com/news/local-news/2015/09/02/reddit-rediscovers-bostons-rodney-king-heres-what-hes-doing-now/`.

WCVB, `SJC backs Boston officer fired twice`, updated July 12, 2017: `https://www.wcvb.com/article/states-highest-court-backs-boston-police-officer-fired-twice/10298461`.

CBS Boston, `Boston police commissioner responds to Karen Read trial testimony from Officer Kelly Dever`, updated July 10, 2025: `https://www.cbsnews.com/boston/news/boston-police-commissioner-michael-cox-kelly-dever-karen-read/`.

Boston 25 News, `Karen Read's legal team demands Boston Police Commissioner Cox be placed on 'Brady List'`, published October 27, 2025: `https://www.boston25news.com/news/local/karen-reads-legal-team-demands-bpd-commissioner-cox-officer-be-placed-brady-list/B3FPSEWTVFHKHPQXHZBO24JDFA/`.

WCVB, `Police Commissioner Michael Cox agrees to testify before Boston City Council on body camera policy`, updated April 15, 2026: `https://www.wcvb.com/article/boston-council-police-commissioner-may-testify-fatal-shooting/71028637`.

CBS Boston, `Boston Police Officer Nicholas O'Malley pleads not guilty to manslaughter after indictment in carjacking shooting`, updated June 4, 2026: `https://www.cbsnews.com/boston/news/boston-police-officer-nicholas-omalley-superior-court/`.

Extracted facts:

Boston.gov identifies Michael Cox as Boston Police Commissioner and says he was a 30-year veteran of BPD before leaving for Ann Arbor in 2019, then returning as commissioner. It lists command roles including Professional Development, Operations, Internal Affairs, Forensic Division, Bureau of Investigative Services, and earlier Anti-Gang Violence Unit service. The Conley opinions describe Cox as a plainclothes Boston police officer beaten by police officers after being mistaken for a fleeing suspect, and identify Kenneth Conley as a Boston police officer at the scene whose testimony became the subject of perjury and obstruction proceedings. Boston.com and WCVB identify David Williams as present or implicated in the Cox beating and describe the later discipline/reinstatement history.

CBS Boston and Boston 25 report that Cox was referenced during Kelly Dever's Karen Read trial testimony and in post-trial allegations from Read's defense about Cox's knowledge of Dever's connection to the case. The reporting identifies this as an allegation and a public response, not an adjudicated finding. WCVB and CBS report that Boston Police Officer Nicholas O'Malley was charged or indicted for voluntary manslaughter in the fatal shooting of Stephenson King Jr.; WCVB reports that Cox agreed to testify before the Boston City Council about body-camera release policies after public pressure over the King shooting and that Cox said the district attorney controls release decisions in the pending prosecution. Keep the O'Malley / King material internal until the underlying video and court record can be reviewed directly.

Board implications:

Keep the existing Cox-to-BPD, Cox-to-Conley, Cox-to-Williams, and Cox-to-Dever connectors. Add a restrained Cox-to-Read/O'Keefe case connector because Cox became part of the public Dever/Read accountability dispute. Do not display the King/O'Malley lane on the public board until the relevant video and court record are reviewed directly. Do not connect Cox to John Mulligan from these sources; the 1995 Cox beating arose from a separate Grove Hall shooting chase, not the Mulligan murder / Sean Ellis lane.

## WEB-READ-RETRIAL-NORFOLK-STAFF-2025

Status: `ingested`, `internal-only unless stronger public-accountability role surfaces`.

Source titles:

Boston 25 News, `Karen Read retrial: List of 150 witnesses prosecution, defense could call`, published March 31, 2025: `https://www.boston25news.com/news/local/karen-read-retrial-list-150-witnesses-prosecution-defense-could-call/BF7FJ4AJARAXZBNURW6INFCZ54/`.

WHDH 7News, `Here's who could testify in Karen Read's retrial`, published March 31, 2025: `https://whdh.com/news/heres-who-could-testify-in-karen-reads-retrial/`.

CBS Boston, `What's next in the Karen Read murder trial?`, published June 2024: `https://www.cbsnews.com/boston/news/karen-read-murder-trial-whats-next-schedule/`.

Boston 25 News, `Karen Read murder trial: List of more than 160 witnesses prosecution, defense could call`, published May 2024: `https://www.boston25news.com/news/local/karen-read-murder-trial-list-more-than-160-witnesses-prosecution-defense-plan-call/U3JOQXF7KJAFDC4TFNZVLWZJGY/`.

Extracted facts:

The 2025 retrial witness-list reporting identifies Coleen Crawford as affiliated with the Norfolk District Attorney's Office, Steve Nelson as affiliated with the Norfolk County District Attorney's Office, Norfolk County District Attorney Michael Morrissey as a listed witness, and Trooper Kathleen Prince as affiliated with the Massachusetts State Police. CBS Boston separately identifies Steve Nelson as a Norfolk County victim witness advocate whose possible testimony was contested in the Read trial. The 2024 witness-list reporting also listed Steve Nelson with the Norfolk County DA's Office, Trooper Kathleen Prince with Massachusetts State Police, and Morrissey with the Norfolk County DA's Office.

Board implications:

Keep Steve Nelson documented as a Norfolk DA office witness-list actor, but do not keep him on the visible public board based on witness-list presence alone. Use this source to support the existing Prince `CREAD`/`IMSP` and Crawford `CREAD`/`INORFOLK` connectors. Do not use witness-list presence alone to imply wrongdoing, investigation control, or testimony content.

## WEB-PRINCE-OCONNELL-SJC-2012

Status: `ingested`, `graph-ready for existing court-record access connectors`.

Source title:

Boston.com, `SJC unseals affidavit in William O'Connell rape case in Norfolk County sought by newspaper`, published August 23, 2012: `https://www.boston.com/uncategorized/noprimarytagmatch/2012/08/23/sjc-unseals-affidavit-in-william-oconnell-rape-case-in-norfolk-county-sought-by-newspaper/`.

Extracted facts:

Boston.com reports that the Supreme Judicial Court ordered a search-warrant affidavit unsealed in the William O'Connell matter and that the affidavit had been filed in Quincy District Court by State Police Trooper Kathleen Prince as prosecutors investigated allegations against O'Connell. The report also says O'Connell was being prosecuted by a special prosecutor at Norfolk DA Michael Morrissey's request because Morrissey had worked with O'Connell on development projects while serving as a legislator.

Board implications:

This supports the existing Prince-to-O'Connell and Prince-to-SJC case connectors as court-record/investigative-affidavit context. It does not add a new Norfolk DA misconduct finding, and it should not be used to expand Prince's graph footprint without additional Read-specific or Root-specific records.

## WEB-READ-BIRCHMORE-DISCOVERY-MOTION-2025

Status: `indexed`, `lead / needs docket-copy verification`.

Source titles:

Scribd public court-document mirror, `Defense Motion To Compel Discovery`: `https://www.scribd.com/document/829355736/Defense-Motion-to-Compel-Discovery`.

Newsweek, `Karen Read in Court for Motions Ahead of April Retrial: What We Know`, published 2025: `https://www.newsweek.com/karen-read-court-hearing-mistrial-motion-dismiss-2032814`.

Extracted facts:

The public motion mirror states that Read's defense sought discovery related to the Sandra Birchmore investigation and named law-enforcement or prosecution witnesses including Michael Lank, Daniel Whitley, Trooper Mike Dunne, Trooper Zach Clark, Coleen Crawford, Detective Kevin Albert, Lieutenant John Fanning, Trooper Guarino, Lieutenant Brian Tully, Deputy District Attorney Lynn Beland, and District Attorney Michael Morrissey. Newsweek reports that defense attorney Elizabeth Little argued for discovery from the Norfolk DA's Birchmore investigation and that the Commonwealth disputed relevance, with Judge Beverly Cannone taking the issue under advisement.

Board implications:

Treat the Birchmore discovery-motion allegations as a cross-case discovery lead, not a visible Birchmore graph expansion yet. Lynn Beland is now visible from separate Walshe and Read/O'Keefe correspondence sources, but this mirror alone still should not support a Beland-to-Birchmore edge without an official docket copy or another stable court-record source.

## WEB-BELAND-NORFOLK-WALSHE-READ-2023-2024

Status: `ingested`, `graph-ready for Beland / Norfolk DA / Walshe / Read-O'Keefe correspondence connectors`.

Source titles:

Cohasset Anchor, `Husband indicted for murder of Ana Walshe`, submitted by the Norfolk District Attorney's Office and published March 31, 2023: `https://cohassetanchor.com/husband-indicted-for-murder-of-ana-walshe/`.

AP News, `Prosecutor: Husband of missing wife bought cleaning supplies`, published January 9, 2023: `https://apnews.com/article/b7af3c2d56d0c5a4ce76af9a3b3e7340`.

Boston 25 News, `25 Investigates: Letters between feds, Norfolk DA released in Karen Read case`, published February 23, 2024: `https://www.boston25news.com/news/local/25-investigates-letters-between-feds-norfolk-da-released-karen-read-case/PCBH3ZECNJEEFNNNX4RFYX6PPE/`.

Court TV, `Prosecutors release letters to federal authorities in Karen Read case`, published January 2024: `https://www.courttv.com/news/prosecutors-release-letters-with-federal-authorities-in-karen-read-case/`.

Extracted facts:

The Norfolk DA-submitted Cohasset Anchor report says First Assistant District Attorney Lynn Beland represented the Commonwealth at Brian Walshe's Quincy District Court arraignment and had overseen the Ana Walshe disappearance investigation by State Police detectives assigned to the Norfolk DA's office and Cohasset Police. AP separately reported Beland's presentation at Brian Walshe's arraignment. Boston 25 and Court TV report that released correspondence between Norfolk prosecutors and federal authorities in the Read/O'Keefe matter identified Beland as a Norfolk prosecutor involved in communications with Acting U.S. Attorney Joshua Levy about federal-investigation material that could implicate state discovery obligations.

Board implications:

Add a restrained public node for Beland. Connect Beland to the Norfolk DA office, the Walshe case lane, Brian Walshe, and the Read/O'Keefe filing/correspondence lane. Do not add federal actors to the public graph, and do not use these sources to make a Beland-to-Birchmore edge.

## WEB-NDAO-CRAWFORD-TULLY-DIGITAL-EVIDENCE-2019

Status: `ingested`, `graph-ready for narrow professional-training connector`.

Source titles:

Norfolk District Attorney's Office, `DA Morrissey hosts area Detectives at homicide conference`, October 2019: `https://www.nfkda.com/Press_Releases/10-01-19%20DA%20Morrissey%20Hosts%20Detectives%20at%20Homicide%20Conference.pdf`.

Extracted facts:

The Norfolk DA press release says more than 115 State Police and municipal police detectives attended a three-day homicide-investigation seminar hosted by Norfolk District Attorney Michael Morrissey, Massachusetts State Police, and MassBay Community College. It identifies Norfolk DA Multimedia Director Coleen Crawford as instructing on proper digital-evidence collection. It also says DA General Counsel Marguerite Grant presented and sat on an Emerging Legal Trends panel moderated by conference organizer Trooper Brian Tully, with Superior Court Judge Rosalind Miller and Christopher Kelly, Digital Evidence Laboratory Director for Attorney General Maura Healey.

Board implications:

Add a narrow `business` connector between Tully and Crawford as a professional/training overlap in the Norfolk DA / MSP digital-evidence lane. This source supports Crawford's Norfolk DA digital-evidence role and a Tully/Crawford professional overlap; it does not establish a case-specific action in Root, Birchmore, or O'Keefe, and it should not be used to infer misconduct.

## WEB-READ-CIVIL-SUIT-2026-06

Status: `indexed`, `lead`.

Source titles:

AP News, `Karen Read sues the police agencies that investigated her Boston police boyfriend's death`, published June 2026: `https://apnews.com/article/karen-read-massachusetts-police-lawsuit-e55ff3681ba221bdb18dc37cfe24a68f`.

Complaint mirror, `Read v. Massachusetts State Police and Town of Canton`, filed in Bristol County Superior Court on June 4, 2026: `https://whdh.com/wp-content/uploads/sites/3/2026/06/Read-v-Canton-PD-MSP-COMPLAINT.pdf`.

Extracted facts:

Read filed a civil suit against the Massachusetts State Police and Town of Canton after the June 18, 2025 verdict in the John O'Keefe case. AP reports that the jury acquitted Read of second-degree murder, manslaughter, and leaving-the-scene charges, while convicting her of operating under the influence. The complaint is an allegation source, not an adjudicated fact source. It alleges negligent hiring, training, and supervision, and places former MSP Trooper Michael Proctor and former Canton Sgt. Sean Goode at the center of the alleged misconduct culture.

Board implications:

This source strengthens the Read/O'Keefe evidence lane around MSP, Canton Police, Proctor, Goode, and institutional oversight. It should be used carefully: verdict facts are treated as adjudicated; complaint allegations remain allegations unless independently proven.

## WEB-BIRCHMORE-FARWELL-SUPERSEDING-2025

Status: `ingested`, `graph-ready`.

Source titles:

DOJ, `Former Stoughton Police Officer Indicted for Allegedly Causing the Death of His Victim's Unborn Baby`, published October 28, 2025: `https://www.justice.gov/usao-ma/pr/former-stoughton-police-officer-indicted-allegedly-causing-death-his-victims-unborn-baby`.

DOJ attachment, `USA v. Matthew Farwell - Superseding Indictment`: `https://www.justice.gov/d9/2025-10/usa_v._matthew_farwell_-_superseding_indictment.pdf`.

Extracted facts:

The superseding indictment alleges that Matthew Farwell killed Sandra Birchmore by strangulation on February 1, 2021, staged her Canton apartment to appear as a suicide, and caused the death of her unborn child. DOJ states that Farwell remains presumed innocent unless proven guilty beyond a reasonable doubt.

Board implications:

This is a primary federal source for Birchmore's victim anchor, Matthew Farwell, Stoughton Police, Canton location context, OCME, and the federal-intervention lane. It supports graph-ready connectors only at the allegation/status level unless and until there is a conviction or other adjudicated finding.

## WEB-BIRCHMORE-FARWELL-DETENTION-AFFIDAVIT-2024

Status: `ingested`, `graph-ready for Stoughton Police institutional notes`.

Source title:

DOJ attachment, `USA v. Matthew Farwell - Detention Affidavit`: `https://www.justice.gov/usao-ma/media/1365701/dl`.

Extracted facts:

The detention affidavit alleges that Matthew Farwell killed Sandra Birchmore on February 1, 2021, to prevent disclosure of possible federal crimes. It says Birchmore joined the Stoughton Police Explorers Academy to learn about law enforcement careers; Farwell was involved as a volunteer and instructor; and he used his position of trust and authority as a sworn police officer and Police Explorers instructor to groom and sexually exploit Birchmore. It also says Canton officers found Birchmore's body during a February 4, 2021 well-being check, her body was transported to OCME, and an OCME pathologist ruled the manner of death suicide in early May 2021.

Board implications:

This source supports Stoughton Police institutional context and source-note language about the Police Explorers program, but the program is an offshoot of the Stoughton Police Department and should not be a standalone public graph institution in the current victim/public-official view. It also strengthens Canton and OCME context. It does not, by itself, support William Farwell, Robert Devine, or Joshua Heal connectors; those names require separate source entries.

## WEB-BIRCHMORE-FARWELL-PRETRIAL-STATUS-2026

Status: `indexed`, `status lead`.

Source titles:

NBC10 Boston, `Sandra Birchmore update: Matthew Farwell loses detention fight`, published May 2026: `https://www.nbcboston.com/news/local/sandra-birchmore-murder-case-farwell-detention/3955511/`.

CBS Boston, `DOJ won't seek death penalty against Matthew Farwell in Sandra Birchmore case`, updated December 9, 2025: `https://www.cbsnews.com/boston/news/matthew-farwell-sandra-birchmore-no-death-penalty/`.

Extracted facts:

NBC10 Boston reports that Matthew Farwell remained in custody after Magistrate Judge M. Page Kelley denied pretrial release and that trial was expected to begin in October 2026. CBS Boston reports that the federal government said it would not seek the death penalty, while Farwell pleaded not guilty.

Board implications:

This is procedural status, not connector evidence. Use it to keep the board's notes current and to preserve the presumption of innocence; do not use it to add new graph edges.

## WEB-BIRCHMORE-FEDERAL-LANE-ACTORS-2025

Status: `indexed`, `internal-only`.

Source titles:

DOJ, `Former Stoughton Police Officer Indicted for Allegedly Causing the Death of His Victim's Unborn Baby`, published October 28, 2025: `https://www.justice.gov/usao-ma/pr/former-stoughton-police-officer-indicted-allegedly-causing-death-his-victims-unborn-baby`.

CBS Boston, `DOJ won't seek death penalty against Matthew Farwell in Sandra Birchmore case`, updated December 9, 2025: `https://www.cbsnews.com/boston/news/matthew-farwell-sandra-birchmore-no-death-penalty/`.

Extracted facts:

The DOJ release identifies U.S. Attorney Leah B. Foley, FBI Boston Special Agent in Charge Ted E. Docks, and Assistant U.S. Attorneys Elizabeth Riley, Torey B. Cummings, and Brian A. Fogerty of the Human Trafficking and Civil Rights Unit. CBS reports that the no-death-penalty filing was made by Foley and the same three AUSAs, and says the decision was attributed to U.S. Attorney General Pam Bondi. CBS also reports that Farwell was set to face trial in Boston federal court in October 2026.

Board implications:

Keep these federal-lane actors in the internal evidence file and out of the public graph unless the project's scope changes. The chart is focused on Massachusetts accountability connectors; the federal lane is currently a procedural/intervention overlay, not a public-board relationship cluster.

## WEB-WALSHE-CASE-STATUS-2025

Status: `indexed`, `local chronology / internal-only for visible graph`.

Source titles:

AP News, `Brian Walshe goes on trial in death of wife who disappeared more than 2 years ago`: `https://apnews.com/article/brian-walshe-trial-wife-3d290aed2d1a0f1999b7f52601f30bf3`.

Court TV, `MA v. Brian Walshe: The Disappearance of Ana Walshe Murder Trial`: `https://www.courttv.com/news/brian-walshe-pleads-guilty-to-murdering-missing-wife-ana/`.

ABC News, `Brian Walshe murder trial: Jury finds husband guilty of killing and dismembering wife`: `https://abcnews.com/US/brian-walshe-murder-trial-wife-jury-reaches-verdict/story?id=128359783`.

Extracted facts:

AP reports that Ana Walshe was last seen early on January 1, 2023, and that Brian Walshe faced a first-degree murder charge after pleading guilty to lesser charges of misleading police and willfully conveying a human body. Court TV reports that Brian Walshe was convicted of first-degree murder in Ana Walshe's presumed death and had pleaded guilty to two charges tied to Ana's disappearance. ABC News reports that Norfolk DA Michael Morrissey's office prosecuted the case and that Morrissey commended the investigators after the verdict.

Board implications:

This supports keeping Ana Walshe as a victim anchor, changing Brian Walshe from `Charged` to `Convicted`, and connecting the Walshe lane to Norfolk Superior Court, the Norfolk DA's office, and the existing investigator-overlap nodes. Brian Walshe's unrelated federal art-fraud case is context only and should stay out of the public chart unless the project opens a separate federal-defendant lane.

## WEB-WALSHE-COHASSET-PUBLIC-OFFICIALS-2025

Status: `indexed`, `graph-ready`.

Source titles:

Cohasset Anchor, `Exclusive: Cohasset Police Department's key role in the Ana Walshe murder investigation as part of collaborative effort`, published December 22, 2025: `https://cohassetanchor.com/exclusive-cohasset-police-departments-key-role-in-the-ana-walshe-murder-investigation-as-part-of-collaborative-effort/`.

CBS Boston, `Husband of missing Cohasset mother Ana Walshe arrested for misleading investigation`, updated January 8, 2023: `https://www.cbsnews.com/boston/news/ana-walshe-missing-cohasset-woman-police-search-brian/`.

Boston.com, `Brian Walshe murder trial: First day recap`, published December 1, 2025: `https://www.boston.com/news/crime/2025/12/01/brian-walshe-murder-trial-opening-statements/`.

CBS Boston, `Brian Walshe prosecutors say they have "binders" of searches made before wife's alleged murder`, updated before trial in 2025: `https://www.cbsnews.com/boston/news/brian-walshe-trial-starting/`.

Extracted facts:

Cohasset Anchor reports that Cohasset Police worked with the Norfolk DA's office and state police, identifies Chief William Quigley, Sgt. Harrison Schmidt, Detective Commander Michael Lopes, Officer Gregory Lowrance, and Sgt. Patrick Reardon, and says Schmidt took the lead on the investigation. CBS Boston reported in January 2023 that the Norfolk DA's office announced Brian Walshe's arrest, that the DA's office became lead organization in the search, that Chief Quigley described the no-electronic-footprint issue, and that Detective Harrison Schmidt was the contact for tips. Boston.com reports that prosecutors called Schmidt as the first witness, that he said he led the Ana Walshe investigation, and that a later police interview included MSP investigators Michael Proctor and David DiCicco. CBS Boston reports that Judge Diane Freniere presided over trial-preparation issues and that Proctor was also an investigator in Walshe's case.

Board implications:

This documents local investigative chronology and identifies local Cohasset police participants, but the visible board should not include Cohasset Police Department or its members in the Walshe lane because Brian Walshe's conviction is not the contested public-accountability issue. Use this source internally while keeping the public graph focused on county-level and state-level actors: Norfolk DA, Norfolk Superior Court, MSP/investigators, OCME, ADA Gregory Connor, Judge Diane Freniere, Brian Walshe, and Ana Walshe.

## WEB-SUFFOLK-FOXWORTH-KAMARA-LARKIN-FLYNN-2021-2023

Status: `ingested`, `graph-ready for Suffolk / Boston wrongful-murder-conviction connector`.

Source titles:

Suffolk County District Attorney's Office, `Suffolk District Attorney Files Nolle Prosequi After Judge Allows Assented-to Motion for New Trial in Wrongful Murder Conviction`, published January 13, 2021: `https://www.suffolkdistrictattorney.com/press-releases/items/foxworth-wrongful-conviction`.

The Boston Globe, `Suffolk judge overturns 1992 murder conviction, clearing Barry Kamara's name at last`, published March 21, 2023: `https://www.bostonglobe.com/2023/03/21/metro/suffolk-judge-overturns-1991-murder-conviction-clearing-barry-kamaras-name-last/`.

The Boston Globe, `Two bad apples? Let's look at the whole barrel`, published March 22, 2023: `https://www.bostonglobe.com/2023/03/22/metro/two-bad-apples-lets-look-whole-barrel/`.

Extracted facts:

The Suffolk DA release states that Robert Foxworth's wrongful murder conviction was vacated and that the office filed a nolle prosequi after concluding he did not receive a fair trial and there was no credible evidence to support a new conviction. The Globe reports that Barry Kamara's 1992 murder conviction was thrown out after prosecutors acknowledged withheld evidence, and identifies the former Suffolk ADA James Larkin and former Boston police Sgt. Det. Daniel Flynn as the prosecutor and detective implicated in both the Kamara and Foxworth wrongful-conviction cases.

Board implications:

Add small exonerated-person nodes for Robert Foxworth and Barry Kamara, plus restrained actor nodes for Larkin and Flynn. Connect Foxworth and Kamara to Suffolk DA, Boston Police, and Suffolk Superior Court; connect Larkin and Flynn to their agencies and to both wrongful-conviction subjects. Do not promote these nodes to victim anchors.

## WEB-GAINES-OMALLEY-OVERTURNED-MURDER-CONVICTION-2024-2025

Status: `ingested`, `graph-ready for narrow Gaines / Peter O'Malley connector and exonerated-node treatment`.

Source titles:

Justia mirror of Massachusetts Supreme Judicial Court decision, `Commonwealth v. Gaines`, SJC-13446, decision dated August 29, 2024: `https://law.justia.com/cases/massachusetts/supreme-court/2024/sjc-13446.html`.

The Boston Globe, `Judge overturns Boston murder conviction for man who served 46 years`, published December 7, 2022: `https://www.bostonglobe.com/2022/12/07/metro/judge-overturns-boston-murder-conviction-man-who-served-46-years/`.

Massachusetts Lawyers Weekly, `Criminal - Murder - New trial`, published September 4, 2024: `https://masslawyersweekly.com/2024/09/04/criminal-murder-new-trial-6/`.

WCVB, `DA declines to re-try man in 1974 Roxbury shoe shop murder`, updated October 16, 2025: `https://www.wcvb.com/article/da-declines-to-re-try-man-in-1974-roxbury-shoe-shop-murder/69063772`.

National Registry of Exonerations, `2025 Annual Report`, published 2026: `https://exonerationregistry.org/sites/exonerationregistry.org/files/documents/2025Exonerations.pdf`.

Extracted facts:

The SJC decision affirms the order granting Raymond Gaines a new trial and identifies the trial evidence as including eyewitness identification, witness testimony, and an alleged confession to Boston police Detective Peter O'Malley. The court says the new-trial order was supported by modern eyewitness-identification science and by prejudice from undisclosed exculpatory material, including material related to key witness David Bass and O'Malley. Globe and Lawyers Weekly coverage describe the Gaines ruling as part of a broader Boston wrongful-conviction pattern involving O'Malley. WCVB reports that the Suffolk DA declined to retry Gaines in October 2025, while noting the DA's office still disputed his innocence. The National Registry of Exonerations lists Raymond Gaines as a 2025 Massachusetts murder/robbery exoneration.

Board implications:

Add Raymond Gaines as a small exonerated/wrongful-conviction node tied to Boston Police, Suffolk DA, Suffolk Superior Court, and the existing Det. Peter O'Malley node. Keep the edge narrow and do not conflate this Peter O'Malley lane with the separate Nicholas O'Malley / Stephenson King Jr. internal-only lead.

## WEB-OMALLEY-SUFFOLK-WRONGFUL-CONVICTION-CLUSTER-2022-2026

Status: `ingested`, `graph-ready for narrow O'Malley / Suffolk / Boston Police wrongful-conviction cluster expansion`.

Source titles:

The Boston Globe, `Judge overturns Boston murder conviction for man who served 46 years`, published December 7, 2022: `https://www.bostonglobe.com/2022/12/07/metro/judge-overturns-boston-murder-conviction-man-who-served-46-years/`.

WBUR, `Wrongfully convicted man sues Boston after serving 15 years in prison`, published October 22, 2025: `https://www.wbur.org/news/2025/10/22/wrongful-conviction-lawsuit-massachusetts-jones`.

Milton Jones federal civil-rights complaint, filed October 21, 2025, hosted by Universal Hub: `https://www.universalhub.com/files/attachments/2025/mjones-complaint.pdf`.

United States District Court, District of Massachusetts, `Brown v. City of Boston`, Memorandum and Order on City of Boston's partial motion to dismiss, August 21, 2025, hosted by Massachusetts Lawyers Weekly: `https://masslawyersweekly.com/files/2025/08/02-462-25.pdf`.

Justia mirror of Massachusetts Supreme Judicial Court decision, `Commonwealth v. Pope`, SJC-13202, decision dated June 8, 2022: `https://law.justia.com/cases/massachusetts/supreme-court/2022/sjc-13202.html`.

United States District Court, District of Massachusetts, `Pope v. City of Boston`, Memorandum and Order on City of Boston's motion to dismiss, November 7, 2024, hosted by Massachusetts Lawyers Weekly: `https://masslawyersweekly.com/files/2024/11/02-528-24.pdf`.

The Boston Globe, `Suffolk DA won't retry man convicted in 1984 Dorchester killing`, published October 24, 2022: `https://www.bostonglobe.com/2022/10/24/metro/suffolk-da-wont-retry-man-convicted-1984-killing/`.

Extracted facts:

The Globe reported in December 2022 that judges had overturned four old murder convictions involving Boston Police Detective Peter O'Malley in a six-month span, identifying Gaines as one of those cases and reporting that O'Malley was tied to the Milton Jones, Floyd Hamilton, and Joseph Pope lanes. WBUR reports that Milton Jones's federal lawsuit accuses retired Boston police detectives Louis McConkey, Peter O'Malley, and John J. Daley of fabricating false eyewitness identifications and withholding key evidence in Jones's 1975 Roxbury bar-owner murder conviction; Jones's complaint says the Suffolk Superior Court expunged his wrongful convictions after a Chapter 258D innocence settlement. In `Brown v. City of Boston`, the federal court states that Albert Brown, also known as Floyd Hamilton, was incarcerated for over thirty years until his conviction was overturned in 2022 based on withheld exculpatory evidence, and that Hamilton sued the City of Boston, Peter O'Malley, and other BPD actors for their role in his arrest and prosecution. The SJC's Pope decision granted Joseph Jabir Pope a new trial based on prejudicial Brady nondisclosure, identifies Detective Peter O'Malley among responding officers, and notes O'Malley's concerns about the Commonwealth's key witness in the withheld Goodale memorandum. The federal `Pope v. City of Boston` order records Pope's allegations that O'Malley failed to be truthful and execute his duties lawfully before and after Pope's investigation and conviction, and the Globe reports that the Suffolk DA filed a nolle prosequi after Pope's new-trial order.

Board implications:

Add Milton Jones, Floyd Hamilton, and Joseph Jabir Pope as small gold-ring wrongful-conviction nodes tied to Boston Police, Suffolk DA, Suffolk Superior Court, and the existing Det. Peter O'Malley node. Keep McConkey, Daley, Curran, Flynn, Goodale, Benny DeJesus, Efrain DeJesus, Albert Dunn, Louis McConkey, John J. Daley, and case-specific witnesses internal for now. This pass proves the O'Malley repeated-actor cluster, not every actor in each underlying case.

## WEB-LUCIEN-BRAZIL-SUFFOLK-BPD-2021-2024

Status: `ingested`, `graph-ready for narrow Lucien / Brazil / Suffolk / Boston Police connector`.

Source titles:

Suffolk County District Attorney's Office, `Firearm conviction in connection to 1994 murder to be vacated`, published August 3, 2023: `https://www.suffolkdistrictattorney.com/press-releases/items/2023/8/4/firearm-conviction-in-connection-to-1994-murder-to-be-vacated`.

WBUR / Associated Press, `Mass. man sues state for $1M after serving 27 years in prison for a case that was later thrown out`, published February 28, 2024: `https://www.wbur.org/news/2024/02/28/james-lucien-lawsuit-boston-police-wrongful-conviction`.

Extracted facts:

The Suffolk DA release states that James Lucien was convicted in 1995 of first-degree murder, armed robbery, and firearm possession in the fatal shooting of Ryan Edwards; that the office's Integrity Review Bureau found significant concerns and errors in the trial record; that the office assented to a new trial on the murder and robbery convictions in 2021; and that Suffolk Superior Court later granted a new trial on the remaining firearm conviction in 2023, after which the Suffolk DA filed a nolle prosequi ending the case. The same release identifies former Boston Police Det. John Brazil's improper actions as prejudicial to Lucien. WBUR/AP reports that Lucien spent nearly three decades in prison, was released in 2021, and later sued the state, with his lawyers alleging corrupt Boston police officials produced false testimony and tainted evidence.

Board implications:

Add James Lucien as a small gold-ring wrongful-conviction node tied to Boston Police, Suffolk DA, Suffolk Superior Court, and the existing Det. John Brazil node. Do not add Kevin Hayden, Jennifer Zalnasky, Robert Ullman, Mark Loevy-Reyes, or Ryan Edwards to the public board from this pass alone; keep those names documented here unless a future repeated-actor or victim-anchor lane supports them.

## WEB-RICCIUTI-ROSA-MCGEE-SUFFOLK-WRONGFUL-CONVICTION-2023-2026

Status: `ingested`, `graph-ready for narrow Ricciuti / Rosa / McGee Suffolk court connector`.

Source titles:

New England Innocence Project, `Thomas Rosa, Jr. Faces Possible Fourth Trial`, updated February 13, 2025, with September 7, 2023 conviction-overturning entry: `https://www.newenglandinnocence.org/innocence-blog/2023/rosaconvictionoverturned`.

New England Innocence Project, `Thomas Rosa, Jr. Exonerated After 34 Years Wrongfully Incarcerated`, published March 18, 2026: `https://www.newenglandinnocence.org/innocence-blog/3/2026/tommyrosaexonerated`.

GBH News, `Man released from prison after 28 years while judge considers innocence plea`, published October 14, 2025: `https://www.wgbh.org/news/local/2025-10-14/man-released-from-prison-after-28-years-while-judge-considers-innocence-plea`.

Commonwealth's response to Ricky McGee's motion for new trial, dated October 2, 2025, as hosted by DocumentCloud: `https://s3.documentcloud.org/documents/26186494/mcgee-r-response-mtn-for-new-trial-final-10225-003.pdf`.

Boston.com, `Prosecutors won't retry man who had murder conviction overturned after 27 years in prison`, published November 20, 2025: `https://www.boston.com/news/crime/2025/11/20/commonwealth-drops-charges-against-man-convicted-of-murder-nearly-30-years-ago/`.

Extracted facts:

NEIP states that Suffolk Superior Court Judge Michael Ricciuti vacated Thomas Rosa Jr.'s convictions on September 6, 2023 because new DNA evidence and advances in eyewitness science undermined the trial evidence, and later states that the Suffolk DA filed a nolle prosequi in March 2026, ending Rosa's prosecution. GBH reports that Suffolk Superior Court Judge Michael Ricciuti released Rickey "FuQuan" McGee in October 2025 after prosecutors filed a motion saying errors created a substantial risk of a miscarriage of justice. The Commonwealth's October 2, 2025 response requested that the court vacate McGee's convictions and grant a new trial, citing a comprehensive reinvestigation, newly discovered evidence, witness-impeachment issues, and the absence of physical evidence tying McGee to the crime scene. Boston.com reports from court filings that Judge Ricciuti granted McGee a new trial on October 27, 2025 and that the Suffolk DA filed a nolle prosequi on November 3, 2025.

Board implications:

Add Judge Michael Ricciuti as a Suffolk Superior Court public-actor node and connect him narrowly to Thomas Rosa Jr. and Rickey McGee. Add Rickey McGee as a small gold-ring wrongful-conviction node connected to Boston Police, Suffolk DA, and Suffolk Superior Court. Do not add Kevin Hayden, Zachary Host, Jennifer Zalnasky, Jeffrey Harris, Jill Tessier, John Nardizzi, Natasha Hamilton, Geta Yalew, or individual Boston Police detectives from this pass; those names remain source-ledger/internal-document material until repeated-actor or official-misconduct proof supports a visible graph edge.

## WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025

Status: `ingested`, `graph-ready for narrow Wright / Anderson / Hampden / Springfield connector`.

Source titles:

Hampden Superior Court, `Commonwealth v. Edward G. Wright, Memorandum of Decision and Order on Defendant's Sixth Motion for New Trial`, April 2025, text-searchable mirror: `https://www.cybgen.com/information/admissibility/Wright2025.pdf`.

New England Innocence Project, `Court Overturns 1985 Springfield Murder Conviction`, published April 15, 2025: `https://www.newenglandinnocence.org/innocence-blog/2025/edwardwrightconvictionoverturned`.

Hampden District Attorney's Office, `Hampden District Attorney's Office Enters Nolle Prosequi in 1984 Murder Case Following Controversial Ruling`, published August 21, 2025: `https://hampdenda.com/hampden-district-attorneys-office-enters-nolle-prosequi-in-1984-murder-case-following-controversial-ruling/`.

New England Innocence Project, `Edward Wright Exonerated!`, published August 21, 2025: `https://www.newenglandinnocence.org/innocence-blog/edwardwrightexonerated`.

Quinn Emanuel, `Wrongful Conviction Vacated After 40 Years`, published June 3, 2025: `https://www.quinnemanuel.com/the-firm/publications/wrongful-conviction-vacated-after-40-years/`.

Extracted facts:

The Hampden Superior Court decision records Edward Wright's 1985 first-degree-murder conviction for the killing of Penny Anderson in Springfield and orders a new trial on Wright's sixth motion. The decision identifies Springfield Police Department Det. Alfred Ingham, the break-in report, the preservation of the crime scene, the shoe-print evidence, and Mark Grant's forensic-chemist testimony as major evidentiary subjects. The court found the undisclosed break-in report was in the control of police and the prosecution team, that it was exculpatory, and that the nondisclosure justified post-conviction relief. The decision also addresses Ingham's trial testimony about who had accessed the apartment after the murder and before key evidence was collected.

NEIP's April 2025 and August 2025 posts identify Hampden County Superior Court Judge Jeremy Bucci as the judge who vacated Wright's conviction, describe the misconduct findings, and report that the Commonwealth ended the prosecution. The Hampden DA's own August 2025 statement identifies DA Anthony D. Gulluni and records the office's decision to file a nolle prosequi in `Commonwealth v. Edward Wright`. Quinn Emanuel's June 2025 account provides corroborating defense-team context for the withheld evidence, false testimony, new DNA testing, and unreliable forensic-evidence claims.

Board implications:

Add Penny Anderson as the underlying murder victim, keep Edward Wright as the small gold-ring exonerated/wrongful-conviction node, add Springfield Police Department and Hampden Superior Court as institution nodes, and connect Det. Alfred Ingham, Judge Jeremy Bucci, and DA Anthony Gulluni narrowly to the Wright/Anderson/Hampden lane. Keep Mark Grant, Judge Sarah Hamilton, defense counsel, possible third-party suspects, witnesses, and additional historical actors in internal notes unless a later pass shows a repeated public-actor pattern or a stronger reason for visible-board use.

## WEB-MURDER-CONVICTION-REVIEW-MATRIX-2026-06

Status: `indexed`, `control surface for future wrongful-conviction graph additions`.

Source titles:

Suffolk County District Attorney's Office, `Firearm conviction in connection to 1994 murder to be vacated`, published August 3, 2023: `https://www.suffolkdistrictattorney.com/press-releases/items/2023/8/4/firearm-conviction-in-connection-to-1994-murder-to-be-vacated`.

WBUR, `Mass. man sues state for $1M after serving 27 years in prison for a murder conviction that was later overturned`, published February 28, 2024: `https://www.wbur.org/news/2024/02/28/james-lucien-lawsuit-boston-police-wrongful-conviction`.

GBH News, `Prosecutors drop 1997 Boston murder case against Rickey 'FuQuan' McGee`, published November 6, 2025: `https://www.wgbh.org/news/local/2025-11-06/prosecutors-drop-1997-boston-murder-case-against-rickey-fuquan-mcgee`.

New England Innocence Project, `Edward Wright Exonerated!`, published August 21, 2025: `https://www.newenglandinnocence.org/innocence-blog/edwardwrightexonerated`.

New England Innocence Project, `Thomas Rosa, Jr. Exonerated After 34 Years Wrongfully Incarcerated`, published March 2026: `https://www.newenglandinnocence.org/innocence-blog/3/2026/tommyrosaexonerated`.

WBUR, `Boston man who says he was wrongfully convicted freed from prison`, published March 10, 2022: `https://www.wbur.org/news/2022/03/10/stephen-pina-withheld-evidence-fatal-shooting-suspect-release`.

New England Innocence Project, `Freedom to Celebrate`, published November 2025: `https://www.newenglandinnocence.org/innocence-blog/2025/11/14/freedom-to-celebrate`.

National Registry of Exonerations, October 2025 newsletter, `An Exoneration without Freedom`: `https://exonerationregistry.org/sites/exonerationregistry.org/files/documents/October_2025_Newsletter_0.pdf`.

AP News, `A Massachusetts man wrongfully convicted of murder was awarded $13 million. He won't get all of it`, published November 2024: `https://apnews.com/article/wrongful-conviction-massachusetts-michael-sullivan-settlement-4456026b55892abb35120a8f1a7b9943`.

GBH News, `Man who was convicted for 1984 Beverly fire gets chance for new trial`, published December 30, 2024: `https://www.wgbh.org/news/local/2024-12-30/man-who-was-convicted-for-1984-beverly-fire-gets-chance-for-new-trial`.

AP News, `Massachusetts court overturns murder conviction of alleged getaway driver`, published November 2024: `https://apnews.com/article/700db5556a1ab3d7805dbeeb3a51da23`.

Extracted facts:

The review matrix consolidates recent and active Massachusetts murder-conviction review lanes into one control surface. It distinguishes final exonerations from vacated convictions, nolle prosequi filings, pending/contested retrial posture, compensation findings, and pure legal-insufficiency reversals. It also flags actor-level connectors when available, including John Brazil in Lucien, Judge Michael Ricciuti in Rosa/McGee, Peter O'Malley in Gaines, and Judge Jeffrey Karp in Carver.

Board implications:

Do not add every matrix row to the public board. Use the matrix to decide whether a future graph change has a repeated public actor, a source-backed institution, and a stable legal posture. James Lucien has moved from candidate to visible small-node treatment through `WEB-LUCIEN-BRAZIL-SUFFOLK-BPD-2021-2024`, the Ricciuti/Rosa/McGee lane has moved from candidate review to visible narrow court-actor treatment through `WEB-RICCIUTI-ROSA-MCGEE-SUFFOLK-WRONGFUL-CONVICTION-2023-2026`, the Milton Jones / Floyd Hamilton / Joseph Pope lanes have moved to visible small-node treatment through `WEB-OMALLEY-SUFFOLK-WRONGFUL-CONVICTION-CLUSTER-2022-2026`, and the Edward Wright lane has moved to visible narrow Hampden/Springfield treatment through `WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025`. Future additions still need separate source-ledger entries before visible graph changes.

## WEB-DELGADO-GARCIA-INDICTMENTS-2026

Status: `indexed`, `graph-ready`.

Source titles:

Massachusetts Attorney General page, `AG Campbell, Attorney David Meier Announce Conclusion of Independent Investigation into State Trooper Enrique Delgado-Garcia's Death, Indictments Returned`, published February 2026: `https://www.mass.gov/news/ag-campbell-attorney-david-meier-announce-conclusion-of-independent-investigation-into-state-trooper-enrique-delgado-garcias-death-indictments-returned`.

AP News, `Indictments follow recruit's death in boxing match during training`, published February 2026: `https://apnews.com/article/massachusetts-police-recruit-death-boxing-4d0a968b62f2bf864fe15933c28b6042`.

AP News, `3 state troopers plead not guilty to charges connected to death of recruit after boxing match`, published April 2026: `https://apnews.com/article/massachusetts-police-recruit-death-boxing-82eb23ef27f2ede3f844101d1553376b`.

Extracted facts:

AP reports that Sgt. Jennifer Penton and Troopers Edwin Rodriguez, David Montanez, and Casey LaMonte were indicted after the 2024 death of Massachusetts State Police recruit Enrique Delgado-Garcia. The reported charges include involuntary manslaughter and causing serious bodily injury to a person participating in training, with an additional perjury charge for Penton. AP also reports that Penton, Rodriguez, and Montanez pleaded not guilty in April 2026. The Mass.gov official page is indexed and should remain the preferred official source, but it returned a 403 from the local fetch attempt during this pass.

Board implications:

This supports Delgado-Garcia's victim anchor and direct edges to the charged academy staff and Massachusetts State Police Academy context, while preserving the presumption of innocence.

## WEB-MSP-ACADEMY-REVIEW-2026

Status: `indexed`, `lead`.

Source titles:

Massachusetts State Police page, `Massachusetts State Police Release Independent Academy Review and Announce Immediate Training Improvements`, published May 2026: `https://www.mass.gov/news/massachusetts-state-police-release-independent-academy-review-and-announce-immediate-training-improvements`.

WBUR, `State police promise 'meaningful action' after report on training death`, published May 20, 2026: `https://www.wbur.org/news/2026/05/20/state-police-boxing-training-death`.

Extracted facts:

WBUR reports that the independent academy review followed Delgado-Garcia's death, called for 100 changes, and that MSP Superintendent Geoffrey Noble said the academy had permanently ended boxing and head-strike activities. WBUR also reports that 31 recommendations were prioritized before the next recruit class resumes, and that the June 2026 class was delayed. The Mass.gov page is indexed and should remain the preferred official source, but it returned a 403 from the local fetch attempt during this pass.

Board implications:

This is reform/context evidence for the Delgado-Garcia lane. It supports institutional context around MSP Academy and Geoffrey Noble, but it should not be used to make new culpability claims about individual defendants.

## WEB-NORFOLK-CONFIDENTIAL-2024

Status: `indexed`, `lead`.

Source title:

NBC10 Boston, `Questions about MA system to investigate murder cases pile up`, published November 2024: `https://www.nbcboston.com/investigations/questions-about-mass-system-to-investigate-murder-cases-pile-up-is-change-on-the-horizon/3557331/`.

Extracted facts:

NBC10 Boston uses Juston Root's case to explain concerns about Massachusetts homicide and police-shooting investigation structure, including state police detectives embedded in district attorney offices. The article identifies the six officers cleared by Norfolk DA Michael Morrissey's office in the fatal Brookline shooting and records Jennifer Root Bannon's criticism of the investigation.

Board implications:

This is a useful narrative and systems source for the Root/Norfolk DA lane. It should support source notes and article framing, not replace the Norfolk DA PDF, Suffolk DA report, body camera record, or case filings for graph-level claims.

## WEB-NORFOLK-DA-FALLOUT-2025

Status: `indexed`, `lead`.

Source title:

Vanity Fair, `Beyond the Karen Read Verdict: DA Michael Morrissey and the Scandal Still Haunting Massachusetts`, published July 2025: `https://www.vanityfair.com/style/story/karen-read-verdict-norfolk-county-da`.

Extracted facts:

Vanity Fair synthesizes the public fallout around the Read/O'Keefe prosecution, Birchmore federal case, and Juston Root shooting. It reports on the reassignment or discipline context for several MSP/Norfolk DA figures and explicitly frames these cases as part of a public-trust crisis around Norfolk County law enforcement and prosecution.

Board implications:

This is a strong lead/synthesis source for the project's current hot-button question, but it is not the final source for individual connectors. Use it to prioritize primary-source retrieval and to explain why the Norfolk County cluster deserves specialized attention.

## ROOT-NDAO-2020-REPORT

Status: `ingested`, `graph-ready`.

Source title: `03-09-20 Norfolk DA Report - Root shooting.pdf`.

Drive ID from `_DRIVE_FULL_INDEX.tsv`: `1JHiwZB4ci75FHK0UwTn8ujfcme31bufI`.

Reviewed local extract: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/_OCR_03-09-20_Norfolk_DA_Report.txt`.

Relevant local lines: `_DRIVE_FULL_INDEX.tsv:1`; `_OCR_03-09-20_Norfolk_DA_Report.txt:4-13`, `30-37`, `174-203`, `216-229`, `340-352`.

Extracted facts:

The Norfolk DA report is on Norfolk District Attorney letterhead under Michael W. Morrissey. It says Morrissey reviewed the February 7, 2020 deadly-force events in Brookline under Massachusetts law, reviewed documents and recordings, and reached findings on the shooting. The OCR states that OCME informed the Norfolk DA there was evidence of 26 entry wounds, and that MSP ballistics found 31 shell casings from six officers. The report concludes that the use of force by six officers was justified and that the Norfolk DA's Office would take no further action.

Board implications:

This supports the existing Root links to `INORFOLK`, `morrissey`, `OCME`, and the Root shooting officer cluster. It should not be used alone to prove misconduct; it proves the official Norfolk DA review, institutional jurisdiction, and no-further-action decision.

## ROOT-GODIN-IAD-2022-0053

Status: `ingested`, `graph-ready`.

Source title: `11-30-22 IAD for David Godin violation BWC for 2-7-2020 violation - IAD2022-0053.pdf`.

Drive ID from `_DRIVE_FULL_INDEX.tsv`: `1bnQNZJsriITH7T5HC-r-HpoWcoO5yiHt`.

Reviewed local extract: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/_OCR_Godin_IAD2022-0053.txt`.

Relevant local lines: `_DRIVE_FULL_INDEX.tsv:5`; `_OCR_Godin_IAD2022-0053.txt:60-75`, `117-126`, `220-235`, `245-254`, `350-379`.

Extracted facts:

The OCR records a BPD IAD report by Lt. Thomas W. Lema Jr. for complaint number 2022-0053, focused on BPD Rule 405 body-worn-camera issues. It records Godin confirming he followed cruisers into Brookline and was later interviewed by the Boston Police Homicide Unit and the Norfolk County DA's Office. It also records questioning about body-worn camera placement, failure to record the incident, and a device audit trail. The OCR also says another FDIT report by Sgt. Det. Mark Sullivan may speak more directly to the violation.

Board implications:

This strengthens the Root evidence lane around Godin, BPD, Norfolk DA investigative handling, and body-worn-camera issues. It supports a graph connector for the Godin/BWC lane and a separate Marc/Mark Sullivan FDIT lead. Do not merge that FDIT trail into the existing Michael Sullivan Form 26 trail.

## ROOT-BANNON-COMPLAINT-2020

Status: `ingested`, `graph-ready for party and claim connectors`.

Source title: `8-10-20 COMPLAINT Filed Juston Root.pdf`.

Public mirror: `https://media.wbur.org/wp/2020/08/081020_root_bpd_lawsuit.pdf`.

Reviewed local source: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/8-10-20 COMPLAINT Filed Juston Root.pdf`.

Extracted facts:

The complaint names Jennifer Root Bannon as Juston Root's sister and estate representative. It names David Godin, Joseph McMenamy, Leroy Fernandes, Brenda Figueroa, Corey Thomas, Paul Conneely, and the City of Boston as defendants. It alleges excessive force and related claims in connection with the February 7, 2020 events, including the BWH encounter, the pursuit into Brookline, the fatal shooting, and the civilian valet collision.

Board implications:

This source supports the existing Root links to the six officer defendants, the City/Boston Police lane, the Massachusetts State Police lane through Conneely, and Jennifer Root Bannon's litigation role if she is added later. Allegations from the complaint should remain allegation-status unless confirmed by an adjudicated source or independent record.

## ROOT-GODIN-BWC-MOTION-2021

Status: `ingested`, `graph-ready for BWC-handling connectors`.

Source title: `05-04-21 District Court filing - Boston Police Officer lied about his body worn camera.pdf`.

Reviewed local source: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/05-04-21 District Court filing - Boston Police Officer lied about his body worn camera.pdf`.

Related public listing: `https://justonroot.com/court-filings`.

Extracted facts:

The filing says Godin repeatedly claimed he was not wearing a body-worn camera, while video from another BPD officer's camera allegedly showed him wearing one and removing it in the cruiser. It describes discovery disputes about BPD body-worn-camera footage, audit logs, preservation, production, and supervisory collection. It also identifies Sgt. Det. William Doogan as transporting Godin and another BPD officer to headquarters, where Godin surrendered his body-worn camera and phone.

Board implications:

This source supports graph connectors for Godin, William Doogan, BPD, and the Root BWC-handling lane. It should not be used to overstate adjudicated misconduct; it is a litigation filing and should be paired with IAD, FDIT, court-opinion, and production-record sources.

## ROOT-FIRST-CIRCUIT-2024

Status: `ingested`, `graph-ready`.

Source title: `_fed_1stCir_opinion.pdf`.

Public mirrors: `https://law.justia.com/cases/federal/appellate-courts/ca1/22-1958/22-1958-2024-04-22.html`; `https://www.govinfo.gov/app/details/USCOURTS-ca1-22-01958`.

Reviewed local extract: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/_fed_1stCir_opinion.txt`.

Relevant local lines: `_fed_1stCir_opinion.txt:19-23`, `87-97`, `116-126`, `132-140`, `237-261`, `284-296`, `365-375`, `377-430`, `453-488`, `539-543`, `981-1016`, `3217-3439`, `4349-4412`.

Extracted facts:

The First Circuit opinion identifies Jennifer Root Bannon as plaintiff-appellant and David Godin, Joseph McMenamy, Leroy Fernandes, Brenda Figueroa, Corey Thomas, Paul Conneely, and the City of Boston as defendants-appellees. The majority affirmed summary judgment and qualified immunity. The opinion also records the BWH response by Godin and Michael St. Peter, the later pursuit and shooting, Conneely's role, body-worn-camera evidence, FDIT reporting by John Broderick and Marc Sullivan, and non-party Brookline/BPD witness material involving Christopher Elcock and David Wagner.

Board implications:

This is the strongest adjudicated federal source for the Root civil-rights lane. It supports existing Root connectors to the six defendant officers, Boston Police, Massachusetts State Police, City of Boston, Broderick, St. Peter, Elcock, Wagner, and the newly separated Marc Sullivan FDIT connector. It also requires the board to preserve the majority outcome: the federal appellate decision affirmed summary judgment for the defendants.

## ROOT-BUKHENIK-FANNING-IMAGE-2020

Status: `ingested`, `graph-supporting lead`.

Source title: `MSP- Yuri Bukhenik Brookline officers.png`.

Drive ID from `_DRIVE_FULL_INDEX.tsv`: `1TB3weUQJ6Jye-_fsU9l_s8Fd45b1hvmH`.

Reviewed local image: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/MSP- Yuri Bukhenik Brookline officers.png`.

Extracted facts:

The OCR reads as a message from Sergeant John Fanning of the Massachusetts State Police at the Norfolk District Attorney's Office to Sergeant Detective John Broderick of Boston Police Area B2 Detectives. It says Tpr. Bukhenik did interviews at Brookline PD for Elcock, Hall, Incharica, Morgan, Amendola, and Wagner, while Tpr. Guarino did interviews at Brookline PD. It also references report-writing and transcript logistics.

Board implications:

This supports existing Root graph connectors for Fanning, Bukhenik, Guarino, Broderick, Elcock, and Wagner. It is not a misconduct source by itself. The `Tpr. Bukhenik Email Correspondence_redacted.pdf` file has since been ingested as `ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020`; the `8 BULLETS 02-06-20 FANNING Email from Public Records Request Norfolk DA.pdf` item remains a retrieval target for any stronger Fanning-specific public-record claim.

## ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020

Status: `ingested`, `graph-ready for Root/Brookline digital-evidence communication connectors`.

Source title: `Tpr. Bukhenik Email Correspondence_redacted.pdf`.

Google Drive URL: `https://drive.google.com/file/d/12eWjzGVhlkpLgr2Y03QlQo4J7hmva5K5/view`.

Drive ID from connector fetch: `12eWjzGVhlkpLgr2Y03QlQo4J7hmva5K5`.

Extracted facts:

The correspondence includes a February 12, 2020 email from Norfolk DA Multimedia Director and Certified Forensic Video Technician Coleen Crawford to Trooper Yuriy Bukhenik, with Sergeant John Fanning copied. The subject identifies the Gill video interview and the Brookline shooting date. Crawford states that she converted and archived the Gill video-interview file and made it available from a digital case folder named for Fanning and the Brookline shooting. The same correspondence packet also shows Fanning and Bukhenik coordinating audio, transcripts, reports, and Brookline Police Department interviews in the Juston Root investigation, and it includes a February 18, 2020 Brookline Lethal Force message asking recipients to prioritize outstanding reports because the DA was preparing a media report.

Board implications:

This directly supports the existing Crawford-to-Root case connector, the existing Fanning-to-Crawford professional connector, and a new Crawford-to-Bukhenik communication connector. It also strengthens the Fanning-to-Bukhenik Root correspondence lane already represented on the board. Use this source only for digital-evidence handling, correspondence, report/transcript coordination, and case-role overlap; it does not establish misconduct by itself.

## ROOT-DRIVE-FULL-INDEX

Status: `ingested`, `lead`.

Source title: `_DRIVE_FULL_INDEX.tsv`.

Local path: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/_DRIVE_FULL_INDEX.tsv`.

Relevant local lines: `1-55`, `808-816`.

Extracted facts:

The index lists the Root report, public-record files, ballistics reports, First Circuit record appendices, NDAO Axon audit PDFs, a February 6, 2020 Fanning email PDF, a February 18, 2020 NDAO media-readiness email image, a Bukhenik Brookline officers image, and two indexed copies of Bukhenik email correspondence. It also lists Suffolk/Boston investigation files and Boston Police interview records.

Board implications:

The index is a recovery surface and lead generator. Items listed here should not become graph edges until the underlying file is reviewed or OCR'd. The Fanning and Bukhenik entries are high-priority retrieval/OCR targets.

## ROOT-CAREER-INVENTORY

Status: `ingested`, `lead`.

Source title: `_CAREER_INVENTORY_NorfolkCounty.md`.

Local path: `/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/_CAREER_INVENTORY_NorfolkCounty.md`.

Relevant local lines: `74-91`, `138-155`, `447-458`.

Extracted facts:

The inventory preserves prior board work on Bukhenik, Fanning, Tully, DiCicco, Morrissey, Traub, Brennan, and open Root follow-up tasks. It specifically flags the Fanning February 6, 2020 email and Bukhenik/Fanning correspondence PDFs as priority retrieval/OCR tasks.

Board implications:

This is a useful internal continuity source, but it should be treated as a lead file. Use it to prioritize work, then confirm against primary records or reliable reporting before changing graph structure.
