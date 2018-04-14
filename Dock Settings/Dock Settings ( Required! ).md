
//Dock Settings//
Run as, in terminal! ( one by one )
_______________________________________________________________________________________________

*Show Apps Button at Left*

gsettings set org.gnome.shell.extensions.dash-to-dock show-apps-at-top true
_______________________________________________________________________________________________

*Use Custom Dock Indicator ( Required )*

gsettings set org.gnome.shell.extensions.dash-to-dock custom-theme-running-dots false
gsettings set org.gnome.shell.extensions.dash-to-dock custom-theme-customize-running-dots false
_______________________________________________________________________________________________

*Disable Custom Dock Shrink ( Required for Good looking) ( optional )*

gsettings set org.gnome.shell.extensions.dash-to-dock custom-theme-shrink false
_______________________________________________________________________________________________

*Dock Transparency mode ( Required! )*

gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode DEFAULT
_______________________________________________________________________________________________

OK! finish.

NOTE: if you have problem use this
_______________________________________________________________________________________________

Restore to Default.
dconf reset -f /org/gnome/shell/extensions/dash-to-dock/
_______________________________________________________________________________________________
