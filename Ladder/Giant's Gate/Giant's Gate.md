# **Introducing**
Giant's Gate is a multiplayer game in Codecombat. Two teams play against each other with their code. <br />

# **Play**
https://codecombat.com/play/ladder/giants-gate/

# **Detail**
Two different teams, red team and blue team. <br />
Each team has two big giants next to the middle track. <br />
To summon a soldier, 
```
hero.summon(unit, x, y)
```
OR <br />
```
hero.summon(unit, defaultSpawnPoints)
```
To cast magic,
```
hero.cast(unit, x, y)
```
After **2 Minutes** your palace (**The Diamond**) and your giants will start subtracting by itselves. <br />
And after your giant died, **Your opponent will have more territories to summon soldiers.**

# **Default Spawn Points**
Some position are marked as 'A' to 'G' as they are **Default Spawn Points**. <br />
You can **summon** soldiers there by typing this code,
```
hero.summon(unit, 'A')
```
# **Summon Units**
You can summon 7 different types of soldiers, <br />
1. 'munchkin'
> Cost time to Summon: 1 second <br />
> HP: 100 <br />
> Speed: 14 <br />
> Attack Damage: 15 <br />
> AC (Frozen time after attacking): 0.6 <br />
> Attack Range: 3M

2. 'thrower'
> Cost time to Summon: 1 second <br />
> HP: 50 <br />
> Speed: 14 <br />
> Attack Damage: 18 <br />
> AC: 0.7 <br />
> Attack Range: 25M

3. 'ogre'
> Cost time to Summon: 2 seconds <br />
> HP: 225 <br />
> Speed: 9 <br />
> Attack Damage: 25 <br />
> AC: 0.6 <br />
> Attack Range: 3M

4. 'shaman'
> Cost time to Summon: 2 seconds <br />
> HP: 155 <br />
> Speed: 10 <br />
> Attack Damage: 25 <br />
> AC: 0.7 <br />
> Attack Range: 7M

5. 'brawler'
> Cost time to Summon: 4 seconds <br />
> HP: 460 <br />
> Speed: 7 <br />
> Attack Damage: 65 <br />
> AC: 1 <br />
> Attack Range: 5M

6. 'warlock'
> Cost time to Summon: 4 seconds <br />
> HP: 310 <br />
> Speed: 8 <br />
> Attack Damage: 40 <br />
> AC: 0.6 <br />
> Attack Range: 30M

7. 'headhunter'  ***(SPECIAL)***
> Cost time to Summon: 6 seconds <br />
> HP: 200 <br />
> Speed: - <br />
> Attack Damage: -- <br />
> AC: --- <br />
> Attack Range: 40M

*Proved by running this code (Lang: Python):* <br />

```
while True:
    allUnits = hero.availableUnits
    for a in allUnits:
        hero.summon(a, 10, 0)
```


# **Cast Units**
You can cast 3 different kinds of spells. **These spells DO NOT work for giants.** <br />
<br />
1. 'fireball'
> Cost time to Cast: 1.3 seconds <br />
> Damage: 100 <br />
> Range: 10 <br />

2. 'lightning'
> Cost time to Cast: 1.3 seconds <br />
> Damage: 150 <br />
> Range: 5 <br />
> *Effect: Stun 0.7 seconds*

**3. 'heal': <br />
> Cost time to Cast: 1.3 seconds <br />
> HEAL: 75 <br />
> Range: 10 <br />**

<sup>This is the end of this chapter.</sup>
