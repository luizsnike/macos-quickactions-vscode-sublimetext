MacOS

Enable 'Quick Actions'

Open in Sublime Text

Open in VS Code

Open in Antigravity

Install the application for the action you want.

Copy the '.workflow' file for the desired action to '~/Library/Services'

Right-click the folder you want to open, select 'Quick Actions' and then the desired action.

Code to make others see the image how_make_others.png

This is the code that should be used:

for f in "$@"; do
  open -a 'Application Name' "$@"
done

