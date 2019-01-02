### Network Plugin for Kibana ###

This is a plugin developed for Kibana that displays a network node that link two fields that have been previously selected.


**Installation Steps from release**
Now this plugin is avalible for differents versions of Kibana (6, 5 and 4), in releases you can download the plugin with all its dependencies installed:

**Go to releases and download the right one for your Kibana**
unzip/untar it into KIBANA_HOME/plugins
Start your Kibana

**Installation Steps from GitHub source code**

Move into plugins folder:  cd KIBANA_HOME/plugins

**Install dependencies:**

cd network_vis
rm -rf images/
npm install

**Start Kibana**

Important: If you have any problem with the plugin version (like a warning message "it expected Kibana version "x.x.x", and found "x.x.x"") only change the value of the "version" tag on the package.json to your Kibana version

**Uninstall:**
cd KIBANA_HOME
rm -rf plugins/network_vis/
Types of networks
Two types of Nodes:
It can select 'Node'-'Node' in buckets to show a network that link two types of nodes. Each type is the result of the field selected.


## Types of networks ##

**Two types of Nodes:**
It can select 'Node'-'Node' in buckets to show a network that link two types of nodes. Each type is the result of the field selected.

https://github.com/dlumbrer/kbn_network/blob/master/images/Easy.png

**Nodes linked by a Relationship:** 
First, select 'Node' on buckets for build the network of one type of nodes, it depends of the field it has been selected. After, select 'Relation' to link the nodes through a relationship that depends of the field it has been selected.

https://github.com/dlumbrer/kbn_network/blob/master/images/Types.png

**Additional Features:**
Intially each node is not stablized in visuzation, it has been keepon roaming around the browser window. After that We stablize those nodes with fixed location, whenever new data loaded it's not changed. Its been formed like Parent-Child Relationship. 









