# Race Condition
"Race Condition" is a fast-paced competitive programming game
where you and your peers see who can pass the most test cases, the fastest!

## Gameplay
Everyone has their own editor, and can run the official tests at anytime (after a cooldown period):
some of these tests are visible, and some are not!

### Gamemodes
**Battle Royale** &mdash; the first $n$ people to pass $T_{\text{Acceptable}}$ of $T_{\sum}$ tests get through to the next round.

**Karting** &mdash; there are a set number of races; each player competes to pass the most tests in the allocated time.

* For each passing test at the end, $d$ points will be allocated to each player.
* As well as a bonus for completing the entire task before the allocated time (1st, 2nd, etc.) calculated using the formula:

    $P - r(p)$

    Where $P$ is the total number of players, and $r(p)$ is the rank of player $p$. ($r(p)$ returns $P$ if player $p$ has not passed all tests).

Of course, it wouldn't be fun without a few power-ups!

### Power-ups
Power-ups can be purchased from the power-up shop through the use of "NFT Points" (TODO: Get pictures of the "bored ape" NFTs to represent each token).

Tokens are randomly allocated to players. Their chances are affected by their rank, and current score. (Pity tokens are also a thing.)

* *Task Switching* &mdash; forces any other player to complete a task from the task table below before submitting their code for testing:

    **Task Table**

    | Name                 | Cost (NFTs)  | Description          |
    |----------------------|--------------|----------------------|
    | CAPTCHA              | 0.5          | Literally a CAPTCHA. |            
    | Snake Eyes           | 0.5          | Roll 2 virtual dice until you get snake eyes (1, 1). |   
    | "Trivial" Quiz       | 1            | The player must get 2/3 on a computer science-themed quiz. |         

* *Polyglot* &mdash; forces any other player to switch programming languages to any different language in the chosen rank for the following task:

    | Rank                | Cost (NFTs) | Multiplier   | Supported Languages |
    |---------------------|-------------|--------------|---------------------|
    | Blissful Ignorance  | 1           | $\times 1.2$ | Python, JavaScript  |
    | Ferris and the Gang | 2           | $\times 1.4$ | PHP, Java, Rust     |

    For the target's troubles, any score is multiplied by the rank's associated multiplier.

* *Test-delayed Development* &mdash; the target player is blocked from testing their code for time $t$:

    | Delay | Cost (NFTs) |
    |-------|-------------|
    | 60s   | 1           |
    | 120s  | 2           |
