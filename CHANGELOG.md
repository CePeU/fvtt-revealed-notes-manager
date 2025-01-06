## 3.0.0

- Working in Foundry V13 only.

## 2.5.1

- Mark as NOT compatible with Foundry V13.

## 2.5.0

- Ensure compatible with Foundry V12 with no compatibility warnings.

## 2.4.4

- Prevent error when a field not related to this module is updated in the Note Config Dialog.

## 2.4.3

- Foundry V11: Get modifications to a Note's revealed state to immediately update on all player's screens too.

## 2.4.2

- Mark compatible with Foundry 11 (299)

## 2.4.1

Don't set the Note's icon tint in setNoteRevealed.

## 2.4

Change the way that Notes are drawn so that this module's tint colour is not permanently stored in the Note, so that the Note's original tint can be used when a specific icon tint is not set by this module.

## 2.3

Provide tint colours to allow GMs to see if notes have been revealed to players. Setting the tint to a blank string will remove this tinting.

## 2.2

Use Note#isVisible as the control mechanism for visibility to players.

## 2.1.1

Update minimum compatible version to V10

## 2.1

Fix problem with Notes never appearing to players.

## 2.0

Update module.json for Foundry 10 compatibility.

No other code changes are required.

## 1.0

Migrate from being embedded in the realm-works-import module to be its own stand-alone module
