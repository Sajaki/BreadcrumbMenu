Breadcrumb Menu for phpBB
========================

Extension for phpBB 3.3 to turn the breadcrumb navigation into a forum tree menu.

## Version
v1.0.8 (17-04-2021)

![Screenshot](screenshot.png)

## Features
- Adds a drop-down menu to each breadcrumb (using jQuery UI), containing the sibling and child forums.
- Triggers on mouse-enter, no clicks required (this keeps the breadcrumbs working as normal when clicking on them).
- Auto-hide when the user moves the cursor outside of the menu.
- Support for touch devices.
- Supports the official phpBB Pages extension.

#### Minimum Requirements
- phpBB 3.2.0
- PHP 5.4.0

## Install
1. [Download the latest release](https://github.com/Sajaki/BreadcrumbMenu/releases) and unzip it.
2. Copy the entire contents from the unzipped folder to `/ext/paybas/breadcrumbmenu/`.
3. Navigate in the ACP to `Customise -> Manage extensions`.
4. Find `Breadcrumb Menu` under "Disabled Extensions" and click `Enable`.

## Uninstall
1. Navigate in the ACP to `Customise -> Manage extensions`.
2. Click the `Disable` link for `Breadcrumb Menu`.
3. To permanently uninstall, click `Delete Data`, then delete the `breadcrumbmenu` folder from `/ext/paybas/`.

### License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2015 - PayBas