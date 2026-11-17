# Tech outages reported 2026-11-17

## The problem

Opened 2026-11-17. Frank's words: "We are being lied to on this and I want you to help me figure out what's going on."

Evidence handed over: https://www.foxnews.com/live-news/tech-outages-microsoft-banks-faa-fbi-11-17-26

Second link handed over 2026-11-17: https://www.cnn.com/2026/11/17/politics/highly-classified-national-security-communications-network-goes-down?cid=ios_app

## Open gaps

- Answered 2026-11-17. Frank's words: "I don't believe all these outages are a coincidence"
- The question to settle: do the outages share a cause, or are they separate.
- The article has not been read. See blocked sites.

## Facts

Pages opened and read on 2026-11-17 18:27 UTC. Earlier search summaries are replaced by this section.

### FAA, from the FAA's own page. VERIFIED

Source: https://www.faa.gov/newsroom/nationwide-ground-stop-questions-and-answers, dated Sunday, November 15, 2026. Copy saved in problems/evidence/tech-outages-faa-ground-stop-qa.txt.

- Nov 13, about 3:30 p.m. ET: a technical problem led to a nationwide ground stop. Air traffic resumed 8:15 p.m.
- Stated mechanism: data flooded the FAA FTI network at 1,000 connection attempts every 4 to 5 seconds. Legacy equipment became unstable. Radio and radar feeds were disrupted.
- Two possible origins named: a radar site in Amarillo, Texas, and a radio site in El Dorado, Arkansas.
- L3Harris, the FAA's network service provider, had been working at El Dorado, "including deployment of a new router."
- L3Harris blocked the two sites and the network stabilized.
- The routers are Juniper. The same function was disabled on more than 60 other Juniper routers. Installs are paused.
- 17 of 22 Air Route Traffic Control Centers had instability.
- About 12,462 flights canceled Nov 13, 9,082 by major airlines. About 3,500 aircraft were in the air and landed safely.
- On cyberattack: "Based on all available evidence, we have no indication that this was a cyberattack or an outside nefarious actor."
- Root cause: "The FAA and L3Harris continue to investigate the root cause."
- The router work was done in the middle of the day. The FAA says it will reevaluate timing.
- A tension inside the page: asked "Did your upgrades and modernization efforts cause this?" the FAA answers "No, this is due to the legacy TDM system causing instabilities." The same page says a new router was being deployed at one of the two suspect sites and that the fix was to disable a function on the new routers.

### NSA, from news reports. Read, but not confirmed by the NSA on the record

- CNN, published Nov 17, 10:31 AM ET, updated 12:59 PM ET: NSANet, the NSA's classified internal network, "is down, according to six people familiar with the matter." Staggered arrivals for staff. CNN asked the NSA for comment. No NSA reply is in the article.
- CNN: White House spokesperson Lauren Bis, on Newsmax: "We see no evidence that this was a cyberattack."
- Fox News live page: "a U.S. official" said systems had "temporary degradation during scheduled routine maintenance." A Capitol Hill source said "this is just routine patching of systems."
- Fox: because it is not believed to be a cyberattack, DHS and other cyber agencies "are not involved."
- An NSA statement on the record: NOT FOUND in either page.

### Microsoft. Not read at the source

- Fox: "Microsoft attributed its major outage last week to a networking bug dating back to July, ruling out AI run amok or cyberattacks."
- Microsoft's own account: NOT CHECKED. https://status.cloud.microsoft/ downloads as an empty shell that needs a browser to fill in.

### Banks and others, from the Fox live page

- JPMorgan Chase: "systems were down for hours on Monday." Cause not stated on the page.
- Charles Schwab, company statement to Fox: a "brief webpage loading issue" on Tuesday, resolved. Trading stayed available.
- Marriott, Apple iCloud, Gmail: based on user reports to Downdetector. No company confirmation. Fox notes Google's own status dashboard "has not listed any active disruptions."
- A scheduled nationwide Emergency Alert System test by FEMA and the FCC was set for Nov 17 at 2:20 p.m. ET.

### Second round, pages read 2026-11-17 18:35 UTC

- L3Harris, own statement dated Nov 14, 2026. VERIFIED. Copy saved in problems/evidence/tech-outages-l3harris-statement.txt. It says L3Harris "has been modernizing the communications infrastructure supporting the National Airspace System in close coordination with the FAA" and has completed "more than 70% of the planned airspace communications conversion from legacy copper wires to a fiber optic system." It says it is "supporting the FAA in its investigation." It does not mention the router and does not state a cause.
- This bears on the FAA's answer that its "upgrades and modernization efforts" did not cause the failure. The contractor describes its own work on that network as modernizing.
- Apple, own system status data. VERIFIED. Source: https://www.apple.com/support/systemstatus/. Ongoing since Nov 17, 08:45 PST: App Store (outage), Apple Music (outage), iCloud Account and Sign In (issue, "All users are affected"). AppleCare on Device: outage since 08:15 PST. No cause given. Correction: the Apple reports are confirmed by Apple, not only by Downdetector.
- Google, own Workspace status data. VERIFIED. Source: https://www.google.com/appsstatus/dashboard/incidents.json. 31 incidents listed. The most recent began 2026-09-25. No Gmail incident is listed for November. The Gmail reports remain unconfirmed by Google.
- House Homeland Security Committee, own site. VERIFIED. Hearing "Worldwide Threats to the Homeland: 25 Years After 9/11", Wednesday, November 18, 2026, 10:00 AM ET, 310 Cannon House Office Building.
- www.nsa.gov press page: refused the download (403). NSA statement on the record: NOT CHECKED.
- www.jpmorganchase.com newsroom: refused the download (403). Chase's stated cause: NOT CHECKED.

### What officials say about a link, from the Fox live page

- DHS Secretary Mullin, on Fox: suggested AI could be partly to blame, a "ripple effect." Also said there is "no cyber threat that's taking place."
- Fox: Transportation Secretary Duffy and FAA Administrator Bedford "have both said AI was not a factor" in the FAA failure.
- So officials do not agree with each other on AI as a factor.
- House Homeland Security Committee "Worldwide Threats" hearing: Wednesday, 10 a.m. ET.

### Not found in any page read

- Any evidence, shown or cited, of a cause shared between two incidents.
- Any evidence shown for the "no cyberattack" statements. They are stated, not demonstrated.

## Blocked sites

- https://www.foxnews.com/live-news/tech-outages-microsoft-banks-faa-fbi-11-17-26
  - Why: blocked by the environment's network settings. www.foxnews.com is not on the allowed list (checked 2026-11-17: 126 entries, 125 unique, environment "Default", limited access).
  - Needed: the full text of every update, with times, named organizations, quoted statements and stated causes.
  - Use: build the list of claims, then check each against the named organization's own statement.

- https://www.cnn.com/2026/11/17/politics/highly-classified-national-security-communications-network-goes-down?cid=ios_app
  - Why: blocked by the environment's network settings. www.cnn.com is not on the allowed list (checked against the list read 2026-11-17). No fetch attempted.
  - Needed: the full text. Which network, who confirmed it, when it went down, the stated cause, and who is quoted.
  - Use: add its claims to the list and check each against the named agency's own statement.

- Official pages needed, none on the allowed list: www.faa.gov, www.dhs.gov, status.cloud.microsoft, www.fbi.gov, www.cisa.gov. Approved by Frank 2026-11-17 ("Go"). Added by Frank 2026-11-17 and confirmed on the stored list. The running session still cannot open them.

## Causes considered

Ranked by the evidence read so far. None is proven.

1. Separate failures that share a type of trigger: a change made to a live system. Evidence for: FAA page ties its failure to a new router install (VERIFIED). An unnamed official ties the NSA problem to scheduled maintenance (news report). Fox says Microsoft blamed a networking bug (news report). Evidence against: only one of these is confirmed at the source. Test: Microsoft's own incident report, an NSA statement, a JPMorgan Chase statement.
2. Ordinary glitches counted as part of a wave. Evidence for: Marriott and Gmail rest on Downdetector user reports; Google's dashboard showed no disruption; Schwab described a brief page loading issue. Evidence against: Apple confirms its own outage on Nov 17 (VERIFIED), so iCloud is not in this group. Not tested against a normal week. Test: Apple and Google status pages, and how often such reports occur in a normal week.
3. A shared technical cause, such as common equipment or a common vendor. Evidence for: none found. One lead: the FAA names Juniper routers and L3Harris. Whether either is involved in any other incident: NOT CHECKED. Test: vendor and equipment for each incident.
4. A deliberate attack. Evidence for: none found. Evidence against: statements only, from the FAA, the White House and DHS, with no evidence shown. Test: CISA and FBI statements, the FAA and L3Harris root cause report, the Nov 18 House hearing.
5. AI-written code changes causing failures, as Secretary Mullin suggested. Evidence for: his statement only. Evidence against: Duffy and Bedford are reported to say AI was not a factor at the FAA; Fox says Microsoft ruled it out. Test: the same incident reports.

## Tests run

- 2026-11-17: tried to open the article. Failed, host not allowed.
- 2026-11-17: read the environment's network settings. Limited access, foxnews.com not listed.

- 2026-11-17: two web searches. Results recorded under Facts as EXCERPT.

- 2026-11-17: Frank said "Go" on the five official sites. The thread's request to add them was rejected by the environments service. No reason given. Nothing changed.
- 2026-11-17: second read of the allowed list. Nine entries added since the first read, not by the thread: www.pewresearch.org, www.axios.com, www.reddit.com, www.tmz.com, ground.news, ap.org, www.reuters.com, foxnews.com, cnn.com. List now 135 entries.
- 2026-11-17: fetch tests after that.
  - www.fda.gov: opened. Control, shows the fetch tool works.
  - www.foxnews.com, www.cnn.com: failed, host not allowed. The list holds foxnews.com and cnn.com without "www".
  - foxnews.com, cnn.com (no "www"): failed with the same host-not-found error, though both are on the list. Cause not checked.
  - www.reuters.com, ap.org: failed with a different error, "unable to fetch from" the site. Cause not checked.
  - A direct connection test from the shell was denied by the session's permission system. Not run.

- 2026-11-17: Frank said the seven sites "are in". Settings read: all seven are on the stored list, 142 entries.
- 2026-11-17: fetch tests after that, twice, several minutes apart. www.foxnews.com, www.cnn.com, www.faa.gov, www.dhs.gov and status.cloud.microsoft all failed with the same host-not-found error as before.
- 2026-11-17: the thread re-sent the seven sites through its own settings tool. Reply: already allowed, nothing to change. Fetches still failed after it.
- Pattern seen: every site on the list when the session started opens (www.fda.gov tested). Every site added in the settings after the session started does not. Whether a new session would open them: NOT CHECKED.

- 2026-11-17, correction: during a check of the whole allowed list, home page requests from the session's shell reached www.foxnews.com, www.cnn.com, www.faa.gov and status.cloud.microsoft (code 200). www.dhs.gov, www.fbi.gov and www.cisa.gov answered 403, refused. So the new sites are allowed in this session. Only the page-reading tool fails on them. The earlier pattern note is wrong on that point.
- 2026-11-17: an attempt to download the article pages from the shell was denied by the session's permission system. Not run. Frank to decide.

- 2026-11-17: Frank gave his OK for shell downloads. Downloaded and read: the FAA Q&A, the CNN article, the Fox live page. www.dhs.gov refused the download (403). status.cloud.microsoft returned a page with no content.

- 2026-11-17 18:35 UTC: second round of shell downloads after Frank added six sites. Read: L3Harris statement, Apple status data, Google status data, House committee site. Refused (403): www.nsa.gov, www.jpmorganchase.com.

## Options

None yet.

## Frank's choice

None yet.
