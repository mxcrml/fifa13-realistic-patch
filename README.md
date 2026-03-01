# FIFA 13 Career Mode Realistic – Rebalance Edition

A careful rework of Gugabelletti's Career Mode mod for FIFA 13. The goal is not to reinvent the mod, but to keep what works (growth and retirement logic, no platinum regens), remove risky or unstable settings, and improve balance without over-modifying core systems.

Mode rebuilt from vanilla FIFA 13 settings for maximum stability.

## Sources
- [Default / Vanilla files](https://soccergaming.com/forums/threads/fifa-13-career-files-ini.172583/) - soccergaming.com
- [Original Gugabelletti patch](https://soccergaming.com/forums/threads/fifa-13-career-mode-realistic-improvements-mod.6475375/) - soccergaming.com

## Changes from Gugabelletti's version
- Fixed preseason friendly scheduling
- Restored form calculator defaults
- Restored default `gpattributemodifiers`
- Rebalanced match importance settings
- Reduced player growth XP and subs factor
- Rebalanced retirement curves
- Restored most transfer files to default values

Full details are available in the difference report.

[**View detailed report**](https://rawcdn.githack.com/mxcrml/fifa13-realistic-patch/dae5e012ab85a075ac40f6f78e9c8c9c517d7954/Report/differences-report.html)

## Installation

Download all files from this repo, then:

1. **Open your FIFA 13 Game folder**

   Navigate to your FIFA 13 installation and open the **Game** folder.

   *Default path: `C:/Program Files (x86)/EA Sports/FIFA 13/Game/`*

2. **Go to the mod data folder**

   Inside the Game folder, navigate to: `dlc\dlc_FootballCompEng\dlc\FootballCompEng\data`

3. **Copy the mod files**

   Copy all `.ini` and `.txt` files from this mod pack and paste them into the folder above.

4. **Run the File Regenerator (*Skipping this step will break the mod*)**

   Run your file regenerator tool (you can download one from the [Regenerator folder](https://github.com/mxcrml/fifa13-realistic-patch/tree/main/Regenerator)) as administrator and let it finish. This updates the game's master index so it recognizes the new files.

5. **Start a new Career**

   This mod only takes effect on a **new career save** - it will not affect existing saves.

**[Demo video of the installation process](https://vento.so/view/6e1edb0e-6caf-433b-8f1a-5abdc3b75632)**

## **Testing status**

First season completed. Overall feel is more balanced than Gugabelletti's original — transfer window ran without crashes or instability. That said, several adjustments were identified along the way and applied in **v2** to further improve the experience (see changelog in Version 2 release).
