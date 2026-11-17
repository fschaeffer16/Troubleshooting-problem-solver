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

- The link's address contains the words: tech outages, microsoft, banks, faa, fbi, 11-17-26. VERIFIED (read from the link itself). This says what the page is about. It does not confirm that anything happened.
- The CNN link's address contains the words: politics, highly classified national security communications network goes down, 2026/11/17. VERIFIED (read from the link itself). It does not confirm that anything happened.
- Whether the two links describe the same event: NOT CHECKED.

Search summaries, 2026-11-17. All EXCERPT. No source page was opened. News outlets are not sources under the rules; they are listed only to show where a claim was seen.

- Microsoft: Outlook and Teams disruption, about Nov 12 to 14. Incident number MO1550821. Stated cause: a problem during a network capacity upgrade. Seen in: learn.microsoft.com community threads (not a source), news reports. Microsoft's own statement: not opened.
- FAA: nationwide ground stop Nov 13. Air traffic resumed 8:15 p.m. that day. About 12,462 flights canceled. FAA says no indication of a cyberattack or outside actor. Seen in: search summary of https://www.faa.gov/newsroom/faa-statement-nationwide-ground-stop
- FAA cause reported as a faulty router installed the week before, router installs paused, 17 of 22 en route centers affected. Seen in: news reports only.
- DHS release dated Nov 13 on a White House briefing about the ground stop: https://www.dhs.gov/news/2026/11/13/icymi-secretary-mullin-and-secretary-duffy-address-nationwide-faa-ground-stop-all
- FBI cyber staff reported to be helping the FAA investigation. Seen in: news reports only.
- Banks: Chase, Bank of America, Wells Fargo and Zelle login problems reported Monday Nov 16. One report cites an FBI official saying a JPMorgan Chase software release was the cause. Another says Bank of America stated its systems were normal. Seen in: news reports only.
- Classified network: one outlet names it as an NSA internal network. CNN headline says a highly classified national security communications network went down. Seen in: news reports only.
- Officials, including the DHS Secretary, are reported as saying there is no cyber threat and no evidence the incidents are connected. Seen in: news reports only.
- No official statement dated Nov 17 was found by a search limited to faa.gov, fbi.gov, cisa.gov, microsoft.com, defense.gov, federalreserve.gov, dhs.gov and whitehouse.gov. NOT FOUND.

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

Not ranked. No cause has evidence that was opened and read.

1. Separate causes, as officials are reported to say. For: each has its own reported cause (Microsoft upgrade, FAA router, Chase release). Against: none read at the source yet. Test: read each organization's own incident statement and compare cause, timing and equipment.
2. A shared technical cause, such as a common vendor, network carrier or equipment. For: none yet. Against: none yet. Test: identify the vendor and carrier behind each failure from the organizations' own reports.
3. A deliberate attack. For: none yet. Against: FAA statement, per search summary, says no indication of one. Test: CISA, FBI and FAA statements, and any later incident report or inspector general review.
4. Some incidents linked, others not. Test: same as 1 and 2, pair by pair.
5. Ordinary outages getting more notice because of the big ones. ASSUMPTION, reasoning only. Test: compare the count of outages in this week with the organizations' own incident histories for normal weeks.

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

## Options

None yet.

## Frank's choice

None yet.
