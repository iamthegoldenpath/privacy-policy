# Privacy Policy
This policy has a general statement, which follows, and a section for each repository it covers.  A repository's section lists anything specific to that work and takes precedence where the two differ.

All scripts, bots, products, and general work do not use telemetry, heartbeats, call-homes, cookies, or tracking, and do not keep logs of what their users do, except where a repository's section below says otherwise.  Any data the scripts, bots, products, or general work generate stays on the platform it originated on and is subject to that platform's data retention and privacy policies.  For example, work deployed on Azure, AWS, or another third party falls under that provider's privacy policy.  The developer is not responsible or accountable for how the platform handles that data.

The scripts, bots, products, and general work are written with security and privacy in mind, and every reasonable effort goes into keeping them that way.  If evidence shows that any of them violates this policy, the work will be changed to close that gap.  Report it through the Issues page of the repository concerned, or through the route given in that repository's section below.

## MaxHam
The general policy applies, with the specifics below.  MaxHam runs on Root, so Root's own privacy policy covers everything the bot stores or logs there.

### What is stored
Everything is kept in the Root community's own app storage.  Use `.settings` to see what is held about you.
- **Quotes:** the text of a message someone reacted to with 💬, its author's display name, and when it was posted.  A quote is a copy, so it survives the original message being deleted.  `.unquote` hides a quote but keeps its text; `.reset` erases everything.
- **Reminders:** the reminder text, and the ID and display name of whoever set it, until it is delivered or cancelled.
- **Locale:** the place name, coordinates, and time zone set with `.locale`.
- **Community configuration:** the admin channels, the ignored channels, the off-limits roles, and any Giphy or YouTube API keys the community supplies.

### What is logged
- **The admin log:** administrative commands, and any command that is refused, are posted to the community's admin log channel and written to the community's app log on Root, including who ran them.
- **Developer logs:** operational logs, which include member IDs, search terms, and role changes, go to Root's developer logging where the community has enabled it.  `.cleartimers` writes each reminder it deletes to this log.
- **`feedback:`:** `@MaxHam feedback:` sends the message, its author's display name and ID, and the channel it was sent from to the developer.  It is not posted anywhere in the community.

### Third-party services
These commands send the text you type to an outside service, without your name or ID.  That service's own privacy policy applies.
- **Giphy:** `.gif` and the animal commands (`.animal`, `.cat`, `.dog`, `.bird`, `.pig`, `.lizard`, `.bear`, `.koala`).
- **Wikimedia Commons:** `.img`.
- **YouTube (Google):** `.yt`.
- **Audius and SoundCloud:** `.sc`.
- **Open-Meteo:** `.locale` and `.weather`.  The place name is sent to find it, and its coordinates are sent for the forecast.

### Reporting
MaxHam's repository is private and has no public Issues page, so report concerns with `@MaxHam feedback:` in any community running the bot.

## golden-path
This is a placeholder for the policy that will come later.  Legal intellectual property review and consulting is being done to draft a proper privacy policy that applies to the product.
