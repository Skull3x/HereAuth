HereAuth
===
Your auth plugin is here, for you. The PocketMine auth plugin with the most customization ever.

```
Copyright (C) 2016 PEMapModder
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
```

Project created (first byte written): Jan 14 2016

Features
===
* Authentication by typing password into chat
    * sorry, no alternative, but there is an option to disallow passwords starting with slashes
* Blocks player from talking password into chat directly
    * disable this in config
* Players can choose not to register (but using the /register command to start registering)
    * enable this in config
* MySQL (W.I.P.) or filesystem (JSON) database support
* Count-limit or rate-limit accounts per IP (account-throttle)
* Time-based and attempts-based brute-force protection
* Customized automatic authentication methods
    * By "customized", I mean to customize **per player**!
* Customized multi-factor authentication methods
* Customized data masking when player is not authenticated
    * Don't let impostors see what is in your inventory/where you are! (W.I.P.)
* Server-customized events to block when not authenticated
    * Only blocks events that you want to block!
* Enforced password control
    * Maybe we are being nanny, but we should disallow players to have weak passwords!
* Require custom extra information from players
* Server-customized messages
* Login logging (W.I.P.)
* An extensive API (W.I.P.)