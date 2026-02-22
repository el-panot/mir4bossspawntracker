# MIR4 Boss Spawn Tracker

A real-time tracking tool for MIR4 boss spawn times across multiple maps and layers. Never miss another boss spawn again!

## Features

- **Real-Time Countdown**: Live countdown timer for each boss spawn with automatic updates every second
- **Multiple Maps**: View boss spawns across all maps including:
  - Continent - Field
  - Mirage Ship - Layer 1
  - Mirage Ship - Layer 3
  - Special Boss locations
  
- **Completion Tracking**: Mark bosses as completed with checkboxes that persist across sessions
- **Smart Sorting**: 
  - Bosses are automatically sorted by completion status (incomplete first)
  - Within each status, sorted by countdown time (soonest first)
  
- **Visual Alerts**:
  - Light red highlighting for spawned bosses that appeared within the last 20 minutes
  - Green countdown text for bosses spawning within 10 minutes
  - Automatic modal showing next 10 bosses to spawn on page load
  
- **Dark Mode**: Toggle between light and dark themes with the floating button
- **Map Filtering**: Filter bosses by specific maps using the sidebar navigation
- **Reset Function**: Clear all completed records with a confirmation dialog

## How to Use

### Basic Navigation
1. Open the tracker in your browser
2. The sidebar on the left shows all available maps
3. Click on a map to filter bosses for that location
4. Click "All Maps" to view all bosses

### Tracking Completion
1. Check the "Completed?" checkbox next to any boss you've defeated
2. Completed bosses move to the bottom of the list automatically
3. Your completion status is saved in your browser (persists across sessions)
4. Use the **"Reset All Completed Records"** button to clear all checkboxes at once

### Understanding the Display
- **Completed?**: Checkbox to mark bosses as completed
- **Area**: The region/world where the boss spawns
- **Boss Name**: Name of the boss
- **Location**: Specific dungeon or area location
- **Spawn Time**: Exact time of the next spawn (in your local time)
- **Countdown**: Time remaining until next spawn in format `Xh Ym Zs`

### Color Indicators
- **Light Red Row**: Boss has spawned and appeared within the last 20 minutes
- **Green Text**: Boss will spawn within the next 10 minutes (urgent!)
- **Normal Text**: Standard countdown display

### Upcoming Bosses Modal
- A modal appears on page load showing the next 10 bosses to spawn
- Auto-closes in 15 seconds or click "Close" button
- Provides quick overview of immediate threats

### Theme Toggle
- Click the floating circular button in the bottom-right corner to switch between light and dark modes
- Your theme preference is saved

## Timezone Important Note

⚠️ **Timers are based on your local time!** Adjust for your server's timezone (e.g., MIR4 Asia servers often use UTC+8)

## Boss Types

The tracker supports:
- **Daily Bosses**: Spawn multiple times per day at fixed times
- **Weekly Bosses**: Spawn once per week on specific days and times

## Support

Developed with ❤️ by GOONS

- **Ko-fi**: [Support us on Ko-fi](https://ko-fi.com/goonsnetwork)
- **WEMIX PLAY**: `0xae9083d1ef02a0a4a341b03a826094568d928cba`

**Not affiliated with Wemade**

## Tips & Tricks

- Use the completion checkboxes to focus on uncompleted bosses
- Enable dark mode for late-night gaming sessions
- The upcoming bosses modal helps you plan your next run
- Green countdown text means act fast - boss spawns soon!
- Light red highlighting shows recently spawned bosses that may still be available
