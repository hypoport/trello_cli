# trello_cli

## Todos

### general
* clean up global vimrc in order to free some leader keys
* generic function to run background tasks with vimscript with fallback
* show markdown links as http links in markdown format (-> browser support)
* DONE get list of joined members of all my organizations
* keep members even if no initials where found in my member list
* markdown -> json -> diff with current state -> commands
* if executing list_cards multiple times then all cards should be concated

### new functions
* add card after card
* add new list
* archive list
* unarchive list
* unarchive card
* rename list
* search cards
 * in list
 * in board
 * closed y/n/a
 * with action member

### restructure existing functions
* DONE cards
* DONE boards
* DONE list_cards <id>
* DONE board_cards <id>
* DONE convert to markdown
 * DONE filter hidden ...
 * DONE map members
 * DONE group by boards
 * DONE clear empty lists
 * DONE convert to markdown

### options
* DONE filter pinned(hidden) by comment: y/n/a
* (filter by dateLastActivity)
* DONE show empty lists: y/n
* DONE custom markdown field: "..."
* DONE show closed cards: y/n/a
* sort cards by: pos dateLastActivity due

