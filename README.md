# rsync-for-windows
rsync windows binary supplied with cygwin project

# how did i distilled these binaries from cygwin
- installed cygwin with rsync normally
- with lucasg's Dependencies project i listed all dependancies of rsync exe from c/cygwin/bin/rsync.exe
- currently these dependencies are "cygcrypto-1.1.dll, cygiconv-2.dll, cyglz4-1.dll, cygwin1.dll, cygxxhash-0.dll, cygz.dll, cygzstd-1.dll" and also windows system dll's (system32/kernel32.dll), but those files ship with every windows installation so, i didnt copy those over.
- copied rsync.exe and all these dependencies to a seperate folder and deleted cygwin. so now i have a portable rsync windows binary.
- enjoy

# thanks to
- https://github.com/thbar/rsync-windows
- https://github.com/lucasg/Dependencies
- https://www.cygwin.com/
