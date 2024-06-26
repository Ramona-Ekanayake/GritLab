Files to submit
done.tar

Instructions
Create the files and directories so that when you use the command ls below, the output will look like this :

$ TZ=utc ls -l --time-style='+%F %R' | sed 1d | awk '{print $1, $6, $7, $8, $9, $10}'
dr-------x 1986-01-05 00:00 0
-r------w- 1986-11-13 00:01 1
-rw----r-- 1988-03-05 00:10 2
lrwxrwxrwx 1990-02-16 00:11 3 -> 0
-r-x--x--- 1990-10-07 01:00 4
-r--rw---- 1990-11-07 01:01 5
-r--rw---- 1991-02-08 01:10 6
-r-x--x--- 1991-03-08 01:11 7
-rw----r-- 1994-05-20 10:00 8
-r------w- 1994-06-10 10:01 9
dr-------x 1995-04-10 10:10 A
$
Note: In order to run the command given in the example above, on Mac operating systems, it is necessary to install the GNU Core Utilities. After installing the command will be slightly different like so:

$ TZ=utc gls -l --time-style='+%F %R' | sed 1d | awk '{print $1, $6, $7, $8, $9, $10}'
The mode from line 4 may look different, for example like:

lrwxr-xr-x 1990-02-16 00:11 3 -> 0
Once it is done, use the command below to create the file done.tar to be submitted.

$ tar -cf done.tar *
$ ls
0  1  2  3  4  5  6  7  8  9  A  done.tar
$
Only done.tar should be submitted.