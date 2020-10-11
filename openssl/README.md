OpenSSL v1.1.1h Light (Win32 x86 version)  

downloaded from:  
https://slproweb.com/download/Win32OpenSSL_Light-1_1_1h.msi  
  
extracted the MSI with:  
msiexec.exe /a Win32OpenSSL_Light-1_1_1h.msi /qb /l log.txt TARGETDIR="C:\Users\Elad\Desktop\Win32OpenSSL_Light-1_1_1h"  
  
The <code>C:\Users\Elad\Desktop\Win32OpenSSL_Light-1_1_1h</code> folder contains a <code>~_tmpdir\</code> sub-folder,  
with an exe file named <code>setup-A1EEC576-43B9-4E75-9E02-03DA542D2A38-1.0.0-light-x86.exe</code>.  

It is an Inno Setup Installer archive (self extracted) version 5.5.7,  
you need to download <code>innounp</code> from:  
https://sourceforge.net/projects/innounp/files/latest/download  
  
Placing <code>innounp.exe</code> in the same folder as <code>setup-A1EEC576-43B9-4E75-9E02-03DA542D2A38-1.0.0-light-x86.exe</code>,  
open up <code>CMD</code> and navigate to folder.  
run <code>innounp.exe -v -x setup-A1EEC576-43B9-4E75-9E02-03DA542D2A38-1.0.0-light-x86.exe</code>,  
  
it will extract the content - two folders: <code>{cf}</code> and <code>{app}</code>,  
under <code>{app}</code> will be some files and <code>bin</code> sub-folder.  

move all the files from <code>{cf}</code> and <code>{app}</code> to be under <code>bin</code> sub-folder,  
overwrite if needed.  
you do not need <code>start.bat</code> or any of the <code>.txt</code>-files.  

All you need is that <code>bin</code>-folder,  
you can move it around without any installations (portable. ready to use).  
since it is x86 (x32 bit) application it will work on any machine (x86 or x64).  





OpenSSL Light-1_1_1h


Standard MSI:

