# How to reverse engineer hidden Shortcuts actions

Look for action identifiers in system files (using e.g. the strings and grep shell commands),  especially in the Tools-prod sqlite file, which can be found in /private/var/mobile/Library/Shortcuts/ToolKit/ on iOS (but because of denied read permissions, you have to access it from iOS backup files, where it's in HomeDomain/Library/Shortcuts/ToolKit/), and on macOS it's in ~/Library/Shortcuts/ToolKit/ (the iOS one contains mostly iOS action ids, the macOS one mostly macOS action ids)

You can find examples of action ids by copying a random action in Shortcuts app and then run the following shortcut which converts the action in clipboard to source: https://www.icloud.com/shortcuts/65d36be39c5a49cc8121e4ea652b606e

When you have an action id you want to try, insert it between the string tags in the following template plist:
~~~xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>WFWorkflowActionIdentifier</key>
	<string></string>
</dict>
</plist>
~~~
Now copy the edited plist to the clipboard and convert the clipboard content to a pastable action with for example the following shortcut: https://www.icloud.com/shortcuts/49dfc2487764413a88c1329703dd76d1

Finally paste the clipboard content into a shortcut and see how it goes
