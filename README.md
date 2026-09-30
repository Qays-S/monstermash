# Monster Mash

A collaborative Git/GitHub exercise: two contributors enter the lyrics to
"Monster Mash" by Bobby "Boris" Pickett using issues, feature branches,
pull requests, and a Kanban project board.

## Roles
- Person 1 (Qays-S): verses, README
- Person 2 (Tim): choruses, closing

## Sprint Plan
| Sprint | Person 1 | Person 2 |
|---|---|---|
| 1 | Verse 1 | Chorus 1 |
| 2 | Verse 2 | Chorus 2 |
| 3 | Verse 3 (double verse) | Chorus 3 |
| 4 | Verse 4 | Chorus 4 |
| 5 | Verse 5 | Chorus 5 |
| 6 | — | Closing |

## Workflow
1. Move the issue card from **ToDo** to **InProgress**.
2. Sync local main: `git checkout main`, `git fetch --all`, `git pull`.
3. Create a feature branch (`verseX` or `chorusX`), make changes, and push.
4. Open a pull request, assign the partner, and move the card to **InReview**.
5. The reviewer approves and merges, or requests changes in the PR.
6. The reviewer moves the card to **Done**.
