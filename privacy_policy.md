# Game Master Privacy Policy

**Effective date:** 16 October 2026  
**Last updated:** 16 October 2026

Game Master is an independently developed application for running custom game events inside Root communities. This policy explains how the application handles personal information through its event, team, voice-room, readiness, results, leaderboard and admin statistics features.

## 1. Who operates Game Master

**Developer and operator:** Michal "Seddsy" Myška  
**Contact:** [Seddsylive@gmail.com](mailto:Seddsylive@gmail.com)

Game Master is not developed by Root Communications, Inc.

For information obtained through the Root Developer Platform, Root's [Developer Terms and Data Processing Addendum](https://www.rootapp.com/developer-terms-of-service) identify **Root Communications, Inc. as the controller** and the application's operator as its processor. We handle this information to operate Game Master under Root's instructions. Root's own practices are described in its [Privacy Policy](https://www.rootapp.com/privacy-policy).

Community administrators choose event settings, organize teams, submit results and use reports. Their handling of downloaded reports and any additional community records may also be subject to their own privacy responsibilities.

## 2. Information the application handles

Game Master receives information through Root's APIs, actions taken in the application, and entries submitted by community administrators.

| Category | Examples |
| --- | --- |
| Member identity | Root user IDs and community nicknames or display names. |
| Community and access settings | The community owner's ID, relevant member roles, configured admin-role IDs, and voice-channel and channel-group IDs and names. |
| Voice presence | Whether a member is connected to the configured main voice channel or an event team room, and which relevant room they are in. |
| Event participation | Event names and IDs, presets, rounds, lobby and team assignments, player-pool membership, excluded players, and prior teammate pairings or waiting priority within an event. |
| Readiness and timing | Ready confirmations, confirmation times, roster versions, countdowns, match start times and starting rosters. |
| Results and standings | Admin-confirmed final rosters, player names and IDs, winners, placements, wins, losses, win rate, result versions and correction times. |
| Admin activity | Admin identity, action and time, affected event or lobby, and relevant before/after values, such as roster moves or result corrections. |
| Event and lifetime statistics | Event records, creation/end times, rounds, starts, results, cancellations, and real user IDs used to count distinct participants. |
| Operational diagnostics | Error information needed to identify room preparation, permissions, storage or connection failures; this can include platform identifiers. |

An administrator can include you in an event by importing members connected to the main voice channel. Joining that channel during an active event can also add you to the player pool. This can happen even if you have not opened Game Master or pressed a join button in the application.

Dummy entries are administrator-created placeholders. They do not receive wins, losses or unique-player credit. Administrators should use fictional names for these entries.

Game Master does **not record, listen to or transcribe voice calls**, capture video or screen shares, or read chat messages or direct messages for its functionality. It does not request your Root password, payment details or precise location. Root separately handles its platform's accounts, communications and infrastructure data.

## 3. Why this information is used

The application uses information to:

- Create events, assign available players to lobbies, rotate teammates and give waiting players priority in later rounds.
- Create restricted team voice rooms, synchronize access and remove empty rooms after a result or cancellation.
- Verify that players are in the correct voice rooms before accepting Ready and starting a match.
- Save final rosters and results, calculate standings, and apply corrections without counting a match twice.
- Provide event history, player details, admin reports and administrator-requested CSV exports.
- Check admin permissions, maintain an action history, recover after restarts and diagnose failures.

Team allocation and standings involve automated calculations. Administrators can adjust rosters and confirm or correct results. Game Master does not combine participation across different communities into a global player profile.

We do not sell or rent application data, use it for advertising, or use it to train AI models.

## 4. Who can see information

**Community members with access to Game Master** can view event participants and rosters, relevant voice/readiness status, match history, player details and leaderboards within that community.

**Authorized admins** can additionally access management controls, the activity log, event/lifetime statistics and CSV exports. The community owner manages application settings. Access checks are performed on the server.

**Root** hosts the production application and its datastore. Each installing community has a separate application instance and database. Root may access hosted information as described in its own terms and privacy policy. See the [Root App overview](https://docs.rootapp.com/docs/app-docs/get-started/app-overview/).

**CSV exports** can contain names, user IDs, event/team participation and outcomes. An authorized admin can download a report to their device. Game Master does not automatically post exports to GitHub or send them to an external reporting service. Administrators are responsible for protecting downloaded copies and handling any subsequent sharing appropriately.

We forward application-data privacy requests to Root and assist under its instructions. Disclosures required by applicable law are handled through the appropriate process.

## 5. Storage and international processing

Production application state is stored through Root's server-side datastore. Root manages its hosted infrastructure and backups. Game Master does not send its event database to a separate developer-operated analytics database.

Root states in its [Privacy Policy](https://www.rootapp.com/privacy-policy) that personal information is stored in the United States. This may involve processing outside your country. Contact Root for information about the transfer mechanisms and safeguards applicable to platform processing.

The application does not add advertising cookies or third-party tracking scripts. Community statistics are an application feature, not anonymous tracking: underlying user IDs are retained for deduplication and event records. Root's own client, website and infrastructure practices remain subject to Root's privacy information.

## 6. Retention

Current storage behavior is as follows:

| Information | Retention behavior |
| --- | --- |
| Active event state | Retained while the event exists. Ending the event removes its active state, including current pool, readiness and pairing bookkeeping, but preserves the historical records described below. |
| Match results and leaderboards | Results have no automatic age-based expiry. The current version stores up to 5,000 match records per community; reaching that limit does not automatically delete the oldest records. Leaderboards and player details are calculated from retained results. |
| Admin activity | The latest 2,000 entries are retained. Older entries are replaced as new actions are recorded. |
| Event and lifetime statistics | Have no automatic age-based expiry. Event records and participant IDs persist independently of match results and the activity log so that historical and unique-player counts survive. |
| Configuration | Retained until changed or the relevant application data is removed. |
| Temporary operations | Round previews and export sessions are usable for up to five minutes. Their in-memory data may remain until replaced, evicted, cleared by a later operation or the server stops. They are not a separate permanent export archive. |
| Downloaded CSV files | Remain on the downloading administrator's device until that person removes them; application-side deletion does not remotely erase those copies. |

These technical limits do not override deletion requirements. We assist Root with removal when required by its instructions or applicable law, including when processing ends. Root controls the decommissioning of hosted instances and the handling of platform backups. The application does not promise instant removal of all backup copies.

Leaving a voice channel, being removed from an event, ending an event or deleting a temporary voice room does **not** automatically erase your past results, activity entries or participant IDs in statistics. Use the privacy-request process below.

## 7. Your privacy requests and choices

For access, correction, deletion or other requests concerning personal information processed through Root, contact **[Root Support](https://www.rootapp.com/support)**. You may also contact [Seddsylive@gmail.com](mailto:Seddsylive@gmail.com); we will direct and forward application-data requests to Root and assist with its instructions.

Identify the relevant community and your Root user ID if available. Provide only what is reasonably needed to identify the records. Do not send passwords, authentication tokens or unnecessary identity documents.

Depending on applicable law, you may have rights to access and correct information, request erasure or restriction, object to certain processing, receive portable data, withdraw consent where consent is the basis, and complain to a supervisory authority. Rights and any exceptions depend on the circumstances. Root handles requests for the application data it controls; its privacy contact can also provide information about the applicable legal basis.

The current application has no self-service personal-data deletion button. For a game outcome or roster mistake, you can also ask a community admin to review the recorded result. A result correction is not the same as deleting your personal data.

## 8. Direct correspondence

If you contact the operator directly, we receive your email address, message and any information you choose to include. We use this correspondence to respond, troubleshoot or route your request, and keep it only as needed to resolve the matter and meet applicable obligations. Email is handled through Gmail; see [Google's Privacy Policy](https://policies.google.com/privacy?hl=en).

For independent correspondence outside Root-controlled application data, Michal "Seddsy" Myška is the controller. Where the GDPR applies, the basis is our legitimate interest in answering enquiries, or compliance with a legal obligation where applicable. Application-data rights requests are forwarded to Root as described above.

## 9. Security

The application uses server-side permission checks, restricted team-room access and separate community datastores. Detailed admin reports and stored participant-ID lists are not included in ordinary player reports. These measures do not prevent other community members from seeing the player-facing information described in Section 4.

No system can guarantee absolute security. Report a suspected exposure or unauthorized access to the operator and Root Support. Do not publish personal records or credentials in a public GitHub issue.

## 10. Children

Game Master is intended for people who meet Root's age requirements. Root currently states that its service is not intended for children under 16. If you believe a child below the permitted age has been included in application records, contact Root Support or the operator so the concern can be referred to Root.

## 11. Changes and contact

We will update this document when application practices change and revise the date at the top. Material changes will be brought to users' attention through the application listing or another appropriate channel.

For questions about Game Master, contact **Michal "Seddsy" Myška** at **[Seddsylive@gmail.com](mailto:Seddsylive@gmail.com)**. For Root platform privacy matters and application-data rights requests, contact **[Root Support](https://www.rootapp.com/support)**.
