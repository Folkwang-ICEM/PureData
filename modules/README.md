# modules
A collection of pd modules that either already do something on their own, or that can be used together with other modules to create a more complex patch.
## triggers
This is a pd module for use in cue/trigger based patches. It can handle "next-trigger", "last-trigger" and "reset-trigger" messages and holds/sends the "current-trigger". Other modules in a patch would then receive the "current-trigger" and react accordingly. One can also use the GUI to set the current-trigger or set up a midi or keyboard input to provoke a "next-trigger".