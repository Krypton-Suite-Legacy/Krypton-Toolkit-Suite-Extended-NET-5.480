# <img src="https://raw.githubusercontent.com/Wagnerp/Krypton-Toolkit-Suite-Extended-NET-5.480/master/Assets/PNG/64%20x%2064/KR%2064%20%20x%2064%20Orange.png" /> Toolkit Suite Extended .NET 5.480

=======

## An extension to the Krypton Toolkit suite of controls for .NET framework 4.8

=======

| NuGet | Current NuGet Version | Github License |
|---|---|---|
| [![NuGet](https://img.shields.io/badge/NuGet-Krypton%20Extended%20.NET%205.480-brightgreen.svg)](https://www.nuget.org/packages/KryptonExtendedToolkit5480/) | ![Nuget](https://img.shields.io/nuget/v/KryptonExtendedToolkit5480.svg) | ![GitHub](https://img.shields.io/github/license/Wagnerp/Krypton-Toolkit-Suite-Extended-NET-5.480.svg)

======

## NOTE: 08/07/2018 Background menu colours will be implemented in the comming weeks. Stay tuned for updates!

======

# Building this repository from code

## In order to compile the code, you MUST restore/update the NuGet packages in order to build successfully!

======

## Control Examples

Please refer to [examples](https://github.com/Wagnerp/Krypton-Toolkit-Suite-Extended-NET-5.480/blob/master/Examples.md) to see what each control looks like.

<!--======
## 2019-06-01 Build 10xx - June Update
* New `Palette Explorer` controls
* Merged all settings into `Toolkit Settings.dll`
* Begun work on [#70](https://github.com/Wagnerp/Krypton-Toolkit-Suite-Extended-NET-5.470/issues/70)
* Implemented [NaviSuite](https://github.com/jacobmesu/Guifreaks-Navisuite) by [Jacobmesu](https://github.com/jacobmesu)
* New file varifier app to work with May's file checksum calculator
* Upgraded to Krypton Toolkit Suite - version: **5.470.xxx**
* Build 10xx (build date Saturday 1st, June 2019) is now available on NuGet
-->

<!--======

## 2019-05-01 Build 9xx - May Update
* Outlook 2003 style toast notification
* File checksum calculator (MD5, SHA-1, SHA-256, SHA-384, SHA-512 and RIPEMD-160)
* New `KryptonPaletteManager` class for dealing with creating custom `KryptonPalette`'s
* Ribbon enhancements, merge two ribbons together
* Capture version information from another file
* Playground application reorganisation
* Images of controls to show developers what they look like
* Image resizing utility - resize & save images on the fly
* New palette explorer user controls - will make it quicker to design the application
* Fix palette theme selector, issue [#71](https://github.com/Wagnerp/Krypton-Toolkit-Suite-Extended-NET-5.470/issues/71)
* General tidyup of code & API updates
* XML documentation files for DLLs
* New palette theme selector
* New `KryptonToastNotification` window
* New circular progressbar control
* Random password generator (for use on future user creation dialog)
* New developer API tools for internal development of the toolkit
* Begun re-working the `Palette Explorer` application
* New `Palette Upgrade Tool` application for upgrading any older palette `xml` files
* Theme `*.xml` files are now available to view and edit in the Visual Studio solution under the **themes** folder
* All theme files are now bundled with the NuGet package
* Upgraded to Krypton Toolkit Suite - version: **5.480.901**
* Build 9xx (build date Wednesday 1st, May 2019) is now available on NuGet
-->

======

## 2019-03-10 Build 798
* Build 798 (build date Sunday 10th, March 2019) is now available on NuGet
* New colour wheel colour dialog
* New toggle switch control
* New rounded textbox control
* Integrated `ookii.dialogs` code
* Working on new folder browser dialog and file browser
* New theme chooser component (proof of concept for a more sophisticated UI for next update)
* Groundwork for new elements for next update
* Upgraded to Krypton Toolkit Suite - version: **5.472.720**
* Removed **LinqBridge** requirement, [#48](https://github.com/Wagnerp/Krypton-Toolkit-Suite-Extended-NET-5.470/issues/48)
* Reorganised `Playground` test application

======

## 01-02-2019 Build 700 & Code parity with **5.470**
* All changes since September 2018
* New NuGet package, build 700 (build date Friday 1st, February 2019) is now available

======

## 2018-07-08 Initial Commit
* Reset build paths, so no errors should be incurred.
* One **new** theme called `Slate Silver`, stylised for the 2007/2010 and 2013 theme sets.
* There are now 50+ **new** palettes to choose from.
* A new toolstrip label capable of background gradeints is now available to use, as per [#28](https://github.com/Wagnerp/Krypton-Toolkit-Suite-Extended-NET-4.70/issues/28).
* Colours... colours... colours... We now have 26 **new** colours to choose from! Find the `xml` files in the `Palettes` folder, this will be updated regulary, so be sure to come back often! Alternatively, if you would like to request/submit a colour palette, then please submit a base colour in a hexadecimal format plus a suitable name for it on the `New Palette Ideas` issues thread.
* Tinkering with the References.
* Start to fill out the WIX installer project.
* Nearly completed first design stage of the `Update File Creator`.
* New installer project (Advanced Installer & WIX).
* Laid basic foundation for a designable `Krypton MessageBox`.
* Migrated `packages.config` over  to `PackageReference` (must have the latest Visual Studio 2017 Preview build to utilise this feature).
* `KryptonNumericUpDown` control can now be used on menu & toolbar controls.
* Build output paths changed for neatness
* The **releases** tab is now activated
* New XML files labelled `Update.xml` and `CheckSum.xml` have been created to explain to developers how to use the updater back-end.
* TODO: Connect the framework up to UI elements.
* Begun fundamental groundwork on an XML based application updater (classes/settings/UI).
* Improved documentation with the aid of [GhostDoc](https://marketplace.visualstudio.com/items?itemName=sergeb.GhostDoc).
* New wizard control based off of [Aero Wizard](https://github.com/dahall/AeroWizard) base implemented, ready for conversion to Krypton controls
* New "Most Recently Used" files option for `File` menu, see `Playground` for proper implementation
* A new Windows Forms application `Playground` has been added to test controls and features added to the toolkit.
* Added a new toolstrip menu item UAC shield control
* Added/cleaned up documentation for methods
* New setter/getter methods for certain properties in `Global Utilities`
* New method `ElevateProcessWithAdministrativeRights(string processName)` for elevating your application with administrative rights (to be used in conjunction with the recently added UAC shield controls)
* New `CODE_OF_CONDUCT.md` file for project
* Krypton UAC shield button
* New options for developers to check if the user is running Windows 7 or higher. 64-bit checks will follow soon.
* Extended 'KryptonTextBox' to have watermark functionality.
* Wrapped 'KryptonTextBox' into a `toolstrip container` object to make it easier to add new functionality i.e watermarks.
* New icons for `MessageBoxes`
* New `Globals.cs` class for custom enumerations. (Needs documentation finishing off)
* NOTE FOR FUTURE REFRENCE: Find suitable icons for `MessageBoxes` (CC license maybe?)
* Fixed bug with Krypton outlook grid
* Incorporated a `base Krypton MessageBox` as a reference for extending
* Fully incorporated `Krypton Outlook Grid` code
* Altered assembly info
* Variables and comments with `color` renamed to `colour`
* Added generic C# `.gitignore` file
* Created solution with two class projects inside labelled `Extended Controls` and `Krypton Outlook Grid`
* Automatic versioning
* High DPI support configuration 
