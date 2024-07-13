# Installations for Windows 10/11

## Thai Fonts

1. If you do not install Thai fonts like `TH Sarabun New` yet, please consider to [download from here](../../assets/thaifonts.zip).
1. Unzip and install into the system.

## MikTeX

1. Browse to [MikTeX.org](https://miktex.org) and [download](https://miktex.org/download/ctan/systems/win32/miktex/setup/windows-x64/basic-miktex-24.1-x64.exe)
1. Install `basic-miktex`. 
	- Make sure that you are always connected to the internet.
	- For installation missing package on-the-fly, choose `Yes`.
1. After successfull installation of MikTeX, open `MikTeX Console` and then `Update` the packages. Next, install `thaispec` package.

## Perl

1. Since we are going to automate the process in LaTeX typesetting, we need to download [Perl for Windows](https://strawberryperl.com) from [here](https://github.com/StrawberryPerl/Perl-Dist-Strawberry/releases/download/SP_53822_64bit/strawberry-perl-5.38.2.2-64bit.msi).
1. Install `strawberry-perl`. This may require administration password to proceed.

## Visual Studio Code

1. In this course, we recommend [Visual Studio Code](https://code.visualstudio.com) for typeseting LaTeX, you may [download here](https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user).
1. After successfull installation of Visual Studio Code, launch the application and browse to the extension panel.
1. Seach for the extension called `LaTeX Workshop` (developed by James Yu) and install it.
1. Open setting (Ctrl+,),  search for `forceRecipeUsage` and then disable this option.