# ALS Wiki Unit Entry Builder

A local, staff-friendly form for generating `Module:InfoUnitData` Lua entries for the Anime Last Stand wiki.

## Open it

Double-click `index.html`. It runs entirely in your browser and does not need installation or an internet connection.

## Use it

1. Enter the unit information.
2. Fill in Deployment, then add Upgrade 1 and the remaining upgrades.
3. Tick status effects separately for each row. “Copy previous effects” carries effects forward only when they continue.
4. Add optional passives and an active ability.
5. Review any warnings, then use **Copy Lua** or **Download .lua**.

The form automatically calculates the displayed stat ranges, deployment cost, total cost, AoE progression, and overall status effects. Work is saved automatically in the browser.

Status-effect mappings: Burn → `burn = "yes"`, Bleed → `bleed = "yes"`, Freeze → `freeze = "yes"`, Slow → `slow = "yes"`, Crippled → `crippled = "yes"`, and Hex → `hex = "yes"`.
