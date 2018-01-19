Provisioning Polycom in Freeswitch

Default Provisioning template is basic

NB! Provision over http unless you import the SSL keys or the phone will not pick up the config
Using windows create an option 160 DHCP option

For some reason using the Keys or Profile config within the Device drives the inital line registration to all the Polycom display slots over writing any contacts/directory/blf you may have configured

You can manually control this with the lineKey.reassignment.enabled="1" parameter in the config file

