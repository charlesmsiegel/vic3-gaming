# INSTALLATION_GUIDE.md

# Victoria 3 Gaming Industry Mod - Enhanced Edition
## Installation Guide and File Overview

This document provides instructions for installing the enhanced version of the Gaming Industry Mod for Victoria 3, as well as an overview of the new features and files.

## Installation Instructions

1. Create a folder named "gaming_industry" in your Victoria 3 mods directory:
   - Windows: Documents\Paradox Interactive\Victoria 3\mod\gaming_industry
   - Mac: ~/Documents/Paradox Interactive/Victoria 3/mod/gaming_industry
   - Linux: ~/.local/share/Paradox Interactive/Victoria 3/mod/gaming_industry

2. Extract all files into this directory, maintaining the folder structure.

3. Create a copy of the descriptor.mod file in the parent mod folder (outside the gaming_industry folder) and rename it to gaming_industry.mod.

4. Edit the path in gaming_industry.mod to point to "mod/gaming_industry".

5. Launch Victoria 3 and enable the mod in the launcher.

## New Features Overview

This enhanced version of the Gaming Industry Mod adds the following improvements:

### Economic Balance Refinements
- Rebalanced building employment structure and profits
- Progressive scaling of gaming establishments
- Better balanced production methods

### Technology Pacing
- Added intermediate technologies to smooth progression:
  - Recreational Codification (between Traditional and Modern Gaming)
  - Game Systemization (between Chess Academy and Professional Gaming)
  - Narrative Mechanics (between Advanced Game Design and Role-Playing Games)

### Interest Group Reactions
- Added modifiers and events for interest group reactions to gaming
- Religious opposition to gambling
- Military enthusiasm for wargaming
- Intellectual interest in strategic games

### Regional Gaming Traditions
- Added production methods for regional games:
  - Xiangqi (Chinese Chess)
  - Backgammon (Mediterranean/Middle East)
  - Tafl Games (Nordic)
  - Hanafuda (Japanese)
- Added events for cultural exchange through gaming

### Colonial Gaming Exchange
- Added events for interaction with indigenous gaming traditions
- Options to appropriate, exchange, or suppress local games
- Cultural and economic consequences of different approaches

### Gaming and Education
- Added Gaming School building for educational integration
- Events for strategic education initiatives
- Military applications of gaming education

### Great Buildings
- Added National Gaming Academy great building
- Significant prestige, education, and diplomatic benefits

### Laws
- Added Gaming Regulation law group:
  - Regulated Gaming (balanced)
  - Gaming Prohibition (religious/moral focus)
  - State Gaming Monopoly (state control)

### Trade Routes and Resources
- Added luxury production methods requiring exotic trade goods:
  - Luxury Chess Sets (ivory, gold, silk)
  - Luxury Casino (fine art, luxury clothes, liquor)
- Events for exotic gaming materials trade

### Diplomatic Tournaments
- Events for using gaming as diplomatic tools
- Options for inclusive tournaments, alliance-exclusive events, or rival diplomacy
- East-West gaming summit events

### Celebrity Gamers
- Added character traits for gaming celebrities
- Events for emerging chess champions
- International recruitment and brain drain mechanics

### Secret Gaming Societies
- Underground casino events in prohibitionist societies
- Secret chess societies in unmodernized nations
- Options for crackdowns or tolerance

### Regressive Gaming Elements
- Added historical figures representing problematic gaming ideologies:
  - Viktor Roth (ultranationalist wargame designer)
  - Edmund Blackwood (occult reactionary game designer)
- Events exploring racial hierarchy in games
- Options to embrace, moderate, or reject regressive elements

### Journal Entries
- Added new guided objectives:
  - Gaming Diplomacy (diplomatic use of gaming)
  - Regional Gaming Traditions (cultural diversity)
  - Luxury Gaming Trade (exotic materials trade)

## File Structure

The mod contains the following new or modified files:

### Common Files
- common/buildings/13_gaming_establishments.txt (updated)
- common/character_traits/gaming_traits.txt (updated)
- common/historical_figures/gaming_figures_extension.txt (new)
- common/laws/gaming_laws.txt (new)
- common/modifiers/gaming_modifiers.txt (updated)
- common/production_methods/gaming_pms.txt (updated)
- common/technology/gaming_technology.txt (updated)
- common/great_buildings/gaming_great_buildings.txt (new)
- common/journal_entries/gaming_journal_entries_extension.txt (new)

### Events Files
- events/gaming_industry_events_extension.txt (new)

### Localization Files
- localization/english/gaming_extension_l_english.yml (new)
- localization/english/gaming_tooltips_l_english.yml (new)
- localization/english/gaming_journal_entries_extension_l_english.yml (new)

### GUI Files
- Various new icons as listed in gfx/gaming_industry_extension_gui.txt

## Creating GUI Assets

The mod requires several new icons. Follow the style guide in gfx/gaming_industry_extension_gui.txt to create or source these icons. All icons should be in DDS format with the following specifications:
- Format: DXT5/BC3 compression
- MipMaps: Generate MipMaps
- Alpha channel: Required

## Compatibility

- This enhanced version should be compatible with other mods that don't modify the same files
- Compatible with all Victoria 3 DLC up to version 1.8.x
- May have minor conflicts with other mods that add buildings or technologies

## Credits

This enhanced version builds upon the original Gaming Industry Mod by adding new features and improvements while maintaining the original concept and structure.

## Support

If you encounter any issues with this enhanced mod, please report them through the mod's distribution page or community forum.