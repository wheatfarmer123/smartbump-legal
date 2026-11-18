# SmartBump Privacy Policy

**Last updated: November 17, 2026**

## 1. Introduction
This Privacy Policy explains what data SmartBump collects, why, how it is stored, and how it is deleted. By using SmartBump, you agree to this policy and our [Terms of Service](TERMS.md).

## 2. Data We Store
SmartBump stores only the data it needs to run the advertising network.

**Server data** (for servers that run `/setup`):
- Server ID
- Ad channel ID (where other servers' ads are posted)
- The invite link SmartBump creates for your server
- Description, tags and ad colour
- Bump count, time of the last bump, and the channel the last bump was made in
- Reminder settings, including a reminder role ID if you choose one
- Ad delivery status: whether ads are working or paused, the reason they were paused, and the number of failed deliveries in a row
- When the server was set up

**User data:**
- The user ID of the last person to bump each server
- Bump history: server ID, user ID, time of each bump, and how many servers the ad reached
- Ratings: user ID, server ID and score
- Reports: the reporter's user ID, the reported server's ID, the server the report was made from, the reason, the time, and how it was handled
- Blacklist entries: the blocked server or user ID, the reason, who added it, and when

**What we do not store:**
- Message content. SmartBump cannot read messages.
- Member lists
- Your server's name, icon, banner, member count or creation date. These are read from Discord when an ad is created and are not saved in our database.

## 3. How We Use Data
Data is used only to operate SmartBump, including to:
- Create and post server advertisements across the network
- Enforce bump cooldowns and send bump reminders
- Show ratings, profiles, leaderboards and statistics
- Detect ad channels that no longer work and notify server owners
- Review reports and prevent abuse

## 4. Advertisements
When a server bumps, its advertisement is posted as a message in the ad channel of every other server in the network. The ad shows the server's name, icon, banner, member count, creation date, description, tags, rating, bump count and invite link, plus the username of the person who bumped. These messages are controlled by the servers that receive them, and SmartBump does not delete them later.

## 5. Logs
To keep SmartBump running and safe, some events are recorded:
- **Private log channel:** a private Discord channel that only the SmartBump team can see. It records servers joining and leaving, setups and resets, paused ads, reports (including the reporter's username and ID, and the reported ad), and error details.
- **Log files:** files on the machine that runs SmartBump. They contain technical events such as server and user IDs involved in bumps and errors. Older log files are deleted automatically as new ones are written.

## 6. Storage and Security
All data is stored in a private SQLite database on the machine that runs SmartBump. Backup copies of the database are made daily and when the bot starts, and only the 7 most recent are kept. We do not sell, rent or share your data with third parties.

## 7. Data Retention and Deletion
- **Server data** is kept while SmartBump is in your server and your server is set up.
- **When SmartBump is removed from a server,** that server's profile, bump history and ratings are deleted automatically.
- **When a server is reset** with the reset option in `/setup`, its profile, bump count, bump history and ratings are deleted.
- **Your rating** can be removed at any time with the Rate button on that server's ad.
- **Reports and blacklist entries** are kept after a server leaves so we can prevent abuse.
- **Backups** may hold deleted data until they are replaced, which normally takes about 7 days.

## 8. Your Rights
You can:
- Delete your server's data with the reset option in `/setup`, or by removing SmartBump from your server
- Remove your rating of any server with the Rate button
- Ask us to access or delete other data about you, such as your bump history, through our support server

## 9. Children
SmartBump is only for people who meet the minimum age required to use Discord in their country. We do not knowingly collect data from anyone below that age.

## 10. Third Parties
SmartBump runs on Discord, so all data also passes through Discord and is covered by [Discord's Privacy Policy](https://discord.com/privacy). We do not share data with anyone else.

## 11. Changes to This Policy
We may update this Privacy Policy at any time. The "Last updated" date at the top will change when we do. Continuing to use SmartBump after an update means you accept the new policy.

## 12. Contact
For privacy questions or data requests, please join our support server (link coming soon).
