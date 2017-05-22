# System Requirements

This documents the decisions made concerning the devices and core components of the fitboard system. It does not provide in depth explanation of how these tools function. This document is broken down based on the requirements of the system.

#

### Breakdown:

**System Goal:** Pressing a button on the Fitboard results in an action in the game.

**Goal Requirements:** 

- [Engine for Games and App](#requirement-engine-for-games-and-app)
- [Scripting language for game control](#requirement-scripting-language-for-game-control)
- [Hardware to relay button presses to computer](#requirement-hardware-to-relay-button-presses-to-computer)
- [Computer input recognition of fitboard](#requirement-computer-input-recognition-of-fitboard)
- [Game recognizes input received from fitboard](#requirement-game-recognizes-input-received-from-fitboard)

#

### Requirement: Engine for Games and App

**Decision:** Unity Engine

- Free
- Can build for many end platforms
- Well documented
- Online support widely available
- Many pre-made assets available in Unity Store
- Team has experience in using this program

#

### Requirement: Scripting language for game control

**Options:** Using Unity the options are C#, JavaScript for Unity (UnityScript), and Boo

**Decision:** C#

- Supported by Unity
- Team has experience in C languages
- C# more widely used by online community, helpful for Q&A forums

#

### Requirement: Hardware to relay button presses to computer

**Decision:** Arduino Mega `// @NickSullivan more info needed`

- The Arduino is easily programmable (and reprogrammable)
- Low Cost
- Team already had experience for pursuing this option

#

### Requirement: Computer input recognition of fitboard

**Decision:** Custom Arduino Driver

- Fast recognition
- Convert fitboard input to key interrupts which can be read by Unity's Input class

#

### Requirement: Game recognizes input received from fitboard

**Decision:** TBD.
