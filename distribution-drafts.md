# Distribution drafts — ready to paste, operator's own account only

Prepared 2026-09-03. This file is drafting only. Nothing in it has been posted,
scheduled, or submitted anywhere. Every draft below is built from primary-source
findings already published on the 18-page `bets/unsettled/` family (page text
quoted/paraphrased from the live HTML, not invented). Community rules were
checked live (sidebar/rules wiki or forum policy page) on 2026-09-03 and are
cited by rule number/name in each per-community note — re-check before posting
if more than a few weeks have passed, since sub rules do change.

## Posting order

Start with **one** post, not a batch: **r/USExpatTaxes** (draft 1, FBAR joint
accounts) is the cleanest fit — general-audience finance/tax sub, explicit
rule welcoming personal-experience/research posts, largest relevant reach.
Watch it for 48–72 hours: upvote ratio, comment tone, any correction. Only
then post **one more**, picking whichever of drafts 2–6 fits something timely
in that community that week (e.g., r/nri if a corrigendum-adjacent question
is already trending there). Space further posts by at least several days each.
Do not queue all six in one sitting.

## What to do with feedback

Corrections are the actual product here, not the traffic. If a commenter
(especially anyone claiming CPA/CA/ACA/enrolled-agent/solicitor credentials)
identifies an error, a missed exception, or a more recent primary source:
copy the correction into a note back to the desk (this repo, `ops/LOG.md` or
a new `research/` file) before doing anything else with it — including before
editing the live page. The pages' whole premise is "we read primary sources
and say so when we're not sure"; a real-world correction is exactly the kind
of update this project exists to absorb. Do not defend the original post
against a well-sourced correction — thank the commenter, verify the source
they cite, and update.

## What NOT to do

- No cross-posting all six drafts at once, same day, same account signature —
  reads as coordinated promotion and will get several of these subs' stricter
  self-promotion rules triggered simultaneously (see per-community notes:
  r/PersonalFinanceCanada and r/UKPersonalFinance both flatly ban self-promo
  without prior mod approval; posting to both the same week from a new/thin
  account profile is a bannable pattern even if each post individually is
  fine).
- No engagement-bait titles, no "you won't believe," no artificial urgency.
  Every title below is finding-first and specific on purpose — that is also
  what these subs' rules reward (r/UKPersonalFinance's "show research done"
  norm, r/nri and Bogleheads' preference for first-person research framing
  over link-only posts).
- No claiming credentials the operator doesn't have. Never write "as a CPA"
  or "as a tax adviser." The honest framing throughout is "I've been reading
  the primary statutes/regs/treaty text directly" — true, checkable, and
  exactly what these pages already do.
- No disputing a correction to defend traffic to the site. If proven wrong,
  say so in the thread and fix the page.
- Where a sub's rules require mod pre-approval for any link (UKPF, HENRYUK,
  PFC, r/CanadaImmigrant per this research pass), message the mods *before*
  posting, not after — do not test whether they notice.

---

## 1. r/USExpatTaxes — FBAR joint-account owner-of-record

**Title:** Being named on your parent's Indian bank account makes you the FBAR
"owner of record" — source of funds doesn't matter (31 CFR 1010.350)

**Body:**

I've been reading 31 CFR 1010.350 directly (not summaries) because a lot of
FBAR guides aimed at Indian-American families get the joint-account mechanics
slightly wrong, in a way that matters.

The common assumption: "It's my father's NRE account. I'm only on it so the
bank doesn't freeze it if something happens to him. I've never put money in
or taken money out." Under the regulation, none of that changes the answer.

31 CFR 1010.350(e)(1), "Financial interest — owner of record": a US person
has a financial interest in a foreign account "for which... the United States
person is the owner of record or holder of legal title, whether the account
is maintained for his or her own benefit or for the benefit of others
including non-United States persons." Being listed as a joint holder makes
you the owner of record, full stop — no economic-interest test, no
source-of-funds test, no exception for an account added purely for succession
convenience. Section (a) sets two independent triggers, "financial interest
in, or signature or other authority over" — either alone is enough.

The spousal joint-account exception (skip filing if you and your spouse
jointly own all your foreign accounts and file FinCEN Form 114a) does not
extend to a parent-child account — the co-owner has to be a spouse, and a
parent usually isn't even a US person, so there's no possibility of using
Form 114a to designate them as filer. Every US-person child named on a
parent's account has to file their own FBAR, every year the account exceeds
the threshold — no shortcut.

I also checked the narrow carve-outs in 1010.350(f)(2) that some people hope
cover "family accounts" — they don't. Every one is occupational: bank
officers, employees of regulated entities, military banking facilities,
correspondent/nostro accounts. Nothing about family relationships.

One thing I could *not* independently confirm this pass: that each joint
owner reports the account's full maximum value (not a pro-rata share).
Every preparer site says this and it's consistent with how Form 114 is
structured (no field for a percentage), but I couldn't get FinCEN's own
line-item instructions PDF to render text to check directly — so I'm
flagging it as well-corroborated, not independently verified by me.

This isn't tax advice — I'm not a CPA or EA, just someone who reads the
regulation text directly instead of trusting paraphrases. Worth checking
with a preparer: are you a joint owner or just have signature authority
(the reg treats these as separate triggers)? Has anyone confirmed no (f)(2)
exception applies rather than assuming one does? Is each account being
reported at its own full value?

*(If anyone wants the full read-through with all the citations laid out,
happy to share in a comment.)*

**Per-community note:** r/USExpatTaxes Rule #3 bans spam/promotional
activity; Rule #4 explicitly welcomes referrals/experience-sharing. This
post is written to stand alone with zero links — safest posture given Rule
#3 is unqualified (no stated ratio, unlike r/nri). Only add the site link
**in a reply**, and only if someone asks for it — the closing line above
sets that up naturally. No flair requirement, no megathread, no stated
best-time norm.

---

## 2. r/nri — EPF Scheme 2026 corrigendum (G.S.R. 703(E))

**Title:** Two High Courts split on whether US-citizen employees in India owe
uncapped EPF contributions — the new EPF Scheme 2026 quietly picked a side,
then a corrigendum flipped it again

**Body:**

This is a live, fairly wild story if you have (or manage) an American
employee on an Indian payroll, and I haven't seen anyone connect the pieces.

Since 2008, "International Workers" under EPF law — a category broad enough
to include a US citizen or green-card holder employed by an Indian company —
have been pulled out of the normal ₹15,000/month wage ceiling on PF
contributions. Full salary, uncapped, plus no withdrawal before age 58 unless
your country has a Social Security totalisation Agreement with India. The US
doesn't have one.

On 25 April 2024 the Karnataka High Court struck this down as
unconstitutional (Value and Budget Housing Corporation & Ors vs Union of
India), reasoning specifically that the government's justification — SSA
reciprocity — makes no sense for workers from non-SSA countries, which is
exactly the American-employee fact pattern. On 4 November 2025 the Delhi
High Court expressly disagreed (SpiceJet Ltd vs Union of India) and upheld
the same provisions. The Supreme Court issued notice on a challenge on 12
March 2026 and hasn't ruled.

Then on 29 June 2026 the entire EPF Scheme, 1952 both courts were arguing
about was replaced wholesale by the EPF Scheme, 2026 (G.S.R. 525(E)). A
July 2026 client note from WTW read the new scheme's text as defaulting
International Workers to the ordinary capped treatment — a real policy
shift, not just renumbering.

That reading didn't survive. On 4 August 2026 the Ministry issued a
corrigendum, G.S.R. 703(E), correcting the exact membership paragraph WTW's
reading turned on — "member," read "member other than international
workers." I read the corrigendum PDF directly rather than relying on a
secondary writeup. Read together with contemporaneous reporting, the
uncapped, no-ceiling treatment for non-SSA-country IWs (including US
citizens) appears to survive into EPF Scheme 2026 after all — though I
couldn't find a dedicated EPFO circular stating that consequence outright,
so I'm holding this as a strong inference from the corrigendum's text, not
a confirmed EPFO position.

None of the EPF-reporting guides I checked (US-side, for FBAR/FATCA
purposes) connect any of this litigation or the corrigendum to what a US
person actually has to report. And EPFO's own public scheme pages, checked
directly, still describe the *superseded* 1952/1995 schemes as current —
two months after the replacement took effect.

Not tax or legal advice — I'm not a CA or lawyer, just reading the judgments,
the gazette text, and EPFO's own pages directly. If you're an employer or
employee in this situation, worth asking counsel: does the ₹15,000 ceiling
apply by default post-corrigendum, and is there a written EPFO circular
confirming it either way?

**Per-community note:** r/nri Rule #3 (Self Promotion) tolerates occasional
self-promo from established members at roughly a 1:10 ratio, but requires
contacting mods first. This draft is written link-free by default; per the
rule, message the mods before adding the site link anywhere (post or
comment), even though the content itself is substantive and on-topic
(Rule #2, relevance). Don't treat the 1:10 ratio as a green light without
the mod contact step — the rule states both conditions.

---

## 3. r/IndiaInvestments — venue note + bi-weekly-thread-ready snippet

**This one needs a judgment call, not a straight post.** r/IndiaInvestments's
audience and rules are built around India-domestic investing questions
(Rule #2, no solicitation of investments; Rule #5, linkspam/blogspam can be
a bannable removal, and any self-link needs a real in-body summary, not a
link-out). The cross-border US/UK/Canada tax content this project produces
is adjacent to their scope at best — it is about the treaty/regulatory
mechanics of *outbound* NRIs' foreign tax filings, not India-domestic
portfolio questions. Two honest options:

1. **Skip a standalone post entirely.** The fit is weak enough that a
   dedicated submission risks a Rule #5 removal regardless of how it's
   written.
2. **Only participate through the sub's "Bi-Weekly Advice Thread: All Your
   Personal Queries."** That's the sub's designated venue for personal-
   situation content per its own linked-post rule. If and when someone in
   that thread asks a question this project's research actually answers
   (e.g., "how does Form 1116 timing work against Indian advance tax
   installments"), reply with the substance directly — no link needed
   unless asked, and even then keep it to a comment, not a new post.

**Ready-to-paste reply, if a matching question appears in that thread:**

> If this is about matching Indian advance-tax payments to Form 1116 (US
> foreign tax credit) — worth knowing that the US calendar year and India's
> April–March year don't map 1:1 by default. On the cash method (the
> default if you've never made a §905(a) election), each Indian tax payment
> is creditable in the US year you actually paid it — so your June/Sept/Dec
> advance-tax installments usually land in one US year, but your March
> installment and any self-assessment payment often land in the *next* US
> year, even though they're the same Indian financial year's tax. There's
> an alternative accrual election under IRC §905(a) that bundles the whole
> Indian year into one US year instead — but it's irrevocable once elected,
> binding all future years. I read this off 26 CFR 1.905-1 and 26 U.S. Code
> §905 directly; worth checking with a US preparer whether your return has
> ever made that election before assuming either treatment.

**Per-community note:** treat this community as low-priority / possibly
not-a-fit rather than force a post. If posting at all, the bi-weekly thread
is the only venue this research supports under their own rules — never a
standalone submission with a link.

---

## 4. r/UKPersonalFinance — FIG regime vs NRE-interest tax-sparing credit

**Title:** The 4-year FIG regime isn't the only way to shelter NRE interest
from UK tax — the India-UK treaty has a free alternative sitting right next
to it (Article 24)

**Body:**

Posting this because every UK-NRI tax guide I've checked explains the FIG
regime correctly but stops one step short of a point that's actually in the
statute and treaty text.

Since 6 April 2025, the remittance basis is gone, replaced by the Foreign
Income and Gains (FIG) regime — a 4-year window (arrival year plus three,
per ITTOIA 2005 s.845B) where you can elect, source by source, to shelter
qualifying foreign income from UK tax. It's not automatic — it's a claim
made in your Self Assessment return (s.845A), and it's not free: claiming it
for *any* amount, even a small one, forfeits your entire personal allowance,
married couple/civil partner relief, and life-insurance relief for that year
(s.845E) — and separately, your CGT annual exempt amount if you claim on a
gain (TCGA 1992 s.1K(6)(b)). Whole-year, binary losses, regardless of how
much you actually claimed.

Because s.845A(2)(b) lets you name *which* sources go into the claim, the
real question for someone with several types of foreign income isn't "do I
claim FIG" — it's "which sources actually need to be in the claim." And NRE
interest specifically has a separate, free route that doesn't touch s.845A
at all: the India-UK DTAA's tax-sparing credit.

Article 12 of the treaty taxes NRE interest as ordinary interest, with no
NRE-specific carve-out. But Article 24(3)–(4) — the double-taxation
elimination article — names India's own NRE exemption, Income-tax Act
s.10(4), *directly* as a "spared" provision (not through the weaker
"substantially similar" route some other provisions use). In plain terms:
India taxes NRE interest at 0%; the treaty lets the UK pretend India
collected tax anyway and gives credit for the tax "spared" — which zeroes
out the UK bill too, without an s.845A claim, without losing the personal
allowance, and for up to 10 fiscal years per source (Article 24(5)) — a
longer runway than the FIG regime's 4 years.

The two strongest guides I found on this (wealthnorth.in, BKL LLP) both
correctly identify the tax-sparing mechanism — but both frame it only as
what you do *after* the FIG window closes, not as a live alternative you
can use *instead of* spending a FIG claim on NRE interest right now.

Caveat I can't resolve from the statute alone: HMRC's own India manual
(DT9553) confirms the tax-sparing mechanism exists but never mentions NRE
interest by name, and I couldn't find a tribunal decision or documented case
walking through this exact claim end-to-end — so whether HMRC processes it
as routinely as the general procedural manual (INTM161270) suggests is my
best read of adjacent evidence, not a confirmed outcome.

Not financial or tax advice — I'm not a chartered tax adviser. This is a
reading of Finance Act 2025's inserted provisions and the treaty text,
posted so the right question can go to a CTA/ATT-qualified adviser before
anyone files a FIG claim.

**Per-community note:** r/UKPersonalFinance Rule #11 flatly bans self-
promotion/ads without prior mod approval — message the mods before adding
any link, in the post or a comment. Rule #4/#5 reward posts that show
research done and reference primary sources, which this fits well as
written link-free. r/HENRYUK was checked as an alternative and is a worse
fit — its Rule #2 explicitly excludes general tax-filing topics as
"not HENRY-specific."

---

## 5. r/PersonalFinanceCanada — EPF/T1135 and the Article 18 pension article

**Title:** Your Indian EPF/PPF can't use the "exempt trust" T1135 carve-out —
and the top India-Canada guide has the treaty's pension article backwards

**Body:**

Sharing this because I went and read the actual statute and treaty text
after noticing two competing claims about Indian EPF/PPF and Canadian T1135
reporting that can't both be right.

**T1135 reporting:** the natural argument is that a retirement fund should
get the same kind of carve-out a US 401(k)/IRA effectively gets. Canada's
Income Tax Act does have an "exempt trust" carve-out from specified foreign
property (s.233.3(1)(n) → s.233.2(1)(a) → s.248(1) "foreign retirement
arrangement" → "prescribed plan or arrangement"). Following that chain to
the actual regulation: Income Tax Regulation 6803 prescribes exactly one
thing — plans under US IRC §408(a), (b), or (h). Nothing Indian, no general
test. EPF/PPF can't reach this carve-out; it's a US-IRA carve-out in
substance. (There's a second, general exempt-trust test in s.233.2(1)(b)
that also plausibly fails on the facts — a 2014 CRA technical interpretation
applying the identical four-condition test to an Australian pension fund
confirms how CRA reads it, though no EPF-specific CRA ruling exists that I
could find.)

**The treaty question is where I found an actual error.** The India-Canada
DTAA's only pension provision, Article 18, is two sentences: "Pensions
arising in a Contracting State shall be taxable only in that State" —
meaning the *source* state (India, for an Indian-paid pension), not the
residence state. A widely-cited generalist guide (countrytaxcalc.com)
states this backwards — as a residence-state rule — and its own worked
example inverts the correct answer. Even the strongest specialist guide I
found (TrustNRI) contradicts itself: its dedicated pension page states
Article 18 correctly, but its separately published, CA-reviewed T1135 blog
post cites a nonexistent "Article 20(2)" (Article 20 is actually "Students
and Apprentices," one paragraph, no subsections) for the identical rule.

**What's genuinely unresolved:** the treaty never defines "pension" at all,
so whether a one-time EPF lump-sum withdrawal even counts as a treaty
"pension" under Article 18 — versus being ordinary income Canada can tax
regardless — isn't settled by the text. I found a real r/nri thread where
someone's Article 18 EPF claim is under active CRA Pre-assessment Review,
which I'm citing only as evidence this is a live, contested question in
practice, not as legal authority.

Not tax advice — I'm not a CPA or Canadian tax lawyer. Worth asking a
preparer: on what statutory basis (if any) would you argue EPF avoids
T1135 given Regulation 6803's closed list, and how would you document an
Article 18 pension position if CRA opens a review on it?

**Per-community note:** r/PersonalFinanceCanada Rule #2 bans self-promotion
outright (no ratio exception, stricter than r/nri) — post link-free, no
comment link either unless a mod pre-approves. Rule #8 penalizes
AI-generated/formatted content with escalating bans, so keep the voice
plainly first-person and avoid list-heavy formatting that reads as
machine-generated. r/CanadaImmigrant was checked and is a worse fit —
immigration-status focused, not tax, and bans solicitation/link-farming
outright.

---

## 6. Bogleheads forum, Non-US Investing subforum — India FTC timing / §905(a)

**Title:** Form 1116 and India's April–March tax year don't map to the same
US tax year by default — and the accrual election that "fixes" this is
irrevocable

**Body:**

Posting this in Non-US Investing since it's relevant to anyone here who's a
US taxpayer with income taxed in India (or any other April–March fiscal-year
country) and claims the foreign tax credit.

Every Form 1116 guide I've read tells you to gather "this year's" Indian TDS
and advance tax. None of them specify *which* year — India's fiscal year
(April–March) or the US calendar year the credit is actually claimed in —
and I went and read the regulation directly (26 CFR 1.905-1, 26 U.S. Code
§905) because the answer isn't obvious and matters for timing your credit.

Default rule, cash basis (most individual filers, absent an election):
26 CFR 1.905-1(c)(1) — the credit falls in the US taxable year the foreign
tax was actually *paid*, not earned, not the Indian assessment year. India's
advance-tax installments fall on 15 June, 15 September, 15 December, and 15
March, plus a self-assessment payment when the return is filed (typically by
31 July). The June/Sept/Dec installments usually land in one US calendar
year; the March installment and the self-assessment payment usually land in
the *next* one — even though all of it is the same Indian financial year's
tax. Someone who pulls a single Form 26AS figure and puts it all on one
Form 1116 is implicitly using the Indian year as the organizing unit, which
the cash-basis regulation doesn't support.

There's an alternative: IRC §905(a) lets you elect the accrual method for
FTC purposes specifically, regardless of your regular accounting method.
Under accrual, the *entire* Indian year's tax becomes creditable in a single
US year — the one containing 31 March, per the regulation's own worked
example (26 CFR 1.905-1(d)(6)(i), Example 1, which uses a April–March
foreign tax year almost identical to India's). The catch, and the reason
this isn't a free simplification: §905(a)'s last sentence makes the election
irrevocable — it binds every future year, permanently. There's no switching
back to cash-basis crediting later because it happened to be more
favorable in some year.

Which method nets a larger usable credit depends on your specific year-to-
year income pattern (the §904 category limit only carries excess credit
back one year, forward ten) — I'm not modeling that here, just flagging
that the choice exists, is irrevocable, and that the India-specific FTC
guide I checked (otherwise genuinely thorough — covers PFIC interaction,
Form 67→44 renumbering, NIIT gap) never mentions it.

Not advice, just a read of the primary regs — worth checking with your
preparer whether a §905(a) election has ever been filed on your return
before assuming which method applies, and whether your March/self-
assessment payments have been credited to the right US year.

**Per-community note:** Bogleheads' "General Etiquette" bans naked links —
this draft has none, and is written as a self-contained explanation with
quoted-in-substance citations, matching the forum's own norm (link only
allowed in replies to *others'* threads, per the No Solicitation policy,
never as a new promotional topic). Their AI-generated-content policy
requires initial posts be the poster's own writing — read this over and
adapt it into your own voice/phrasing before posting, don't paste verbatim.

---

*Sources for every finding above: the five underlying pages in
`bets/unsettled/` — `fbar-joint-accounts.html`,
`epf-international-worker-wage-ceiling.html`, `uk-fig-regime-nre-interest.html`,
`canada-epf-t1135-article18.html`, `india-fiscal-year-ftc-timing.html`.
Re-read the live page before posting to catch any update made after this
draft was written (all five carry "Last reviewed" dates and update boxes
that get edited in place).*
