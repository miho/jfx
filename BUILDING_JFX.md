 TBD
 
      scoop install ant
      
      C:\path\to\cygwin\current\cygwin-setup.exe --packages make,zip,unzip,openssh,make,makedepend,bison,flex,g++,gperf,perl,ruby,python --site http://mirrors.kernel.org/sourceware/cygwin --no-desktop --no-shortcuts --no-startmenu --no-admin --quiet-mode
      
 inside cygwin:     
 
     ./gradlew -PCOMPILE_WEBKIT=true -PCOMPILE_MEDIA=true -PBUILD_SDK_FOR_TEST=false -PCONF=RELEASE :sdk -x :web:test
