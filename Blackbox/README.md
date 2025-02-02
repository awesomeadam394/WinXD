# Blackbox
The Blackbox is one of the more useful components in WNT. It is a graphical user interface that works regardless of the
client's current state.

![https://media.videogamesm12.me/OPdtut5b0zA3vCA4.png](https://media.videogamesm12.me/OPdtut5b0zA3vCA4.png)

## Tabs
The Blackbox currently has 4 tabs in it, with each one providing a unique set of information. Here's what each tab has:

| Tab      | Description                                                   |
|----------|---------------------------------------------------------------|
| General  | The left side of the text in the in-game F3 menu.             |
| Players  | A table of players that the client knows is currently online. |
| Entities | A table of entities currently loaded by the client.           |
| Maps     | A table of map art data currently loaded in by the client.    |

## Notice for Linux and MacOS users
Due to an unusual bug in how Linux and MacOS render things in JSwing (one which causes the entire JVM to crash when
using the Blackbox), I've made the decision to disable the component for users running those operating systems for the
sake of stability.

The way to mitigate the issue in question will likely be to run the Blackbox as a separate process from Minecraft's,
however this has yet to be implemented.