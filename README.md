[![Build Status](https://dev.azure.com/usysware/dpack/_apis/build/status/usysware.dpack?branchName=master)](https://dev.azure.com/usysware/dpack/_build/latest?definitionId=1&branchName=master)
![Azure DevOps tests (branch)](https://img.shields.io/azure-devops/tests/usysware/dpack/1/master)

[[What is DPack Rx]](#what-is-dpack-rx) [[What's included]](#what-features-are-included-so-far) [[Major changes]](#major-changes) [[Future plans]](#future-plans) [[Contribute]](#help-needed) [[Donate]](#donate)

# DPack is in BETA!

Please be aware that [DPack Rx](https://marketplace.visualstudio.com/items?itemName=SergeyM.DPackRx) currently is and will remain for a while in **BETA** status. Tread carefully and report any issues you might find. Thanks!

### DPack Rx (former DPack)

FREE tools collection designed to greatly increase developer's productivity, automate repetitive processes and expand upon some of Microsoft Visual Studio features. Visual Studio 2017 and 2019 are supported.

### What is DPack Rx?

DPack Rx is an effort to remedy former [DPack](https://marketplace.visualstudio.com/items?itemName=SergeyM.DPack-16348) limitations: bring it under OSS umbrella, upgrade it for more modern Visual Studio integration, and apply more modern technology and development practices. I also felt the effort needed a new product name.

Driving principal behind DPack design is fire-and-forget user experience with minimal impact on the development environment. To adhere to that principal most of the major features are invoked on demand, present a dialog (if applicable), which goes away once user interaction ends. Little to no impact on the development environment is expected from thereafter. Taking all that into account, features such as ToolWindow support don't fit well into that design paradigm.

### What features are included so far?

-	*File Browser* feature

![FileBrowser](https://user-images.githubusercontent.com/55639583/73682340-35322300-468e-11ea-8984-d224cea72995.gif)
-	*Code Browser* feature

![CodeBrowser](https://user-images.githubusercontent.com/55639583/73682351-395e4080-468e-11ea-9126-c762fd39e4ad.gif)
-	*Bookmarks* feature

![Bookmarks](https://user-images.githubusercontent.com/55639583/73682355-3bc09a80-468e-11ea-94b6-226f257932d6.gif)

- *Surround With* feature - serves as a shortcut for built-in subset of Visual Studio Surround With templates

### Major changes

- Both *File Browser* and *Code Browser* features UI has been revamped completely in WPF
- *Bookmarks* feature has been rebuilt from the ground using editor taggers
- *Bookmarks* feature bookmarks are no longer saved with the solution. This might be subject to change in the future
- *Bookmarks* feature ToolWindow's been deprecated
- Former browsers *ToolWindow Mode* is no longer available (see the note above on design principals)
- *Solution Browser* rather infrequently used feature won't be migrated. If you rely on it then consider staying with older DPack extension
- *Code Navigation* obscure feature won't be migrated either
- *Surround With* feature has been considerably simplified

### Future plans 
- ~~CI pipeline setup~~
- ~~Publish to Visual Studio Gallery~~
- ~Setup Wiki page~
- Migrate former DPack *Solution Backup* feature
- Migrate former DPack *Solution Statistics* feature

### Help needed

- Testing the latest beta on VS 2017 and 2019
- Graphics for DPack's menu items

Thanks and enjoy.

Sergey @ USysWare

### Donate

If you wish to express your appreciation 
for the time and resources the authors have expended developing and supporting 
DPack over the years, we do accept and appreciate donations.
You can contribute via PayPal donate button below.

Thank you for your support!

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif "Donate")](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=DXDC8CEJZRQLE&source=url)
