# Choose your own adventure diagram

```mermaid
flowchart TD
    A[Start] -->|_You are walking on a path..._| B(_You run into a wizard!_)
    B --> C{What do you do?}
    C -->|Choice 1| D[Smack the wizard!] 
    C -->|Choice 2| E[Talk to the wizard.]
    D -->|_The wizard banishes you to a far away land!_| F(_The End..._)
    E -->|_The wizard gives you a magic sword._| G[_You continue walking an you meet a troll!_]
    G -->H{What do you do?}
    H -->|Choice 1| I[You run away!] 
    H -->|Choice 2| J[You fight the troll!]
    I-->|_The troll throws a boulder at you. You get knocked unconscious..._| K(_The End..._)
    J -->|_You attack the troll with your sword! The troll dissolves into thin air. <br>The wizard appears and congratulates you on your first adventure._| L(_The End...for now!_)
```
## Description of diagram
>
>**A:** This is the start of the adventure.
>
>**B:** This is the first scenario where you meet a wizard!
>
>**C:** You are given two choices for interacting with the wizard.
>
>**D:** This choice is where you smack the wizard, ending the adventure.
>
>**E:** This option is where you talk to the wizard, continuing the adventure to the next scenario.
>
>**G:** This is the second scenario in the adventure where you meet a troll!
>
>**H:** You are given two choices for interacting with the troll.
>
>**I:** This choice is where you run away from the troll, ending the adventure.
>
>**J** This choice is where you fight the troll and are congratulated by the wizard. This ends the adventure.

_Note: The letters that are not listed (F, K, and L) are where the adventure ends._
