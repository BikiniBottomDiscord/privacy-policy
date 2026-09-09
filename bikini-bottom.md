# Bikini Bottom Discord Bots Privacy Policy

**Effective date:** September 9, 2026  
**Last updated:** September 9, 2026

This policy describes how the private Discord bots operated for the Bikini Bottom Discord community process data. It applies to Neptune's Helper, Jellyfish, Ol' Reliable, Jellymon, Bank of Bikini Bottom, Barg'n Mart, Fully Automated Nutcracker, Kelpy G, droiddevic, and other Bikini Bottom bots that link to this policy (collectively, the "Bots").

The Bots are provided only to support the Bikini Bottom community. They are not data-brokerage, advertising, or analytics services.

## Data the Bots Process

Depending on the features a member uses, a Bot may process:

- Discord identifiers, including user, member, guild, channel, role, and message IDs;
- usernames, display names, avatars, roles, and other server membership information;
- server events such as joins, leaves, role changes, boosts, and moderation-related events;
- commands, mentions, reactions, buttons, and other interactions directed to a Bot;
- message content when needed to recognize text commands, operate community games, award activity-based progress, relay a member's message to server staff, moderate Bot interactions, or test a Bot feature;
- presence or activity information when needed for an enabled feature;
- voice-channel state while providing music or other voice features; and
- Bot-specific records such as settings, preferences, cooldowns, game progress, scores, inventories, virtual currency, purchases, licenses, teams, battle records, moderation or abuse-prevention records, and feature-testing results.

The exact data used depends on the Bot and feature. A Bot does not use every category above for every member.

## How Data Is Used

The Bots use data only to:

- provide requested commands, games, economy, music, utility, moderation, and community features;
- maintain member progress, rankings, inventories, preferences, roles, and virtual currency;
- detect abuse, enforce cooldowns or server rules, and keep the Bots reliable;
- diagnose errors, test changes, and improve features before release; and
- protect the security and integrity of the Bots and the Bikini Bottom community.

Presence, voice-state, and ordinary message content are processed in memory when a feature needs them and are not used to build advertising profiles. Full message content is not stored outside Discord. Limited interaction or error details may appear in operational logs when a member invokes a Bot or a feature fails.

The Bots do not sell personal data. Data is not used to train machine-learning or artificial-intelligence models and is not shared for third-party advertising.

## Storage

Some Bot data is stored in a local database on systems controlled by the Bot operators. The database is encrypted at rest via AWS DynamoDB. Persistent records can include Discord identifiers and the Bot-specific progress, settings, moderation, or abuse-prevention data described above. This storage is necessary for features that must continue across restarts, such as game progress, inventories, rankings, virtual currency, role-related features, and user preferences.

Where an enabled leaderboard feature requires it, a Bot may send a member's username, avatar URL, level, and points to the Bikini Bottom community website API so the leaderboard can be displayed.

Discord messages, channels, embeds, and staff records that remain solely within Discord are stored by Discord and are also subject to Discord's privacy policy and terms.

The operators may use service providers needed to host, secure, back up, or maintain the Bots. Such providers may process data only to provide those services. Data may also be disclosed when required by law or reasonably necessary to protect members, the Bots, or the community.

## Retention

- **Persistent feature data:** Game, economy, preference, role, moderation, and similar records are kept while needed to provide the applicable feature, preserve its integrity, or prevent abuse. They may remain associated with a Discord user ID until deletion is requested or the feature is retired.
- **Operational logs:** An automated batch cleanup deletes operational log files after 30 days.
- **Presence, voice state, and ordinary message content:** These data are processed temporarily in memory and are not retained as standalone off-platform records. Limited portions may remain temporarily in operational logs when part of a Bot interaction or error.
- **Backups:** Deleted records may remain in restricted backups until those backups are overwritten or deleted during normal maintenance. No single fixed backup schedule applies to every Bot.
- **Security and abuse-prevention records:** A Discord identifier and relevant enforcement information may be retained longer when reasonably necessary to prevent repeated abuse, fraud, or circumvention.

## Member Choices and Data Requests

Members can stop most collection by not invoking or interacting with a Bot. Some processing, such as activity-based features, moderation, join/leave handling, or server-wide game events, may occur automatically where the feature is enabled. Because the Bots operate as integrated services in one private community, members cannot separately opt out of every instance of member, presence, or message processing while continuing to use all related features.

Members may request access to or deletion of data associated with their Discord account by:

- contacting **@dovedevic** on Discord (formerly **@dovedevic#0522**);
- contacting Bikini Bottom server staff via Neptune's Helper; or
- opening an issue at <https://github.com/BikiniBottomDiscord/privacy-policy/issues>.

Please include the relevant Discord user ID and the Bot or feature involved. Do not post sensitive information in a public GitHub issue. The operators may ask for reasonable verification that the requester controls the account. A deletion request may reset or remove game progress, currency, inventories, rankings, preferences, and access to related features. Data that must be retained for security, abuse prevention, legal obligations, or the integrity of other members' records may be limited or de-identified instead of deleted.

## Security

The operators use reasonable administrative and technical safeguards appropriate to these private community Bots. The locally operated database is encrypted at rest.

## Changes to This Policy

This policy may be updated as the Bots or legal requirements change. The current version will remain available at:

<https://github.com/BikiniBottomDiscord/privacy-policy/blob/main/bikini-bottom.md>

## Contact

Questions or concerns about this policy can be sent to **@dovedevic** on Discord, to Bikini Bottom server staff, or through the repository issue tracker linked above.
