Installation:

```
composer install
```

To start the battle:
```
php index.php
```

Battle output:
```
Start Battle!

hero health: 94
hero strength: 73
hero speed: 45
hero defence: 53
hero luck: 16

beast health: 77
beast strength: 73
beast speed: 44
beast defence: 46
beast luck: 29

ROUND: 1
Attacker: Hero
Attacker Health: 94
Defender: Wild Beast
Defender Health: 50

ROUND: 2
Attacker: Wild Beast
Attacker Health: 50
Defender: Hero
Defender Health: 74

ROUND: 3
Attacker: Hero
Attacker Health: 74
Defender: Wild Beast
Defender Health: 23

ROUND: 4
Attacker: Wild Beast
Attacker Health: 23
Defender: Hero
Defender Health: 54

ROUND: 5
Attacker: Hero
Attacker Health: 54
Defender: Wild Beast
Defender Health: 0

Winner is: Hero
GAME OVER!!
```

Unit tests can be run by:
```
vendor/bin/phpunit tests/
```