# Developer Workspace

Notes and settings files for configuring a developer workspace can be time
consuming. This repository has the settings that
[kriswuollett](https://twitter.com/kriswuollett) uses. Although this repository
is not meant to be customizable for different individuals, suggestions are
welcome through filing issues or sending a pull request. That being said, feel
free to adapt to your own personal developer workspace as you deem appropriate.

# Keyboard Shortcuts

Keyboard shortcuts among the OS and power user apps like developer tools are
often in conflict. In addition, one may prefer using a standard three-button
mouse instead of a trackpad. To accommodate these situations, one approach is to
customize the OS-level keyboard shortcuts in a way that minimizes conflict with
application-level keyboard shortcuts. This has the 

For example on macOS, the Mission Control keyboard shortcuts can be updated to
virtually match the
[trackpad multi-touch](https://support.apple.com/en-us/HT204895) for the same.
Similarly the Input Sources change shortcut, which normally is `Ctrl-Space`, can
be updated to avoid conflicting with code completion in many IDEs. On Apple
systems, an __Input Source__ is the mechanism in which different writing systems
can be used. Even if not multilingual, its important for a developer to insure
that different languages will display properly. The alignment of text can be
altered in unexpected ways if emojis, symbols or logograms are mixed with the
Latin script for example.

The following tables contain a summary of some of the changes.

Key | Description
--- | --------------------------------------------------------------------------
⌘ | Command (macOS), Windows (Windows)
⎇ | Alt, Option (macOS)
^ | Control
⇧ | Shift

Platform | Category | Shortcut | Keys | Reasoning
-------- | -------- | -------- | ---- | ---------
macOS | Launchpad | Show Launchpad |  ^⎇⌘K | macOS 4-finger swipe _**up**_, J is Vi move _**up**_
macOS | Mission Control | Mission Control | ^⎇⌘↑ | macOS 4-finger swipe up
macOS | Mission Control | Show Notification Center | ^⎇⌘L | macOS 2-finger _**right**_-edge to left, L is Vi move _**right**_
macOS | Mission Control | Application windows |  ^⎇⌘↓ | macOS 4-finger swipe down
macOS | Mission Control | Move left a space |  ^⎇⌘← | macOS 4-finger swipe left
macOS | Mission Control | Move right a space |  ^⎇⌘→ | macOS 4-finger swipe right
macOS | Input Sources | Select the previous source in Input Menu | ^⎇⌘Space | macOS defaults conflict with common code completion shortcuts
macOS | Input Sources | Select next source in Input Menu | _remove_ |　macOS seems to ignore this shortcut
