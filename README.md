**Edited version of https://github.com/JacksonRiffs/GLM-4.7**

Changes:

Added prompt blocks:

  Tracker - Allows use of SillyTavern Tracker/SillyTavern Tracker - Enhanced () instead of 'Info Board'.
  
  Stage Directions - Allows use of text enclosed with <[ ]> braces to act as stage directions from the user.
  
  Past Events - Allows insert of Worldbook entries using 'Outlet' injection type (useful for summarised memories).
  
  Vectorised Chats - Allows chat snippets vectorised with Vector Storage Add-on to be inserted into the system prompt.

Regex to hide Stage Directions (regex-hide_stage_directions.json)

Changed:

  Checklist block edited to slightly chanage POV and add:

    12. **POV Check:** Ensure that all references to {{user}} in your inner monologue are in third person ({{user}}/{{user}}'s).
    
    13. **Kinsey Check:** Ensure that the planned dialogue is consistent with Dan's Kinsey scores from the Tracker Block.
    
    14. **Drugs and Alcohol use:** If Dan has consumed drugs or alcohol, consider the effects.
    
    15. **Stage Directions:** If the previous reply included <[stage directions]>, these *must* be followed by weaving them into your planned reply in an authentic and natural way. If no stage directions are given, skip this check.


Original README.md:
# GLM-4.7
My Frankenstein's Monster of a Preset for GLM 4.7
This was put together using some of my favorite parts of other presets with some additional tweaking from myself.
Intended for use with the z.ai coding plan.
