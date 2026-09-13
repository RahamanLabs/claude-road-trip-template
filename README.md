# Road Trip Planning Template

Three text files for planning a long drive with Claude.
I used them for a 713 km monsoon drive, Hyderabad to Goa, August 2026.

I say Claude throughout because that's what I actually used. Nothing here is
specific to it — the files are plain markdown and the prompts are plain English,
so ChatGPT, Gemini or anything else works the same way. Substitute the name.

Written up here: **[How I Planned a Hyderabad to Goa Road Trip With AI](https://medium.com/@mustaf.here/hyderabad-to-goa-by-road-part-5-of-5-how-i-planned-the-trip-with-claude-3790664edf16)**

## The files

Build them in number order. `01` and `02` hold the work; `03` is the short one you
actually carry.

| File | Holds |
|---|---|
| [`01_ROUTE.md`](01_ROUTE.md) | Routes compared, timing, food stops, map links, roads to refuse |
| [`02_SAFETY.md`](02_SAFETY.md) | Risks ranked, what's closed, decision rules, verdict by leg |
| [`03_SUMMARY.md`](03_SUMMARY.md) | Decisions, hard rules, checklist, dated conditions |

Under every heading there's a line in italics saying who fills that section in:
you, Claude, or you looking it up from a real source.

Never let Claude fill in something you're meant to look up. It will invent
a confident, wrong number. Ask it which authority publishes the figure, then go
read that authority.

## Start here

**1.** Open `03_SUMMARY.md`. Fill in the **Trip** block only, seven lines. Ignore
the rest of the file.

**2.** Open `01_ROUTE.md`. Fill in **What I am optimizing for**, four or five
lines. Nobody can decide this for you.

**3.** Open a new AI chat, attach all three files, and paste this:

> I'm planning a road trip. Three template files attached. We're working on
> `01_ROUTE.md` only today. My trip facts are in the Trip section of
> `03_SUMMARY.md`, and what I'm optimizing for is at the top of `01_ROUTE.md`.
>
> Rules for this whole project. Name a source and a date for every factual claim.
> If you can't, say so and tell me to put it in Open Questions, never fill a gap
> with something plausible. Keep answers short, bottom line first. Push back when
> I'm wrong.
>
> Start with the section called Primary route. Compare every sensible route
> against what I'm optimizing for, score them, recommend one. Give it back as
> markdown I can paste into the file, same headings.

**4.** Work down `01_ROUTE.md` one section at a time. For each: *"Next section:
[HEADING]. Same rules. Markdown, same headings, flag anything you can't source."*

**5.** Open a map and trace the route it recommends, section by section, checking
the road numbers. Don't skip this. It's where Claude is least reliable.

**6.** New chat for `02_SAFETY.md`. Same opening prompt, swap the file name, and
start with: *"Rank the risks on this route in this season by what's most likely to
actually hurt us, not by what sounds dramatic. For each: the number with its
source and date, the specific check that tells me if it's a problem this week, and
the mitigation."*

**7.** New chat for `03_SUMMARY.md`: *"Both other files are done and attached.
Pull everything genuinely settled into Decisions taken, one line each, written as
decisions not options. Anything unsettled goes to Open questions instead. Then
draft Hard rules from the risks in `02_SAFETY.md`, numbered, each with a trigger.
Tell me what you moved to Open questions and why."*

**8.** A day or two before you go, fill in the **Conditions snapshot** in
`03_SUMMARY.md` and **Restrictions in force** in `02_SAFETY.md` yourself, from
real sources. These expire fastest. Then work the checklist.

## Reading it on the trip

Roughly the reverse of the build order.

- **Week before:** `02_SAFETY.md` in full, while you can still change the plan.
- **Night before:** `03_SUMMARY.md`. Read the hard rules out loud to everyone.
- **Morning you leave:** re-check the conditions snapshot. If a decision rule says
  cancel, cancel.
- **On the road:** `01_ROUTE.md`. Timing, map links, roads to refuse.
- **At a decision point:** Decisions taken in `03_SUMMARY.md`. Check the one named
  condition, then drive.

Download or print all three. You'll want them without signal.

## Five rules

1. Attach all three files every session. Say which one you're working on.
2. Source and date for every claim, or it goes to Open Questions.
3. Verify geography on a map yourself.
4. Check dates and days of the week by hand. A one-day error looks trivial and
   quietly breaks every timing conclusion. This happened to me.
5. Items move from Open Questions to Decisions when you say so, not when the
   conversation runs out of energy.

## Editing

Fill in the `[SQUARE BRACKETS]`. Don't rename headings, you'll be pointing the
Claude at them. Delete any section that doesn't apply. Keep the file names and
the date line at the top of each file.

## License

Free to copy and adapt. Attribution appreciated, not required.
Template by Mustafizur Rahaman.
