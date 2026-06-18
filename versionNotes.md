##  Release v0.1-devbuild

The first functional development build of RYÛKO, ready for testing and designated version 0.1-devbuild. 
A simple high stakes duel between two characters, Drgon and Tiger, each with a randomised deck, each conforming to the basic statistics system and featuring a broad range of cards. See the rulebook for more info on rules.

* Available here for Mac Silicone and Windows x64. 
* Please lodge your bugs at https://github.com/evilgoosey/RYUKOpublic/issues 

Many thanks and have fun!

##  Change Log v0.1-devbuild

This update introduces a major overhaul to the combat system, focusing on procedural generation and clearer mechanics.

##  Combat System Overhaul
*   **New Alignment Rules:** Block logic is now simpler and easier to process at a glance. Blocks must now **match** the Zone of the attack and oppose the Angle. 
    *   *Angle Example: Horizontal blocks meet Vertical attacks* 
    *   *Zone  Example: Inside blocks meet Inside attacks.*
*   **Procedural Blocking:** Block cards are no longer static. The system now generates hundreds of unique block cards 
*   **Block Qualities:** Blocks now have distinct qualities such as follow-up effects, motion breaks, and balance breaks. Blocks now balance qualities against the raw chance of being relevant blocks. 
*  **Naming Conventions** "Arm" Attacks are now called "Strike" Attacks.

##  Card Library & Generation
*   **Expanded Deck:** The card pool has grown significantly to include roughly **116 new unique cards**.
*   **Procedural IDs:** Attack and Block cards currently display their internal ID/Seed number while formal naming conventions are being developed.
*   **Technique Updates:** Various bug fixes applied to Technique card execution.

##  Gameplay & Balance
*   **Increased Difficulty:** NPC behaviour has been tweaked to be more aggressive, specifically regarding card drawing and turn-passing strategies.
*   **Injury System:** Fixed an issue where injury cards were not able to be discarded correctly.

##  User Interface
*   **Improved Verbosity:** UI text has been expanded to help new players understand deck mechanics and combat states faster.

---
**Known Issues:**
*   Formal names for procedural cards are still in development (currently showing IDs).
*   NPCs still shakey with discarding injuries and some techniques.
