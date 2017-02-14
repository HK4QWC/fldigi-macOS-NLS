#Build information:

##built
Tue Feb 14 12:56:45 COT 2017 by ccorrea@Alterego.local on x86_64-apple-darwin16.4.0 for x86_64-apple-darwin16.4.0

##configure flags
'--prefix=/opt/local' '--with-libintl-prefix=/opt/local' '--enable-nls' '--disable-flarq' '--disable-silent-rules' '--enable-maintainer-mode' '--enable-dependency-tracking' '--enable-static' '--enable-optimizations=sse2' '--host=x86_64-apple-darwin16.4.0' '--target=x86_64-apple-darwin16.4.0' '--build=x86_64-apple-darwin16.4.0' '--with-hamlib' '--with-portaudio' '--with-asciidoc' 'build_alias=x86_64-apple-darwin16.4.0' 'host_alias=x86_64-apple-darwin16.4.0' 'target_alias=x86_64-apple-darwin16.4.0'

##compiler
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin

##compiler flags
-I$(srcdir) -I$(srcdir)/include -I$(srcdir)/irrxml -I$(srcdir)/libtiniconv -I$(srcdir)/fileselector -I$(srcdir)/xmlrpcpp -I/opt/local/include -I/opt/local/include -pipe -Os -stdlib=libc++ -D_LARGEFILE_SOURCE -D_LARGEFILE64_SOURCE -D_THREAD_SAFE -D_REENTRANT -I/opt/local/include -I/opt/local/include -D_THREAD_SAFE -pthread -I/opt/local/include -I/opt/local/include/libpng16 -pipe -Wall -fexceptions -O2 -msse2 -mfpmath=sse -I$(srcdir)/xmlrpcpp -DNDEBUG

##linker flags
-L/opt/local/lib -lportaudio -framework CoreAudio -framework AudioToolbox -framework AudioUnit -framework Carbon -L/opt/local/lib -Wl,-headerpad_max_install_names /opt/local/lib/libfltk_images.a -lpng -lz -ljpeg /opt/local/lib/libfltk.a -lpthread -framework Cocoa -L/opt/local/lib -lsndfile -L/opt/local/lib -lsamplerate -L/opt/local/lib -lhamlib -L/opt/local/lib -lpng16 -L/opt/local/lib -lintl -Wl,-framework -Wl,CoreFoundation

##libraries
* FLTK 1.3.4
* libsamplerate 0.1.9
* libsndfile 1.0.26
* PortAudio 19
* Hamlib 3.0.1
