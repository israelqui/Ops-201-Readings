# Reading 5
## Why does it matter?
- Its important to know how different terminals work for other OS. Windows OS are most common in the business world and there is a big chance we would end up working with it.

1. How can you list the files in the current directory using the command prompt?
- "dir" command

2. How might the “sfc” command and the “gpupdate” command help in troubleshooting on Windows?
- scf (system file checker) scans all the core operating system. "gpupdate" command will force a group policy update to a computer. gpupdate/target:name_of_computer_or_user/force 
sfc is in case the system has malware and gpupdate forces updates in order to keep it up to date.

3. What advantages does the “robocopy” command offer over the “xcopy” command, and why is it useful for file transfers in certain situations?
- xcopy works if you want to copy multiple files and multiple directories at a single time. robocopy is a better version of xcopy which has the ability to resume a file transfer if it is interrupted anytime. Good for wide area network or non-terrestial links, where connectivity may be intermittent. On the surface both look and sct very similar.

4. Think about any real-life scenarios from your cultural context where the use of command line tools could be beneficial. Describe one such scenario and explain how a specific command line tool would help address the situation. 
- I used the command line tool when my old high school computer was acting up and was slow. At the moment i was aware that the computer was infected because even updates wouldn't fix it. I decided to Restore the computer to its factory settings. "%systemroot%\system32\restore\rstrui.exe" it fixed my problem and made my computer feel brand new. and preformed as when i first bought it.

## Analogy 
- Command prompt is the terminal that windows OS uses. This article explains the most popular windows command tools to copy multiple files, change directories, navigate through them, etc. 
## Things I want to know more about.
- Is the windows command prompt the most used in the industry? 
### sources
- https://theorangeone.net/posts/vscode-grammar-checks/
