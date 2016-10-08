Name: Date of Birth on Registration
Description: Adds options to require a date of birth in the registration form, and to deny users under a certain age.
Website: https://github.com/MattRogowski/Date-of-Birth-on-Registration
Author: Matt Rogowski
Authorsite: https://matt.rogow.ski
Version: 1.0.0
Compatibility: 1.6.x, 1.8.x
Files: 2
Templates added: 1
Template changes: 1

To Install:
Upload ./inc/plugins/dobonreg.php to ./inc/plugins/
Upload ./inc/languages/english/dobonreg.lang.php to ./inc/languages/english/
Go to ACP > Plugins > Activate

Information:
This plugin will add options to the registration form for users to enter their date of birth.

You can choose to require a full date of birth, just a day and month, or make it fully optional.

You can also choose to deny users under a certain age.

Change Log:
03/10/10 - v0.1 -> Initial 'beta' release.
05/10/10 - v0.1 -> v0.2 -> Fixed bug where the check would still be run in the Mod CP and Admin CP when editing a profile. Now only checks when you register or edit your own account. To upgrade, reupload ./inc/plugins/dobonreg.php.
13/10/10 - v0.2 -> v0.3 -> Fixed bug where you couldn't edit your birthday properly in the User CP. To upgrade, deactivate, reupload ./inc/plugins/dobonreg.php, activate.
23/10/10 - v0.3 -> v0.4 -> Improved how the birthday is validated and stopped bug where same error would be shown twice. One setting added, added ability to stop people registering or viewing forum if they tried to register and entered an underaged birthday. To upgrade, deactivate, reupload ./inc/plugins/dobonreg.php and ./inc/languages/english/dobonreg.lang.php, activate.
25/08/14 - v0.4 -> v1.0 -> MyBB 1.8 compatible. To upgrade, deactivate, reupload ./inc/plugins/dobonreg.php, activate.

Copyright 2016 Matthew Rogowski

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at

 ** http://www.apache.org/licenses/LICENSE-2.0

 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.