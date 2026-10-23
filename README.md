Game Master Privacy Policy

**Effective date:** 16 October 2026  
**Last updated:** 23 October 2026

Game Master is an independently developed application for running custom game events inside Root communities. This policy explains how the application handles personal information through its event, team, voice-room, readiness, results, leaderboard and admin statistics features.

## 1. Who operates Game Master

**Developer and operator:** Michal "Seddsy" Myška  
**Contact:** [Seddsylive@gmail.com](mailto:Seddsylive@gmail.com)

Game Master is not developed by Root Communications, Inc.

For information obtained through the Root Developer Platform, Root's [Developer Terms and Data Processing Addendum](https://www.rootapp.com/developer-terms-of-service) identify **Root Communications, Inc. as the controller** and the application's operator as its processor. We handle this information to operate Game Master under Root's instructions. Root's own practices are described in its [Privacy Policy](https://www.rootapp.com/privacy-policy).

Community administrators choose event settings, organize teams, submit results and use reports. Their handling of downloaded reports and any additional community records may also be subject to their own privacy responsibilities.

### Privacy information and choices

This policy is a privacy notice, not a request for blanket consent. Reading this policy, using Game Master or remaining in a community does not by itself constitute consent to every use or disclosure of personal information. A separate acceptance of this policy is not required for the application's ordinary local event features. Those features process information under the applicable controller's lawful basis and instructions; this policy does not create or change that legal basis.

Optional cross-community participation currently requires a separate, session-specific player action before assignment and sharing, as described in Section 5. A community administrator cannot provide that choice on a player's behalf. Merely publishing this notice does not authorize external sharing. Where processing relies on consent, it must be obtained separately and can be withdrawn as applicable. Where another lawful basis applies, the relevant controller remains responsible for establishing it and providing information about it.

## 2. Information the application handles

Game Master receives information through Root's APIs, actions taken in the application, and entries submitted by community administrators.

| Category | Examples |
| --- | --- |
| Member identity | Root user IDs and community nicknames or display names. |
| Community and access settings | The community owner's ID, relevant member roles, configured admin-role IDs, and voice/text-channel and channel-group IDs and names. |
| Voice presence | Whether a member is connected to the configured main voice channel or an event team room, and which relevant room they are in. |
| Event participation | Event names and IDs, game presets, lobby formats, map pools and selected maps, game setup instructions, rounds, lobby and team assignments, the selected in-game host, player-pool membership, excluded players, and prior teammate pairings or waiting priority within an event. |
| Navigation preferences | Your last page and Player/Admin pages, saved locally on your device under your Root user ID. |
| Personal draw preference | Your Root user ID, your Available to play or Taking a break choice, and a version counter used to prevent conflicting updates. |
| Temporary game access | Host/admin-submitted invite links, join codes or lobby names, optional notes, and who updated them. These are shared only with that lobby and authorized admins through the app and its restricted Root chat. |
| Readiness and timing | Ready confirmations, confirmation times, roster versions, countdowns, match start times and starting rosters. |
| Optional match evidence | Player-submitted result images, Root asset URIs, submitter IDs and submission times when enabled by the game preset. |
| Optional player statistics | Admin-entered kills, deaths and/or assists, individually enabled by the game preset. These are included with the community’s match history; blank values are not treated as zero. |
| Derived performance | Cumulative totals or per-recorded-match averages for enabled statistics, and an automatically calculated KDA ratio when kills, deaths and assists are enabled. |
| Results and standings | Admin-confirmed final rosters, player names and IDs, winners, placements, wins, losses, win rate, result versions and correction times. |
| Admin activity | Admin identity, action and time, affected event or lobby, and relevant before/after values, such as roster moves or result corrections. |
| Event and lifetime statistics | Event records, creation/end times, rounds, starts, results, cancellations, and real user IDs used to count distinct participants. |
| Operational diagnostics | Error information needed to identify room preparation, permissions, storage or connection failures; this can include platform identifiers. |

An administrator can include you in an event by importing members connected to the main voice channel. Joining that channel during an active event can also add you to the player pool. This can happen even if you have not opened Game Master or pressed a join button in the application.

Choosing Taking a break excludes you from future automatic draws until you resume. It returns you from an unstarted lobby to the player pool. An already running match keeps its team assignment for accurate results, and historical results are retained. Your break status can be seen by other members viewing the event.

Navigation preferences remain in local app storage until replaced or cleared. They are separate from community event records and do not grant admin access. If local storage is unavailable, navigation works without remembering your location.

Dummy entries are administrator-created placeholders. They do not receive wins, losses or unique-player credit. Administrators should use fictional names for these entries.

Each prepared lobby has a temporary text channel for its teams to exchange game join details. Members send those messages through Root; Game Master does not read or archive their content. The app posts its own setup message mentioning the selected host, the map when configured, administrator-provided game settings and a request to share an invite link or party code. It stores its own message ID, last sent text and delivery status to update that message when the host or map changes. It does not generate game access credentials. A host or admin can enter an invite link, join code or lobby name and an optional note in the app. These temporary details are stored with the active lobby and included in its setup message. Other lobbies and pool players do not receive them through app snapshots. Join details are cleared from the app when the host changes or cleanup completes; the last delivered setup-message text can remain in active state until an update succeeds or cleanup removes it. Game Master cannot revoke an invite inside the game or remove copies other users have saved. The channel is removed during cleanup after the game is resolved or cancelled and everyone has left the team voice rooms. Root controls its own platform retention.

Game Master does **not record, listen to or transcribe voice calls**, capture video or screen shares, or read chat messages or direct messages for its functionality. It does not request your Root password, payment details or precise location. Root separately handles its platform's accounts, communications and infrastructure data.

When screenshot reporting is enabled, assigned real players may voluntarily submit one result image during their match, before confirmation; a later upload replaces that player's earlier reference. Screenshots are uploaded through Root's image picker and stored as Root assets. Game Master gives community admins the submitted image references for review and gives each submitter access to their own reference; it does not send them to other players or the cross-server relay. Anyone who receives an asset URL may be able to retain or share it outside the app. Include only the match result and avoid unrelated personal information. There is no automatic image recognition or extraction of statistics. Player summaries use the game preset’s current totals or average display preference. Averages use only matches with a recorded value for the relevant statistic. KDA uses matches with all three values recorded and is calculated as (total kills + total assists) divided by total deaths, with a divisor of 1 when total deaths are zero. Leaderboard sorting changes display order; it does not change a player’s standing rank. Admin-entered enabled statistics are visible in match history. In shared events, evidence and statistics remain in the submitting community's local app state; they do not form part of the other community's result approval.

## 3. Why this information is used

The application uses information to:

- Create events, assign available players to lobbies, rotate teammates and give waiting players priority in later rounds.
- Create restricted team voice rooms, synchronize access and remove empty rooms after a result or cancellation.
- Verify that players are in the correct voice rooms before accepting Ready and starting a match.
- Save final rosters and results, calculate standings, and apply corrections without counting a match twice.
- Provide event history, player details, admin reports and administrator-requested CSV exports.
- Check admin permissions, maintain an action history, recover after restarts and diagnose failures.

Team allocation and standings involve automated calculations. Administrators can adjust rosters and confirm or correct results. Game Master does not combine participation across different communities into a global player profile. In an optional cross-server match, each community records results and statistics only for its own players.

We do not sell or rent application data, use it for advertising, or use it to train AI models.

## 4. Who can see information

**Community members with access to Game Master** can view event participants and rosters, relevant voice/readiness status, match history, player details and leaderboards within that community.

**Authorized admins** can additionally access management controls, the activity log, event/lifetime statistics and CSV exports. The community owner manages voice setup. Members with Root’s Manage Apps permission configure admin roles through Root App settings; the community owner always retains app access. Access checks are performed on the server.

**Root** hosts the production application and its datastore. Each installing community has a separate application instance and database. Root may access hosted information as described in its own terms and privacy policy. See the [Root App overview](https://docs.rootapp.com/docs/app-docs/get-started/app-overview/).

**CSV exports** can contain names, user IDs, event/team participation, outcomes and enabled raw kills, deaths and assists where recorded. Unknown values remain blank, and dummy entries do not receive player statistics. An authorized admin can download a report to their device. Game Master does not automatically post exports to GitHub or send them to an external reporting service. Administrators are responsible for protecting downloaded copies and handling any subsequent sharing appropriately.

We forward application-data privacy requests to Root and assist under its instructions. Disclosures required by applicable law are handled through the appropriate process.

## 5. Storage and international processing

Production application state is stored through Root's server-side datastore. Root manages its hosted infrastructure and backups. Game Master does not send its event database to a separate analytics database. Optional cross-server sessions send the limited shared information described below to an external relay.

Root states in its [Privacy Policy](https://www.rootapp.com/privacy-policy) that personal information is stored in the United States. This may involve processing outside your country. Contact Root for information about the transfer mechanisms and safeguards applicable to platform processing.

The application does not add advertising cookies or third-party tracking scripts. Community statistics are an application feature, not anonymous tracking: underlying user IDs are retained for deduplication and event records. Root's own client, website and infrastructure practices remain subject to Root's privacy information.

### Optional cross-server sessions (new feature)

The optional cross-server feature is included starting with version 0.3.1. The following applies when a community administrator explicitly creates or joins a shared session.

Before assignment, each player must expressly accept the session-specific sharing notice in Player mode. An acceptance time, user ID, session and paired-community ID are recorded locally for that choice; the latest 2,000 admin activity entries can include this record. Admins cannot opt in on another player’s behalf. Two communities exchange opted-in, selected players’ Root user IDs and display names, team assignments, relevant voice-presence/Ready flags, game-host selection, game settings, the selected map, joining details, countdown/start acknowledgements and proposed/confirmed match outcomes through an operator-managed relay at `game-master-relay.onrender.com`. Pool members, personal pause settings, local voice/chat channel IDs, unrelated event history, Root credentials and installation tokens are not included in the shared event payload. The relay sees each installation’s own authentication credential when authenticating HTTPS requests and stores a hash of it.

Selected participants and authorized admins in the paired communities can view the shared rosters and relevant game information. Pool players do not receive the remote roster or joining details through Game Master. Each community keeps its own private Root chat and voice room; user chat messages and audio are not forwarded. The app posts its own setup information in the local chats. Only each community’s own players receive results and statistics in that community.

The external relay is hosted on Render. Its operator and hosting/storage administrators can access shared information; HTTPS transport is not end-to-end encryption. Render may process infrastructure and access diagnostics under its [Privacy Policy](https://render.com/privacy). The current service is deployed in Frankfurt; this does not establish that all provider support, logs or backups are restricted to Germany.

The app creates sessions lasting up to two hours. Relay shared-state/message payloads are cleared when the session is closed, expires or an installation is revoked; expired-session maintenance runs periodically. Closed metadata and request fingerprints can remain for up to 24 hours. Installation metadata and credential hashes remain until administratively managed; the initial relay retains revoked installation records. Hosting backups have separate retention: Render documents daily disk snapshots retained for at least seven days in its [persistent-disk documentation](https://render.com/docs/disks). Deletion from the active relay does not instantly remove backups.

Each Root instance also retains its active synchronization state until the admin ends/dismisses the shared event. Temporary join details and last delivered app briefing are cleared during completed room cleanup; result history and statistics follow the retention rules below. The app stores that community’s installation credential in Root’s server-side application data. Starting with version 0.3.2, first creating or joining a shared event registers a server-generated installation ID, authentication credential and the community ID/name with the relay; the relay stores the credential hash. Earlier versions use operator-issued credentials. It is not returned in app snapshots. A relay operator can revoke or replace credentials. Privacy requests concerning shared information should identify both communities/session where possible and can be sent to the operator contact above as well as Root Support.

## 6. Retention

Current storage behavior is as follows:

| Information | Retention behavior |
| --- | --- |
| Active event state | Retained while the event exists. Ending the event removes its active state, including current pool, readiness and pairing bookkeeping, but preserves the historical records described below. |
| Result screenshot references | Kept with a retained match or active lobby. References for cancelled or otherwise unrecorded lobbies are removed when that lobby leaves active state. Replacing a reference or removing app data does not delete the underlying Root asset; Root controls asset storage and retention. |
| Optional player statistics | Retained with match results, including subsequent admin corrections. |
| Match results and leaderboards | Results have no automatic age-based expiry. The current version stores up to 5,000 match records per community; reaching that limit does not automatically delete the oldest records. Leaderboards and player details are calculated from retained results. |
| Admin activity | The latest 2,000 entries are retained. Older entries are replaced as new actions are recorded. |
| Event and lifetime statistics | Have no automatic age-based expiry. Event records and participant IDs persist independently of match results and the activity log so that historical and unique-player counts survive. |
| Configuration | Retained until changed or the relevant application data is removed. |
| Temporary game access | Active join details and the app’s last delivered setup-message text are removed with lobby cleanup. They are not copied to result history, statistics, CSV exports or admin activity details. Root controls retention of messages on its platform. |
| Personal draw preference | Stored per community across events and restarts until changed or the relevant application data is removed. Resuming stores your available choice and version counter; ending an event does not reset this preference. |
| Temporary operations | Round previews and export sessions are usable for up to five minutes. Their in-memory data may remain until replaced, evicted, cleared by a later operation or the server stops. They are not a separate permanent export archive. |
| Downloaded CSV files | Remain on the downloading administrator's device until that person removes them; application-side deletion does not remotely erase those copies. |

These technical limits do not override deletion requirements. We assist Root with removal when required by its instructions or applicable law, including when processing ends. Root controls the decommissioning of hosted instances and the handling of platform backups. The application does not promise instant removal of all backup copies.

Leaving a voice channel, being removed from an event, ending an event or deleting a temporary voice room does **not** automatically erase your past results, activity entries or participant IDs in statistics. Use the privacy-request process below.

### Preset deletion

Starting with version 0.3.6, an authorized admin can delete a game preset or lobby format after the related local or shared event has been ended and dismissed. The admin must type its name to confirm permanent deletion. Deleting a game removes its linked game/format scoring profiles across its lobby formats; deleting a format removes its linked scoring profiles across games. The independent formats or games themselves remain available.

The operation removes linked retained match results, player performance values, standings calculated from those results, event-statistics records and their participant IDs, associated event activity entries, and stored screenshot references for those records. It also clears temporary export and round-preview caches. Global configuration, personal break preferences and unrelated events or presets remain. General configuration audit entries can remain under the activity-log retention limit.

This does not delete the underlying Root-hosted image files, previously downloaded CSV files, information retained in the other community, or provider backups. Those copies are governed by the relevant recipient or platform and the privacy-request process below. Preset deletion is a community-wide management action, not a self-service request to erase one player's data.

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
