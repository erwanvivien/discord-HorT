# discord-HorT
A Heads or Tails discord bot

## Usages
- [``$hart``](https://github.com/erwanvivien/discord-HorT#default-command)
- [``$harts``](https://github.com/erwanvivien/discord-HorT#Multiple-draws)
- [``$hartlim``](https://github.com/erwanvivien/discord-HorT#More-results-if-not-satisfied)
- [``$hartspec``](https://github.com/erwanvivien/discord-HorT#Specific-results-from-any-SubReddit)
- [``$add`` or ``$remove``](https://github.com/erwanvivien/discord-HorT#Add-or-remove-from-list-of-SubReddits)



- Default command

``$hart`` or ``$hort`` for a simple heads or tails situation (they are the same)

HOW TO USE:
```
$hart [show] [novideo] [bad/good]
```



- Multiple draws

``$harts`` or ``$horts`` for many heads or tails situations (same again)

HOW TO USE:
```bash
$harts nb [show] [novideo] [bad/good]     # with (1 <= nb <= 10)
```



- More results if not satisfied

``$hartlim`` or ``$hortlim`` for more results (equivalent to ``$hart``, takes longer)

HOW TO USE:
```bash
$hartlim nb [show] [novideo] [bad/good]     # with (1 <= nb <= 100)
```



- Specific results from any SubReddit

``$hartspec`` or ``$hortspec`` for results in a specific SubReddit (equivalent to ``$hartlim``)

HOW TO USE:
```bash
$hartspec sub_name [nb] [show] [novideo] [bad/good]     # with (1 <= nb <= 10)
```



- Add or remove from list of SubReddits

``$add`` or ``$remove`` for more results 

HOW TO USE:
```bash
$add good/bad sub_name
```
