# Discord API Diff
This repository automatically tracks changes to interesting/useful Discord api objects.

## How this works
Every set interval, data indicated by the file names is pulled from the api, compared against the existing content, then updated if changes are detected.

For `changelogs.json`, `collectibles.json`, `profile-effects.json`, and `quests.json`, top level entries may only get added or updated. If an entry is removed from the api, it will **not** be removed from the repo.

For `csp.json`, both additions and removals are tracked (since both are interesting).
