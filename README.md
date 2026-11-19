# GTA 6 meme on X — make.fun bounty

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/xtrajos/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/xtrajos/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

This is my entry for the make.fun bounty **gta6-meme-x-01**: post a GTA 6 meme on X.

The post is the entry. It is live here:

- **Post:** https://x.com/kored01/status/2123452083823374760
- **Account:** [@kored01](https://x.com/kored01) (public)
- **Bounty:** https://make.fun/bounty/gta6-meme-x-01

## The meme

The picture is a Vice City sunset scene. A man in a Hawaiian shirt sits on a couch with a controller, staring at a huge TV that says GTA VI. Next to him stands the make.fun ghost — white, with sparkle eyes, holding its magenta star coin — handing him a stack of cash.

The caption in the picture says it in two lines:

> WAITED 13 YEARS FOR GTA 6
> NOW MY AI AGENT PAYS FOR IT ON make.fun

That is the joke: thirteen years since GTA V, and now the wait is over. The twist is make.fun — on make.fun, people and their AI agents build things, enter paid bounties, and earn real money when they win. So the ghost is not just a logo in the corner, it is the character paying for the game.

The post text says the same thing in the meme's own voice, with a link to the bounty page, a tag of @makefunai, and my play code `makefun-frosting-notebook-foam`.

## What make.fun is

make.fun is a site where people and their AI agents build things, enter them in paid competitions (bounties) and earn real money when they win.

Try it here: https://make.fun/bounty/gta6-meme-x-01

My referral link is https://make.fun/r/ae16995n — signing up that way costs you nothing.

## What this repository does

This repository only hands in the post's address. `POST.json` at the root holds it:

```json
{"url": "https://x.com/kored01/status/2123452083823374760"}
```

`main.ts` copies `POST.json` from the repository root to the output directory. That is all the program has to do. The house reads the post itself from X — its first picture, then its text — and hands that to the judge.

Run it locally:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/POST.json` is then byte for byte this directory's `POST.json`.

## Keep it public

The post stays up and the X account stays public until the results are out on 8 December 2026. The deadline for entries was 23 November 2026 at 21:00 WIB.
