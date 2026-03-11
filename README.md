# Claude Copy

A Claude Code plugin with 23 battle-tested direct-response copywriting skills, built on the Prometheus library.

## Skills

| Command | Description |
|---------|-------------|
| `/claude-copy:ad` | Write paid ad copy (Facebook, Instagram, YouTube, Google) using Alex Hormozi's Chunking system — 50 hooks, 10 frameworks, Kaleidoscope remixing |
| `/claude-copy:webinar` | Write webinar scripts and sales presentations using Jason Fladlien's One to Many system — intro, content, Half-Dozen Yeses transition, staged close |
| `/claude-copy:landing-page` | Write complete landing page copy — above-the-fold, full body, offer stack, CTA, trust elements, and P.S. with Awareness Ladder targeting |
| `/claude-copy:beto` | Master orchestrator — analyzes your brief and builds a copy battle plan using the right skills in the right order |
| `/claude-copy:research` | Automated niche research across Reddit, Amazon, YouTube, Meta Ads, and competitors to find exact audience language |
| `/claude-copy:headline` | Write and evaluate headlines using frameworks from Ogilvy, Schwartz, Hopkins, Halbert, Kennedy, and Makepeace |
| `/claude-copy:lead` | Write high-converting leads (opening paragraphs) matched to audience awareness level |
| `/claude-copy:structure` | Architect a complete copy piece — landing page, sales letter, VSL — with 18-step logical sequence |
| `/claude-copy:voice` | Define and maintain brand voice — tone, personality, conversational writing adapted to your audience |
| `/claude-copy:emotion` | Identify and apply the right emotional drivers for each audience and product |
| `/claude-copy:benefits` | Transform features into emotional and practical benefits using the BBQ vs. Steak technique |
| `/claude-copy:bullets` | Write persuasive bullets and subheads using the 4 U's framework and 4 proven structures |
| `/claude-copy:offer` | Build an irresistible offer — price anchoring, value stack, bonuses, guarantee, urgency |
| `/claude-copy:objection` | Anticipate and destroy objections using the Judo technique and proof |
| `/claude-copy:cta` | Write calls-to-action that convert for landing pages, emails, ads, and sales letters |
| `/claude-copy:story` | Write sales stories and narratives using Hero Journey, ABT, and "They Laughed When..." |
| `/claude-copy:email` | Write complete email sequences — launch, nurture, cart abandonment, teleseminar |
| `/claude-copy:credibility` | Build credibility using the 4-Legged Stool Test — big idea, promise with argument, broad proof, supplier trust |
| `/claude-copy:proof` | Present concrete, convincing proof to back up promises and eliminate skepticism |
| `/claude-copy:curiosity` | Create and maintain curiosity using the slippery slide effect, open loops, and intrigue seeds |
| `/claude-copy:testimonial` | Collect, format, and position testimonials for maximum credibility |
| `/claude-copy:review` | Review and edit copy using the CUB framework (Confusing, Unbelievable, Boring) |
| `/claude-copy:testing` | Plan and interpret A/B tests to maximize conversion — always targeting the weakest link first |

## Installation

### Option 1: Load for a single session

```bash
claude --plugin-dir /path/to/claude-copy
```

### Option 2: Install globally (always loaded)

Add to `~/.claude/settings.json`:

```json
{
  "plugins": [
    "/path/to/claude-copy"
  ]
}
```

### Option 3: Clone and install

```bash
git clone https://github.com/igoroliveirg/claude-copy.git
```

Then add the cloned path to your `~/.claude/settings.json`.

## Usage

Start with `/claude-copy:beto` if you have a complete copy task — it will analyze your brief and tell you exactly which skills to run and in what order.

For single elements, invoke the specific skill directly:

```
/claude-copy:headline landing page for a weight loss supplement targeting women 40+
/claude-copy:offer product: online investment course, price: $497
/claude-copy:email 5-email launch sequence for a productivity SaaS
```

## The Beto Orchestrator

`/claude-copy:beto` is the master skill that knows all 19 other skills and when to use each one. Give it a copy brief and it returns:

- **Brief diagnosis** — type of piece, audience, awareness level, price
- **Copy battle plan** — skills in execution order with instructions for each
- **Critical skills** — what cannot be skipped
- **Recommended depth** — short / medium / long / maximum

## Source

Built on the Prometheus copywriting library, drawing from:
- Adweek Copywriting Manual
- Breakthrough Advertising (Gene Schwartz)
- Big Black Book series
- Quick-Start Copywriting System
- $100M Playbook: GOATed Ads (Alex Hormozi)
- ACQ Advertising Handbook (Alex Hormozi)
- One to Many: The Secrets to Webinar Success (Jason Fladlien)
- Landing Page Optimization (Tim Ash, Maura Ginty, Rich Page)
- The Conversion Code (Chris Smith)
- Principles from Ogilvy, Halbert, Kennedy, Makepeace, Bencivenga, Hopkins, and Schwab
