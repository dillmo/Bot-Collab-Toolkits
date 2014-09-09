Bot Collaboration Toolkits
==========================
This repository serves as the source for the Bot Collaboration Toolkits. They
are designed to improve the intelligence of Awesomenauts bots by having them
provide information to each other.

Contributing
------------
In the spirit of open source, anybody can contribute to the project. There are
two ways you can help. You can either modify the file,
Mod_BotCollabToolkit_Allnauts.xml, or you can create your own collab toolkit
for your own bot. These latter ones are designed to contain code specific to
collaborating with your bot. For instance, a Swiggins AI might report that he
has somebody hooked so that other bots could choose whether to help ganking.

Any modifications you make should be documented under the section, Usage. If
you are making a bot-specific toolkit, place the documentation under a
subsection for it.

Any added functionality should be in a certain format. You must have code that
has an AI automatically serve data, which contains the information (i.e. team
fight over here), as well as a magnitude if applicable. This magnitude can also
be calculated by the reciever, if easier, and is used to make it easy for bots
to prioritize events. The reciever code should simply set some values based on
the data it recieves, such as setting a bool isTeamFight to true and
teamFightPriority to 8. These priorities should calculate however you think is
best and there is not limit to them. If you think something should be 1-4 or
1-100, it is totally up to you.

Usage
-----

### AllNauts

### BrainyVoltar
