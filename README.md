# ck3_intrigue

CK3 Mod focused on schemes, interactions, and overall scheming balancing.

------
## Current Features
- Schemes
    - Hostile
        - Antagonize Council
        - Antagonize Spouse
        - Convert Faith
        - Intimidate
        - Instigate Revolt
        - Tarnish Reputation
        - Theft
    - Personal
        - Mentor Skill
    - Warfare
        - Warfare Misinformation (-enemy_army_speed)
        - Raid Supply Routes (-enemy_supply_duration/+supply_duration)
- Levelled-Trait with positive & negative tracks.
    - Gain positive-track XP and bonuses as schemes are successful
    - Gain negative-track XP and maluses as schemes and secrets are exposed
- Schemes have more chances to fail, be discovered, and agents are more difficult to recruit
- Rules to activate/deactivates schemes & levelled-trait
------
## Requirements
- Travel the Distance
------
## Compatibility
- Overwrites no vanilla files, but overwrites some scheme & secret-related effects vanilla functions as well as NScheme from defines.
- Should be compatible with most mods. No testing on compatibility yet.
------
## Outstanding Bugs
- Some missing localization
------
## Improvements/Todo
### Graphic Design
    - Mod Thumbnail
    - Icons Warfare Interaction/Schemes
    - Icons Schemes
    - Icons Trait
        - The number of sub-icons/colour combinations can be higher than 4 as the trait is 10 with two tracks, which would allow a smoother color change as the user progress through tracks
        - Sub-Trait Icons (positive/negative) [colour proposal]
            - Schmeing Adept (low/low) [grey]
            - Known Thief (low/high) [red-ish]
            - Ruthless Schemer (high/high) [golden-red-ish]
            - King/Queen of Shadows (high/low) [golden-ish]
        - Track Icons
            - Prolific Schemer (positive) [gold or green]
            - Known Schemer (negative) [red]
### Localization/Flavor
    - Flavorize all localization
    - Works but can be improved
        - Event Scenes Flavor
### Logic
    - ai_will_do & ai_recipients & ai_potential & ai_blockers for all schemes
    - Add rules for warfare schemes
    - Works but can be improved
        - Improve interaction trait-based stress further
        - Success chances & odds prediction
        - Update countermeasure for schemes
------
## New Features Plans/Ideas 
    - Targetted find secrets
    - Investigate true parents
    - Start fires in capital (development hit)
    - Warfare Schemes
        - Deploy Scouts (+army_speed)
        - Guerrila Warfare (+enemy_hostile_territory_attrition)
------
## Testing
    - Scheme Invalidations
    - Everything