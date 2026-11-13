# That's a 1 - Discord Bot

## 🚀 Setup Guide

1. **Install Node.js**: Ensure you have Node.js installed on your computer.
2. **Install Dependencies**: Open this folder in your terminal/command prompt and run:
   ```bash
   npm install
   ```
3. **Configure Token**:
   - Open the file named `.env`.
   - Replace `YOUR_TOKEN_HERE` with your actual Discord Bot Token.
   - [Get a Token Here](https://discord.com/developers/applications) (New Application -> Bot -> Reset Token)
4. **Run the Bot**:
   ```bash
   npm start
   ```

## 🎮 Commands
- `/roll [type] [tone]` - Roll for a result (e.g., `/roll type:Melee tone:80`)
- `/mode [fail/success]` - Switch between Nat 1 and Nat 20
- `/setting [flavor]` - Change the theme (Fantasy, Sci-Fi, etc.)
- `/system [ruleset]` - Set D&D 5e, Pathfinder, etc.
