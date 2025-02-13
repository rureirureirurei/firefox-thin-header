# Firefox Thin Header

Custom modifications to Firefox that give the header a cleaner, QT-browser-like look.

![Screenshot 1](screen1.png)
![Screenshot 2](screen2.png)

---

## Overview

- Hide default header icons.
- Reduce the header's height.
- More minimalistic, QT-inspired interface

---

## Installation

To apply these modifications, follow these steps:

1. **Enable UserChrome Customizations:**
   - Open Firefox and navigate to `about:config`.
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
   - Set it to **true** if it isn't already.

2. **Locate Your Firefox Profile Folder:**
   - In Firefox, click on the menu button and go to **Help > More Troubleshooting Information**.
   - Under **Application Basics**, click **Open Folder** next to **Profile Folder**.

3. **Set Up the `chrome` Folder:**
   - If it doesn't exist, create a new folder named `chrome` inside your profile folder.

4. **Copy the File:**
   - Place the provided `userChrome.css` file from this repository into the `chrome` folder.

5. **Restart Firefox:**
   - Restart the browser to see the changes take effect.

**The chrome folder has nothing to do with Google Chrome—it's just ambiguous naming.*

---

## Author

*Created by rureirureirurei*  
If you use or modify this project, please keep the credit intact.

---

Happy browsing!
