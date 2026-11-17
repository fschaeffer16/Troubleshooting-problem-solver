# Handoff

## What this thread is and where everything lives

A problem solver for Frank. The rules are in CLAUDE.md. Read it first.

- problems/: one file per problem.
- TRACKER.md: every problem and its status.
- SESSIONS.md: a dated review of every session.
- DECISIONS.md: Frank's rulings, dated, in his words.
- LEARNINGS.md: mistakes made and the lesson.
- allowed-sites.md: the master list of allowed sites for the "Default" environment, sorted, with baseline and swap sites and a swap log. Keep it current after every change.

## Problems in progress

- Tech outages reported 2026-11-17 (problems/tech-outages-2026-11-17.md). Blocked. The Fox News and CNN articles Frank gave could not be opened. Frank's position: "I don't believe all these outages are a coincidence". Search summaries only so far, nothing opened and read. Five official sites approved by Frank but not added: the environments service rejected the thread's request. See the problem file, Tests run.

## Standing rulings

See DECISIONS.md.

- 2026-11-17, pushing: "You can push without me. You cannot push solutions or builds of fixes or solutions without me"
- 2026-11-17, Reddit and TMZ: "You can use Reddit and TMZ you just have to face check them"
- 2026-11-17, site requests: "When you want sites added give them to me in code formatting"
- 2026-11-17, news sites: "My sites were an attempt to give you access to news. You can research reliable tech news sites, science news sites, health news study sites, geopolitical sites, whatever you need for information."
- 2026-11-17, spin and conspiracy theories: "You are here to dig into problems, eliminate political spin and conspiracy theories... now notice I did not say to ignore spin or conspiracy theories. They need to sometimes be tested before discounted to see if maybe they were born from a small slice of truth that we need to pull and research more."

## Blocked

- Tech outages problem: the needed sites are on the allowed list. On 2026-11-17 the page-reading tool (WebFetch) could not open them, but shell requests reached www.foxnews.com, www.cnn.com, www.faa.gov and status.cloud.microsoft. www.dhs.gov, www.fbi.gov and www.cisa.gov refused the shell request (403). Downloading the article pages from the shell was denied by the permission system. A new session should try the page-reading tool first on https://www.faa.gov/newsroom/faa-statement-nationwide-ground-stop.
- allowed-sites.md has a list check dated 2026-11-17 with duplicates, one broken site and forwarding sites. No clean-up approved yet.
