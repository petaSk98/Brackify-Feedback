# Brackify

A bracket-style voting tournament app for Reddit. Communities vote head-to-head to crown a winner.

---

## What is Brackify?

Brackify lets you run elimination tournaments directly inside Reddit posts. Think of it like a sports playoff bracket, but for anything your community wants to vote on — best fan art, favorite memes, top movie picks, you name it.

An organizer creates a tournament with a set of entries (images or text), and the community decides the winner through a series of one-on-one votes. Two entries face off, the community picks a favorite, and the winner advances to the next round. This continues until one entry remains — the champion.

---

## Creating a Tournament

Any subreddit member can create a tournament in a few steps:

1. **Create a new post** — Use the subreddit menu and select "Create a new post" under Brackify. You'll be asked for a tournament name — this becomes part of the post title (e.g. "Brackify: Best Fan Art 2026"). You can also leave it blank and name it later. The post is created under your username. It may take a moment to appear in the feed — this is normal. Try refreshing the page after a minute or two.
2. **Set a title and description** — The tournament name you chose in the previous step is pre-filled here. You can change it, and optionally add a description. You can also add a cover image and drag it to position it the way you want. The title can be styled with a font preset, color, and size.
3. **Add entries** — Upload images, paste image URLs, or add text entries. You need at least 2 entries and can add up to 64. Both even and odd numbers work — if there's an odd number, one entry gets a free pass (BYE) in the first round and advances automatically. No entry can receive more than one BYE per tournament.
4. **Choose who can submit** — You can add all entries yourself, or allow community members to contribute their own (see [Submission Modes](#submission-modes) below).
5. **Configure rules** — Set how long each round lasts (1–24 hours) and optionally require a minimum number of votes before a round can close early. These settings are saved as drafts automatically while you adjust them.
6. **Start the tournament** — Once everything looks good, hit start. You'll see a preview of the anchor comment that will be posted under the tournament. This comment lists your entries and tournament details. After confirming, the bracket is generated and voting begins. In community mode, if you still have unpublished draft entries, you'll be asked whether to include them in the tournament or start without them. Any unpublished entries from other users are automatically removed at start time.

### Optional settings

- **Per-round duration** — You can set a different duration for each round. By default, the final round gets extra time (1.5× the base duration, up to 24 hours).
- **Vote threshold** — Set a minimum number of votes per matchup. If all matchups in a round reach the threshold, the round closes early — even if the timer hasn't run out.
- **Voter requirements** — Restrict voting by minimum account age, minimum karma, or require a verified email. Users who don't meet the requirements can still view the bracket but cannot vote.
- **Show image labels** — Toggle whether item names are displayed below images during voting and in the bracket.
- **Use filename as name** — When enabled, uploaded images automatically get their filename (without the file extension) as their display name. For example, uploading `sunset_beach.jpg` names the entry "sunset\_beach". You can still rename any entry manually afterward. This option only applies to image uploads — it has no effect on text entries or image URLs. In community mode, this option is available to all users for their own draft entries. When the organizer toggles it, it sets the tournament-wide default for future uploads. When a community user toggles it, only their own drafts are affected.
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

Only the organizer adds entries. All entries remain in draft state until the tournament starts — there is no separate publish step. Other users see a waiting screen with tournament info (if the title is set) or a generic "being prepared" message. Once the organizer launches the tournament, entries are finalized and voting begins automatically.

### Community submissions

Everyone can contribute entries before the tournament begins — including the organizer. The organizer sets how many items each user can submit (1–20). Submissions close when the bracket reaches 64 entries, the organizer pauses them, or the organizer starts the tournament.

#### How it works for everyone

In community mode, **all entries start as drafts** — whether submitted by a regular user or the organizer. Drafts are private: only you can see them. Nobody else — not even the organizer — can see your drafts until you publish them.

You can upload images, paste image URLs, or type text entries. There's also a **bulk text mode** that lets you paste multiple text entries at once (one per line).

While your entries are in draft, you can freely add, remove, rename, and rearrange them. Think of it as a workspace where you prepare your submission before making it public.

#### Publishing your entries

When you're ready, tap **"Publish my entries"** to confirm your entries with a Reddit comment. The comment appears under the community submissions thread and serves as a public record of what you contributed. You can include a personal message along with it.

Before publishing, the app checks:
- **Duplicate names** — Your entry names can't match any already-published entry (case-insensitive). If duplicates are found, you'll see which ones need renaming.
- **Available space** — All your drafts must fit within the tournament's 64-entry limit. If there isn't enough room for all of them, you'll need to remove some first.
- **All or nothing** — Either all your drafts are published at once, or none are. You can't publish just some of them.

**Important:** Your entries are only confirmed once the comment is posted. If you close the page without publishing, your drafts are saved and will be waiting for you when you come back — but they'll be removed when the tournament starts.

#### Updating your entries

After publishing, you can still make changes:

- **Add more entries** (within your limit) — new entries start as drafts. When you're ready, publish them the same way as before. A reply is posted under your original comment listing the additions.
- **Rename a published entry** — edit the name inline and press Enter. A comment dialog opens immediately asking you to confirm the change. A reply is posted under your original comment showing the rename. If the new name is already taken by another published entry, the rename is blocked before the dialog opens.
- **Remove a published entry** — tap delete, confirm, and a comment dialog opens. A reply is posted documenting the removal.

Each change to a published entry requires its own comment — there is no batching for edits. This ensures every change has a clear audit trail.

#### What you can see

- **Your entries** — shows all your entries (drafts and published).
- **Other entries** — shows everyone else's published entries. You can choose to reveal or hide them to avoid spoilers.

#### The organizer's role

In community mode, the organizer submits and publishes entries the same way as everyone else. The organizer's entries follow the same rules — they start as drafts, must be published via comment, and are subject to the same duplicate checks. Changes to the organizer's own published entries (rename, delete) also require a comment confirmation, just like for regular users.

The organizer does **not** have a per-user submission limit (unlike regular users), but is still subject to the overall 64-entry tournament cap.

In addition to submitting entries, the organizer can:

- **Remove** any community-submitted entry — a reply is posted under the submitter's comment explaining the removal (with an optional reason).
- **Rename** any entry — a reply is posted under the submitter's comment showing the old and new name (with an optional reason).

These audit actions are always documented as public comments.

#### Pausing community changes

The organizer can **pause community changes** at any time during setup. When paused:

- Community users cannot add, edit, rename, or remove entries.
- Their existing published entries remain in the tournament.
- The organizer can still add, edit, and manage all entries freely.

This is useful when the organizer wants to finalize the setup without further changes from the community — for example, before reordering entries or starting the tournament.

Pausing is a toggle — the organizer can resume community changes at any time.

#### Switching between modes

The organizer can switch from organizer-only mode to community mode at any time. Any entries already added become drafts that need to be published via comment.

**Once any entry is published** (by the organizer or a community member), **switching back to organizer-only mode is blocked.** This protects the audit trail — published entries have associated comments that would become orphaned if the mode changed. The organizer can use the **pause** feature instead to temporarily stop community input without switching modes.

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

- **Community submissions thread** — When the organizer switches to community mode, the app posts a system comment under the post announcing that submissions are open. All community submission comments are grouped as replies under this thread, keeping the main comment section clean.
- **Anchor comment** — Posted when the organizer starts the tournament. Lists the organizer's published entries and tournament details (round count, duration, item count). If the organizer has unpublished drafts at start time, they're asked whether to include them in the tournament or leave them out.
- **Submission comments** — Posted by community contributors when they publish their entries. These appear as replies under the community submissions thread. Updates to entries are posted as further replies under the user's own submission comment.
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

- **Minimum 2 entries, maximum 64** per tournament. The 64-entry cap counts only published entries — your drafts don't count toward it until you publish.
- **Per-user limit** — In community mode, the organizer sets how many entries each user can submit. This limit counts both your drafts and published entries combined.
- **Unique names required** — Every published entry must have a unique name (case-insensitive, trimmed). You can have duplicate names in your drafts — they're only checked when you publish. Renaming a published entry is also checked for duplicates before the comment dialog opens.
- **Odd numbers are fine** — if the entry count is odd, one entry receives a free pass (BYE) and advances to the next round automatically.
- **Images are resized** automatically to fit the app. Maximum upload size is 20 MB per image.
- **Image naming** — Images are automatically named "Image 1", "Image 2", etc. (or from the filename if the "use filename" option is enabled). You can rename any entry freely while it's in draft. Renaming a published entry requires a comment.
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
