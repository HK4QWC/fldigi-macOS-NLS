# fldigi-macOS-NLS
This is a repository for fldigi binaries with NLS support compiled for **macOS Sierra**.

Here you will find **fldigi-3.23.21** (2017-01-30) and **fldigi-3.23.22.4** (2017-02-13).

Currently, fldigi includes internationalization files for **Spanish** (es), **French** (fr), **Italian** (it), **Polish** (pl), **German** (de) and **Dutch** (nl).

Fldigi(Fast Light Digital Modem Application) is a cross-platform sound card modem program that supports most of the  digital modes used on the amateur radio bands.

Copyright (C) 2007-2010 Dave Freese, Stelios Bounanos, and others.
License GPLv3+: GNU GPL version 3 or later <http://www.gnu.org/licenses/gpl-3.0.html>

##Quick and easy how-to

1. Download and install [EnvPane](https://github.com/hschmidt/EnvPane), an OS X preference pane for environment variables developed by [Hannes Schmidt](https://diaryproducts.net/)
2. Downlad fldigi-3.23.21.dmg or fldigi-3.23.22.4.dmg
3. Open the DMG file and copy fldigi and flarq to your Applications folder 
4. In the EnvPanel preference panel configure the variable LANGUAGE with the value of the language you want. Current possible values are: _es_, _fr_, _it_, _pl_, _de_ and _nl_.
5. Run fldig.app and enjoy!

**Keep in mind that:**

* If you set an unsupported language value for the LANGUAGE variable, fldigi will use english for its GUI.
* Fldigi must be restarted if you change the LANGUAGE variable while fldigi is running.
