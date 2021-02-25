<h1 style="text-align:center;">
CHEATSHEET FOR CMD 
</h1>
#### CHEATSHEET

| Command        | Explained           
| ------------- |:-------------:
| cd  &lt;PATH&gt; |change directory to path (1)
| cd ..| go to parent folder   
|cd %HOMEPATH%|go to homepath
| start .| open current directory in explorer      
|dir| list of files in current directory
|mkdir &lt;PATH&gt;| make a directory at path (1)
|netstat -ano &#124; findstr :&lt;PORT&gt;|find a port (2)
|taskkill /PID &lt;PID&gt; /F|kill process with PID (3)
||
||

<p style="text-align: left;"> (1) (replace &lt;PATH&gt; with path name) <br>

(2) (replace &lt;PORT&gt; with port number) <br>

(3) you can find pid by executing: 'netstat -ano &#124; findstr :&lt;PORT&gt;' (2) <br>

</p>

#### TIPS & TRICKS

| Trick        | Explained           
| ------------- |:-------------:
|in explorer press 'ALT + D'  and type 'cmd' |open cmd with explorer

|WIN + R and type 'cmd'| open cmd
||



#### KAURI
| Trick        | Explained           
| ------------- |:-------------:
|%KAURI_HOME%/bin/kauri -c conf -r %HOME%\.m2\repository|run KAURI project (1)
||

(1) Add path to kauri to environment variables %KAURI_HOME%
