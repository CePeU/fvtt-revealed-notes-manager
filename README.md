![Latest Release Download Count](https://img.shields.io/github/downloads/farling42/fvtt-revealed-notes-manager/latest/module.zip)

# Introduction 

This module provides an option to have a 'revealed' state on scene Notes.

When enabled, then the 'revealed' state will be used to determine if the Note is visible to players.

(The default Foundry VTT behaviour is for Notes to be visible to players only if the linked document is accessible by the player.)

There is an option to set the tint colour of the Note icon to indicate if the linked document is reachable or not (if the Note has no linked document, then it will always be displayed in the "unreachable" tint).

# Use - Note Configuration Panel

Two new options appear in the Note configuration panel (select the Notes layer, and double right-click on a note to open the configuration panel).

**Use Reveal State** will enable the Note to be managed by this module.

**Revealed to Players** will indicate whether this Note is visible to players or not.

# Use - Module Settings

The Module Settings window provides two configurable parameters:

**Note Tint Colour when linked** is used to tint the Note icon when the Note's linked document is reachable by the player (reachable means that the player has at least LIMITED permission on the linked document).

**Note Tint Colour when not linked** is used to tint the Note icon when either the Note has no linked document, or the linked document is not reachable.

*(There are other modules which allow Notes to be created without being linked to a document.)*

## Support

If you like what it does, then all contributions will be gratefully received at [Kofi](https://ko-fi.com/farling) or [Paypal](https://paypal.me/farling)
or if you're feeling really generous you could set up a regular contribution at [Patreon](https://www.patreon.com/amusingtime) 
