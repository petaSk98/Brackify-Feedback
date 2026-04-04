# Brackify

A bracket-style voting tournament app for Reddit. Communities vote head-to-head to crown a winner.

---

## What is Brackify?

Brackify lets you run elimination tournaments directly inside Reddit posts. Think of it like a sports playoff bracket, but for anything your community wants to vote on — best fan art, favorite memes, top movie picks, you name it.

An organizer creates a tournament with a set of entries (images or text), and the community decides the winner through a series of one-on-one votes. Two entries face off, the community picks a favorite, and the winner advances to the next round. This continues until one entry remains — the champion.

---

## Features at a Glance

- **Image and text tournaments** — upload images, paste URLs, or create styled text entries
- **2 to 64 entries** — works with any count, even or odd
- **Community submissions** — let your community contribute entries before the tournament starts
- **Customizable rules** — round duration, vote thresholds, voter requirements
- **Live bracket** — interactive, zoomable bracket with color-coded paths
- **Feed preview** — see matchups and results without opening the post
- **Notifications** — get notified when a new round starts or the winner is announced
- **Everything is transparent** — all changes to entries are documented in public comments
- **Mobile-friendly** — responsive design with compact bracket layout on small screens

---

## How Voting Works

1. Open the tournament post on Reddit.
2. You'll see a landing screen with the title, description, and current round status.
3. Tap **"Vote"** to enter the voting view.
4. Pick your favorite by tapping on it, then confirm.
5. Move on to the next matchup or explore the bracket.

You can zoom into images during voting — pinch to zoom on mobile, or Ctrl + scroll on desktop.

**Your vote is final** — once you confirm, it cannot be changed.

### When a round ends

Each matchup runs for a set time (1–24 hours, chosen by the organizer). When time runs out, the entry with more votes advances. If the organizer set a minimum vote count, the round can also end early once every matchup reaches it.

**Ties:** If both entries get the same number of votes, the one with a better overall track record in the tournament advances. In the first round (where there's no history yet), a coin flip decides. In the final, a tie means both entries are crowned co-champions. Tied matchups are marked in the bracket.

**Matchup shuffling:** From round 2 onward, winners are re-paired so that the strongest performers face the weakest ones. This keeps the most exciting matchups for the later rounds — similar to how playoff brackets work in sports.

### After you vote

Once you've voted on all matchups in the current round, you'll see a recap of your picks — including which ones are leading and whether your vote flipped the lead. Then you're taken to the bracket view to follow the rest of the round.

---

## Creating a Tournament

Any subreddit member can create a tournament:

1. **Create a new post** — Use the subreddit menu and select "Create a new post" under Brackify. You'll be asked for a tournament name — this becomes part of the post title. You can also leave it blank and name it later. The post may take a minute or two to appear in the feed.
2. **Set title and description** — Optionally add a description and a cover image. The title can be styled with a font preset, color, and size.
3. **Add entries** — Upload images (up to 20 MB, automatically resized), paste image URLs, or add text entries. You need at least 2 and can add up to 64. If there's an odd number, one entry gets a free pass in the first round.
4. **Choose who can submit** — Add all entries yourself, or allow community members to contribute (see [Community Submissions](#community-submissions)).
5. **Configure rules** — Set round duration, vote threshold, and voter requirements. Settings save automatically as you go.
6. **Start the tournament** — Review the tournament announcement that will be posted as a comment, then confirm. The bracket is generated and voting begins.

### Customization options

| Option | Description |
|---|---|
| **Per-round duration** | Set a different duration for each round. The final round automatically gets 50% extra time (up to 24h). |
| **Minimum votes** | Set a minimum number of votes each matchup needs. Once every matchup reaches it, the round ends early. |
| **Voter requirements** | Restrict voting by account age, karma, or verified email. |
| **Use filename as entry name** | Uploaded images automatically get their filename as their display name (e.g. `sunset_beach.jpg` → "sunset_beach"). |
| **Default text style** | Set a default font, look preset, colors, and gradient for text entries. Individual entries can override it. |

### Text entry styling

Text entries support visual customization: choose from several font and color presets, add gradients, or pick a custom background color. You can set a default style for all text entries or customize each one individually.

---

## Community Submissions

When the organizer enables community mode, everyone can contribute entries before the tournament starts.

### The basics

- The organizer sets how many entries each user can submit (1–20).
- Submissions close at 64 total entries, when the organizer pauses them, or when the tournament starts.
- All entries start as **private drafts** — only you can see yours. You can freely add, remove, rename, and rearrange drafts before publishing.

### Publishing

When you're ready, tap **"Publish my entries"**. This posts a Reddit comment under the tournament as a public record of your contribution. You can include a personal message.

Before publishing, the app checks for duplicate names and available space. All your drafts are published at once — you can't pick and choose which ones to publish.

**Important:** If you close the page without publishing, your drafts are saved — but unpublished drafts are removed when the tournament starts.

### Editing published entries

After publishing, you can still make changes — each one requires a comment so it's publicly documented:

- **Add more** — new entries start as drafts, then publish as before.
- **Rename** — edit inline, confirm via comment dialog. Blocked if the name is already taken.
- **Remove** — tap delete, confirm via comment dialog.

### The organizer's role

The organizer submits entries the same way as everyone else (drafts → publish → comment). In addition, the organizer can:

- Remove or rename any community entry (documented as a reply under the submitter's comment).
- **Pause community changes** — temporarily freeze all community editing while keeping existing entries.
- The organizer has no per-user submission limit but is still subject to the 64-entry cap.

### Switching modes

The organizer can switch from organizer-only to community mode at any time. Once any entry is published, switching back is blocked because published entries are tied to public comments. Use the pause feature instead to temporarily stop new submissions.

---

## Exploring the Tournament

### Bracket

A visual tree of the entire tournament. Pan and zoom to explore it. On mobile, the bracket switches to a compact vertical layout. You can also manually toggle between layouts.

Tap any matchup to see full details — vote counts, the winner, and your pick. Navigate between matchups with arrows, keyboard, or swipe.

**Color coding:**
- **Cyan** — your votes and picked path
- **Green** — current live round (with pulse indicator)
- **Purple** — matchup winners and leading entries
- **Gold** — the champion's path

**Indicators:** closest match of the round (🎯), most dominant win of the round (🔥), "Tie!" badge for equal votes, "Close match!" badge for tight margins, BYE badge, leading pulse animation, and a toggleable legend explaining all symbols. Each round awards at most one 🎯 and one 🔥.

Between rounds, a ceremony overlay announces the next round and recaps how many of your picks advanced.

### Ranking

A leaderboard of all entries ranked by how far they advanced in the bracket. Entries eliminated in the same round are sorted by total votes received. Tap any entry to see its full tournament journey.

### Winner screen

When the tournament ends, the champion is announced with a celebration. You can view the final bracket, check rankings, and **share your picks** as a Reddit comment — including your accuracy and whether you picked the champion.

The winner card shows the final score with a description ("Photo finish", "Close match", "Clear win", or "Landslide"), who submitted the entry, and tournament stats.

If the final ends in a tie, both entries are crowned co-champions. The entry with the stronger tournament record is featured as the primary winner.

### Feed preview

You don't have to open every post to follow along. Brackify shows a live preview in the Reddit feed:

- **Before you vote** — spoiler-free teaser with current matchups (no vote counts).
- **After you vote** — recap with animated vote count reveals and highlighted winners.
- **Finished tournaments** — the champion's bracket journey, round by round.

The preview also shows the current round and time remaining.

---

## Notifications and Comments

### Notifications

Notifications are off by default. After you finish voting in a round, you'll be offered the option to subscribe. You can also toggle them anytime with the bell icon in the bracket view.

When subscribed, you'll be notified when a new round starts or the winner is announced.

### Comments posted by the app

Brackify posts comments to keep everything transparent and traceable:

- When the tournament starts, an announcement comment is posted with the entry list and rules.
- When community members publish their entries, a comment is posted under the tournament thread.
- When entries are renamed or removed, a reply is posted under the original submission comment.
- After each round, a recap comment shows all matchup results.
- When the tournament ends, you can post your own results comment or share your picks.

All tournament-related comments are grouped under a single thread to keep the comment section clean. Before anything is posted under your name, you'll see a preview and must confirm it.

---

## Limits and Tips

- **2–64 entries** per tournament. Drafts don't count toward the cap until published.
- **Odd numbers are fine** — one entry gets a free pass to the next round. No entry gets more than one free pass per tournament. Free passes are given to the strongest performer from the previous round.
- **Unique names required** — every published entry must have a unique name (case-insensitive). Checked at publish time and when renaming.
- **Images are resized** automatically. Maximum upload size is 20 MB.
- **Round duration** — 1 to 24 hours per round, with optional per-round overrides.
- **One vote per matchup** — your vote is final.
- **Only the organizer** who created the tournament can manage it.
- **Vote counts update in real time** — no need to refresh.

### Running inside Reddit

Brackify runs as an embedded Reddit app. A few things to keep in mind:

- **Switching tabs?** The app refreshes data automatically when you return.
- **"Live updates paused"?** The app temporarily lost contact with the server. Tap the message to reconnect.
- **Round ended while voting?** You'll see a message and the app will update automatically.
- **Something looks off?** Refreshing the page is always safe.

---

## Feedback and Bug Reports

If you run into a problem, have an idea, or want to help test:

**[github.com/petaSk98/Brackify-Feedback](https://github.com/petaSk98/Brackify-Feedback)**

Your input helps make Brackify better for everyone.
