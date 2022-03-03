================================================================================
           ___         _ ___  ____  ___ _    ___  ___ ___                       
          | _ \__ _ __| (_) \/ /\ \/ / / |  | _ \/ __| __|                      
          |   / _` / _` | |>  <  >  <| | |  |   / (__| _|                       
          |_|_\__,_\__,_|_/_/\_\/_/\_\_|_|  |_|_\\___|___|  [ 2021 ]            
                                                                                
=====================| https://radixx11rce2.blogspot.com |======================
                                                                                
____________                                                                    
RELEASE INFO                                                                    
ииииииииииии                                                                    
. Name......: Pichon 9.x Patch                                                  
. Date......: 2021-08-02                                                        
. Version...: 1.2                                                               
. File......: Patch.exe                                                         
. MD5.......: b3f5e6ed3007a157714fd71f9b7b36a4                                  
. SHA1......: 8475c3dac79f198ed56db89fddde93b2eb5d7d22                          
                                                                                
___________                                                                     
TARGET INFO                                                                     
иииииииииии                                                                     
. Category..: Graphics/Icons                                                    
. Protection: Online Account                                                    
. OS........: WinALL                                                            
. Homepage..: https://icons8.com/app                                            
                                                                                
__________________                                                              
TARGET DESCRIPTION                                                              
ииииииииииииииииии                                                              
Find the icons you need and add them into any graphics design project thanks to 
this application, which bundles a generous icon collection and searching        
capabilities.                                                                   
                                                                                
__________                                                                      
HOW TO USE                                                                      
ииииииииии                                                                      
. Interactive Mode: Copy patch to installation dir and apply. Optionally, you   
can run it from elsewhere and specify the target location when required.        
                                                                                
. Silent and Very Silent Modes: Use the command line options described in the   
"Command Line Options/Exit Codes" section.                                      
                                                                                
_____                                                                           
NOTES                                                                           
иииии                                                                           
. To run this patch you will need at least .NET Framework 4.5 (Windows XP is no 
longer supported).                                                              
                                                                                
. Do not click on "Logout" in the "Account" tab, otherwise your license file    
will be deleted and the program will return to free mode. In that case, just    
close the program and re-run the patch to generate a new license file.          
                                                                                
_______________________________________________                                 
COMMAND LINE PARAMETERS & EXIT CODES (ADVANCED)                                 
иииииииииииииииииииииииииииииииииииииииииииииии                                 
. OPTIONS (you can use "/" or "-")                                              
                                                                                
/help or /?                                                                     
                                                                                
Shows a message box with a short description of the standard command line       
parameters.                                                                     
                                                                                
/email:<email>                                                                  
                                                                                
Specifies the email for the account info. If this option is not used, the patch 
will ask for an email (interactive and silent modes only). In very silent mode, 
a default email will be used if it was not specified with this option.          
                                                                                
/ignore                                                                         
                                                                                
Ignore any error during creation of backup files and continue with the patching 
process.                                                                        
                                                                                
/nobackup                                                                       
                                                                                
Do not create a backup before patch target files. By default, a backup  is      
always created. This option also can be turned on/off from Options menu, in the 
main UI.                                                                        
                                                                                
/nodirselect                                                                    
                                                                                
Do not show the folder selection dialog when the target program location cannot 
be determinated or because it was not specified (/workingdir option).           
                                                                                
/overwrite                                                                      
                                                                                
Overwrite existing backup files. By default, any backup file found will not be  
overwritten. In this case, a message will ask for overwrite confirmation        
(interactive and silent modes only).                                            
                                                                                
/silent                                                                         
                                                                                
Apply the patch in silent mode. It does not show the main UI, only the folder   
selection dialog (if required) and any status messages.                         
                                                                                
/verysilent                                                                     
                                                                                
Apply the patch in very silent mode. It does not show the main UI or any        
dialog/status messages.                                                         
                                                                                
/workingdir:<path>                                                              
                                                                                
Specifies location of the target program. If this option is not used (default), 
the program location is obtained following this sequence: current folder (where 
the patch is located), from the registry (if available), folder selection dialog
(interactive and silent modes only). IMPORTANT: if path contains white spaces,  
enclose it in double quotes.                                                    
                                                                                
. EXIT CODES (for batch files)                                                  
                                                                                
0: No error (nothing done).                                                     
                                                                                
1: Patcher is already running.                                                  
                                                                                
2: Administrative privileges are required (actually not used, the patch already 
requests for elevation when executed).                                          
                                                                                
3: A fatal error has occurred and cannot continue.                              
                                                                                
4: The patching process has succeeded.                                          
                                                                                
5: The patching process has succeeded but a system restart is required. This    
status code is rarely used but can be required for some targets.                
                                                                                
6: The patching process was not completed, only a part was succeeded.           
                                                                                
7: The patching process has failed. The target is already patched, is an        
unsupported version or because some other reason.                               
                                                                                
8: The patching process was aborted by the user or because some other reason.   
                                                                                
9: Specified location to the target progam is invalid (only when /workingdir    
option was used).                                                               
                                                                                
______________                                                                  
NEWS & UPDATES                                                                  
ииииииииииииии                                                                  
Almost all my releases have an "Options" menu. This menu can be opened by       
cliking the little button in the upper right corner of the main window (the one 
with a down arrow icon). This menu has two useful options:                      
                                                                                
. News & Announcements: This option allows to check for the latest news         
  regarding to my site or any other important announcement.                     
                                                                                
. Check for Updates: This option allows to verify if there is a new version of  
  this release, check its changelog and download the new version directly.      
  Almost at the same time you will find the new version also posted on my site. 
                                                                                
NOTE: These options require an Internet connection in order to work. In case    
you have a firewall, probably you will need to make an exception.               
                                                                                
___________________________                                                     
ANTIVIRUS & FALSE POSITIVES                                                     
иииииииииииииииииииииииииии                                                     
Some antivirus can detect this release as a threat and try to remove it. The    
reason for this is because my releases are packed/protected in order to reduce  
its size and avoid alterations to the code. This protection can be erroneously  
identified as a threat, it is what is commonly known as a FALSE POSITIVE. Just  
ignore it, it is safe to use.                                                   
                                                                                
IMPORTANT: there will be no risk when using my releases as long as you have     
downloaded it from the links posted on my site or from the "Check for Updates"  
option. If you have downloaded this release from another site, I CANNOT         
GUARANTEE ITS INTEGRITY. In such case, I will not take responsability for       
eventual problems that arise when using it. Be careful!                         
                                                                                
As a precaution, always check the release hashes.                               
                                                                                
__________                                                                      
DISCLAIMER                                                                      
ииииииииии                                                                      
This release is provided AS IS for FOR EVALUATION PURPOSES ONLY! If you can     
afford the software, please BUY IT. Support the developer to make a better      
product.                                                                        
