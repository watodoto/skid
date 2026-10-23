## how to do manualescape for dumb skids
this is expecting you to be using windows obv

### installing part
1. download manualescape files from [the thread](https://discord.com/channels/1375357349425971231/1544493919419629670/1558154241544159243)
2. install python from the [microsoft store](https://apps.microsoft.com/detail/9pnrbtzxmb4z?hl=en-US&gl=US)
3. install the shit you need
```cmd
python -m pip install --upgrade pip
python -m pip install protobuf requests
```
4. run manualescape
```cmd
cd %USERPROFILE%\Downloads
python manualescape.py
```
### using part
1. get your serial number by doing one of these
   - sign out, press alt+v, then look at **SN:** in the top right of the screen
   - just flip the fucking Chromebook over
2. type it into manualescape and press etner
3. open https://accounts.google.com/v3/signin/identifier?flow=deviceEnrollment&flowName=GlifSetupChromeOs in incognito mode
4. open devtools with Ctrl shift i
5. go to application, then drop-down "Cookies"
6. sign in
7. once it starts loading forever after you sign in, check the accounts.google cookie
8. go to the value of oauth_code and copy it
9. paste it into the script and press enter
10. boom done you did manualescape
