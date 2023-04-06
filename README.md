# reloadNode
Simple script that updates the localization and reload missing frames with selecting the read node and pressing 'shift+u'. 

## install
1. Add the following to your menu.py:

nuke.menu('Nodes').addCommand('Golan gizmos/Golan/reloadNode', "reloadNode.cacheNode()", "shift+u")
