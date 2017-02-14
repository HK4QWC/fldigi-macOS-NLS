# fldigi-macOS-NLS
This is a repository for fldigi binaries with NLS support compiled for **macOS Sierra**.

Here you will find **fldigi-3.23.21** (2017-01-30) and **fldigi-3.23.22.4** (2017-02-13).

Currently, fldigi includes internationalization files for **Spanish** (es), **French** (fr), **Italian** (it), **Polish** (pl), **German** (de) and **Dutch** (nl).

##Quick and easy how-to

1. Download and install [EnvPane](https://github.com/hschmidt/EnvPane), an OS X preference pane for environment variables developed by [Hannes Schmidt](https://diaryproducts.net/)
2. Downlad fldigi-3.23.21.dmg or fldigi-3.23.22.4.dmg
3. Open the DMG file and copy fldigi and flarq to your Applications folder 
4. In the EnvPanel preference panel configure the variable LANGUAGE with the value of the language you want. Current possible values are: _es_, _fr_, _it_, _pl_, _de_ and _nl_.
5. Run fldig.app and enjoy!

**Keep in mind that:**

* If you set an unsupported language value for the LANGUAGE variable, fldigi will use english for its GUI.
* Fldigi must be restarted if you change the LANGUAGE variable while fldigi is running.

##About fldigi

Fldigi is a software modem for Amateur Radio use. It is a sound card based
program that is used for both transmitting and receiving data in any of the
following modes:

BPSK and QPSK        31, 63, 125, 250 (both), and 63F and 500 (BPSK only)
PSKR                 125, 250, and 500
CW                   speeds from 5 to 200 wpm
DominoEX             4, 5, 8, 11, 16 and 22; also with FEC
Hellschreiber        Feld Hell, Slow Hell, Hell x5/x9, FSKHell(-105) and Hell 80
MFSK                 4, 8, 11, 16, 22, 31, 32 and 64; most with image support
MT63                 500, 1000 and 2000
OLIVIA               various tones and bandwidths
RTTY                 various baud rates, shifts, nbr. of data bits, etc.
THOR                 4, 5, 8, 11, 16 and 22
Throb and ThrobX     1, 2, and 4
WWV                  receive only - calibrate your sound card to WWV
Frequency Analysis   receive only - measure the frequency of a carrier

Fldigi can also control a transceiver using Hamlib or RigCAT I/O, perform online
or cdrom QRZ queries, log QSOs with the built-in logbook or Xlog, and send
reception reports to the PSK Automatic Propagation Reporter.


The latest version can always be found at:

  https://sourceforge.net/projects/fldigi/

Visit this page for extensive documentation and an archive of XML files for
transceivers supported by RigCAT.


The wiki page contains FAQs and HOWTOs, as well as links to all Fldigi
resources:

  https://fedorahosted.org/fldigi/

The GIT repository can be found at:

  https://sourceforge.net/p/fldigi/fldigi/ci/master/tree/

For support, news and updates, join one or more of the following mailing lists
and Yahoo groups.  Stable releases are announced to all lists and groups; test
(alpha) releases are announced to fldigi-alpha and fldigi-announce.

  * linuxham group
    General discussion on fldigi, related software and other ham radio topics
   https://groups.io/g/linuxham

  * win-fldigi group
    For Windows users of fldigi
    http://groups.yahoo.com/group/win-fldigi/

  * NBEMSham group
    Special focus on NBEMS operation
    http://groups.yahoo.com/group/NBEMSham/

  * fldigi-alpha list
    Discussion of fldigi testing and related subjects
    https://sourceforge.net/p/fldigi/mailman/fldigi-alpha/

  * fldigi-devel list
    Fldigi development topics
    https://sourceforge.net/p/fldigi/mailman/fldigi-devel/
    
    Copyright (C) 2007-2010 Dave Freese, Stelios Bounanos, and others. License GPLv3+: GNU GPL version 3 or later http://www.gnu.org/licenses/gpl-3.0.html
