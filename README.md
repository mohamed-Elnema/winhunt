# winhunt
while am studying for elearnsecurity eCHTP , i wrote small tool to hunt for clues like:
1. windows processs running without user which indicates(Process injected)
2. windows process running with NT\System Authority and not in expected path and checks the parent process if its the expected or not.
3. Windows Process Network Connections and Listening ports it will show high risks (powershell,notepad.exe,system processes)
4. hunt for webshells or files which contains unsafe functions like(exec, fsockopen...etc)
