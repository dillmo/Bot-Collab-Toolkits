Bot Collaboration Toolkits
==========================
This repository serves as the source for the Bot Collaboration Toolkits. They
are designed to improve the intelligence of Awesomenauts bots by having them
provide information to each other.

Contributing
------------
In the spirit of open source, anybody can contribute to the project. To do so,
you can create plugins. These are behavior trees that allow bots to both send
and recieve certain information. To create a plugin, first create a file
Mod_BotCollab_Plugin_PluginName.xml. Then add an executeBehaviourTree block for
it in Mod_Bot_Collab_Plugins.xml. From then on, you only have to build out your
plugin from the file you created. To see how you should code your plugin, have
a look at other plugins, such as Mod_BotCollab_Plugin_Class.

All non-release code can be found in the folder, Experimental. Please put your
plugin here.
