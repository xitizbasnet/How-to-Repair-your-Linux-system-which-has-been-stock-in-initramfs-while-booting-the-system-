How to Repair your Linux system which has been stock in (initramfs) while booting the system?


------------------------------------------------------



First Step:
First find out the Hard Drive where the Operating System has been installed. In my case it was on sdc5.

------------------------------------------------------

Second Step:
Now type the following command: 

"fsck -f /dev/sdc5"

and Hit Enter

------------------------------------------------------



Third Step
Hit  "y"  in every single line where it show to enter "Yes/No"

------------------------------------------------------
 
 
 
Fourth Step:
After all the process has been complete and it shows the following message

"/dev/sdc5/: File System has modified"


Then forcefully shutdown the sytem by hiting the power button.



------------------------------------------------------



Fifth Step:
Boot the System.


------------------------------------------------------


Sixth Step:
Congrulation we have solved the issue.
