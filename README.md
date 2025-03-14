<p align="center">
  <img src="https://i.imgur.com/DffARTu.png" alt="Players List" width="700">
</p>
<br>

<p align="center">
  <img src="https://i.imgur.com/5O0bDqA.png" alt="Players List" width="700">
</p>

# Reveal R* SCID (RID) Auto-Refresh on Profile Change

This userscript fetches Social Club main user info and displays a custom overlay with detailed stats. It automatically refreshes when the profile URL changes and provides comprehensive data without overwhelming your profile view.

## 🔥 Features

- **Automatic Profile Refresh:**  
  Auto-detects URL changes and refreshes the displayed data when navigating between Social Club member profiles.

- **Main User Info:**  
  Retrieves Social Club main user details including name, RID, status, and privacy settings.

- **RDO Rank & Mugshot:**  
  Fetches and displays the player's RDO rank (inserted right below Total Friends) along with the RDO mugshot.

- **Challenge Stats:**  
  Retrieves and shows RDO Activity Logs with challenge goals, progress bars, and timestamps.

- **Money Stats:**  
  Displays cash statistics (total cash earned/spent) and—if the game is RDR2—gold stats (deposited/withdrawn).

- **Ability Cards:**  
  Presents predefined ability cards for COMBAT and DEAD EYE categories.

- **Weapon Stats:**  
  Shows detailed weapon statistics (kills, deaths, shots, hits, headshots) within a dedicated dashed box.

- **Criminal Record:**  
  Includes a block showing the number of homicides, capital murders (LEOs), mass homicide/vehicular manslaughter, active fugitive status, and corpse despoiling.

- **Games Information:**  
  Lists owned games (with special treatment for GTAV and RDR2) along with last seen information and, for RDR2, the cash/gold details.

- **Friends List:**  
  Displays a collapsible list of friends with avatars and RIDs (with copy-to-clipboard functionality).

- **Suspicious Stats Detection:**  
  Checks money and gold values against set thresholds and flags the account as modded (M) or non-modded (NM) with a visual indicator in the top-right corner.

- **Custom UI Overlay:**  
  Inserts a styled, collapsible box that organizes friends, challenge goals, and additional RDO stats.

- **Error Handling & Rate Limiting:**  
  Only fetches data for the main user to avoid 429 errors and gracefully handles errors by displaying a clear error message when needed.

## 📦 Installation

1. Install a userscript manager such as [Violentmonkey](https://violentmonkey.github.io/) or [Tampermonkey](https://www.tampermonkey.net/).
2. Create a new userscript and paste the script into it.
3. Save the script.
4. Visit any Social Club member profile page (e.g., `https://socialclub.rockstargames.com/member/USERNAME`) to see the script in action.

## ⚙️ Usage

- **Automatic Data Fetching:**  
  The script automatically fetches and displays the user’s stats in a custom overlay when you navigate to a Social Club profile page.

- **Profile Change Detection:**  
  It continuously watches for URL changes, refreshing the data when a new profile is loaded.

- **Collapsible Sections:**  
  Click the toggle icons (e.g., `[+]`/`[-]`) to expand or collapse sections like Friends, RDO Activity Logs, and Additional RDO Stats.

- **Copy-to-Clipboard:**  
  Simply click on the RID (or a friend's RID) to copy it to your clipboard. A small toast notification confirms the action.

## 📜 License

This script is released under the **Restricted MIT License** (but of SCRID).
