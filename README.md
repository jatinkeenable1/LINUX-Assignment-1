<h1 align="center" style="color:Black; font-size:50px"> <u> Linux Assignment </u> </h1> 



# 1 . How to make a directory

**Mkdir :- create directories or folders**

**Command :- mkdir** 

**Example :- jatin\@jatin:\~/1$ mkdir test**

**jatin\@jatin:\~/1$ ll**

**total 12**

**drwxrwxr-x   3 jatin jatin 4096 Dec 14 12:29 ./**

**drwxrwxrwx 103 jatin jatin 4096 Dec 14 12:28 ../**

**drwxrwxr-x   2 jatin jatin 4096 Dec 14 12:29 test/**

**Output :-** 

****![](https://lh7-us.googleusercontent.com/uhqq0N6BjtL2RkSbJ34hWwq9m3z1Sd9SsDFkKMaIwrRbEoY485StfOmpoSqeF1sUqQSbPOjODOXYTDd7Qw1xrWH6w9vjDCoKUzXVsUFvrg_w0YcH4cSelPQrjHzUF9YMSS1UeeP0do9JItz11ahDlPE)****

# 2 . Remove a directory

**rmdir :- This command is used to remove empty directories**

**rm -rf : - This command is more powerful and can remove directories along with their contents.**

**Command : rmdir and rm -rf** 

**Output :-**

**jatin\@jatin:\~/1$ ls**

**blank  test**

**jatin\@jatin:\~/1$ rmdir blank**

**jatin\@jatin:\~/1$** 

**jatin\@jatin:\~/1$ rm -rf test/**

**jatin\@jatin:\~/1$ ls**

**jatin\@jatin:\~/1$** 

****![](https://lh7-us.googleusercontent.com/4zHqFnhN_ngZaqSDqyAHWHpR9HcWXJgFVwGwD5rGJeFd546t9GWHm1gd8ENfEBheQe4ivWTFm-MgSQuWQhEewlFmD2fNAW3pZihFGGzzZ-UQgIghhYhR_Z2bgFZjHywi9hl3KkzTtNmPrPRWP7LQ-hQ)****

# 3 . Make a copy of a file

**Cp : used to copy files and directories** `-r` **(recursive)** 

**Command :- cp -r** 

**Output ;-** 

**jatin\@jatin:\~/1$ ls**

**2  demo**

**jatin\@jatin:\~/1$ cp -r demo/ 2/**

**jatin\@jatin:\~/1$ cd 2/**

**jatin\@jatin:\~/1/2$ ls**

**demo**

**jatin\@jatin:\~/1/2$** 

****![](https://lh7-us.googleusercontent.com/5lt4oYs2e3DXCbq6li6W6mbx_JA8MB0I_4-R1F8TrCg6dWjwKtwB3Q1mAyLXQLpVAJJXT_p1NVjquyAWdzPUtXJ6G-8EDT2D-510YxibHWoN-0iBdHFT7h-PFfmHCo_5kKzvuHFO-l9KpKRQCRhmixI)****

# 4 . Move or rename a file

**mv :- The** `mv` **command in Unix/Linux is used to move files or directories from one location to another. It's also used to rename files and directories by effectively "moving" them to a new name in the same directory.**

**Command :- mv**

**Output :-** 

**jatin\@jatin:\~/1$ ls**

**2  demo  test.txt**

**jatin\@jatin:\~/1$ mv test.txt demo.txt**

**jatin\@jatin:\~/1$ ls**

**2  demo  demo.txt**

**jatin\@jatin:\~/1$ mv demo.txt /home/jatin/1/2/**

**jatin\@jatin:\~/1$ ls**

**2  demo**

**jatin\@jatin:\~/1$ cd 2/**

**jatin\@jatin:\~/1/2$ ls**

**demo  demo.txt**

**jatin\@jatin:\~/1/2$** 

****![](https://lh7-us.googleusercontent.com/7MFvRCwc1RtSjk_OXuON1FejsTDYuEbAs2CFhdRlAgxE5F39zrOvGiqIGnTOTlAtOEODkQecEvokZTTKT9qwbBmNPXsbNI9mFG1ewx5xVfvraOoplrL8j_q7hhZV0aiapG1EISHCA3sfZZk45hDPT4Y)****

# 5 . Create an empty file

**Touch :- The** `touch` **command in Unix/Linux is used to create empty files or update the timestamps of existing files**

**Command :- touch**

**Output :-** 

**jatin\@jatin:\~/1/2$ touch xyz.txt**

**jatin\@jatin:\~/1/2$ ls**

**xyz.txt**

**jatin\@jatin:\~/1/2$ cat xyz.txt** 

**jatin\@jatin:\~/1/2$** 

****![](https://lh7-us.googleusercontent.com/eQ8LTLCSOCJ4Yg3gFsmXBI4jeRIXOWO_VYIZOaNAk8RDyG6IRLqhMnXrc93fpp1O4deQnyxgNHw2QYQCYfRXIjVpDVo4hGydR2EbhjFHMJjkfLWC-21v5OEw8VrjfDVxzcObmQthwmGlvUpdRGTBx_A)****

# 6 .  Remove multiple files with a single command

**rm :- To remove multiple files with a single command in Unix/Linux, you can use the** `rm` **command** 

**Command :- rm**

**Output :-** 

**jatin\@jatin:\~/1/2$ ls**

**a  x  xyz.txt  y  z**

**jatin\@jatin:\~/1/2$** 

**jatin\@jatin:\~/1/2$ rm a x xyz.txt y z** 

**jatin\@jatin:\~/1/2$ ls**

**jatin\@jatin:\~/1/2$** 

****![](https://lh7-us.googleusercontent.com/6z6h2tyqw9DXXJYv5374CwsxccOfHVUL7xjiCBrzOQrP-es4LkuwYFYeUzokphJyld8opAoIcRsbjOBfAlkZadlog1as1WcSePkLSOpoqfQGoF8l55Ohcwup32PugwyR0vX5moSGjSTALR_IXSfhcS0)****

# 7 . Remove content from the folder without removing folder

**rm -rf : - This command is more powerful and can remove directories along with their contents.**

**Command :- rm -rf** 

**Output :-** 

**jatin\@jatin:\~/1$ rm -rf /home/jatin/1/demo/text.txt** 

**jatin\@jatin:\~/1$ cd demo/**

**jatin\@jatin:\~/1/demo$ ls**

**jatin\@jatin:\~/1/demo$** 

****![](https://lh7-us.googleusercontent.com/NkXUAu37K9Ea6B6IL62vJciCLxeZRqnUDEku7vCQcYsPbKIe0eUn5F6v6L9JtF_yPgswR2-uYMPbWr19ytzBBNDhFUZ8tN0Im9_qOqFubgM-NsydBkimhf41gvhM3ML7FIIs2VZ7J7hxwxLvNnjJ-jk)****

# 8 . Create multiple folder(a-z) with a single command

**Mkdir :-** 

**You can create multiple folders (from A to Z) using a single command in Unix/Linux by combining** `mkdir` **with brace expansion:**

**Command :- mkdir**

**Output :-** 

**jatin\@jatin:\~/1/demo$ mkdir {a..z}**

**jatin\@jatin:\~/1/demo$ ls**

**a  b  c  d  e  f  g  h  i  j  k  l  m  n  o  p  q  r  s  t  u  v  w  x  y  z**

**jatin\@jatin:\~/1/demo$** 

****![](https://lh7-us.googleusercontent.com/HJwdlcAlyyIFJeFQFWg_5qvAE7clMCm3CkOrsFKXt0fwIUTPCjBvUp_rB3upLDGcJvqGhgVjtt4qSsnhN2r_bPb4i-KDMoZFfomT7-NKRDXanCvWFEyHFBx2fvKdS7yDejDRlHKHkopIM0TQGrEtZ3U)****
