# nginx-command-for-win
nginx command start, stop, restart in os windows for the *.bat file (start.bat, stop.bat, and reload.bat

### start.bat
```bat
@ECHO OFF 
start C:\nginx\nginx.exe
ping 127.0.0.1 > NUL
echo Starting nginx
ping 127.0.0.1 > NUL
EXIT
```

### stop.bat
```bat
@ECHO OFF
start C:\nginx\nginx.exe -s stop
```

### reload.bat
```bat
@ECHO OFF
start C:\nginx\nginx.exe -s reload
```
