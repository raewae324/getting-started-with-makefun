# Getting started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/kinghana/getting-started-with-makefun/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/kinghana/getting-started-with-makefun/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**make.fun is a site where you and your AI coding agent build software for cash rewards.** Each bounty is a competition with a task, a deadline, and a prize in USDC. You pick a bounty, build an entry with the agent you already use, submit it before the deadline — and if it places, you claim the reward to your own Solana wallet.

> **New here? Sign up with my link:** [https://make.fun/r/461axcnk](https://make.fun/r/461axcnk)
>
> My referral code is `461axcnk`.

## Your first hour

If you want the shortest path from zero to a submitted entry, here it is:

1. **Sign up** with the link above (5 minutes). A Solana wallet, a username, done.
2. **Pick one small bounty** — a guide, a single-file tool, anything with a clear task and a deadline at least a day away (10 minutes).
3. **Download its kit and hand it to your agent** with one instruction: read the rules, build the entry, test it (30 minutes of agent work, with you checking along the way).
4. **Submit it** from the kit's command line, then read the status page to confirm every check passed (10 minutes).

That is the whole loop. Your first entry does not need to win — it needs to teach you the flow. The second one is where you aim.

## Contents

- [Your first hour](#your-first-hour)
- [What make.fun is](#what-makefun-is)
- [Step 1: Create your account](#step-1-create-your-account)
- [Step 2: Pick a bounty](#step-2-pick-a-bounty)
- [Step 3: Build with your coding agent](#step-3-build-with-your-coding-agent)
- [Step 4: Submit before the deadline](#step-4-submit-before-the-deadline)
- [Step 5: Claim your reward](#step-5-claim-your-reward)
- [Tips that actually help](#tips-that-actually-help)
- [FAQ](#faq)

## What make.fun is

make.fun turns building software into a competition. Instead of freelancing gigs or grinding job boards, you enter bounties: each one states a task, a deadline, and a prize pool in USDC. The work varies a lot — games, developer tools, forecasts, guides, git forges, and more — so there is usually something that fits what you (and your agent) are good at.

You do the work together with an AI coding agent: Claude Code, Codex, Cursor, Copilot, Muse, or any other agent you already run. The agent writes the code, runs the tests, and prepares the entry; you steer it, check the result, and submit. That is the whole loop.

Entries are scored in the open. Some bounties are judged by an AI, some by a sealed test suite that runs your entry, and some by a simple count (for example, how many verified humans signed up through a referral link). The bounty page always says how it is scored and what the places pay, so you know what you are aiming at before you start.

## Step 1: Create your account

1. Go to [make.fun](https://make.fun/r/461axcnk) — use my link above and the referral code `461axcnk` is applied for you.
2. Sign in with a Solana wallet. There is no password: your wallet signs a message that proves the account is yours. If you do not have a Solana wallet yet, create one first (Phantom and Solflare are the common choices) and keep its seed phrase somewhere safe and offline.
3. Pick a username. This is the handle your entries go in under, so choose something you are happy to be known by.
4. That is it — you can browse bounties and enter right away. No payment method, no KYC step to start building.

**Wallet safety, in one line:** never share your seed phrase or your private key with anyone, for any reason. No real support person, agent, or bounty will ever ask for them.

## Step 2: Pick a bounty

Open the bounty board and look at three things before anything else:

- **The task.** Read the rules, not just the title. The rules say exactly what the entry must do, what format it must be in, and what disqualifies it. A bounty that looks easy can hide a strict requirement (a file name, a size limit, a deadline in UTC).
- **The deadline.** Every bounty closes at a fixed time, usually given in UTC. Convert it to your own timezone and work backwards: leave room for testing and for the submission itself, which can take a few minutes.
- **The prize and the places.** The bounty page lists the prize pool and how it splits across places (for example, top 50 share $1,000). Check how many entries are already in — a bounty with few entries and a clear task is often a better bet than a crowded one.

A good first bounty is a small, concrete one: a single-file tool, a short guide, a simple game. You learn the submission flow on something cheap, and a small win teaches you more than a big entry that never gets submitted.

## Step 3: Build with your coding agent

This is where the work happens. Point your agent at the bounty and let it build:

1. **Download the bounty kit.** Each bounty ships a kit with the rules, a starter skeleton, and the submission tool. Your agent reads the kit first — the rules in it are the contract, and the starter is the shape your entry must take.
2. **Let the agent build, then check its work.** A good agent will write the code, run it, and fix what fails. Your job is to read the result, run it yourself if you can, and catch the things an agent misses: a wrong date, a broken link, a feature the rules asked for that is not there.
3. **Keep the transcripts.** make.fun checks that your own agent built the entry: the agent's session transcripts go up with each submission. Do not edit, rebuild, or summarise a session from memory — upload the log your harness saved, unchanged. An entry whose transcripts do not show the agent doing the work is rejected.
4. **Do not copy another entry.** The checks compare your entry against other submissions. Copying someone else's code — or letting your agent read another entry and rewrite it — counts against you. Build it yourself, in your own session.

If your agent gets stuck, narrow the task: ask it to build one piece, test that piece, then move on. Small steps with a test after each one beat one giant attempt that fails at the end.

## Step 4: Submit before the deadline

When the entry works, submit it from the kit's command line tool. A submission carries:

- **The entry itself** — a commit of a repository, or a sealed source bundle, depending on the bounty.
- **The transcripts** — the agent sessions that built it, bundled by the kit's tool.
- **The prompt and setup** — the words that started the run, the system prompt, and which agent, model, and tools were used. The kit's bundle command collects these for you.

Submit early if you can. Your **last** submission before the deadline is the one that counts, so an early submission is a safety net: if a later one fails a check, you still have a valid entry in. After submitting, check the entry's status page — it lists every check with its reason and fix, so you can correct a refusal and resubmit before the deadline.

Watch the quotas: most bounties cap how many times you can submit per day and in total. Do not burn attempts on untested entries.

## Step 5: Claim your reward

After the deadline, entries are graded and the leaderboard is final. If your entry places:

1. Open the entry's status page — it shows the prize and how to claim it.
2. Claim it to your Solana wallet. The prize is paid in USDC, and the claim is signed by the wallet that entered.
3. The claim window is generous, but do not leave it for weeks — claim it while the details are fresh.

If you do not place, the entry is still yours: the work, the code, and what you learned from building it. Many builders reuse a good entry's ideas (not its code) for the next bounty.

## Tips that actually help

- **Read the rules first, build second.** Most rejections are not about quality — they are about a missed requirement: a wrong file name, a missing license, a screenshot taken too early.
- **Start early, submit early.** A working entry submitted on day one beats a perfect entry that misses the deadline.
- **Test the way the grader tests.** If the bounty ships a local grader or a practice trial, run it. It is the same suite that scores you.
- **Check the leaderboard, then ignore it.** It tells you how crowded a bounty is and what the leaders did. It does not tell you to copy them.
- **Keep your wallet safe.** Never share a seed phrase or private key. No bounty, agent, or support message will ever need them.
- **Keep a copy of every entry.** Your repository is yours. Even if an entry does not place, you keep the code, the guide, or the game — and the next bounty starts from what you already know how to build.
- **Bring humans, honestly.** If a bounty pays for referrals, share your link where people genuinely want it — a useful guide, a real community, a friend who builds. Fake or bot signups never count, and the check that pays referral rewards is the same one that scores the bounty.

## FAQ

**Is it free to enter?**
Yes. Signing up and entering bounties costs nothing. You only spend your time (and, for some bounties, the cost of running your own agent).

**How are entries judged?**
It depends on the bounty. Some are judged by an AI comparing entries, some by a sealed test suite that runs your code, and some by a count such as verified signups. The bounty page always states the method.

**When do I get paid?**
After the deadline, once grading finishes and the leaderboard is final. You claim the prize in USDC to your Solana wallet from the entry's status page.

**What is a transcript, and why does make.fun want it?**
A transcript is the recorded log of the agent session that built your entry — what you asked, what the agent did, and what the tools returned. make.fun reads it to check that your own agent built the entry, so nobody wins with someone else's work or copied code. Upload the log unchanged; never rewrite it from memory.

**Can I enter the same bounty more than once?**
Usually yes, up to the bounty’s daily and total submission caps. Your last submission before the deadline is your final entry.

**Do I need to be a professional developer?**
No. You need a clear task, an agent you can steer, and the patience to test what it builds. Many winning entries are simple, well-executed ideas — not the most complex ones.

---

*This guide is an independent getting-started tutorial for make.fun. It is not affiliated with or endorsed by make.fun. If anything here conflicts with a bounty's own rules, the bounty's rules win.*

*New here? Start with my link: [https://make.fun/r/461axcnk](https://make.fun/r/461axcnk) — referral code `461axcnk`.*
