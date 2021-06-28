<h1 style="text-align:center;">
CHEATSHEAT FOR LINUX <br>(C.S.)
</h1>
<h4> Standard </h4>

| Command                                     |                                             Explained                                             |
| ------------------------------------------- | :-----------------------------------------------------------------------------------------------: |
| cd /u9/                                     |                                change directory to /u9/ directory                                 |
| ll                                          |                          list of directories/files in current directory                           |
| SHIFT + F                                   |                                          follow log file                                          |
| CTRL + C                                    |                                          stop following                                           |
| q                                           |                                               quit                                                |
| man rpm                                     |                                          manual for rpm                                           |
| pwd                                         |                                      show current directory                                       |
| &lt;(LETTER(S))&gt; + tab (x2)              |                                show files that starts with letters                                |
| cd ~                                        |                                         go to root folder                                         |
| less &lt;FILE_PATH&gt;                      |                                   shows the content of the file                                   |
| cat &lt;FILE_PATH&gt;                       |                    also shows the content of the file, but more minmimalistic                     |
| nano &lt;FILE_PATH&gt;                      |                                    use this for editing a file                                    |
| CTRL + X                                    |                                  save file that has been edited                                   |
| chown                                       | allows you to change the user and/or group ownership of a given file, directory, or symbolic link |
| CTRL + L                                    |                                           clear screen                                            |
| CTRL + A                                    |                                      go to beginning of line                                      |
| CTRL + E                                    |                                         go to end of line                                         |
| CTRL + U                                    |                                            clear line                                             |
| CTRL + Y                                    |                                    recall cleared line (undo)                                     |
| mv &lt;FILE_PATH&gt; &lt;FILE_PATH&gt;      |                         move from &lt;FILE_PATH&gt; to &lt;FILE_PATH&gt;                          |
| rm &lt;FILE_NAME&gt;                        |                                          remove the file                                          |
| atrm &lt;JOB_ID&gt;                         |                                        remove jobs at at-l                                        |
| df -h                                       |                                         check disk space                                          |
| top                                         |                                             cpu usage                                             |
| ps -aux &#124; grep &lt;PROCESS_ID&gt;      |                                   check procces with number (1)                                   |
| ps -eaf &#124; grep &lt;PROCESS_NAME&gt;    |                                    check procces with name (1)                                    |
| gzip &lt;FILE_NAME&gt;                      |                                          make a zip file                                          |
| sudo kill -9 &lt;PROCESS_ID&gt;             |                                       force kill process id                                       |
| ls -ltrh                                    |                           alternatief voor 'll', gesorteerd op laatste                            |
| unzip {FILE_NAME}.zip                       |                                    unzip a .zip file in linux                                     |
| zcat {FILE_NAME}.zip &#124; less +G         |                          read a zip file (! DON'T USE FOR BIG ZIP FILES)                          |
| netstat -tlp &#124; grep 44141              |                              toont wie luistert op poortnummer 44141                              |
| grep -rnw '&lt;FILE_PATH&gt; ' -e 'pattern' |                            zoeken in file path achter bepaal 'pattern'                            |
| tailf &lt;FILE_NAME&gt;                     |                                          follow the logs                                          |
| vgs                                         |                                         check partitions                                          |
|                                             |
|                                             |
|                                             |
|                                             |
|                                             |
|                                             |

(1) find PROCESS_NUMBER with top

<h4> Services </h4>

| Command                                  |               Explained               |
| ---------------------------------------- | :-----------------------------------: |
| service ebestuur status                  |      check status of 'ebestuur'       |
| /u9/ebestuur/scripts/ebestuur-restart.sh |           restart ebestuur            |
| service cape-ebestuur status             |    check status of 'cape-ebestuur'    |
| service cape-ebestuur start              |     start service 'cape-ebestuur'     |
| service daisy-ebestuur-merlin status     | start service 'daisy-ebestuur-merlin' |
| service daisy-ebestuur-merlin start      | start service 'daisy-ebestuur-merlin' |
| service daisy-ebestuur-merlin stop       |             stop service              |
|                                          |
|                                          |
|                                          |
|                                          |
|                                          |
|                                          |
|                                          |
|                                          |
|                                          |
|                                          |
|                                          |

<h4> Common </h4>

| Command                                                                |                      Explained                      |
| ---------------------------------------------------------------------- | :-------------------------------------------------: |
| less +G /u9/ebestuur/ebestuur/logs/kauri-wrapper.log                   |                     logs kauri                      |
| less +G /u9/ebestuur/ebestuur/logs/ebestuur/ebestuur-&lt;DATE&gt;.logs |                 logs from ebestuur                  |
| cd /u9/ebestuur/scripts                                                |                  scripts ebestuur                   |
| nano /u9/ebestuur/ebestuur/conf/ebestuur-web/general.xml               |             modules kiezen vb. enotulen             |
| /usr/java/daisy-ebestuur/install/daisy-init.sh                         |       daisy initialiseren zodat ze kan runnen       |
| chown ebestuur:ebestuur tenant-config-standard.xml’                    |               geef ebestuur ownership               |
| nano /u9/ebestuur/ebestuur/conf/baseservice-context.properties         |    baseservice-context.properties file aanpassen    |
| nano /u9/ebestuur/scripts/daisy/install_daisy                          | file om ports aan te passen indien meerdere tenants |
| mysql -u root -p                                                       |                    MySQL Monitor                    |
|                                                                        |
|                                                                        |
|                                                                        |
|                                                                        |
|                                                                        |

<h4> TIPS & TRICKS </h4>

| Trick                     |                                      Explained                                       |
| ------------------------- | :----------------------------------------------------------------------------------: |
| SELECT TEXT > RIGHT CLICK | COPY TEXT IN TERMINAL (hint: select from left to right, so no 'enter' wil be copied) |
| RIGHT CLICK               |                                PASTE TEXT IN TERMINAL                                |
| ssh &lt;SERVER_NAME&gt;   |                              open server from 'updater'                              |
| exit                      |              quit from current server (and go back to server 'updater')              |
| top > shift 1             |                                  cpu's zien in top                                   |
| shift + /                 |                                    zoeken in text                                    |
|                           |
|                           |
|                           |
|                           |
|                           |
|                           |
|                           |
