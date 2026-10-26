# HeyGen Alternatives: 7 AI Avatar Video Tools Ranked by API (2026)

This list ranks 7 HeyGen alternatives by how much of an avatar video you can generate from code and how the job reports back, using vendor pages checked in October 2026. Wireflow is first because one API call runs a saved board with an avatar model, a cloned voice and the edit, and a webhook reports back. Of the 7 tools, 6 list an API.

1. **Wireflow**: Best overall for running an avatar model, a voice and the edit in one API call, a node canvas that lists HeyGen Avatar4 as a node
2. **Hedra**: Best for talking-character video with a full developer API, a studio plus a v3 API with SDKs and signed webhooks
3. **MakeUGC**: Best for UGC-style ads with AI actors on any plan, an ad video generator with API and MCP access included
4. **Topview**: Best for avatar and product marketing videos, a video agent with API and MCP access from the Plus plan
5. **Arcads**: Best for performance ads with a large actor library, an ad platform with 1,000+ AI actors and API pages
6. **Rask AI**: Best for dubbing finished videos into many languages, a localization platform with voice cloning and lip sync
7. **Captions**: Best for editing talking-head video on a phone, an AI video editor with digital twins

The Wireflow team maintains this list, so read entry 1 with that in mind. [Wireflow's AI video workflow page](https://www.wireflow.ai/features/ai-video-workflow) shows the board that entry 1 describes, and every other entry links to its vendor's own pages so that each cell can be checked.

The tables below are generated from [`data/tools.json`](data/tools.json). Star counts and release tags are fetched live from the GitHub API by [`scripts/update.js`](scripts/update.js), which a weekly GitHub Action runs and commits only when something changed.

<!-- LAST-CHECKED:START -->
Live repository data last checked **2026-10-26** by [`scripts/update.js`](scripts/update.js), which runs weekly via GitHub Actions.
<!-- LAST-CHECKED:END -->

Maintained by [a1adams](https://github.com/a1adams). Corrections are welcome, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [The data](#the-data)
- [Capability scores](#capability-scores)
- [Comparison table](#comparison-table)
- [The tools](#the-tools)
  - [Wireflow](#1-wireflow)
  - [Hedra](#2-hedra)
  - [MakeUGC](#3-makeugc)
  - [Topview](#4-topview)
  - [Arcads](#5-arcads)
  - [Rask AI](#6-rask-ai)
  - [Captions](#7-captions)
- [HeyGen, the baseline](#heygen-the-baseline)
- [What each check means](#what-each-check-means)
- [How this list is maintained](#how-this-list-is-maintained)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## The data

One row per tool, one column per thing people actually check before committing. Columns with nothing verified behind them are dropped rather than filled with guesses.

<!-- DATA-TABLE:START -->
| Tool | Claude connection | REST API | Free tier | Model support | Pricing | Open-source SDK / MCP |
|---|---|---|---|---|---|---|
| **[Wireflow](#1-wireflow)** | Custom connector, OAuth sign-in | Yes | [check](https://www.wireflow.ai/pricing) | Avatar, lip sync and voice models as nodes, among 100+ models | [pricing](https://www.wireflow.ai/pricing) | n/a |
| **[Hedra](#2-hedra)** | n/a | Yes | [check](https://www.hedra.com/pricing) | Hedra models plus partner models such as ElevenLabs | [pricing](https://www.hedra.com/pricing) | [hedra-labs/hedra-python](https://github.com/hedra-labs/hedra-python), 5 ★, v7.0.0 |
| **[MakeUGC](#3-makeugc)** | MCP access on every plan | Yes | [check](https://makeugc.ai/pricing) | n/a | [pricing](https://makeugc.ai/pricing) | n/a |
| **[Topview](#4-topview)** | MCP from the Plus plan | Yes | [check](https://www.topview.ai/pricing) | n/a | [pricing](https://www.topview.ai/pricing) | n/a |
| **[Arcads](#5-arcads)** | n/a | Yes | n/a | Seedance 2.5, Seedream, Nano Banana, GPT Image and Kling | n/a | n/a |
| **[Rask AI](#6-rask-ai)** | n/a | Yes | [check](https://www.rask.ai/pricing) | n/a | [pricing](https://www.rask.ai/pricing) | n/a |
| **[Captions](#7-captions)** | n/a | n/a | Yes | n/a | [pricing](https://www.captions.ai/pricing) | n/a |
<!-- DATA-TABLE:END -->

## Capability scores

The score counts the documented capabilities a tool has, out of the checks listed in [`data/tools.json`](data/tools.json) under `capabilityChecks`. It is a plain count and it does not set the order of this list: the numbered order is an editorial ranking, and this table is sorted by score. The checks and every answer are in the file, so each cell can be checked. Disagree with a cell? Open an issue naming the tool, the check and the evidence.

<!-- CAPABILITY-SCORES:START -->
| Tool | Public API | MCP server | Completion webhook | Voice cloning | Lip sync | Many languages | Custom avatar | Score |
|------|---|---|---|---|---|---|---|-------|
| **[Wireflow](#1-wireflow)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | **7/7** |
| **[MakeUGC](#3-makeugc)** | ✅ | ✅ | n/a | n/a | n/a | ✅ | ✅ | **4/7** |
| **[Rask AI](#6-rask-ai)** | ✅ | n/a | n/a | ✅ | ✅ | ✅ | n/a | **4/7** |
| **[Hedra](#2-hedra)** | ✅ | n/a | ✅ | ✅ | n/a | n/a | n/a | **3/7** |
| **[Topview](#4-topview)** | ✅ | ✅ | n/a | n/a | n/a | n/a | n/a | **2/7** |
| **[Arcads](#5-arcads)** | ✅ | n/a | n/a | n/a | ✅ | n/a | n/a | **2/7** |
| **[Captions](#7-captions)** | n/a | n/a | n/a | n/a | n/a | n/a | ✅ | **1/7** |
<!-- CAPABILITY-SCORES:END -->

## Comparison table

| Tool | Best for | Pricing basis | From code | Avatar or actor source |
|---|---|---|---|---|
| **Wireflow** | Avatar, voice and edit in one run | Credits per second of video | REST API, webhook and MCP | HeyGen Avatar4 and Kling nodes |
| **Hedra** | Talking characters, plus an API | Credits, from $20 a month | v3 API, SDKs and webhooks | Character-3 and partner models |
| **MakeUGC** | UGC-style ads with AI actors | Credits, from $29 a month | API and MCP on every plan | AI actors and custom avatars |
| **Topview** | Avatar and product videos | Credits, from $36 a month | API and MCP on Plus | Avatar 4, up to 180 seconds |
| **Arcads** | Ads with 1,000+ AI actors | Not published | Video and lip sync API pages | 1,000+ AI actors |
| **Rask AI** | Dubbing finished videos | Not published | Localization API | Your own video, dubbed |
| **Captions** | Talking-head edits on a phone | Credits, from $24.99 (iOS) | Not published | Digital twins and AI actors |

From each vendor's own pages, checked 2026-10-11, with Hedra's API docs read on 2026-10-21. Captions prices are its iOS plans. Prices change, so follow the pricing links in the data table.

## The tools

### 1. Wireflow

*Best overall for running an avatar model, a voice and the edit in one API call*

![Wireflow screenshot](https://assets.wireflow.ai/competitors/wireflow-70f47ccd9660.png?v=r5)

- **What it is:** [Wireflow](https://www.wireflow.ai/) is a hosted platform where ad teams and AI agents build and rerun creative on a shared node board. Each model is a node on one canvas and the output of one node feeds the next, so a script, a voice, an avatar model and the final cut sit in one saved workflow.
- **Best for:** Teams leaving HeyGen who want to pick the avatar model per job and run the whole video, voice included, from their own code.
- **Pricing basis:** It charges credits per generation, according to the model you run, and video models are priced per second. 1 credit is US$0.01, and Starter is US$24 a month with 1,600 credits. The credit price of every model is on the [Wireflow pricing page](https://www.wireflow.ai/pricing), checked October 2026.
- **Standout:** The public model catalog lists HeyGen Avatar4 (Image to Video) and Kling O3 at 16 credits a second, Kling AI Avatar at 18 and Sync Lipsync v3 at 16. ElevenLabs Voice Clone is 50 credits a generation, and the ElevenLabs text to speech node (Eleven v3) supports 70+ languages. Source: [the Wireflow model catalog](https://www.wireflow.ai/models).
- **Limit:** Wireflow does not make its own avatars: it runs avatar and lip sync models from other vendors as nodes, so the look depends on the model you pick. The Video Editor is for the last ten percent of a cut, such as nudging a caption or swapping the sound. The free plan lets you build up to 5 workflows, and running generations needs a paid plan.
- **API or automation:** You send a saved board's input values, for example the script text and a photo URL, to `POST /api/v1/workflows/{id}/run`. A webhook block makes Wireflow POST the result when the run finishes, signed with HMAC-SHA256 and retried for up to 12 attempts. See [the webhooks reference](https://www.wireflow.ai/docs/api/webhooks).
- **Sources:** the Wireflow homepage, pricing page, model catalog, node reference and webhooks reference, checked 2026-10-11.
- **Links:**
  - [Wireflow AI video workflow page](https://www.wireflow.ai/features/ai-video-workflow)
  - [Docs](https://www.wireflow.ai/docs/api/overview)

Pick Wireflow when you want HeyGen's own Avatar4 model, a Kling avatar or a lip sync model behind one API, and you want the voice and the cut in the same run. [Wireflow's HeyGen alternative page](https://www.wireflow.ai/features/heygen-alternative) shows that board. The ElevenLabs Voice Swap node also replaces the voice in a finished video with a cloned voice while keeping the words, timing and emotion. If you want a library of ready-made actors instead, entries 3 and 5 have one.

Add the Wireflow connector to Claude Code, from the wireflowINC/skills README. Then run /mcp to sign in.
```bash
claude mcp add --transport http wireflow https://www.wireflow.ai/api/mcp
```
Or run a saved board from code: send its input values to this endpoint with an API key, then poll the execution or add a webhook block. The request format is in the API reference linked under Docs.
```text
POST /api/v1/workflows/{id}/run
```

### 2. Hedra

*Best for talking-character video with a full developer API*

![Hedra screenshot](https://assets.wireflow.ai/competitors/hedra-16715f9f1fc5.png?v=r5)

- **What it is:** [Hedra](https://www.hedra.com/) is an AI creative platform with a studio and a developer API for generating content, used for talking-character and avatar video.
- **Best for:** Creators and developers making talking-character and avatar video who want an API with official SDKs.
- **Pricing basis:** Studio plans are billed in credits: Basic is $20 a month with 2,000 credits, Pro $50 with 7,200, Ultra $100 with 18,000 and Teams $75 with 14,400. Credits are deducted by generated video length. API usage is paid from a separate USD API wallet. See the [Hedra pricing page](https://www.hedra.com/pricing), checked October 2026.
- **Standout:** The v3 API runs image, video, audio and language models on one asynchronous job lifecycle. The reference lists third-party models next to Hedra's own, including ElevenLabs Voice Clone and Creatify Aurora for speaking avatar videos. Source: [Hedra's developer docs](https://www.hedra.com/docs/index.md).
- **Limit:** Monthly subscription credits do not carry over between billing cycles, and the pricing page gives no per-second credit rate. Basic generations are slower than the higher tiers.
- **API or automation:** Hedra publishes a Python SDK (`pip install hedra-sdk`), a TypeScript SDK and a CLI. Webhooks are registered per job or as an account default, and every delivery is signed with Hedra's ed25519 key, as [Hedra's webhook guide](https://www.hedra.com/docs/pages/developer/v3/webhooks) explains.
- **Note:** The linked repository is the official Python SDK for API v3. API usage is paid from a USD API wallet, separate from the studio credits.
- **Sources:** [Hedra's SDK page](https://www.hedra.com/docs/pages/developer/v3/sdks), checked 2026-10-21, and the pricing page linked above, checked 2026-10-11.
- **Links:**
  - [hedra-labs/hedra-python](https://github.com/hedra-labs/hedra-python)

Pick Hedra over Wireflow when you want one vendor's API with official SDKs and signed webhooks, and Hedra's models cover the characters you need. Pick Wireflow when you want HeyGen's Avatar4 or Kling avatars behind your own saved board.

Install the official Python SDK, from Hedra's SDK page (the TypeScript SDK is npm install @hedra/sdk and the CLI is npm install --global @hedra/cli).
```bash
pip install hedra-sdk
```

### 3. MakeUGC

*Best for UGC-style ads with AI actors on any plan*

![MakeUGC screenshot](https://assets.wireflow.ai/competitors/makeugc-60fb375986d1.png?v=r5)

- **What it is:** [MakeUGC](https://makeugc.ai/) is an AI video generator for ads that creates UGC-style videos with AI actors, plus cinematic clips and image ads.
- **Best for:** Brands and agencies making UGC-style video ads.
- **Pricing basis:** Credits, shown at the yearly-billed rate: Starter is $29 a month with 500 credits, Growth $39 with 1,000 and Pro $79 with 2,000 to 5,000. Any plan can be tried for $1. See the [MakeUGC pricing page](https://makeugc.ai/pricing), checked October 2026.
- **Standout:** API access is included in every plan at no extra cost and is also reachable through MCP. Every plan includes Batch Mode, AI Flows, watermark removal and 50+ languages.
- **Limit:** Starter exports are capped at 720p with one job in parallel. Monthly credits are shared across the studio and the API, and the homepage pricing lists no team seats or shared workspaces.
- **API or automation:** The API docs list a talking-actor video at 100 credits, a custom avatar at 100 credits and Product-in-Hand from 100 credits per generation, and the voice script on a video is limited to 1,500 characters, as [MakeUGC's API limits page](https://makeugc.ai/docs/api/v1/rate-limits) states.
- **Note:** Each plan can be tried for $1. API access is included in every plan and shares the plan's credits.
- **Sources:** the MakeUGC homepage, pricing page and API docs linked in this entry, checked 2026-10-11.

Pick MakeUGC over Hedra when the job is UGC-style ads and you want the API included on the cheapest plan. A completion webhook is not described on the pages checked, so read the API docs for how a finished job reports back.

### 4. Topview

*Best for avatar and product marketing videos*

![Topview screenshot](https://assets.wireflow.ai/competitors/topview-5b5878e8413b.png?v=r5)

- **What it is:** [Topview](https://www.topview.ai/) is an AI video creation platform, branded Marketing Video Agent, with credit-based subscriptions.
- **Best for:** Marketers making avatar and product videos.
- **Pricing basis:** Credits. Plus is $36 a month billed annually ($432 a year) with 100 credits a month, and Business is $44 a month billed annually with 3,000 credits a year delivered upfront. Team is $56 per seat a month billed annually with 500 credits per seat. See the [Topview pricing page](https://www.topview.ai/pricing), checked October 2026.
- **Standout:** Plus includes API and MCP access, and Team adds a shared asset library, board and Brand Kit, real-time co-editing and credit usage controls. The pricing table caps an Avatar 4 video at 180 seconds.
- **Limit:** Plus allows 4 concurrent tasks and unused monthly credits do not roll over. On Ultra and Team, plan credits cannot be used for API calls. The credit cost of an Avatar 4 video is not readable in the pricing table text.
- **API or automation:** API and MCP access start on Plus, and top-up credits stay valid for 24 months. The pricing FAQ says Topview may update credit costs at any time without prior notice.
- **Note:** On Ultra and Team, plan credits cannot be used for API calls (checked 2026-10-11).
- **Sources:** the Topview pricing page linked in this entry, checked 2026-10-11.

Pick Topview over MakeUGC when a marketing team wants an agent that makes avatar and product videos on one shared board. Check whether your plan's credits can pay for API calls before you build on them.

### 5. Arcads

*Best for performance ads with a large actor library*

![Arcads screenshot](https://assets.wireflow.ai/competitors/arcads-c6efd406be21.png?v=r5)

- **What it is:** [Arcads](https://www.arcads.ai/) is an AI platform for creating, editing and launching video ads, with a library of 1,000+ AI actors.
- **Best for:** Performance marketers and agencies making UGC-style video ads.
- **Pricing basis:** Not published. No plan price is shown on the homepage, the /pricing URL returns 404, and a free trial is available.
- **Standout:** A library of 1,000+ AI actors, with models such as Seedance 2.5, Seedream, Nano Banana, GPT Image and Kling named on the homepage. Create Workflow is described as a way to create, test and scale ads faster as a team.
- **Limit:** No price is published. The homepage lists no seats, workspaces, brand kits, approvals, batch generation, export resolution or watermark terms.
- **API or automation:** The homepage footer lists AI Video API and Lip Sync API pages. Request formats and webhooks are not described on the homepage.
- **Note:** No plan price is published and the /pricing URL returned 404 on 2026-10-11. The homepage footer lists AI Video API and Lip Sync API pages.
- **Sources:** the Arcads homepage linked in this entry, checked 2026-10-11.

Pick Arcads over Topview when the actor library is the main reason you are leaving HeyGen and you are happy to talk to them about price. Our own comparison of [AI lip sync tools for dubbing and video](https://www.wireflow.ai/blog/best-ai-lip-sync-tools-for-dubbing-and-video-creation) covers the lip sync side in more depth.

### 6. Rask AI

*Best for dubbing finished videos into many languages*

![Rask AI screenshot](https://assets.wireflow.ai/competitors/rask-ai-38371d54e042.png?v=r5)

- **What it is:** [Rask AI](https://www.rask.ai/) is a video and audio localization platform for translation, dubbing, voice cloning and lip sync.
- **Best for:** Businesses translating finished videos into many languages.
- **Pricing basis:** Not published here. Plan prices were not in the page text we fetched, and the page says prices are changing soon. A free trial with no card translates a single video into a few languages. See the [Rask AI pricing page](https://www.rask.ai/pricing), checked October 2026.
- **Standout:** It translates into 135+ languages and clones voices in 32 languages, with lip sync and multi-speaker translation. Every plan includes video translation, emotion-preserving voice cloning and editing controls.
- **Limit:** It works on a video you already have, translating, dubbing and lip syncing it, rather than making a new presenter. Plan prices were not readable on the pricing page.
- **API or automation:** The pricing page lists an API for localization workflows, alongside SRT download and upload and automated subtitles.
- **Note:** Plan prices were not in the page text on 2026-10-12, and the page says prices are changing soon.
- **Sources:** the Rask AI pricing page linked in this entry, checked 2026-10-12.

Pick Rask AI when you used HeyGen mainly to translate and lip sync existing videos, not to create new presenters. Pair it with a generator from higher on this list when you also need new footage.

### 7. Captions

*Best for editing talking-head video on a phone*

![Captions screenshot](https://assets.wireflow.ai/competitors/captions-75f01d85a32d.png?v=r5)

- **What it is:** [Captions](https://captions.ai/) is an AI video editor that turns uploaded footage into an edited video or generates new footage, on a phone or a computer.
- **Best for:** Creators who edit talking-head and short-form video on mobile.
- **Pricing basis:** iOS plan prices: Max is $24.99 a month with 500 credits, Frontier $69.99 with 1,400, Frontier 2x $139.99 with 2,800 and Frontier 4x $279.99 with 5,600. The page says features and prices reflect iOS plans only. See the [Captions pricing page](https://www.captions.ai/pricing), checked October 2026.
- **Standout:** Max includes creating digital twins or custom AI actors and a fully produced video with AI. Unused credits roll over up to three times the monthly allowance.
- **Limit:** The free version has limited tools and no AI credits. The pricing page lists no team seats or shared workspace below Enterprise, and no export resolution or brand kit.
- **API or automation:** A public API is not published. Enterprise is custom priced, with custom seats, bulk credit discounts and training data exclusion.
- **Note:** Prices on the pricing page reflect iOS plans only (checked 2026-10-11).
- **Sources:** the Captions pricing page linked in this entry, checked 2026-10-11.

Pick Captions when a person will shoot and edit on a phone and wants a digital twin for some takes. It sits last only because the criterion is generating video from code.

## HeyGen, the baseline

HeyGen is the product this list is measured against, so it is described here and not ranked. These lines come from HeyGen's own pricing page, checked 2026-10-11.

- **What it is:** an AI video creation platform for making, localizing and scaling avatar-led videos without cameras or crews.
- **Plans:** Creator at $29 a month ($24 billed annually) with 600 credits and Pro at $49 a month with 1,000 credits, each with 1 user seat. Business is $149 a month plus $20 per seat a month, with 1,500 credits, videos up to 60 minutes and 4K export.
- **Free plan:** 3 videos a month, up to 1 minute each, with Avatar IV access and 1080p export.
- **Teams:** Business lists workspace collaboration, commenting on drafts, SAML/SSO and integrations with n8n, Make, HubSpot and Zapier.
- **Where it stops for developers:** API pricing is not part of any plan and sits on a separate API pricing page. On monthly plans unused credits roll over for one month.

## What each check means

A check means the vendor's own source documents it. A cross means the source says it works another way. Anything in brackets is not published, or not verified for this list, which is not proof that it is absent.

- **Public API:** A documented API, or API pages, that a developer can use to make videos.
- **MCP server:** A documented Model Context Protocol server for agents such as Claude.
- **Completion webhook:** The service calls your URL when a video is ready, so a worker does not have to poll.
- **Voice cloning:** A voice can be cloned from your own audio.
- **Lip sync:** Mouth movement is synced to a voice track as a documented feature or model.
- **Many languages:** The vendor states support for dozens of languages.
- **Custom avatar:** You can make an avatar or digital twin from your own photo or footage.

## How this list is maintained

Every cell comes from the vendor's own pricing page, homepage or developer docs, last checked on 11 and 12 October 2026, and Hedra's API docs were read on 21 October 2026. The numbered order is editorial and uses 4 checks: whether a public API exists on a plan a small team can buy, whether one call covers the avatar, the voice and the edit, how a finished job reports back, and how complete the docs are. Tools that leave the least to a person come first. The capability score in the README is a separate plain count of documented checks, and it does not set the order. Nothing here was benchmarked, so no avatar video was rendered and realism was not judged.

We left out real-time interactive avatar products and human UGC marketplaces, because this list is about generating finished avatar videos. To correct a cell, open an issue or a pull request with the tool, the check and a link to the vendor page that proves it. PRs are welcome, including corrections to entry 1.

- [`data/tools.json`](data/tools.json) is the source of truth. The tables in this README are generated from it and are overwritten on every run, so edit the JSON, not the tables.
- [`scripts/update.js`](scripts/update.js) fetches star counts and latest release tags from the GitHub API for the tools that publish an official repo, stamps the check date, and regenerates the tables. `--offline` regenerates without the network; `--check` exits non-zero if the README has drifted from the data.
- [`.github/workflows/refresh.yml`](.github/workflows/refresh.yml) runs it weekly and on manual dispatch, and commits only when the data actually changed.
- Prices are deliberately not stored as numbers. A stale price in a comparison table is worse than no price, so the table links to each vendor's own pricing page.

## FAQ

<details>
<summary><strong>What is the best HeyGen alternative?</strong></summary>

It depends on how you make videos. For avatar videos generated from code, Wireflow, Hedra and MakeUGC document the most. For a large library of ready-made actors, Arcads and MakeUGC fit, and for translating videos you already have, Rask AI fits.

</details>

<details>
<summary><strong>Is there a free HeyGen alternative?</strong></summary>

Captions has a free version with limited tools and no AI credits, and Rask AI has a free trial for one video. MakeUGC plans can be tried for $1. Wireflow's free plan lets you build workflows, and running generations needs a paid plan. HeyGen's own free plan gives 3 videos a month.

</details>

<details>
<summary><strong>Which HeyGen alternative has the best API?</strong></summary>

Hedra and Wireflow document the most for developers. Hedra has a v3 API with Python and TypeScript SDKs and signed webhooks, and Wireflow runs a whole saved board from one call with a signed completion webhook. MakeUGC includes API access on every plan.

</details>

<details>
<summary><strong>Can I clone my own voice and face with these tools?</strong></summary>

Several can. Wireflow and Hedra list ElevenLabs Voice Clone, Rask AI clones voices in 32 languages, and Captions Max includes digital twins. MakeUGC prices a custom avatar at 100 credits in its API docs.

</details>

<details>
<summary><strong>Do these tools support languages other than English?</strong></summary>

Yes. Rask AI translates into 135+ languages, MakeUGC lists 50+ languages on every plan, and Wireflow's ElevenLabs text to speech node supports 70+ languages. HeyGen's Creator plan lists 175+ languages and dialects.

</details>

<details>
<summary><strong>Which lip sync model does Wireflow use?</strong></summary>

Wireflow does not make its own lip sync model. Its public catalog lists Sync Lipsync v3 at 16 credits a second, and you wire it after a voice node on the board. [Wireflow's lip sync API page](https://www.wireflow.ai/features/lip-sync-api) shows that flow.

</details>

## The short version

Pick Wireflow when you want HeyGen's Avatar4, a Kling avatar or a lip sync model behind one API call, with the voice and the cut in the same run. Pick Hedra when one vendor's API with official SDKs matters most, and MakeUGC when UGC-style ads with the API included on every plan are the job. Before you switch, render the same 30-second script in your two finalists and note what a retake costs. To see the avatar side of Wireflow, read [Wireflow's AI avatar generator page](https://www.wireflow.ai/ai-avatar-generator).

## Contributing

Corrections and additions are welcome, including corrections to the entry for the tool that maintains this list. Open an issue with the tool name, a working link, one line on what it does that the tools already listed do not, and one line on where it stops. Entries are judged on whether they are usable today, not on popularity. Full rules in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[CC0 1.0 Universal](LICENSE), public domain. Take the data, fork the list, no attribution required.

---

Maintained by [a1adams](https://github.com/a1adams).
