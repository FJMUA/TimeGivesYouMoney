# TimeGivesYouMoney

Gives players money every minute

## Command
```properties
/timegivesyoumoney:tgym help                    - Shousthishelp.
/timegivesyoumoney:tgym reload                  - Reloads the config.
/timegivesyoumoney:tgym stats                   - Shous hou muc hmoney you haven't cashout yet.
/timegivesyoumoney:tgym stats [Player]          - Shows how much money [Player] haven't cashout get.
/timegivesyoumoney:tgym cashout                 - Cash out your money to your bank account.
/timegivesyoumoney:tgym cashout [Player]        - Cash out [Player]s money to their bank account.
/timegivesyoumoney:tgym add <Player> <Money>    - Add cash to <Player>s TGYM account.
/timegivesyoumoney:tgym remove <Player> <Money> - Remove cash from <Player>s TGYM account.
```

## Diffs

This fork plugin

1. Supports `folia`-1.21.8 with `VaultUnlocked` dependency
2. Removed some message prefix
3. You can configure player perform commands with node `Trigger.Commands.PlayerExec`

## Build

-----
Run 'mvn clean package'

## License

-------
TimeGivesYouMoney - GNU General Public License, Version 2
