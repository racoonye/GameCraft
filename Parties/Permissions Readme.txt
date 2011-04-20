Below are the permission nodes you can use.  These nodes
simply overrule the default configuration file.  If a player
has none of the below permissions, his default chat/tp
permissions will be whatever is in the config file.  You can
easily make blacklists / whitelists using the below nodes in
conjuntion with the config file.  Also note, that in this case
if a player has both the allow and deny node for something,
the allow will take precedence.  This is so that in case a user
group inherits a deny permission, you can still allow them to
do somthing.

Permissions Nodes:
parties.allow.chat
parties.deny.chat
parties.allow.tp
parties.deny.tp
parties.allow.join
parties.deny.join
parties.allow.create
parties.deny.create