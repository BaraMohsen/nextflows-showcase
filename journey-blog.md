# From "What's an MCP?" to a Shipped Server — My Cohort Journey

When I started this cohort, I genuinely didn't know what MCP (Model Context
Protocol) was. I knew I'd be building "something that connects to an AI,"
and that was about it. Six weeks later, I'd shipped a real, tagged, public
project — and picked up a lot more along the way than I expected.

## Week 1: Just Git, Nothing Fancy

The first task was almost embarrassingly simple: create a GitHub repo, make
one commit, push it. That was it. But it was also the first time I actually
understood what `git add`, `git commit`, and `git push` were doing instead
of just copying commands I didn't fully get. Small start, but it mattered.

## Weeks 2–3: Building the Actual Tools

Then came the real project — a Personal Expense Tracker MCP server, working
alongside a partner. I built the tools that let an AI assistant add an
expense, list expenses, and get a spending summary, all backed by a simple
local CSV file. This is where I first saw an AI model actually calling code
I wrote, not just answering questions. That was the moment it clicked.

## Week 4: Getting Reviewed (and Not Loving Every Minute of It)

A teammate tested my tools and found real problems — no cap on how much
data could come back, no limit on category length, weak month validation.
Getting that kind of feedback isn't always fun, but fixing it and having
him confirm "well done" afterward felt like actual progress, not just
finishing a checklist.

## Week 5: Testing Things I Assumed Already Worked

I wrote a real test plan and ran it by hand in MCP Inspector — happy paths,
invalid inputs, empty data. A few things I assumed were fine weren't. I also
had someone outside my usual pairing partner clone my repo cold and follow
only the README, no help from me. Watching where they got stuck taught me
more about writing clear docs than any guide could have.

## Week 6: Shipping It for Real

This week was about making the project look like something a stranger could
actually pick up and run — a license, a clean `.gitignore`, a public repo,
a tagged `v1.0.0` release tested from a completely fresh clone. I also
connected the server to Claude Desktop myself, which meant debugging a
config issue that had nothing to do with my code and everything to do with
file paths on Windows. Frustrating in the moment, useful in hindsight.

## What I Actually Learned

Not just MCP or TypeScript or Zod — I learned how to read an error message
instead of panicking at it, how to take feedback without getting defensive,
and how to write documentation for someone who isn't me. I also learned
that a "finished" project isn't the one that just runs on your own laptop —
it's the one that runs on someone else's.

Thanks to my mentor and to NextFlows Academy for building a cohort that
actually made us ship something real, not just follow a tutorial.

**Project repo:** [Personal Expense Tracker MCP](https://github.com/MohammadYousef-001/Personal-Expenses-Tracker)
