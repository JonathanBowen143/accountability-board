# Source Ledger

Last updated: June 11, 2026.

This ledger records source surfaces reviewed or identified for the board. It is intentionally separate from `index.html`; evidence belongs here first, graph edges second.

## WEB-HISTORICAL-CONNECTOR-TIGHTENING-1921-2022

Status: `ingested`, `graph-ready for existing historical nodes only`.

Source titles:

Mass.gov, `Sacco & Vanzetti: The trial`: `https://www.mass.gov/info-details/sacco-vanzetti-the-trial`.

Mass.gov, `Sacco & Vanzetti: Justice on Trial`: `https://www.mass.gov/info-details/sacco-vanzetti-justice-on-trial`.

Massachusetts Supreme Judicial Court, `Attorney General v. Nathan A. Tufts`, 239 Mass. 458, decided June 21, 1921, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/239/239mass458.html`.

Massachusetts Supreme Judicial Court, `Attorney General v. Joseph C. Pelletier`, 240 Mass. 264, decided January 3, 1922, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/240/240mass264.html`.

WBUR, `In High-Profile Prosecutions, Martha Coakley Made Her Name`, published September 9, 2009: `https://www.wbur.org/news/2009/09/09/martha-coakley-background`.

GBH, `Gov. Baker seeks pardons in infamous Fells Acres child abuse case`, published November 18, 2022: `https://www.wgbh.org/news/local/2022-11-18/gov-baker-seeks-pardons-in-infamous-fells-acres-child-abuse-case`.

Extracted facts:

Mass.gov's Sacco/Vanzetti trial account states that the Norfolk County grand jury indicted Sacco and Vanzetti, the trial began in the Dedham courthouse on May 31, 1921, Superior Court Judge Webster Thayer presided, and District Attorney Frederick Katzmann prosecuted the case. Mass.gov's Justice on Trial account adds that the trial judge had sole authority over repeated new-trial motions, denied them all, and that then-existing appellate rules denied the SJC authority to review the strength of the trial evidence.

The Tufts decision states that the Supreme Judicial Court had jurisdiction under G.L. c. 211, section 4, to hear and determine an Attorney General information seeking removal of a district attorney when public-good charges of malfeasance, misfeasance, or nonfeasance were made. The Pelletier decision likewise treats district-attorney removal as a Supreme Judicial Court proceeding under the Attorney General's information and describes the statutory mechanism as designed to protect the public from corrupt, dishonest, dishonorable, inefficient, or incapacitated public officers.

WBUR reports that Martha Coakley joined the Middlesex DA's office in 1986 and that Scott Harshbarger, then a former Middlesex DA, had first hired Coakley into that office. WBUR and GBH both connect Coakley to the Fells Acres aftermath: WBUR says Coakley used her power as Middlesex DA to oppose Gerald Amirault's parole, while GBH reports that Coakley lobbied against Amirault's commutation.

Board implications:

Add existing-node historical tightening edges only: Katzmann to Thayer as a Sacco/Vanzetti trial role connector; Tufts and Pelletier to the SJC as district-attorney removal proceeding connectors; and Harshbarger to Coakley as a professional Middlesex DA lineage connector. Coakley's Middlesex DA office edge already exists and should remain. Do not use this pass to add Fred Moore, SJC justices, Boston book-war actors, Watch and Ward officers, or additional Fells Acres actors without a separate source-ledger entry.

## WEB-DEEGAN-FBI-INFORMANT-MURDER-CONVICTIONS-1965-2009

Status: `ingested`, `high-priority historical graph candidate; federal-lane scope decision needed`.

Source titles:

U.S. House Committee on Government Reform, `Everything Secret Degenerates: The FBI's Use of Murderers as Informants`, House Report 108-414, February 3, 2004, GovInfo: `https://www.govinfo.gov/content/pkg/CRPT-108hrpt414/html/CRPT-108hrpt414-vol1.htm`.

U.S. Court of Appeals for the First Circuit, `Limone, et al v. United States`, No. 08-1327, decided August 27, 2009, Justia mirror: `https://law.justia.com/cases/federal/appellate-courts/ca1/08-1327/08-1327p-01a-2011-02-25.html`.

U.S. Court of Appeals for the First Circuit, `Peter J. Limone et al. v. Dennis Condon et al.`, 372 F.3d 39, decided June 10, 2004, Justia mirror: `https://law.justia.com/cases/federal/appellate-courts/F3/372/39/593452/`.

U.S. District Court for the District of Massachusetts, `Limone v. United States`, 497 F. Supp. 2d 143, decided July 26, 2007, CaseMine mirror: `https://www.casemine.com/judgement/us/5914b3eaadd7b04934769118`.

Massachusetts Supreme Judicial Court, `Commonwealth vs. Joseph L. Salvati`, 420 Mass. 499, decided June 12, 1995, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/420/420mass499.html`.

National Registry of Exonerations, `Government Misconduct and Convicting the Innocent`, September 1, 2020: `https://exonerationregistry.org/sites/exonerationregistry.org/files/documents/Updated%20CP_Government_Misconduct_and_Convicting_the_Innocent%20%281%29.pdf`.

Extracted facts:

Edward "Teddy" Deegan was murdered in Chelsea on March 12, 1965. In 1968, Peter Limone, Louis Greco, Henry Tameleo, and Joseph Salvati were convicted in Suffolk County proceedings tied to Deegan's murder, with Limone, Greco, and Tameleo receiving death sentences later reduced to life imprisonment and Salvati receiving a life sentence. The SJC's 1995 Salvati decision records the original 1968 convictions and the Suffolk County posture of the case.

The First Circuit's 2009 opinion states that FBI agents cultivated Joseph Barboza as a cooperating witness, that the Commonwealth's convictions were based principally on Barboza's testimony, and that in December 2000 the FBI disclosed reliable intelligence it had possessed all along that undercut Barboza's account. By the time of disclosure, Tameleo and Greco had died in prison, Salvati had been paroled, and Limone remained incarcerated; the convictions of all four men were later vacated. The First Circuit affirmed federal liability and the damages awards on intentional-infliction-of-emotional-distress grounds.

The House report states that federal officials had information from surveillance and informants indicating that Joseph Barboza, Vincent "Jimmy" Flemmi, and other organized-crime actors were involved in the Deegan murder, and that the FBI had information contradicting Barboza's trial account. The report also records Judge Margaret Hinkle's January 5, 2001 new-trial order for Limone and the Suffolk County DA's January 30, 2001 non-prosecution posture for Salvati after newly disclosed FBI documents undermined Barboza's credibility and the Commonwealth's theory.

The National Registry of Exonerations treats the Limone, Greco, Tameleo, and Salvati convictions as a murder-exoneration example involving official misconduct. The Registry's 2020 report states that Barboza's testimony was used to convict the four men, that documents revealed FBI knowledge contradicting the convictions, and that all four were exonerated in 2001.

Board implications:

This is the strongest identified mid-20th-century Massachusetts murder-corruption gap in the current project. It has a local Massachusetts murder prosecution, Suffolk County court/DA posture, federal FBI informant misconduct, exoneration treatment, and later federal damages litigation. Do not add it to the visible public graph until the board decides whether a historical federal-lane exception is allowed. If opened later, the likely minimal public-board scope is: Edward "Teddy" Deegan as the underlying murdered person; Peter Limone, Louis Greco, Henry Tameleo, and Joseph Salvati as small wrongful-conviction victims; Suffolk DA / Suffolk Superior Court as local prosecution and court institutions; and a carefully labeled FBI Boston / federal-informant institution connector. Keep Joseph Barboza, Vincent Flemmi, H. Paul Rico, Dennis Condon, Raymond Patriarca, John Durham, Judge Margaret Hinkle, state detectives, prosecutors, and family/civil-litigation actors internal until a separate pass decides whether the public board is ready for named federal and organized-crime actors.

## WEB-WATCH-WARD-PELLETIER-ALLEN-SJC-1913-1975

Status: `ingested`, `graph-ready for narrow existing-node connectors`.

Source titles:

Massachusetts Historical Society, `Discovering the New England Watch and Ward Society`, published February 2011: `https://www.masshist.org/beehiveblog/2011/02/discovering-the-new-england-watch-and-ward-society/`.

Massachusetts Historical Society, `Godfrey Lowell Cabot papers II, 1909-1969: Guide to the Collection`: `https://www.masshist.org/collection-guides/view/fa0197`.

Northeastern University Archives and Special Collections, `New England Watch and Ward Society records`: `https://archivesspace.library.northeastern.edu/repositories/2/archival_objects/305812`.

American Heritage, `The Knave of Boston`: `https://www.americanheritage.com/knave-boston`.

Massachusetts Supreme Judicial Court, `Attorney General v. Joseph C. Pelletier`, 240 Mass. 264, decided January 3, 1922, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/240/240mass264.html`.

Extracted facts:

The Massachusetts Historical Society describes the New England Watch and Ward Society as a private organization with considerable political influence in the Boston area and region from 1878 to 1967. MHS records also place Godfrey Lowell Cabot inside the organization, including Watch and Ward material in the Cabot papers and society records from 1913 to 1921. Northeastern's archive record documents the organization's institutional continuity: founded in 1878, renamed the New England Watch and Ward Society in 1891, renamed again in 1957 and 1967, and merged into the Crime and Justice Foundation in 1975.

American Heritage's historical account links Cabot's Watch and Ward context to the Pelletier accountability lane: Cabot petitioned the SJC for Pelletier's impeachment and later brought documents to the Boston Bar Association, which examined Pelletier, Daniel H. Coakley, William J. Corcoran, and Nathan A. Tufts. The SJC's Pelletier decision confirms the official public-accountability mechanism: Attorney General J. Weston Allen brought an information under G.L. c. 211, section 4, seeking removal of Suffolk County District Attorney Joseph C. Pelletier.

Board implications:

Add narrow visible connectors from Watch and Ward Society to District Attorney Joseph Pelletier and to the Massachusetts Supreme Judicial Court as court-removal/accountability context. Keep Godfrey Lowell Cabot, Daniel H. Coakley, William J. Corcoran, Boston Bar Association actors, J. Frank Chase, H.L. Mencken, booksellers, and Boston Booksellers Committee actors documented internally unless a later pass intentionally opens the private-influence and censorship subnetwork. Do not treat Watch and Ward as a public agency; it is a private political-influence and accountability-pressure connector in this lane.

## WEB-CURLEY-COMMUTATION-AND-COAKLEY-1903-1950

Status: `ingested`, `internal-only historical lead; not public-board-ready without a Coakley/Pelletier subnetwork`.

Source titles:

U.S. House of Representatives History, Art & Archives, `CURLEY, James Michael`: `https://history.house.gov/People/Listing/C/CURLEY%2C-James-Michael-%28C000996%29/`.

National Governors Association, `Gov. James Michael Curley`: `https://www.nga.org/governor/james-michael-curley/`.

Mass Moments, `Mayor Curley Jeopardizes Election`: `https://www.massmoments.org/moment-details/mayor-curley-jeopardizes-election.html`.

Massachusetts Historical Society, `Good Government Association Records, 1900-1936`: `https://www.masshist.org/collection-guides/view/fa0403`.

American Heritage, `The Knave of Boston`: `https://www.americanheritage.com/knave-boston`.

Extracted facts:

The U.S. House biographical directory records that James Michael Curley was convicted in 1903 of conspiracy, sentenced to county jail, later convicted on January 18, 1946 of conspiracy and mail fraud, and had his sentence commuted by President Harry S. Truman on November 26, 1947. NGA records Curley as Massachusetts governor from 1935 to 1937, later reelected Boston mayor, and says he served five months in prison after the 1947 mail-fraud conviction. Mass Moments frames the 1946 mail-fraud charge as `somewhat spurious`, says anti-Curley forces played a large role in bringing corruption charges against him, and describes Truman's commutation before Curley returned to finish his mayoral term. MHS records place Curley in the Good Government Association candidate-file universe, a reform/civic-accountability context around Boston municipal politics. American Heritage ties Curley to Daniel H. Coakley in the Mishawum Manor / moving-picture executive extortion story and ties Coakley, Pelletier, Corcoran, Tufts, Godfrey Lowell Cabot, Watch and Ward, the Boston Bar Association, and the SJC into the existing Pelletier accountability lane.

Board implications:

Do not add Curley to the visible board from the commutation alone. The commutation is historically important and politically contested, but it currently points into a federal clemency / Boston machine-politics lane rather than a clean existing-node connector. The strongest local board bridge is Curley's documented relationship to Daniel H. Coakley, who is already internal to the Watch and Ward / Pelletier lane. Revisit Curley only if the public graph intentionally opens the Coakley/Pelletier/Corcoran/Tufts subnetwork or adds a historical Boston municipal-corruption layer. If added later, label him `Mayor James Michael Curley` or `Gov. James Michael Curley` based on the specific connector, not as a generic commutation node.

## WEB-TITICUT-FOLLIES-BRIDGEWATER-SJC-1966-1993

Status: `ingested`, `graph-ready for narrow Bridgewater / SJC institution connector; film stays internal`.

Source titles:

Zipporah Films, `Titicut Follies`: `https://zipporahfilms.com/titicut-follies`.

Massachusetts Supreme Judicial Court, `Commonwealth v. Wiseman`, 356 Mass. 251, decided June 24, 1969, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/1969/356-mass-251-2.html`.

U.S. District Court for the Southern District of New York, `Cullen v. Grove Press, Inc.`, 276 F. Supp. 727, decided November 30, 1967, Justia mirror: `https://law.justia.com/cases/federal/district-courts/FSupp/276/727/1461254/`.

Boston TV News Digital Library, `Titicut Follies, 1967`: `https://bostonlocaltv.org/blog/2012/02/titicut-follies-1967`.

WBUR, `Documentarian Discusses Legacy Of Troubles At Bridgewater Hospital`, published August 18, 2014: `https://www.wbur.org/news/2014/08/18/fred-wiseman-bridgewater-state-hospital`.

Massachusetts Association for Mental Health, `The History of Bridgewater State Hospital, Bridgewater, Massachusetts`, October 2023: `https://mamh-web.files.svdcdn.com/production/files/BSH-History-10-2-23.pdf?dm=1696270673`.

Extracted facts:

Zipporah Films identifies `Titicut Follies` as a 1967 documentary about conditions at the State Prison for the Criminally Insane at Bridgewater, Massachusetts. `Cullen v. Grove Press` states that Wiseman and assistants were permitted to enter Bridgewater in 1966 to film a real-life documentary about care and treatment of inmates, that the final 84-minute film was titled `Titicut Follies`, and that conditions in public institutions such as Bridgewater were matters of legitimate public interest. `Commonwealth v. Wiseman` confirms the Massachusetts SJC litigation: the Commonwealth and others sought to enjoin all showings of the film, the Superior Court decree enjoined showing the film to any audience and required delivery of film material for destruction, and the SJC treated the film as informative to specialized professional and student audiences while upholding restricted-showing relief.

The Boston TV News Digital Library summarizes the public-history arc: Wiseman filmed at Bridgewater, Massachusetts officials tried to stop public release on privacy grounds, the ban became historically significant because it was not an obscenity ban, later litigation loosened restrictions, and the film was eventually broadcast publicly. WBUR describes the film as making Bridgewater a national symbol of mistreatment of people with mental illness and says the film was banned for more than twenty years. The 2023 Bridgewater history report uses `Commonwealth v. Wiseman` as a key source for the suppression history and places the dispute inside the longer institutional history of Bridgewater State Hospital.

Board implications:

Do not add `Titicut Follies (1967)` as a public-board node. Use the film and litigation as internal evidence for a narrow institution-level connector from Bridgewater State Hospital to the Massachusetts Supreme Judicial Court with a `filing` edge. Do not add Frederick Wiseman, Elliot Richardson, Judge Harry Kalus, Judge Andrew Gill Meyer, Grove Press, individual Bridgewater staff, inmates, or later patient-death actors to the public board from this pass alone. This lane supports the broader institutional-suppression theme, not a claim that Watch and Ward directly controlled the film dispute.

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

## WEB-COX-OPAT-CRB-OVERSIGHT-2025-2026

Status: `ingested`, `internal context; public OPAT node removed after scope review`.

Source titles:

Boston.gov, `Police Accountability and Transparency`: `https://www.boston.gov/departments/police-accountability-and-transparency`.

City of Boston Office of Police Accountability and Transparency Civilian Review Board, `Letter to Commissioner Cox Re: Authority of OPAT Investigations and Civilian Review Board Findings Under Massachusetts Law`, dated May 1, 2026: `https://www.boston.gov/sites/default/files/file/2026/05/Letter%20to%20Comr%20Cox%20from%20CRB%205-1-2026.pdf`.

WBUR, `Boston police chief routinely rejects disciplinary recommendations by oversight board`, published August 28, 2025: `https://www.wbur.org/news/2025/08/28/boston-police-commissioner-officers-discipline`.

GBH, `Councilors push for clarity on Boston police bodycam policies after Roxbury shooting`, published April 8, 2026: `https://www.wgbh.org/news/politics/2026-04-08/councilors-push-for-clarity-on-boston-police-bodycam-policies-after-roxbury-shooting`.

NBC10 Boston, `Karen Read's attorney demands disciplinary review of Boston police commissioner`, published October 28, 2025: `https://www.nbcboston.com/news/canton-karen-read-case/karen-read-michael-cox-kelly-dever-police/3835137/`.

Extracted facts:

Boston.gov describes the Office of Police Accountability and Transparency as a civilian body that investigates Boston Police Department misconduct and supports the OPAT Commission, Civilian Review Board, and Internal Affairs Oversight Panel. Boston.gov's OPAT page lists CRB meeting records and correspondence, including the May 1, 2026 CRB letter to Commissioner Cox. In that letter, the CRB disputes BPD's position that OPAT or CRB findings require a separate IAD investigation before sustained findings or discipline; the letter says Massachusetts law does not require police misconduct investigations to be conducted exclusively by internal affairs units and says OPAT investigations may provide a lawful factual record, subject to the commissioner's independent judgment and civil-service protections.

WBUR reports that Cox has often rejected or not responded to OPAT disciplinary recommendations, including a reported OPAT recommendation involving Officer Matthew Conley. GBH reports that the Boston City Council pushed for clearer body-camera-release protocols after Boston Police Officer Nicholas O'Malley was charged in the fatal shooting of Stephenson King Jr., and that OPAT's executive director said OPAT had been denied access to the King footage. NBC10 Boston reports that Karen Read's attorney demanded a disciplinary review of Cox and alleged that Cox publicly denied involvement in the Read/Dever matter despite alleged earlier notice; this remains an allegation and public response posture, not an adjudicated finding.

Board implications:

Do not keep a standalone `Boston OPAT` node on the public board for the current layer. OPAT is officially separate from the Boston Police Department and should not be treated as a BPD subunit, but the present board is focused on victims, public officials, and recurring case actors. Roll the OPAT/CRB material into the Cox/BPD accountability evidence notes unless later OPAT records create a repeated visible actor, adjudicated finding, or direct public-board connector. Keep the Stephenson King Jr. / Nicholas O'Malley lane internal until the underlying video, court record, and charging record are reviewed directly.

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

## WEB-READ-MCLAUGHLIN-ALBERT-2025

Status: `ingested`, `graph-ready for narrow personal and family connectors`.

Source titles:

ABC News, `Paramedic testifies she heard Karen Read say, 'I hit him,' in murder retrial`, published May 5, 2025: `https://abcnews.com/US/karen-read-murder-retrial-paramedic-testimony/story?id=121479249`.

Court TV, `Key players in the Karen Read murder case`: `https://www.courttv.com/news/key-players-in-the-karen-read-murder-case/`.

Extracted facts:

ABC reports that defense attorney Alan Jackson questioned Canton firefighter/paramedic Katie McLaughlin about her relationship with Caitlin Albert, including shared social functions. McLaughlin described Caitlin as someone she went to high school with, shares mutual friends with, and socializes with, while saying they were not close friends and did not have a one-on-one relationship. Court TV identifies Caitlin Albert as the daughter of Brian and Nicole Albert and notes that Caitlin attended high school with McLaughlin.

Board implications:

Add a narrow McLaughlin-to-Caitlin Albert personal/acquaintance connector and a Caitlin-to-Nicole Albert family connector. The McLaughlin connector should not be treated as a close-friendship claim or a misconduct finding; it documents a litigated acquaintance/social-overlap issue in the Read/O'Keefe retrial.

## WEB-READ-HIGGINS-CANTON-PD-2024

Status: `ingested`, `graph-ready for narrow professional/institutional and call/contact connectors`.

Source titles:

Boston.com, `Karen Read trial: Defense grills Brian Higgins on the fate of his cellphone, SIM card`, updated May 24, 2024: `https://www.boston.com/news/crime/2024/05/24/karen-read-murder-trial-livestream-video-friday-may-24-brian-higgins/`.

NBC10 Boston, `ATF agent testifies about flirtatious text exchanges with Karen Read as trial continues`, published May 24, 2024: `https://www.nbcboston.com/news/local/karen-read-trial-day-17/3379021/`.

Extracted facts:

Boston.com reports that Higgins had a satellite office at the Canton police station and accessed the station's sally port on January 29, 2022, before Read's SUV was brought in. NBC10 Boston reports that Higgins testified he went to the Canton Police Department after leaving the Albert home, where he had an office and stored ATF vehicles, and that he went there to move work vehicles so the lot could be plowed. NBC10 Boston also reports that Higgins testified Canton Police Chief Kenneth Berkowitz and Brian Albert were calling him around 6:30 a.m. Boston.com reports that Alan Jackson questioned Higgins about phone conversations with Brian Albert and then-Canton Police Chief Kenneth Berkowitz; Higgins denied collusion and denied discussing the matter with Albert.

Board implications:

Add a narrow Higgins-to-Canton Police `business/professional tie` connector. This explains why a federal ATF agent already in the Read/O'Keefe witness cluster also belongs near the Canton Police institution. Also add a narrow Higgins-to-Berkowitz `communication/community tie` connector for the reported call/contact trail. Do not treat either connector as Canton Police employment, a federal-prosecution lane, or a misconduct finding. Do not add a separate Higgins-to-Brian Albert call connector unless a later source supports a cleaner public-facing communication edge beyond their existing personal/friendship connector.

## WEB-READ-GUARINO-PHONE-DATA-2024-2025

Status: `ingested`, `graph-ready for narrow phone-data/evidence-handling connectors`.

Source titles:

WBZ NewsRadio, `Karen Read Retrial: Day 2 Of Testimony Ends`, published April 23, 2025: `https://wbznewsradio.iheart.com/content/karen-read-retrial-day-2-of-testimony/`.

Boston.com, `Karen Read murder trial: O'Keefe's mother takes the stand`, updated April 23, 2025: `https://www.boston.com/news/crime/2025/04/23/karen-read-murder-trial-livestream-video-wednesday-april-23/`.

CBS Boston, `Karen Read's angry voicemails to John O'Keefe played at murder trial`, updated June 20, 2024: `https://www.cbsnews.com/boston/news/karen-read-trial-live-stream-today-day-27/`.

Extracted facts:

WBZ NewsRadio reports that MSP Trooper Nicholas Guarino testified as a forensic expert involved in extracting and reviewing phone data from John O'Keefe, Karen Read, Jennifer McCabe, and Kerry Roberts. Boston.com reports that Guarino testified about accessing cellphone data from several individuals in Read's case, including Read and O'Keefe, and that he does phone and computer forensic investigative work for the Norfolk County District Attorney's Office. CBS Boston reports that Guarino examined O'Keefe's cellphone, investigated multiple phones and computers connected to the case, and walked jurors through Waze and phone location data tied to O'Keefe's path of travel.

Board implications:

Add narrow Guarino-to-John O'Keefe, Guarino-to-Jennifer McCabe, and Guarino-to-Kerry Roberts `case/evidence-handling` connectors. Guarino-to-Karen Read already exists through the Read/O'Keefe case lane. These connectors document phone-data extraction, review, and testimony context only; they do not adjudicate the accuracy of the digital evidence, the prosecution theory, the defense theory, or any misconduct allegation.

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

## WEB-ROSARIO-LOWELL-MIDDLESEX-ARSON-MURDER-WRONGFUL-CONVICTION-1982-2023

Status: `ingested`, `graph-ready for Lowell Police / Middlesex court connectors`.

Source titles:

Massachusetts Supreme Judicial Court, `Commonwealth v. Victor Rosario`, 477 Mass. 69, decided May 11, 2017, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/477/477mass69.html`.

New England Innocence Project, `The Story Behind the Exoneration of Victor Rosario`: `https://www.newenglandinnocence.org/eleven-year-journey`.

New England Innocence Project, `A Step Closer to Justice for Victor Rosario!`, published May 11, 2017: `https://www.newenglandinnocence.org/innocence-blog/2017/5/11/a-step-closer-to-justice-for-victor-rosario`.

U.S. District Court for the District of Massachusetts, `Rosario v. City of Lowell`, civil action No. 1:19-cv-10532-LTS, order dated September 27, 2019, GovInfo: `https://www.govinfo.gov/content/pkg/USCOURTS-mad-1_19-cv-10532/pdf/USCOURTS-mad-1_19-cv-10532-0.pdf`.

Loevy & Loevy, `Victor Rosario wins one of the largest wrongful conviction settlements in New England history`: `https://www.loevy.com/big-wins/victor-rosario-historic-settlement/`.

Middlesex District Attorney's Office, `District Court Locations`: `https://www.middlesexda.com/about-us/pages/district-court-locations`.

Extracted facts:

The SJC records that Victor Rosario was convicted in 1983 of arson in a dwelling house and eight counts of second-degree murder after a 1982 Lowell fire, and affirmed the order allowing his new-trial motion. The SJC framed the new-trial posture around newly discovered evidence, including fire-science evidence and the circumstances of Rosario's confession. NEIP identifies the Decatur Street fire as a Lowell fire that killed eight people, including five children, describes Rosario as a bystander who tried to help, and reports the SJC decision as a landmark ruling that left Middlesex DA Marian Ryan's office to decide whether to retry him.

The federal Rosario civil-rights order records that the underlying investigation involved a fire on Decatur Street in Lowell, that Rosario was incarcerated for thirty-two years, that the SJC affirmed his new-trial order in 2017, and that the Middlesex DA declined to proceed with a new trial after the SJC ruling. Loevy & Loevy reports that the Lowell City Council approved a $13 million settlement and attributes the wrongful-conviction claim to Lowell police evidence fabrication, coercive confession practices, and junk fire science. Middlesex DA's district-court page identifies Lowell as part of the Lowell District Court region and places that region within the Middlesex DA's office structure.

Board implications:

Victor Rosario already appears as a small wrongful-conviction victim node. Add a Lowell Police Department institution node and narrow connectors from Rosario to Lowell Police and Middlesex Superior Court, plus a structural Lowell Police to Middlesex DA jurisdiction connector. Keep the City of Lowell, Lowell fire investigators, individual Lowell police officers, Massachusetts State Police Officer David Coonan, Lowell Fire Department, William Gilligan, unknown officers, Garcia brothers, civil-rights counsel, settlement actors, and individual fire victims internal unless a later source pass identifies repeated public actors or a reason to open a fire-science / false-confession subnetwork.

## WEB-REGIONAL-CITY-MURDER-CANDIDATE-SCAN-1979-2026

Status: `indexed`, `regional expansion queue; not all graph-ready`.

Source titles:

Worcester County District Attorney's Office, `Charges Dropped Against Gary Cifizzari in 1979 Murder`, published December 10, 2019: `https://worcesterda.com/charges-dropped-against-gary-cifizzari-in-1979-murder/`.

New England Innocence Project, `Commonwealth Drops Case Against Gary Cifizzari`, published December 10, 2019: `https://www.newenglandinnocence.org/innocence-blog/2019/12/10/commonwealth-drops-case-against-gary-cifizzari`.

Massachusetts Supreme Judicial Court, `Commonwealth v. Gary J. Cifizzari`, 397 Mass. 560, decided June 12, 1986, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/397/397mass560.html`.

Massachusetts Supreme Judicial Court, `Commonwealth v. Mark Schand`, 420 Mass. 783, decided June 14, 1995, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/420/420mass783.html`.

NEPM, `Springfield To Pay $6.5 Million To Man Wrongfully Imprisoned For 27 Years`, published December 8, 2020: `https://www.nepm.org/regional-news/2020-12-08/springfield-to-pay-6-5-million-to-man-wrongfully-imprisoned-for-27-years`.

U.S. District Court for the District of Massachusetts, `Schand v. City of Springfield`, civil action No. 3:15-cv-30148-WGY, memorandum and order dated May 6, 2019, GovInfo: `https://www.govinfo.gov/content/pkg/USCOURTS-mad-3_15-cv-30148/pdf/USCOURTS-mad-3_15-cv-30148-1.pdf`.

WAMC, `Man Sues Police For Wrongful Murder Conviction`, published January 29, 2014: `https://www.wamc.org/new-england-news/2014-01-29/man-sues-police-for-wrongful-murder-conviction`.

New England Innocence Project, `Court Overturns 1985 Springfield Murder Conviction`, published April 15, 2025: `https://www.newenglandinnocence.org/innocence-blog/2025/edwardwrightconvictionoverturned`.

New England Innocence Project, `DNA Testing Will Proceed in Shawn Tanner's Case`, published October 31, 2025: `https://www.newenglandinnocence.org/innocence-blog/2025/10/31/shawntannerdnatesting`.

Social Law Library, `Commonwealth vs. Shawn L. Tanner`, February 2026 slip opinion: `https://www.socialaw.com/services/slip-opinions/february-2026/commonwealth-vs-shawn-l-tanner/`.

Extracted facts:

The Worcester County DA and NEIP both report that the Worcester DA dropped the case against Gary Cifizzari in December 2019 after DNA evidence undermined his 1984 Worcester County murder conviction in the 1979 killing of Concetta Schiappa. The SJC's 1986 Cifizzari opinion records the original first-degree murder conviction, bite-mark evidence, and Worcester County Superior Court posture. This is a strong Worcester County lane, but it is Milford/Worcester County, not a clean Worcester city police lane.

The Springfield/Hampden cluster is deeper than the current board shows. The SJC's Schand opinion records Mark Schand's first-degree murder conviction. NEPM reports that Springfield agreed to pay Schand $6.5 million after he was wrongfully imprisoned for twenty-seven years, after a judge found he was wrongfully convicted and the DA dropped charges. The federal Schand civil-rights order identifies remaining claims against City of Springfield and former Springfield police officers. WAMC reports that Charles Wilhite sued Springfield police after a murder conviction, vacatur, and acquittal at retrial. NEIP's Edward Wright materials already support the visible Springfield/Hampden lane, with withheld evidence and false testimony findings.

The New Bedford/Bristol lane is significant but not exoneration-ready. NEIP reports that Shawn Tanner was convicted of a 1988 Dartmouth murder and sought DNA testing before his death, while the Bristol County DA opposed completion of testing after his death. The 2026 SJC slip opinion concerns the continuing validity of post-conviction DNA testing after death. This is an important Bristol / Dartmouth / New Bedford-region lead, but it should remain internal until DNA results or a posthumous exoneration posture changes the case.

Board implications:

Next regional priorities should be sequenced rather than dumped into the public board. Lowell / Rosario has been hardened through a separate pass, and Springfield / Hampden has been extended through the later `WEB-SCHAND-WILHITE-SPRINGFIELD-HAMPDEN-WRONGFUL-CONVICTIONS-1986-2020` entry. Next, document Cifizzari as a Worcester County candidate, but do not treat it as a Worcester city police lane. Keep Tanner / New Bedford-Bristol internal pending DNA-testing outcome and final legal posture. Do not add Dana Gaul to the public board from this pass because he appears to be a wrongful-arrest / dismissed-charge lane, not an overturned murder conviction or resolved exoneration.

## WEB-SCHAND-WILHITE-SPRINGFIELD-HAMPDEN-WRONGFUL-CONVICTIONS-1986-2020

Status: `ingested`, `implemented as narrow Springfield / Hampden small-node expansion`.

Source titles:

Massachusetts Supreme Judicial Court, `Commonwealth v. Mark Schand`, 420 Mass. 783, decided June 14, 1995, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/420/420mass783.html`.

Centurion, `Mark Schand`: `https://centurion.org/cases/mark-schand/`.

NEPM, `Springfield To Pay $6.5 Million To Man Wrongfully Imprisoned For 27 Years`, published December 8, 2020: `https://www.nepm.org/regional-news/2020-12-08/springfield-to-pay-6-5-million-to-man-wrongfully-imprisoned-for-27-years`.

U.S. District Court for the District of Massachusetts, `Schand v. City of Springfield`, civil action No. 3:15-cv-30148-WGY, memorandum and order dated May 6, 2019, GovInfo: `https://www.govinfo.gov/content/pkg/USCOURTS-mad-3_15-cv-30148/pdf/USCOURTS-mad-3_15-cv-30148-1.pdf`.

WAMC, `Man Sues Police For Wrongful Murder Conviction`, published January 29, 2014: `https://www.wamc.org/new-england-news/2014-01-29/man-sues-police-for-wrongful-murder-conviction`.

GBH, `2 Unjust Perjury Prosecutions: Are They Revenge For Charles Wilhite Being Found Innocent Of Murder?`, published March 23, 2015: `https://www.wgbh.org/news/commentary/2015-03-23/2-unjust-perjury-prosecutions-are-they-revenge-for-charles-wilhite-being-found-innocent-of-murder`.

U.S. District Court for the District of Massachusetts, `Wilhite v. Pioggia et al.`, civil action No. 14-30023, complaint filed January 29, 2014, public PDF mirror: `https://static1.1.sqspcdn.com/static/f/634737/24293838/1391114235713/1%2B-`.

Extracted facts:

The SJC's Schand opinion records Mark Schand's first-degree-murder conviction in Hampden County and identifies the Springfield After Five Lounge shooting in which Victoria Seymour was fatally shot. Centurion reports that Hampden DA Mark Mastroianni did not oppose a new trial, that Judge C. Jeffrey Kinder granted a new trial and immediate release in October 2013, and that prosecutors dismissed the charges later that month. NEPM reports that Springfield approved a $6.5 million settlement after Schand was wrongfully incarcerated for almost three decades, and the federal civil-rights order identifies the City of Springfield and former Springfield officers as remaining defendants in the civil lane.

WAMC reports that Charles Wilhite spent three years in prison after a Springfield murder conviction, that witnesses later recanted, that a judge vacated the conviction, and that Wilhite was found not guilty at a second trial in January 2013. GBH and the Wilhite complaint identify the underlying murder victim as Alberto Rodriguez, the Pine Street Market shooting location, the Springfield Police Department detective allegations, and Judge Peter A. Velis's new-trial role. The Wilhite complaint also identifies the Hampden prosecution and court posture, but the named detective allegations remain internal until repeated-actor review supports public-board use.

Board implications:

Add Mark Schand and Charles Wilhite as small gold-ring wrongful-conviction nodes, not large victim anchors. Add Victoria Seymour and Alberto Rodriguez as underlying homicide-victim nodes, also not large anchors. Connect Schand and Wilhite narrowly to Springfield Police Department, Hampden County DA, and Hampden Superior Court. Add a narrow Wilhite-to-Judge-Peter-Velis connector because Velis is already on the board and the reviewed Wilhite sources document his new-trial role. Keep Mark Mastroianni, Judge C. Jeffrey Kinder, City of Springfield, Anthony Pioggia, Steven Tatro, the named Schand civil defendants, witnesses, counsel, and settlement actors internal for now.

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

## WEB-PINA-DISAMBIGUATION-SUFFOLK-1999-2026

Status: `ingested`, `internal hold; disambiguates Stephen Pina and Daniel Pina`.

Source titles:

Massachusetts Supreme Judicial Court, `Commonwealth v. Stephen Pina`, 430 Mass. 266, decided December 29, 1999, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/430/430mass266.html`.

Suffolk Superior Court, `Commonwealth vs. Stephen A. Pina, Memorandum and Order on Motion for New Trial`, dated February 3, 2025, hosted by Massachusetts Lawyers Weekly: `https://masslawyersweekly.com/files/2025/03/12-011-25.pdf`.

Massachusetts Lawyers Weekly, `Man granted new trial awaits justice as DA challenges murder conviction reversal`, published February 28, 2025: `https://masslawyersweekly.com/2025/02/28/exoneree-awaits-justice-as-da-challenges-murder-conviction-reversal/`.

Massachusetts Lawyers Weekly, `Cases scheduled to be heard in March`, published February 20, 2026: `https://masslawyersweekly.com/2026/02/20/cases-scheduled-to-be-heard-in-march-12/`.

National Registry of Exonerations, October 2025 newsletter, `An Exoneration without Freedom`: `https://exonerationregistry.org/sites/exonerationregistry.org/files/documents/October_2025_Newsletter_0.pdf`.

Massachusetts Parole Board, `Daniel Pina Life Sentence Decision`, Mass.gov PDF: `https://www.mass.gov/doc/daniel-pina-life-sentence-decision-2/download`.

Extracted facts:

Stephen A. Pina is the Suffolk / Mission Hill case. The 1999 SJC opinion identifies the February 26, 1993 shooting death of Keith Robinson in Mission Hill, the first-degree murder conviction, the trial judge, and trial appellate participants including ADA Rosemary Daly and ADA Robert Tochka. The 2025 Suffolk Superior Court order by Judge Peter B. Krupp allowed Pina's third motion for new trial and vacated his conviction, citing the combined force of newly available DNA evidence, undisclosed information about the Commonwealth's key eyewitness, undisclosed or newly discovered third-party-culprit evidence, and newer eyewitness-identification science. Massachusetts Lawyers Weekly reports that the Suffolk DA's office planned to pursue a gatekeeper appeal, identifies ADA Ian MacLean for the Commonwealth, and reports that Pina could still face retrial. Its 2026 SJC schedule lists `Commonwealth v. Pina`, SJC-13783, as the Commonwealth's appeal from the allowance of Pina's third new-trial motion.

Daniel Pina is a separate Suffolk / Boston cab-driver murder case. The National Registry newsletter states that Daniel Pina was sentenced to life in 2000 after pleading guilty to the 1997 murder of a Boston cab driver, and that he was exonerated in 2025 based on evidence that he had falsely confessed and that a co-defendant had falsely implicated him. The Massachusetts Parole Board decision identifies the victim as 27-year-old Domingo Mejia and records Daniel Pina's guilty plea to second-degree murder. The reviewed public sources did not yet identify a named detective, prosecutor, court ruling, nolle prosequi filing, or repeat public actor suitable for public-board treatment.

Board implications:

Do not create a generic `Pina` node. Keep Stephen Pina and Daniel Pina separate in the matrix. Stephen Pina remains internal because the reviewed sources show a vacated conviction and active appellate/retrial uncertainty rather than final exoneration or prosecution closure. Daniel Pina remains internal because the National Registry gives a strong exoneration posture, but the reviewed sources do not yet isolate the police, prosecutor, court, or repeated public actor needed for a visible graph edge. Next useful work is to refresh SJC-13783 and locate Daniel Pina's full exoneration case record or dismissal/nolle source.

## WEB-CARVER-ESSEX-BEVERLY-FIRE-2024-2026

Status: `ingested`, `internal hold; Essex appeal posture refreshed`.

Source titles:

Massachusetts Appeals Court, `Commonwealth v. James B. Carver`, 33 Mass. App. Ct. 378 (1992), Justia mirror: `https://law.justia.com/cases/massachusetts/court-of-appeals/volumes/33/33massappct378.html`.

Essex Superior Court, `Commonwealth vs. James B. Carver, Memorandum of Decision and Order on Defendant's Fifth Motion for New Trial`, No. 8877CR13527, December 23, 2024, Scribd mirror: `https://www.scribd.com/document/810273734/Karp-Ruling-James-Carver`.

GBH News, `Man who was convicted for 1984 Beverly fire gets chance for new trial`, published December 30, 2024: `https://www.wgbh.org/news/local/2024-12-30/man-who-was-convicted-for-1984-beverly-fire-gets-chance-for-new-trial`.

Boston.com, `Man convicted for 1984 Beverly fire that killed 15 granted new trial`, published December 31, 2024: `https://www.boston.com/news/local-news/2024/12/31/man-convicted-for-1984-beverly-fire-that-killed-15-granted-new-trial-da-to-appeal/`.

Boston College Law Magazine, `Thirty-five Years a Prisoner`, published February 14, 2025: `https://lawmagazine.bc.edu/2025/02/thirty-five-years-a-prisoner/`.

The Appeal / Boston Institute for Nonprofit Journalism, `James Carver Released After Wrongful Arson Conviction`, published May 14, 2025: `https://theappeal.org/james-carver-released-longform/`.

The Mass Dump, `Essex County DA Fights to Send James Carver Back to Prison in Elliott Chambers Fire Case`, published April 2, 2026: `https://massdump.ghost.io/james-carver-appeals-court-briefs/`.

Massachusetts Appeals Court Oral Arguments, `Oral Arguments, May 13, 2026, Desmond, Hand, Hodgens, JJ.`, YouTube stream listing `2025-P-0596 COMMONWEALTH vs. JAMES BENJAMIN CARVER`: `https://www.youtube.com/watch?v=XZlVJaCQ9mc`.

Mass.gov, `New opinions`, current opinions and unpublished-decision links: `https://www.mass.gov/info-details/new-opinions`.

Massachusetts Appeals Court Summary Dispositions, 128archive docket search for `25-P-0596`: `https://128archive.com/?Action=search&DocketNumber=25-P-0596`.

Massachusetts Appeals Court Summary Dispositions, 128archive party search for `Carver`: `https://128archive.com/?Action=search&PartyName=Carver`.

Extracted facts:

The 1984 Elliott Chambers rooming-house fire in Beverly killed 15 people. The 1992 Appeals Court opinion records that Carver was charged with 15 counts of second-degree murder and one count of burning a dwelling house, that the first trial ended in a mistrial because of prosecutorial misconduct, and that the second-trial convictions were affirmed. The 2024 Karp ruling mirror identifies the case as Essex Superior Court No. 8877CR13527, records Carver's fifth motion for new trial, and states that Judge Jeffrey Karp heard testimony from fire-science experts Craig Beyler and Michael Mazza and eyewitness-identification expert Nancy Franklin.

GBH, Boston.com, Boston College Law Magazine, The Appeal, and The Mass Dump all support the current posture: Judge Karp vacated the convictions and ordered a new trial in December 2024; Carver was released in February 2025; Essex DA Paul Tucker's office objected to release and appealed; and the Appeals Court argument was scheduled for May 13, 2026. The Appeal's longform account supports describing Carver as wrongfully convicted, while the Mass Dump reports the prosecution position that Karp abused his discretion and the defense position that the new fire-science evidence shows no proof that a crime occurred. The reviewed sources did not show a final Appeals Court decision, retrial decision, or nolle prosequi as of the June 10, 2026 refresh pass.

June 10, 2026 post-argument refresh: Mass.gov's new-opinions page points current unpublished Appeals Court dispositions to 128archive and listed recent published/unpublished materials through June 10. Justia's Massachusetts Appeals Court 2026 page showed recent published decisions through June 8, 2026 without a Carver entry. A 128archive docket search for `25-P-0596` returned zero dispositions. A 128archive party search for `Carver` returned three party-name hits, none of which was the 2026 Carver appeal; the relevant criminal hit was the older `Commonwealth v. Carver`, 08-P-2097, released October 16, 2009. Broad web search did not locate a final Appeals Court decision, retrial decision, or prosecution-ending filing.

Board implications:

Treat Carver as a wrongfully convicted person in the project evidence. Keep him internal for now because the Essex DA appeal/retrial posture remains live and the reviewed sources do not isolate a repeated public actor beyond this case. If the appeal resolves or the prosecution ends, consider a narrow Essex lane with Carver as a small gold-ring node, Essex DA, Essex Superior Court, Judge Karp, and any source-backed fire-investigation actor with repeated or institutional value.

## WEB-TSE-SUFFOLK-LEGAL-INSUFFICIENCY-2024

Status: `ingested`, `graph-ready; legally invalid conviction victim`.

Source titles:

Massachusetts Supreme Judicial Court, `Commonwealth v. Tse`, SJC-13344, decided November 20, 2024, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/2024/sjc-13344-0.html`.

AP News, `Massachusetts court overturns murder conviction of alleged getaway driver`, published November 2024: `https://apnews.com/article/700db5556a1ab3d7805dbeeb3a51da23`.

Extracted facts:

The SJC records that Dewane M. Tse was convicted in Suffolk Superior Court of first-degree murder and armed assault with intent to murder after the 2018 Mattapan shooting that killed Yashua Amado and injured Darrell Smith and Jerome Smith. The SJC found the evidence insufficient to prove beyond a reasonable doubt that Tse knew of or shared the unidentified shooter's lethal intent, reversed the convictions, set aside the verdicts, and remanded for entry of required findings of not guilty.

Board implications:

Add Dewane Tse as a small gold-ring victim/system-harm node tied to Suffolk DA, Suffolk Superior Court, and the Massachusetts Supreme Judicial Court. Do not make Tse a large victim anchor because the board's larger anchors remain reserved for murdered or killed people who organize a current accountability lane. Do not add Yashua Amado, Darrell Smith, Jerome Smith, the unidentified shooter, trial counsel, appellate counsel, or case-specific prosecutors without a separate source-ledger entry and a clearer board purpose.

## WEB-MICHAEL-J-SULLIVAN-MIDDLESEX-WRONGFUL-CONVICTION-2014-2024

Status: `ingested`, `graph-ready; wrongful-conviction victim`.

Source titles:

Massachusetts Supreme Judicial Court, `Commonwealth v. Michael J. Sullivan`, 410 Mass. 521, decided July 1, 1991, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/410/410mass521.html`.

Massachusetts Supreme Judicial Court, `Commonwealth v. Michael J. Sullivan`, 469 Mass. 340, decided August 15, 2014, Justia mirror: `https://law.justia.com/cases/massachusetts/supreme-court/volumes/469/469mass340.html`.

AP News, `A Massachusetts man wrongfully convicted of murder was awarded $13 million. He won't get all of it`, published November 2024: `https://apnews.com/article/wrongful-conviction-massachusetts-michael-sullivan-settlement-4456026b55892abb35120a8f1a7b9943`.

Boston.com, `Lowell man proven innocent of 1986 murder awarded $13 million, but state law caps payout at $1 million`, published November 24, 2024: `https://www.boston.com/news/local-news/2024/11/24/lowell-man-proven-innocent-of-1986-murder-awarded-13-million-but-state-law-caps-payout-at-1-million/`.

Heinlein Beeler Mingace & Heineman, P.C., `Law With Impact - HBMH Law Secures $13 Million Verdict and Jury Finding of Innocence in Wrongful Conviction Case`, published November 20, 2024: `https://www.bostoninjuryattorney-blog.com/law-with-impact-hbmh-law-secures-13-million-verdict-and-jury-finding-of-innocence-in-wrongful-conviction-case/`.

Extracted facts:

The 1991 SJC decision records Michael J. Sullivan's Middlesex County convictions for armed robbery and first-degree murder in the killing of Wilfred McGrath. The 2014 SJC decision affirmed a new-trial order after reexamination of the purple jacket: the State Police crime laboratory and a private laboratory found no blood on the cuffs, DNA on the cuffs did not come from McGrath, and the hair evidence could no longer identify McGrath as the source. The SJC held that the physical evidence from the jacket had been a real factor in the jury's deliberations because it was the only physical evidence tying Sullivan directly to the scene.

AP reported in November 2024 that a jury found Sullivan innocent of the 1986 murder and robbery and awarded $13 million, subject to the Massachusetts statutory compensation cap. AP also reported that the jury found a State Police chemist falsely testified at trial, that a new trial was ordered in 2012, that Sullivan was released in 2013, that the SJC upheld the new-trial order in 2014, and that the state decided against retrying the case in 2019. Boston.com identifies Robert Pino as the chemical analyst who asserted that blood and hair were found on Sullivan's jacket, reports that Pino was fired from the MSP crime lab in 2007, and quotes the civil complaint's fabrication allegation. The HBMH account identifies the civil case as `Michael Sullivan v. Commonwealth of Massachusetts and Robert Pino`, Suffolk Superior Court No. 1984CV01892, and states that the Middlesex DA dropped the case in 2019.

Board implications:

Add Michael J. Sullivan as a small gold-ring wrongful-conviction victim node using the distinct graph ID `mjsullivan`. Connect him narrowly to Middlesex DA, Middlesex Superior Court, and Massachusetts State Police. Add Robert Pino as a narrow exposed State Police crime-lab node connected to Massachusetts State Police, the existing State Police Crime Laboratory institution node, and Michael J. Sullivan. Do not merge Sullivan with the existing Laura Sullivan, Sgt. Michael Sullivan, Brian Sullivan, Marc Sullivan, or Karen O'Sullivan nodes. Keep Gary Grace, Emil Petrla, Steven Angier, Dana Curhan, trial prosecutors, trial judges, compensation-case counsel, and Wilfred McGrath internal unless a later pass isolates a repeated public actor, official docket record, or broader crime-lab accountability lane.

## WEB-PINO-STATE-POLICE-CRIME-LAB-2007-2024

Status: `ingested`, `graph-ready; narrow Sullivan crime-lab connector`.

Source titles:

Innocence Project, `Massachusetts DNA database chief is fired`, published April 16, 2007: `https://innocenceproject.org/news/massachusetts-dna-database-chief-is-fired/`.

SouthCoastToday / The Standard-Times, `State police DNA database chief fired`, published April 15, 2007: `https://www.southcoasttoday.com/story/news/state/2007/04/15/state-police-dna-database-chief/52920848007/`.

Boston.com / Boston Globe, `Man gets new trial in 1986 Somerville murder after DNA testing backs claim of innocence`, published November 21, 2012: `https://www.boston.com/uncategorized/noprimarytagmatch/2012/11/21/man-gets-new-trial-in-1986-somerville-murder-after-dna-testing-backs-claim-of-innocence/`.

WCVB, `Former State Police Crime Lab Administrator Tells Troubling Story`, published 2007: `https://www.wcvb.com/article/former-state-police-crime-lab-administrator-tells-troubling-story-1/8144054`.

Boston.com, `Lowell man proven innocent of 1986 murder awarded $13 million, but state law caps payout at $1 million`, published November 24, 2024: `https://www.boston.com/news/local-news/2024/11/24/lowell-man-proven-innocent-of-1986-murder-awarded-13-million-but-state-law-caps-payout-at-1-million/`.

United States District Court for the District of Massachusetts, `Pinero v. Pino et al`, Civil Action No. 11-40080-FDS, memorandum and order on motion to reconsider, April 17, 2012, Justia mirror: `https://cases.justia.com/federal/district-courts/massachusetts/madce/4%3A2011cv40080/135933/24/0.pdf`.

Extracted facts:

The Innocence Project reported in April 2007 that Robert Pino, DNA database administrator for the Massachusetts State Police crime lab, was fired three months after suspension for allegedly mishandling DNA evidence. The report says officials accused Pino of allowing collection of samples not permitted by law, reporting incomplete results to police, and reporting database matches to prosecutors after statutes of limitation had expired. It also records that Pino's union disputed the firing. The SouthCoastToday / Standard-Times article page identifies the story as Pino's firing from the State Police DNA database role, and its summary says the allegations involved evidence in about two dozen sexual-assault cases. WCVB's 2007 account similarly described Pino as a fired former State Police Crime Lab administrator while reporting Pino's position that he had not been negligent and was being made a fall guy for broader lab problems.

The Boston.com / Globe 2012 Sullivan account ties Pino directly to Michael J. Sullivan's wrongful-conviction lane: Sullivan's attorney identified Pino as the State Police chemist who testified at the 1987 trial, and the article reported that Pino had been fired in 2007 after alleged mishandling of DNA samples. The 2024 Boston.com account identifies Pino as the chemical analyst who asserted that blood and hair were found on Sullivan's jacket, reports that later testing found no blood and did not find McGrath's DNA on the jacket, and quotes the civil complaint's allegation that Pino fabricated evidence. The federal `Pinero v. Pino` order shows Pino also appeared in litigation involving a DNA-match prosecution that ended in nolle prosequi, but the federal court dismissed the civil-rights action for failure to state a claim and the dismissal source does not create a wrongful-conviction connector.

Board implications:

Add Pino as an exposed State Police crime-lab node connected narrowly to Massachusetts State Police, the existing State Police Crime Laboratory institution node, and Michael J. Sullivan. Do not create a duplicate State Police Crime Lab institution node, and do not connect Pino to Pinero, Mark Delaney, Carl Selavka, or other cases without a separate source-ledger entry. If a later pass finds another exoneration, court decision, or official audit tying Pino's lab work to a resolved wrongful-conviction lane, expand from the narrow Sullivan connector to a broader crime-lab accountability lane.

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

The review matrix consolidates recent and active Massachusetts murder-conviction review lanes into one control surface. It distinguishes final exonerations from vacated convictions, nolle prosequi filings, pending/contested retrial posture, compensation findings, and legal-insufficiency reversals. It also flags actor-level connectors when available, including John Brazil in Lucien, Judge Michael Ricciuti in Rosa/McGee, Peter O'Malley in Gaines, Judge Jeffrey Karp in Carver, the SJC's required-not-guilty disposition in Tse, and the Middlesex/State Police forensic-evidence posture in Michael J. Sullivan.

Board implications:

Do not add every matrix row to the public board. Use the matrix to decide whether a future graph change has a repeated public actor, a source-backed institution, and a stable legal posture. James Lucien has moved from candidate to visible small-node treatment through `WEB-LUCIEN-BRAZIL-SUFFOLK-BPD-2021-2024`, the Ricciuti/Rosa/McGee lane has moved from candidate review to visible narrow court-actor treatment through `WEB-RICCIUTI-ROSA-MCGEE-SUFFOLK-WRONGFUL-CONVICTION-2023-2026`, the Milton Jones / Floyd Hamilton / Joseph Pope lanes have moved to visible small-node treatment through `WEB-OMALLEY-SUFFOLK-WRONGFUL-CONVICTION-CLUSTER-2022-2026`, the Edward Wright lane has moved to visible narrow Hampden/Springfield treatment through `WEB-WRIGHT-HAMPDEN-SPRINGFIELD-WRONGFUL-CONVICTION-2025`, and the Michael J. Sullivan lane has moved to visible narrow Middlesex/State Police/Pino treatment through `WEB-MICHAEL-J-SULLIVAN-MIDDLESEX-WRONGFUL-CONVICTION-2014-2024` and `WEB-PINO-STATE-POLICE-CRIME-LAB-2007-2024`. The Stephen Pina and Daniel Pina lanes have been disambiguated through `WEB-PINA-DISAMBIGUATION-SUFFOLK-1999-2026`, but both remain internal holds. Future additions still need separate source-ledger entries before visible graph changes.

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

This supports Root graph connectors for Fanning, Bukhenik, Guarino, Broderick, Elcock, and Wagner. It supports a Fanning-to-Broderick communication connector and Bukhenik-to-Elcock / Bukhenik-to-Wagner case-handling connectors because the message names Broderick as the recipient and identifies Bukhenik as having done the Brookline PD interviews for Elcock and Wagner. It is not a misconduct source by itself. The Guarino/Brookline interview reference remains a source note until a reviewed transcript or named-subject record supports a narrower public connector. The `Tpr. Bukhenik Email Correspondence_redacted.pdf` file has since been ingested as `ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020`; the `8 BULLETS 02-06-20 FANNING Email from Public Records Request Norfolk DA.pdf` item remains a retrieval target for any stronger Fanning-specific public-record claim.

## ROOT-BUKHENIK-CRAWFORD-FANNING-EMAIL-2020

Status: `ingested`, `graph-ready for Root/Brookline digital-evidence communication connectors`.

Source title: `Tpr. Bukhenik Email Correspondence_redacted.pdf`.

Google Drive URL: `https://drive.google.com/file/d/12eWjzGVhlkpLgr2Y03QlQo4J7hmva5K5/view`.

Drive ID from connector fetch: `12eWjzGVhlkpLgr2Y03QlQo4J7hmva5K5`.

Reviewed local copy: `/Users/jonathanbowen/Downloads/Tpr. Bukhenik Email Correspondence_redacted.pdf`.

Extracted facts:

The correspondence includes a February 12, 2020 email from Norfolk DA Multimedia Director and Certified Forensic Video Technician Coleen Crawford to Trooper Yuriy Bukhenik, with Sergeant John Fanning copied. The subject identifies the Gill video interview and the Brookline shooting date. Crawford states that she converted and archived the Gill video-interview file and made it available from a digital case folder named for Fanning and the Brookline shooting. The same correspondence packet also shows Fanning and Bukhenik coordinating audio, transcripts, reports, and Brookline Police Department interviews in the Juston Root investigation, and it includes a February 18, 2020 Brookline Lethal Force message asking recipients to prioritize outstanding reports because the DA was preparing a media report.

Board implications:

This directly supports the existing Crawford-to-Root case connector, the existing Fanning-to-Crawford professional connector, and the Crawford-to-Bukhenik communication connector. It also strengthens the Fanning-to-Bukhenik Root correspondence lane and supports the Fanning-to-Broderick communication connector plus the Bukhenik-to-Elcock and Bukhenik-to-Wagner interview-handling connectors represented on the board. Use this source only for digital-evidence handling, correspondence, report/transcript coordination, and case-role overlap; it does not establish misconduct by itself.

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
