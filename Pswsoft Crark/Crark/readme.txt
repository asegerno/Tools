I'll be grateful about your opinion and bug-reports
about this version. Please send it:

pavel@semjanov.com?subject=cRARk

----
Parallel Password Recovery (http://www.parallelrecovery.com)
has licensed cRARk engine and PDL language to use in own
products. The key features not included in cRARk are:
1) GUI
2) Password Definition Master
3) multicores/multiprocessors support
4) pause/resume of password recovery

-----
This is command-line utility! Please run it from
command (DOS) prompt.
Program site:
http://www.crark.net

Please bear in mind you have quite no chance to crack unknown
password (longer than 6 symbols) if you have no additional
info about it. So, the primary purpose for this utility is
to recover your forgotten passwords. 

To quick start password cracking:

1) If you're using Windows, please run 'driver-timeout.reg'
and reboot

2)  Rename the needed language definition file (like "english.def", "spanish.def") to
the "password.def" file

3) Read about password definition rules (section 4.2) until
you understand password definition examples from 4.4.

4) Change the password.def file below the '##' line
according the character set you will use.  To do it,
read section 4.2.1 of documentation. For example, if
you decide to use both case Latin letters and digits,
change password definition to
  [$a $A $1] *

5) Test your password definition using -v option.
You also may test the cracker on this archive.
Run:
   crark -pcrackme.def crark55.rar

6) Run the program

   crark your_rar_archive.rar,

7) If you have questions, read the FAQ (section 5) first.

8) Read the full docs, finally

  Please remember I almost have no time to support
this free utility, but I'll be grateful about bug reports.

   If you will make "password.def" file for other language,
send it to me please.

  Good luck!

  Pavel Semjanov, St. Petersburg