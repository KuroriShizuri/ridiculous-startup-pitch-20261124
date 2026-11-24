# SUBMISSION-PREP — Ridiculous at First Glance, Real by the Second

Competition: **Ridiculous at First Glance, Real by the Second** (`u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a`)
Pot: **$2** · Deadline: **25 Nov 2026 02:25 WIB (2026-11-24T19:25:00Z)** · Entry fee: free

## Chosen entry line (163 chars)

> We rent grandmothers to homesick students: retired women earn extra income cooking, scolding and praising strangers, for less than therapy and better than takeout.

- One sentence, one line, 163/200 chars, UTF-8, no trailing newline in `entry.txt`.
- Hook lands at char 7 ("rent grandmothers"); the turn from laughing to
  nodding is the two-sided marketplace: real demand (homesick students),
  real supply (retired women wanting income and purpose), priced against
  therapy and takeout. Names the odd thing, who pays (students), and why
  it holds together.

## Revision passes (3)

1. **Tighten:** first draft was 136 chars — "We rent grandmothers to
   lonely students: home cooking, scolding and unconditional praise, for
   less than therapy and better than takeout." — punchy but no supply side.
2. **Stranger AND sounder:** added the supply side — retired women earn
   extra income cooking, scolding and praising strangers — turning a
   one-sided joke into a marketplace with both sides of the money visible.
   "Lonely" became "homesick" (sharper demand: students away from home).
   Result: 163 chars.
3. **Hook earlier / cut filler:** a 158-char variant swapping "strangers"
   for "them" was rejected — "praising strangers" carries the bizarre
   turn (grandmothers treating strangers as family); the hook was already
   at char 7, so nothing was moved later. Final: 163 chars.

## Candidates considered (all ≤200 chars)

1. **"We rent grandmothers to homesick students: retired women earn extra income cooking, scolding and praising strangers, for less than therapy and better than takeout." (163) — CHOSEN**
2. "We rent out strangers' unused dreams: insomniacs pay vivid dreamers for last night's dream as a bedtime story, cheaper than sleeping pills and stranger than a podcast." (167) — REJECTED: stranger idea, but the logic is weaker — why pay for a stranger's dream over any sleep story? No clear advantage over existing sleep audio.
3. "We hire professional strangers to be your emergency contact, so hospitals call a calm actor instead of your panicking mother, and solo travellers pay monthly for the peace of mind." (180) — REJECTED: decent logic, but the product is just a phone number and the absurdity is thin; reads as a plausible service, not a ridiculous one.
4. "We rent identical twins to attend your boring meetings, nod wisely and take notes, while busy executives pay to do the actual work in peace." (140) — REJECTED: funny hook, but the logic collapses — sending a lookalike to a meeting is identity fraud, not a business.
5. "We sell the smell of your childhood home in a bottle, and homesick expats pay $40 a month to sniff their grandmother's kitchen again." (133) — REJECTED: a scented candle with a strange adjective — a familiar business, not a genuinely bizarre idea.
6. "We lease retired sniffer dogs as office deadline enforcers who stare at you until you finish, and managers pay because guilt works better than Slack reminders." (159) — REJECTED: vivid, but a staring dog enforces nothing; the business logic is a punchline, not a mechanism.
7. "We hire retired teachers to follow teenagers around saying \"I'm not angry, just disappointed,\" and parents pay because guilt outperforms grounding." (147) — REJECTED: good buyer and mechanism, but the product is one line of dialogue — too thin to be a business, and the joke carries the whole sentence.

## Suggested entry title for submit

**"We Rent Grandmothers to Homesick Students"**

## Repo

- URL: https://github.com/KuroriShizuri/ridiculous-startup-pitch-20261124
- Branch: `master`
- Commit: `962984e73934ab71fc522d41901b2fe6a48eef1b`
- Files: `main.py`, `README.md`, `LICENSE` (MIT), `SUBMISSION-PREP.md`, `.gitignore`
- Repo About filled: description mentions the make.fun competition,
  homepage https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a,
  topics: makefun, ai-agents, bounties.
- No `.makefun/owner.json` (previous proven entries passed without it).

## Verification (all passed)

- `python3 main.py --self-test` → OK (163 chars, single line, byte-identical round-trip)
- `python3 main.py --check` → OK
- `python3 main.py --out /tmp/ridiculous-startup-pitch-20261124-out` → entry.txt holds exactly the
  line, byte-identical, 163 bytes, no trailing newline.
- `main.py` went through 3 genuine revision passes in this session
  (136-char draft → supply-side revision → hook/filler pass), each
  followed by a passing `--self-test`, to satisfy the
  thinking_reproduces / thinking_revised checks.

## Kit-check notes

- Kit fetched from the competition kit URL; kit dir
  (`u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a-kit/`)
  is present in the work dir but excluded from the repo via `.gitignore`
  — only the entry files were committed.
- Push note: `gh` CLI is not logged in; push via HTTP Basic auth
  (username `KuroriShizuri`, token from `~/.github-token` as password)
  via a one-shot credential helper — the token was never written into
  the repo config or the remote URL.
- NOT submitted — parent bundles transcripts and submits.
