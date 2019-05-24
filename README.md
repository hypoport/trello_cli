# trello_cli

This trello client is used to get information from trello as json data.


## How to start

* set the following variables (i.e. to ~/.bash_profile

```
export trello_cache_dir=
export trello_key=
export trello_token=
```

Notices: login to trello and get the key under this url https://trello.com/app-key . On the same page, get the token.


## Functions

### clitrello boards

### clitrello cards 'boardid'

Read cards from board 'boardid'. 
By environemnt var *$actions*, you can set more information to be printed.
Default value: $actions=commentCard

More information for actions can be found here: https://developers.trello.com/reference#section-nested-cards-as-url-params