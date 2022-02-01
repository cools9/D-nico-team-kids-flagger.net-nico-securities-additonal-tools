Welcome Thank you for chosing
Nico securities your new firewall
nico securities is a fire wall and it's features are:-
Deep scan
drive cleaner(nico securities)
Usb scan
Usb cleaner
Folder lock
Safe browsing
________________________________
# Batch Antivirus

In this repository you will find the best Batch-created Antivirus: Batch Antivirus! (BAV)
We store the database and antivirus components. Please ensure to download all files for a better protection.

## Is Batch Antivirus good enough to use as a regular antivirus?

Sadly, the answer is no. Batch Antivirus contains a small database (40000 hashes), so new malware isn't there. 
We recomend using another antivirus such as Microsoft Defender or Malwarebytes.  
But, if you can use real-time protection along Microsoft Defender, that will be safer.


## Does Batch Antivirus needs to be installed?

No, you can use it portably with a non-administrator account. It doesn't create any services nor processes.


## Why is scanning so slow?

Scanning is slow because it launches a different process for every file. We're trying to optimize it. There's no new version for `BAV.bat` because of that.

## Does web protection register websites I visit?

No, Batch Antivirus doesn't collect **any** data.  
Privacy is always important for us. Batch Antivirus uses the command `netstat -no` to get active connections to the PC. Then it compares to the file `VirusDataBaseIP.bav` and if the IP is found, it's a malicious website.  
So no, we don't collect any data.

It checks for API/system calls and behaviour. It might be a false positive as it uses some suspicious API like CryptoAPI, used sometimes in ransomware.


## What I need to do if I want to use the database?

You can distribute programs along with database, but please credit us as it's not easy to make a such database searching a big part of the hashes manually.

how to use folder lock

# Folder_lock
<P>-----NOTE: ONLY WORKS ON WINDOWS-----</P>

<P>Folder_lock is a batch script which lets you password protect any folder of your choice.</P>

Steps:

1. Clone the repository onto your local computer.
2. Open the locker.bat file in a text editor and replace mypassword on line #21 with your own password
3. Now run the locker.exe file and it creates a folder named "Folder_". 
4. This creates a folder with the name Folder_ or whatever name you gave in step #3.
5. Copy the files you want to protect into this folder.
6. Run Locker.bat again. It will promt you if you want to lock the folder. Type in Y to lock your folder.
   It protects your folder and hides it. (It can't be seen from the 'Show hidden files' option also)

<P>----To open your folder again---</P>
7. Run the locker.bat file, enter your password and the file appears again.
Password - mypassword


