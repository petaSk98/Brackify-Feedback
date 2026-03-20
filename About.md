# Brackify

A bracket-style voting tournament app for Reddit. Communities vote head-to-head to crown a winner.

---

## What is Brackify?

Brackify lets you run elimination tournaments directly inside Reddit posts. Think of it like a sports playoff bracket, but for anything your community wants to vote on — best fan art, favorite memes, top movie picks, you name it.

An organizer creates a tournament with a set of entries (images or text), and the community decides the winner through a series of one-on-one votes. Two entries face off, the community picks a favorite, and the winner advances to the next round. This continues until one entry remains — the champion.

---

## Creating a Tournament

Any subreddit member can create a tournament in a few steps:

1. **Create a new post** — Use the subreddit menu and select "Create a new post" under Brackify. The post is created under your username. It may take a moment to appear in the feed — this is normal. Try refreshing the page after a minute or two.
2. **Set a title and description** — Give your tournament a name (required) and optionally add a description. You can also add a cover image and drag it to position it the way you want. The title can be styled with a font preset, color, and size.
3. **Add entries** — Upload images, paste image URLs, or add text entries. You need at least 2 entries and can add up to 64. Both even and odd numbers work — if there's an odd number, one entry gets a free pass (BYE) in the first round and advances automatically. No entry can receive more than one BYE per tournament.
4. **Choose who can submit** — You can add all entries yourself, or allow community members to contribute their own (see [Submission Modes](#submission-modes) below).
5. **Configure rules** — Set how long each round lasts (1–24 hours) and optionally require a minimum number of votes before a round can close early. These settings are saved as drafts automatically while you adjust them.
6. **Start the tournament** — Once everything looks good, hit start. You'll see a preview of the anchor comment that will be posted under the tournament. This comment lists your entries and tournament details. After confirming, the bracket is generated and voting begins.

### Optional settings

- **Per-round duration** — You can set a different duration for each round. By default, the final round gets extra time (1.5× the base duration, up to 24 hours).
- **Vote threshold** — Set a minimum number of votes per matchup. If all matchups in a round reach the threshold, the round closes early — even if the timer hasn't run out.
- **Voter requirements** — Restrict voting by minimum account age, minimum karma, or require a verified email. Users who don't meet the requirements can still view the bracket but cannot vote.
- **Show image labels** — Toggle whether item names are displayed below images during voting and in the bracket.
- **Use filename as name** — When enabled, uploaded images automatically get their filename (without the file extension) as their display name. For example, uploading `sunset_beach.jpg` names the entry "sunset\_beach". You can still rename any entry manually afterward. This option only applies to image uploads — it has no effect on text entries or image URLs.
- **Default text style** — Choose a default visual style for text entries (font preset, look preset, colors, gradient). Individual entries can be styled differently.

### Text entry styling

Text entries support several visual options:

- **Font preset** — Choose from default, modern, elegant, or impact fonts.
- **Look preset** — Apply a visual theme (coral, paper, ember, vivid, ice, sage, dusk, mono).
- **Gradient and inversion** — Optionally add a gradient or invert the color scheme.
- **Custom background color** — Override the preset with a specific color.

These options are available both as a default for all text entries and per individual entry.

---

## How Voting Works

1. **Open the tournament post** on Reddit.
2. You'll see a landing screen with the tournament title, description, cover image, and the current round status.
3. Tap **"Vote →"** to enter the voting view.
4. **Pick your favorite** by tapping on it.
5. **Confirm your vote.**
6. Move on to the next matchup or explore the bracket.

Each matchup has a time limit set by the organizer. When time runs out (or the vote threshold is reached across all matchups in the round), the entry with more votes advances to the next round. If there's a tie, the higher-seeded entry (the one listed first in the matchup) advances — this is standard in bracket tournaments. Tied matchups are marked in the bracket so you can see where it happened. In the final round, a tie results in shared winners — both entries are crowned co-champions.

Once you've voted on all matchups in the current round, you'll see a recap of your picks — including which ones are leading and whether your vote flipped the lead. After that, you're taken to the bracket view where you can follow the progress while the round is still open.

You can zoom into images during voting — pinch to zoom on mobile, or Ctrl + scroll on desktop.

**Your vote is final** — once you confirm, it cannot be changed.

---

## Submission Modes

The organizer chooses one of two modes when setting up the tournament:

### Organizer only

Only the organizer adds entries. Other users see a waiting screen with tournament info (if the title is set) or a generic "being prepared" message until the tournament starts. Once the organizer launches the tournament, voting begins automatically.

### Community submissions

Everyone can contribute entries before the tournament begins. The organizer sets how many items each user can submit (1–20). Submissions close when the bracket reaches 64 entries or the organizer starts the tournament.

#### Submitting entries

In this mode, you can upload images, paste image URLs, or type text entries. There's also a **bulk text mode** that lets you paste multiple text entries at once (one per line).

Your submissions start as **pending** — they're visible to you and the organizer, but they aren't finalized until you publish them.

#### Publishing your entries

When you're ready, tap **"Publish"** to post a Reddit comment under the tournament listing your entries. This comment serves as a public record of what you contributed. You can include a personal message along with it.

**Important:** Your entries are only confirmed once the comment is posted. If you close the page without publishing, your pending entries are removed when the tournament starts.

#### Updating your entries

After publishing, you can still make changes — add more entries (within your limit), remove your own, or rename them. These changes are **staged locally** until you commit them. When you commit, a reply is posted under your original comment showing what changed (added, removed, or renamed).

#### What you can see

- **"Your submissions" tab** — shows all your entries (pending and confirmed).
- **"All submissions" tab** — shows everyone's confirmed entries. You can choose to reveal or hide other users' entries to avoid spoilers.

#### Organizer review

The organizer can see all entries (including pending ones from other users). Before starting the tournament, the organizer can:

- **Remove** any community-submitted entry — a reply is posted under the submitter's comment explaining the removal (with an optional reason).
- **Rename** any entry — a reply is posted under the submitter's comment showing the old and new name (with an optional reason).

These audit actions are always documented as public comments.

---

## Staying in the Loop

### Notifications

Notifications are **off by default**. After you finish voting in a round, you'll be offered the option to subscribe. You can also toggle notifications anytime using the **bell icon** in the bracket view.

When subscribed, you'll receive Reddit notifications (like a reply or mention) when:
- A new round starts.
- The tournament winner is announced.

You can turn notifications off and back on at any time. The app remembers that you've been asked, so it won't prompt you again in later rounds.

### Comments posted by the app

Brackify uses Reddit comments to keep a transparent record of tournament activity:

- **Anchor comment** — Posted when the organizer starts the tournament. Lists the organizer's entries and tournament details (round count, duration, item count).
- **Submission comments** — Posted by community contributors when they publish their entries. Updates are posted as replies under the original comment.
- **Audit comments** — Posted as replies when the organizer removes or renames a community entry. Includes the reason if one was provided.
- **Round closure recaps** — Posted after each round closes. Shows all matchup results — who advanced, any close calls, and what's coming next.
- **Results comment** — The organizer can post a final results comment when the tournament ends, with a personal message.
- **Share my picks** — After the tournament ends, voters can share their picks as a comment, including how many of their picks matched the winners and whether they picked the champion.

---

## In Your Feed

You don't have to open every tournament post to see what's going on. Brackify shows a live preview right in the Reddit feed:

- **Before you vote** — A spoiler-free teaser showing the current matchups without vote counts, so you can jump in without anything being revealed.
- **After you vote** — A recap of your matchups with animated vote count reveals, showing how your picks are doing. Winners are highlighted.
- **Finished tournaments** — The champion's journey through the bracket, round by round, with vote progressions.

The preview also shows the current round and how much time is left. Tap the post to vote or explore the full bracket.

---

## Exploring the Tournament

### Bracket

A visual tree of the entire tournament. See which entries won, which are still competing, and the path to the final. You can pan and zoom to explore it. On mobile (screens under 640px), the bracket automatically switches to a compact vertical layout that's easy to scroll through. You can also manually switch between layouts.

Tap any match in the bracket to see full details — vote counts, the winner, and which entries you voted for. Use arrows, keyboard keys, or swipe to move between matchups.

The bracket uses color coding to help you navigate:
- **Cyan** marks your votes and your picked path
- **Green** highlights the current live round (with a pulse indicator)
- **Purple** shows matchup winners and leading entries
- **Gold** traces the champion's path through the bracket

Additional indicators:
- **Close match badge** — shown when the vote margin is under 15%.
- **Tie icon** — marks matchups that ended in a tie.
- **BYE badge** — marks entries that advanced without a match.
- **Leading pulse** — animated indicator on the currently leading entry while the round is active.

A toggleable **legend** explains all bracket symbols.

Between rounds, a brief **ceremony overlay** announces the next round name and how many competitors remain, along with a recap of how many of your picks advanced.

### Ranking

A leaderboard of all entries sorted by how far they advanced and total votes received. Entries that tied share their placement. Tap any entry to see its full journey through the tournament, who submitted it, and which round it reached.

### Winner Screen

When the tournament ends, the champion is announced with a confetti celebration. From here you can:

- View the final bracket.
- Check the full ranking.
- **Share your picks** as a Reddit comment — including your accuracy (e.g., "7/10 correct picks") and whether you picked the champion. This can only be done once.

If the final ends in a tie, both entries are crowned co-champions and shown side by side.

The winner card shows:
- The winning entry (image or text).
- The final score with a description ("Photo finish", "Close match", "Clear win", or "Landslide").
- Who submitted the entry.
- Tournament stats (votes cast, matchups played, rounds).

---

## How Results Work

- Each matchup runs for a set amount of time (chosen by the organizer, between 1 and 24 hours per round).
- If the organizer set a vote threshold, the round closes early once **all** matchups in that round reach the threshold.
- When a round ends, the entry with more votes advances. Losers are eliminated.
- **Ties:** If both entries have the same number of votes, the higher-seeded entry advances. In the final, a tie means both entries share the win as co-champions.
- Results for each matchup are visible in the bracket as soon as the round closes. Tied matchups are marked with a special icon.
- The tournament continues round by round until one entry remains — the champion.

Vote counts update in real time while a round is active — you don't need to refresh to see the latest numbers.

### BYE logic

If the entry count is odd, one entry receives a free pass (BYE) and advances automatically. The app tries to be fair about BYE assignment:

- No entry receives more than one BYE per tournament.
- Entries that won a real match are preferred over those that already received a BYE.
- Among eligible entries, the one with the strongest win record gets the BYE.

---

## Limits and Things to Know

- **Minimum 2 entries, maximum 64** per tournament.
- **Odd numbers are fine** — if the entry count is odd, one entry receives a free pass (BYE) and advances to the next round automatically.
- **Images are resized** automatically to fit the app. Maximum upload size is 20 MB per image.
- **Round duration** can be set between 1 and 24 hours per round, with optional per-round overrides.
- **One vote per matchup** — your vote is final and cannot be changed.
- Only the organizer who created the tournament can manage it (edit entries, start it, etc.).
- The tournament post is created under the organizer's Reddit username.

### Good to know

Brackify runs inside Reddit as an embedded app. Because of that, a few things may behave slightly differently than a standalone website:

- **The tournament post may take a minute or two to appear in the feed** after creation. This is how Reddit processes new posts — just refresh the page after a moment.
- **If you switch away and come back**, the app automatically refreshes the data when the tab regains focus. In most cases, you'll see the latest state right away.
- **If the app shows a connection notice**, it means it temporarily lost contact with the server. The app polls for updates regularly — if polling fails, you'll see a "Live updates paused" message. Tapping it will attempt to reconnect. This can happen if your internet connection is unstable or if Reddit's servers are under heavy load.
- **If a round ends while you're still on the voting screen**, you'll see a brief message letting you know. The app will update to show the next round or the final results.
- **Images stored temporarily** — Uploaded images that can't be saved to Reddit's CDN are stored in a temporary fallback. If the fallback expires (after 30 days), the image shows a placeholder. The app attempts to migrate fallback images to permanent storage in the background.
- **Refreshing the page** is always a safe option if something looks out of date.

---

## Feedback and Bug Reports

If you run into a problem, have an idea for improvement, or want to help test the app, visit:

**[github.com/petaSk98/Brackify-Feedback](https://github.com/petaSk98/Brackify-Feedback)**

There you can:

- Report bugs
- Suggest new features
- Share feedback about your experience

Your input helps make Brackify better for everyone.
