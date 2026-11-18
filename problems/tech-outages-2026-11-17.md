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

### DHS release of Nov 13, text supplied by Frank

Source: the DHS page, pasted by Frank 2026-11-17. The thread did not open the page. Its title and date match the search result seen earlier. Copy saved in problems/evidence/tech-outages-dhs-release-2026-11-13.txt.

- Timing: the briefing was Friday evening, Nov 13, while the ground stop was in effect or just lifted.
- Mullin: "We have seen zero evidence that this is a cyberattack or an SI attack." Said the same evening. The FAA's page two days later says the root cause is still under investigation.
- Mullin on the cause: "our air traffic control system is outdated and it hasn't been a priority from Congress." The release does not mention the new router or the contractor's work.
- Mullin: "The President has declared this a national emergency, and now we have to have Congress act and fund it."
- Mullin: "We have all of our assets, be it from DOW, to CISA, to all of our NOCs ... NSA is working with us."
- A formal emergency proclamation: NOT FOUND in one web search. News reports differ on who declared it. No proclamation number or text seen. EXCERPT only. The White House site and the Federal Register have not been read.
- News reports, search summary only: Mullin and Duffy asked Congress for US$50 billion for the air traffic control system; the President asked Congress for funding on Nov 15. EXCERPT.

Observations, reasoning only:

- "Zero evidence" on the first evening means none had been found by then. It is not a finding that an attack was ruled out.
- The release blames age and funding. The FAA's own page says the trigger was a new router being installed. Both can be true: an old network that could not absorb a fault from new equipment. The release gives only one half.
- On Nov 13 Mullin said zero evidence of an "SI attack." On Nov 16 he suggested AI could be partly to blame through a "ripple effect" (Fox). Those are different claims, attack versus accident, but his account moved.
- On Nov 13 the NSA was "working with us" on the FAA event. On Nov 17 the NSA's own network was reported down, and Fox reports DHS is "not involved" in that. No evidence connects the two. Noted as a question, not a finding.

### Frank's framing, 2026-11-17, and the first base rate check

Frank's words: "Either these are normal and never reported or it is an awlful lot of coincidences"

Frank also reported two items the thread has not verified: Apple now says its iCloud issue was caused by an internal update, and the National Weather Service says a 40-minute website outage today was caused by routine maintenance. Both: NOT CHECKED at the source.

Checks run 2026-11-17 20:22 UTC:

- Google, own Workspace incident list (https://www.google.com/appsstatus/dashboard/incidents.json). VERIFIED. 31 incidents listed, the first beginning 2025-11-24 and the last 2026-09-25. By month: Nov 2025 2, Dec 1, Jan 2026 3, Feb 2, Mar 2, Apr 5, May 6, Jun 3, Jul 0, Aug 3, Sep 4. None listed for October or November 2026.
- So one large provider lists about 31 incidents in about 12 months for one product family. That is one data point for "normal and rarely reported." It covers one company only.
- Apple, own status data, second read. VERIFIED. Nov 17: iCloud Account and Sign In issue, "All users are affected", ongoing. iCloud Mail and iCloud.com affected. App Store outage 08:45 to 12:00 PST, resolved. Apple Business, Apple School Manager and Schoolwork issues from 10:40 PST. The status data gives no cause. The words "internal update" are NOT FOUND there.
- Apple, Nov 16: Volume Purchase Program outage, 10:06 to 11:23 PST, with the note "We performed routine maintenance."

Reasoning, ASSUMPTION until tested:

- The two options are not the only ones. A third: one rare event (a nationwide ground stop) drew attention, and common events that would normally go unreported were then gathered into one story. A fourth: the failures are separate but share a type of trigger, a change made to a live system.
- Every stated cause so far is a change: router install (FAA, VERIFIED), scheduled maintenance (NSA, unnamed official), networking bug (Microsoft, per Fox), internal update (Apple, per Frank), routine maintenance (NWS, per Frank), software release (Chase, one news report).
- Test for "normal": incident histories from each organization's own status pages for the past 12 months, counted per week, compared with this week.
- Test for "shared trigger type": whether changes are the usual cause of outages in general, from an industry body's outage data, and whether mid-November is a heavy period for changes before holiday freezes.

### Third round, pages read 2026-11-17 20:24 UTC

- White House, Presidential Actions page (https://www.whitehouse.gov/presidential-actions/). VERIFIED. Entries dated Nov 12 and Nov 16 are nominations only. Nothing dated Nov 13, 14 or 15. No proclamation or order about a national emergency, air traffic control or the ground stop is listed. NOT FOUND on that page. Not checked: the Federal Register, and whether the page lags behind signing.
- Amazon Web Services, own public event list (https://health.aws.amazon.com/public/events). VERIFIED. 11 events listed. Dates of start, UTC: Mar 1 and Mar 2 (Middle East regions, still open), Aug 19, Aug 21, Sep 3, Sep 21, Oct 4, Oct 30, Nov 6, Nov 11, Nov 15.
- AWS, Nov 15: "signup errors, authentication issues, and connectivity issues in the US-EAST-1 Region" from 3:05 AM to 6:10 AM PST, with some load balancers affected until 6:21 AM. No root cause given. This incident falls inside the cluster window and was not in the news pages read.
- AWS, Nov 11 to 12: API errors and launch failures in the Tokyo region, about 6 hours. AWS, Nov 6: launch failures in US-WEST-2, under 2 hours, cause given as "a subsystem that supports EBS Volumes."
- AWS count by month from that list: Aug 2, Sep 2, Oct 2, Nov 3 in the first 15 days. How far back the list reaches: not checked.
- Microsoft Azure, own status history (https://azure.status.microsoft/en-us/status/history/). VERIFIED. The page as downloaded shows two post incident reviews, both September 2026. Nothing for November. Microsoft's Outlook and Teams outage is a Microsoft 365 matter and is not on this page. Microsoft's own account of it: still NOT CHECKED.
- National Weather Service, home page and news page. A statement on a website outage: NOT FOUND on either.
- Uptime Institute: refused the download (403). Industry data on outage causes: NOT CHECKED.

Frank, 2026-11-17, on the bank outages: "It was more than Chase Bank"

- Seen so far: an earlier search summary named Chase, Bank of America, Wells Fargo and Zelle user reports on Monday, and said Bank of America stated its systems were normal. EXCERPT. The Fox page names Chase and Schwab. Which banks had confirmed outages, from the banks themselves: NOT CHECKED.

### Fourth round, 2026-11-18 02:33 UTC: CNN article re-read, CISA catalog read

Frank sent the CNN link again. The article had changed since the first read. First read: updated Nov 17, 12:59 PM ET. Now: updated Nov 17, 7:14 PM ET.

New in the CNN article (news report; the quotes are on the record but were read through CNN, not at the agencies):

- NSA statement, Tuesday afternoon: "The National Security Agency experienced temporary degradation during scheduled routine maintenance." It says mission-critical capabilities remain operational.
- Director of National Intelligence Jay Clayton, on Fox Business: the NSA outage was the result of applying a software patch for major vulnerabilities discovered last month. "The patching that has gone on following that has caused some of these systems to not come back up when you patch them as expected."
- CNN: the vulnerabilities are in PHP. "AI tools helped researchers exploit them, setting off a scramble by government agencies and corporations around the world to address the issue in recent weeks. The NSA itself urged organizations to apply software patches."
- Clayton: no sign that any of the recent outages were the result of a cyberattack.
- A source told CNN restoration "was ongoing but not yet complete." The staff voicemail went from "code yellow" Tuesday morning to "code green" Tuesday evening.
- The NSA's "scheduled routine maintenance" and the DNI's account, urgent patching that broke systems, describe the same event differently.

CISA Known Exploited Vulnerabilities catalog. VERIFIED. Source: https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json, catalog version 2026.11.17, 1,782 entries.

- CVE-2026-109618, "PHP Memory Corruption Vulnerability", and CVE-2026-109619, "PHP Stale Internal Request-State Vulnerability". Both: "allows for unauthenticated remote code execution." Both added 2026-10-26, due 2026-10-29.
- The entries note PHP is a component "that could be used by different products."
- They link a CISA alert dated 2026-10-21 titled, from its address, "critical vulnerabilities php require immediate patching". That page refused the download (403). Not read.
- Being in this catalog means CISA has evidence the flaw is being exploited. That is not evidence that any outage in this problem was an attack.
- The three-day deadline is not unusual this year. Of 298 entries added in 2026, 159 have a three-day deadline. Median: 3 days.
- Entries added per month: May 21, Jun 23, Jul 26, Aug 31, Sep 43, Oct 36, Nov 16 through the 17th.
- Entries added in the three weeks before the outages include PHP (Oct 26), Linux Kernel (Oct 28), Cisco firewall software (Oct 29), WordPress Core (Nov 3), OpenSSH (Nov 9), Check Point (Nov 13).

What this means, reasoning only:

- There is now a candidate shared cause that is not an attack and not pure coincidence: many organizations patching the same widely used software, urgently, in the same weeks, and some patches breaking systems.
- It is on the record for the NSA only. No source ties the PHP patching to Apple, the banks, Microsoft, the Weather Service or the FAA. The FAA's stated cause, a router install, is a different kind of change.
- Secretary Mullin's "no cyber threat that's taking place" sits badly beside his own department's catalog, which lists actively exploited flaws that required patching within days. Both statements can be squared only if he meant that the outages themselves were not attacks.
- His "ripple effect" remark about AI and self-fixing code may be a loose version of this: AI-assisted discovery of flaws, then rushed patches, then breakage. Not confirmed.

### Fifth round, 2026-11-18 02:42 UTC: PHP project and SEC

PHP project, own news archive (https://www.php.net/archive/2026.php). VERIFIED. Copy saved in problems/evidence/tech-outages-php-advisory-2026-10-21.txt.

- 20 Oct 2026: advance notice of a security release for "two critical vulnerabilities, both rated CVSS v4.0 9.2."
- 21 Oct 2026: "Security advisory: Critical remote code execution vulnerabilities, update now." Fixed in PHP 8.5.12, 8.4.27, 8.3.36 and 8.2.35. CVE-2026-109618 and CVE-2026-109619, the same two numbers as in the CISA catalog.
- "Who is at risk: all PHP installations serving web requests." It describes "a demonstrated exploit where an unauthenticated request can trigger the attack before any application code runs."
- Older versions 7.4, 8.0 and 8.1 got source backports "given the severity."
- The stopgap measures require settings changes and "restart every worker."
- The advisory does not mention AI.

Timing, from the verified dates:

- Fix released Oct 21. CISA catalog entry Oct 26, federal deadline Oct 29. Microsoft outage about Nov 12 to 14. FAA Nov 13. AWS Nov 15. Banks Nov 16. NSA and Apple Nov 17.
- So the outages came three to four weeks after the fix was out, not in the days right after. That weakens explanation 1 for systems that patch quickly. It still fits slow-to-patch systems, such as a classified network, and the DNI says the NSA was patching on Nov 17.

SEC. NOT CHECKED.

- www.sec.gov answered with a page titled "Your Request Originates from an Undeclared Automated Tool" (403). The SEC wants automated tools to declare who they are. The thread did not supply an identity and did not retry.
- Company filings on cyber incidents since Nov 12: not read. The SEC reporting rule itself: not read.
- Frank, 2026-11-18: "Skip the SEC test for now". The test stays on the list, parked.

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

Ranked by the evidence read through 2026-11-18 02:33 UTC. None is proven as the explanation for the whole cluster.

1. A shared upstream trigger: a wave of urgent security patching, set off by the PHP flaws of October 2026, breaking systems at separate organizations. Evidence for: DNI Clayton on the record for the NSA (via CNN). CISA catalog confirms the flaws, the dates and the urgency (VERIFIED). Stated causes elsewhere are also changes: Apple "internal update" and Weather Service "routine maintenance" (Frank's reports, not checked), Chase "software release" (one news report). Evidence against: no source ties any incident other than the NSA's to this patching. Test: each organization's own cause statement; whether the affected systems run PHP; the CISA alert of Oct 21; the Nov 18 House hearing.
2. Separate failures that share only a type of trigger, a change to a live system, with no common upstream cause. Evidence for: FAA router install (VERIFIED), a different kind of change. Microsoft "networking bug dating back to July" (via Fox). Test: Microsoft's own incident report; FAA and L3Harris root cause report.
3. Normal background outages, noticed because of one rare event. Evidence for: Google lists 31 incidents in 12 months; AWS had a Nov 15 outage that drew no coverage in the pages read. Evidence against: Apple's Nov 17 outage affected "All users"; AWS November pace slightly above recent months. Test: 12-month histories for more organizations.
4. Shared equipment or vendor. Evidence for: none found. Leads: Juniper routers and L3Harris at the FAA. Test: vendor and equipment for each incident.
5. A deliberate attack causing the outages. Evidence for: none found. The PHP flaws are being exploited somewhere, per CISA, but no source says an outage here was an intrusion. Evidence against: statements from the FAA, the White House, DHS and the DNI, with no evidence shown. Test: CISA and FBI statements, root cause reports, the House hearing.
6. AI-written code changes, as Secretary Mullin suggested. Evidence for: his statement only. Possibly a loose account of explanation 1. Test: the same incident reports.

Explanations 1, 2 and 3 can all be partly true at once. The FAA fits 2. The NSA fits 1. The small ones fit 3.

### Frank's question, 2026-11-18

Frank's words: "If you were doing a test to precede a major cyber attack would you announce it or make it look like a bunch of unrelated coincidences?"

The point stands: an attacker would hide it, so official denials and the look of coincidence do not rule out explanation 5. Real coincidences look the same, so the look alone does not support it either. What separates the two is evidence a hidden test would leave and an accident would not. Tests added:

- SEC filings. Public companies must report material cybersecurity incidents to the SEC. Check JPMorgan Chase, Apple, Microsoft, Amazon and L3Harris filings since Nov 12. The rule and its deadline are from memory, to be confirmed at sec.gov. ASSUMPTION until read.
- Technical root cause reports from the FAA and L3Harris, Microsoft and Amazon. Detail that outside engineers can check is hard to fake.
- Whether the new Juniper routers at the FAA misbehaved by design, by fault, or by tampering. The FAA disabled a function on more than 60 of them.
- CISA or FBI advisories that carry technical signs of intrusion tied to these dates.
- Sworn testimony at the Nov 18 House hearing.
- Start times. A staged test would more likely show failures clustering in time or following one actor's pattern. Patch breakage follows each organization's own patch schedule.

### Two more explanations from Frank, 2026-11-18

Frank's words: "It could be a distraction tactic to hide something else." and "It could be them planting things in systems that have connections they are finding in each network"

Added to the list as explanations 7 and 8. Who "them" is: not stated, asked.

7. A distraction, to hide something else. Evidence for: none found. Evidence against: none found. What it predicts: something else of consequence happening Nov 12 to 18 that drew less notice. Test: needs a target. Without a guess at what is being hidden, the search has no end. Asked Frank.
8. Intruders planting access in connected networks, with the outages as a side effect or as cover. Evidence for: the PHP flaws allow outsiders to run code and are being exploited (CISA, VERIFIED). Patching periods give cover. The FAA describes its failure as a flood of connection attempts, 1,000 every 4 to 5 seconds, which it attributes to a function on the new routers; the root cause is not final. Evidence against: planting access works best unnoticed, and outages draw attention. No source reports an intrusion. Test: the CISA "Forensics Triage Requirements" tied to the PHP entries, which tell agencies to look for signs of intrusion, and whatever comes of them; SEC filings; the FAA and L3Harris root cause report on the routers; CISA and FBI advisories.

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

- 2026-11-17: Frank pasted the DHS release text. One web search for a formal national emergency proclamation: none found.

- 2026-11-17 20:22 UTC: counted Google's own incident list by month and re-read Apple's status data. Results under Facts.

- 2026-11-17 20:24 UTC: third round of shell downloads after Frank added five sites. Read: White House actions page, AWS event list, Azure status history, Weather Service home and news pages. Refused (403): uptimeinstitute.com.

- 2026-11-18 02:33 UTC: re-downloaded the CNN article (changed since first read). Read CISA's Known Exploited Vulnerabilities catalog. The CISA alert page of 2026-10-21 refused the download (403).

- 2026-11-18 02:42 UTC: read the PHP project's news archive and change log. www.sec.gov refused the request as an undeclared automated tool.

## Options

None yet.

## Frank's choice

None yet.
