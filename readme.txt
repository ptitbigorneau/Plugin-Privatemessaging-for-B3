# privatemessaging plugin
# Plugin for B3 (www.bigbrotherbot.com)
# www.ptitbigorneau.fr

privatemessaging plugin (v1.1) for B3

Installation:

1. Place the privatemessaging.py in your ../b3/extplugins and the 
privatemessaging.ini in your ../b3/extplugins/conf folders.

2. Open your B3.xml file (default in b3/conf) and add the next line in the
<plugins> section of the file:

<plugin name="privatemessaging" config="@b3/extplugins/conf/privatemessaging.ini"/>

4. Run the privatemessaging SQL script (privatemessaging.sql) on your B3 database