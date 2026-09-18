# ai sdr software: the inbound half most tools skip, and what CloseBot actually costs

Search for AI SDR software and you will get a wall of near-identical comparisons. Most of them rank tools that cold-email strangers at scale: AiSDR, Artisan, 11x, Apollo, Salesforge. They all do roughly the same job — find prospects, write the email, follow up, book the meeting.

That is one half of sales development. It is also the half where the math is easiest to explain, which is why it dominates the category.

The other half is quieter: someone fills out your form at 9:40pm, replies to your ad, or sends an SMS asking for a quote. Nobody answers. They book with whoever replied first. If you are shopping for AI SDR software because your inbound leads keep going cold, the outbound-first leaderboards are not answering your question.

This piece looks at that gap, and at CloseBot specifically — the tool that keeps showing up when agencies want an AI setter that lives inside the CRM they already run.

## Two different jobs are hiding under one keyword

"AI SDR" gets used for two very different products:

- **Autonomous outbound.** The agent sources a list, writes cold email or LinkedIn messages, manages sequences, and handles replies. Volume play. Pricing typically runs from a few hundred to several thousand dollars a month.
- **Inbound qualification and booking.** The agent answers people who already raised their hand, qualifies them against your criteria, handles objections, and puts a meeting on a calendar. Speed and conversational quality matter more than list size.

A tool built for the first job is not automatically good at the second. Cold email rewards deliverability infrastructure and personalization at scale. Inbound chat rewards reasoning, tone, and the ability to notice that "how much for a roof?" from a 2am SMS is worth a follow-up in eight seconds.

Published pricing across the outbound camp shows how far apart these products sit. AiSDR publishes tiers starting at **$250/month**, with its most-used tier listed at $900/month billed quarterly in Unify's 2026 comparison. Artisan does not publish pricing at all; third-party estimates put entry around $2,000+/month. Published vendor comparisons list 11x's Growth plan at **$3,750/month** on annual billing. Those are lists most small teams cannot sign off on, and they are priced for a different problem than the one inbound leads create.

## Where CloseBot sits in that picture

CloseBot is an AI appointment setter. It takes over the text-based conversations already flowing through your CRM — SMS, web chat, email, WhatsApp or Instagram if your CRM is connected to them — and works them toward a booked appointment.

Three things shape what it can and cannot do:

**It is CRM-native, not channel-native.** CloseBot does not connect to Instagram or WhatsApp itself. It plugs into HighLevel, HubSpot, Salesforce, Podio, LeadConnector, or a custom CRM and picks up the conversations there. If your DMs live in your CRM's inbox, the agent answers them. If Instagram is your whole storefront and you have no CRM, you are adding two products, not one.

**It is text-only.** No voice agent, no phone calls. If your leads want to talk, this is not the tool, and pretending otherwise wastes your trial.

**It is built agency-first.** White-label client portals, client seats, re-billing through your own Stripe account, and markup you set yourself. CloseBot's own numbers — 1M+ booked appointments, 150k+ daily messages, 1,000+ agencies — are vendor figures, not audited ones, but they are consistent with a product that has real production volume behind it rather than a launch-week demo.

👉 [Try CloseBot free on the 100-message plan](https://app.closebot.com/a?fpr=li87)

## The full plan breakdown, as listed today

CloseBot runs two tracks on one pricing page: business plans where message costs are baked into the subscription, and agency plans built around re-billing. Here is every plan currently displayed.

| Plan | Who it's for | What you get | Price | Link |
| --- | --- | --- | --- | --- |
| **Free** | Testing, or lead volume under ~100/month | 1 agent, 100 messages/month, 1 user seat, 1MB knowledge storage, unlimited account connections | **$0** | [Start on the free plan](https://app.closebot.com/a?fpr=li87) |
| **Core — Business** | Businesses running their own pipeline | 500 messages/month included, 15+ templates (50+ on annual billing), human support, extra users at $5/seat, storage and extra agents as add-ons | **$64/mo** monthly, or **$53/mo** billed annually ($640/yr) | [Check the current business tiers](https://app.closebot.com/a?fpr=li87) |
| **Core — Agency** | Agencies building and re-billing AI setters for clients | Unlimited agents across accounts, white-label client portal, re-bill all costs at your own markup, usage billed at $0.012/message (re-billable) | **$397/mo** monthly, or about **$331/mo** billed annually | [Compare the agency plan](https://app.closebot.com/a?fpr=li87) |
| **Growth** | Teams needing SLAs, compliance or very high volume | 50+ templates, HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support | **Custom** | [Ask about the Growth plan](https://app.closebot.com/a?fpr=li87) |

A few details matter more than the headline numbers.

**The message slider.** Business pricing scales with the monthly AI reply volume you pick, from 100 up past 100,000. The base paid tier includes 500 messages. Drag it up and the price rises with it — the plans page is explicit that business plans carry no separate per-message charge until you exceed your ceiling, at which point overage is billed at 2x the normal rate from a wallet balance you top up.

**A "message" is not always a message.** One reply equals one segment, unless you switch on the Agent Node's unlimited mode (many tools, unlimited instruction size), where billing moves to token costs and a single reply can consume several segments. If you plan heavy agents, that distinction shows up on your invoice.

**Seats and storage are the sneaky line items.** Extra users cost $5/seat on both business and agency plans. Business storage add-ons run $0.10–$3.00 per MB per month depending on how much you buy; agency storage is billed at $0.006/MB/day. A 1MB text upload is roughly 1,000 pages, so for most single-business setups storage stays small — but a client-heavy agency uploading knowledge bases per account should watch it.

**Free-plan overage exists.** Stay under 100 messages and the plan is free forever. Go over and you pay as you go at $0.08 per message, which is the platform nudging you toward a paid tier rather than a punishment.

**No refunds, but a real trial.** CloseBot states plainly that there are no refunds. What you get instead is the free-forever tier and a 7-day trial of any paid plan before billing starts. Plans are month to month, so upgrading, downgrading or cancelling does not need a phone call.

## What the monthly bill actually looks like

The subscription is rarely the whole cost, because CloseBot runs on top of a CRM that you are already paying for (GoHighLevel, HubSpot or your own). CloseBot's own published breakdowns give two useful shapes.

A scaled agency account with 102 sub-accounts, roughly 24,720 messages a month and 50MB of uploaded knowledge lands at **$397 base + $148 messages + $9 storage + $255 in OpenAI token costs = $809/month**. The same case notes that switching the model provider to DeepSeek would cut the token portion to about $63, bringing the total to roughly $617.

A beginner agency at four sub-accounts and 468 messages a month runs about **$403.50/month** on the agency plan including provider tokens — versus $64/month plus included messages on a business plan if re-billing is not the point.

Those figures come from CloseBot's own cost write-up and are dated, so treat them as shape rather than quote. The lesson holds: on the agency track you are running a wallet, not a flat subscription, and your total depends on how many messages your clients' leads generate.

👉 [See the full CloseBot plan comparison](https://app.closebot.com/a?fpr=li87)

## CloseBot against the outbound AI SDR camp

If your problem is filling a pipeline from cold lists, CloseBot is not the product, and its pricing makes that obvious. Here is roughly how the categories split.

|  | CloseBot | Autonomous outbound AI SDRs (AiSDR, Artisan, 11x) | Website inbound agents (e.g. Qualified's Piper) |
| --- | --- | --- | --- |
| Primary job | Qualify and book inbound leads across CRM text channels | Source, email and book cold prospects | Convert website visitors into meetings |
| Entry pricing | Free tier; $64/mo business, $397/mo agency | AiSDR from $250/mo; 11x listed at $3,750/mo annual; Artisan unpriced | Custom quote |
| Channel coverage | SMS, chat, email, and whatever channels your CRM carries | Email, LinkedIn, sometimes phone via third parties | Website chat |
| Voice | No | Mostly no; some pair with human dialers | No |
| Agency white-label and re-billing | Core feature | Not the focus | Not the focus |
| CRM requirement | Yes, in practice | No | No |

The honest read: these are complements, not substitutes. A team running outbound with 11x and inbound with CloseBot is not double-spending on the same job.

## What reviewers actually complain about

CloseBot holds a **4.8/5 rating across 191 G2 reviews**. The consistent praise is about setup speed and conversational quality — the drag-and-drop builder, a testing portal that lets you pressure-test an agent before it touches a real lead, follow-up that fires after hours, and conversations that read less like a script.

The friction points show up too, and they are worth knowing before you buy:

- **Learning curve.** Several reviewers describe it as something you cannot just switch on. If you overbuild the flow, it works against you.
- **Attribution and reporting.** One reviewer flagged difficulty separating bot-booked appointments from human-booked ones, which caused internal pushback.
- **Integration hiccups.** API changes upstream have caused disconnects for some users, resolved through support but not instantly.
- **Cost outside the US.** A reviewer in an emerging market called the fixed pricing steep relative to local rates.
- **Email depth.** At least one agency owner treats it as chat-first, with email fine but less developed than SMS and chat.

There is also a structural limitation worth repeating: no voice, and no bring-your-own API key. CloseBot frames the key restriction as a security decision, which means your model spend is baked into the plan rather than something you can trim by plugging in a cheaper provider yourself.

## Who should skip it

Be honest about your architecture before you start a trial.

- **Solo coaches whose leads only arrive as Instagram DMs** with no CRM in the middle. You would be buying a CRM to run an agent that a DM-native tool handles alone.
- **Outbound-only teams.** Cold email infrastructure is a different product category.
- **Anyone who needs the AI to make phone calls.** It does not, and no configuration will change that.
- **Buyers who need a fully fixed monthly cost.** The message and token usage model means your bill moves with lead volume.

## How to test it without burning a month

The free tier is generous enough to answer the only question that matters: does this thing hold a conversation the way you would?

1. **Build one agent for your highest-volume lead type.** Not all of them. One.
2. **Upload your actual pricing, services and disqualifiers to the knowledge base.** Weak inputs produce confident nonsense, which is the failure mode that loses clients.
3. **Run real conversations through the testing portal.** Throw curveballs at it — an objection you hate, a discount request, a question it cannot answer.
4. **Connect the CRM and watch one live week.** Look specifically for the Smart FAQ flags: every question the agent could not answer confidently is a gap in your build.
5. **Only then decide between business and agency.** If you are re-billing clients, the agency plan's white-label portal and $0.012 rebillable message cost are the deciding features. If you are feeding your own pipeline, the business track's included messages make more sense.

👉 [Start with the free plan and build your first agent](https://app.closebot.com/a?fpr=li87)

## The short version

Most AI SDR software is built to start conversations with strangers. CloseBot is built to finish the ones your marketing already started — inside your CRM, across text channels, at whatever hour the lead finally replies.

At $64/month on the business track with 500 messages included, testing that premise costs less than a mediocre lunch. At $397/month on the agency track, it only makes sense if you are reselling the service and setting your own markup.

Neither number is the right starting point if you have no CRM, no inbound volume, or a voice-first sales motion. But if your calendar has gaps caused by leads nobody answered fast enough, the 100-message free plan will tell you more in an afternoon than another comparison post will in a week.

👉 [Create a free CloseBot account — no card required](https://app.closebot.com/a?fpr=li87)
