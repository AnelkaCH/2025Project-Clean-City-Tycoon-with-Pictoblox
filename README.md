# Clean City Tycoon 🪫⚡🌳

A strategy simulation game built with PictoBlox for **Codeavour 6.0**, where players manage a city's entire energy supply using only clean and renewable sources. The project reached the **national round** of the competition.

## What It Does

The player is put in charge of meeting a growing city's daily energy demands, but the catch is that only clean energy sources are available: windmills, solar panels, hydropower, and nuclear. Each source has its own output, cost, and trade-offs.

A dynamic weather system runs in the background and directly affects how effective each power source is on any given day. Solar panels underperform on cloudy days. Wind turbines are most effective during storms. Hydro output depends on rainfall. This means the player cannot just build the same setup and leave it and they have to actively respond to changing conditions.

Every day, the city's energy requirement increases. Budget is limited, so the player has to decide which sources to invest in, how to balance short-term output with long-term capacity, and when to expand versus when to hold. Running out of energy or going over budget ends the game.

The core loop is budgeting and critical thinking: there is no single winning strategy, and the weather system makes every run slightly different.

## Built With

- **PictoBlox** = block-based programming environment (Scratch-compatible, `.sb3` format)
- Dynamic weather simulation system
- Energy calculation logic per power source type
- Incremental difficulty scaling (daily demand increase)
- Budget and resource management mechanics

> Note: The final competition submission was lost. This repository contains an earlier, incomplete version of the project. The core mechanics are present, but some features may be unfinished or placeholder.

## Demo

https://github.com/user-attachments/assets/54a5abec-fb9f-472b-9c87-9fd36acd8511

## What I Learned

**Systems design before code.** Clean City Tycoon had a lot of moving parts (weather, four energy types, budget, daily scaling) and we had to think through how they interacted before writing a single block. Getting the balance wrong made the game either trivially easy or impossible, so we iterated a lot on the numbers.

**Block-based logic has real limits.** As the game grew more complex, managing the logic inside PictoBlox became difficult. Variables, conditionals, and event triggers were scattered across sprites. We learned quickly that structure and naming conventions matter even when you are dragging blocks, not typing code.

**Working under competition constraints.** Codeavour had a theme and judging criteria, which meant we had to balance building something we thought was interesting with building something that would score well. That tension between personal vision and external requirements is something that comes up in real product work too.

## Team

Built as a team project at Bukit Sion Further Education (Year 11, 2024) for Codeavour 6.0.
