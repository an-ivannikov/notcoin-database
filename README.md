# Notcoin (NOT) Database
**Parsed Notcoin data right after the end of mining.**

  - 1️⃣ **ALL Squads (teams)** (the statistics indicate 54,050, but I did not find 4 squads). **54,046 records**. Additionally contains Descriptions (group.descriptions field) of channels/groups and the number of subscribers (group.members field).
  - 2️⃣ **Users** who were in the **TOP100** of each squads at the time of parsing. **780,707 records**. Additionally contains Bio (user.descriptions field) of users.
  - 3️⃣ **Statistics** were also collected at the time of parsing. **457 records**.

**The most valuable thing is Squads, to understand which team/chat were more effective.**


## MongoDB Export Files
>  [notcoin-database-export.zip](https://t.me/ivannikov_pro/65) (128.7 MB) *encrypted.

> To import into the [MongoDB](https://www.mongodb.com/) Database and view, use [MongoDB Compass](https://www.mongodb.com/products/tools/compass).

```text
.
├── csv
│   ├── NOTCOIN.notcoin_stats.csv (88 KB)
│   ├── NOTCOIN.notcoin_teams.csv (21.1 MB)
│   └── NOTCOIN.notcoin_users.csv (162.9 MB)
└── json
    ├── NOTCOIN.notcoin_stats.json (308 KB)
    ├── NOTCOIN.notcoin_teams.json (43.3 MB)
    └── NOTCOIN.notcoin_users.json (555.1 MB)
```


- Notcoin (NOT) Database

![Notcoin (NOT) Database](/images/notcoin_database.png "Notcoin (NOT) Database")

- Notcoin (NOT) Squads Database

![Notcoin (NOT) Squads Database](/images/notcoin_database_squads.png "Notcoin (NOT) Squads Database")

- Notcoin (NOT) Users Database

![Notcoin (NOT) Users Database](/images/notcoin_database_users.png "Notcoin (NOT) Users Database")
