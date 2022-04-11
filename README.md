# Carball AI RLbot
Used to convert a PPO Reinforcement Learning training bot in [RlGym](https://rlgym.github.io/) to the [RLbot](https://rlbot.org/) framework for easier testing against official and user created bots.  
The RLGym version of the bot can be found [HERE](https://github.com/BenjaminChilson/CapstoneProject_RocketLeagueAI)  

## Play Against our Bot
1. Clone this repo  
2. Download RLBot [HERE](https://github.com/RLBot/RLBotGUI/releases/download/v1.0/RLBotGUI.msi)  
3. Open RLBot, Click Add->Load Folder->Select Cloned Folder
4. Add Carball AI & Human to seperate teams
5. Click Launch Rocket League and start match
## Extra Installations (If needed)
Menu->Install Missing Python Packages  
`rlbot==1.*`
`torch>=1.5.1+cpu`
`rlgym-compat>=1.0.2`
`rlgym-tools>=1.6.1`
`numpy`
`stable_baselines3`
`pickle5`

## Changing the bot

- Bot behavior is controlled by `bot.py`
- Bot appearance is controlled by `appearance.cfg`
- Switch branches to reflect the desired model (Main contains the 500m Model)

See https://github.com/RLBot/RLBotPythonExample/wiki for documentation and tutorials.


