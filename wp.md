## write protection guide for skids on a ti50 (like nissa)
### setup
1. go to your power options on your Chromebook and press "restart"
2. Ctrl alt shift r and confirm powerwash
3. sign in just far enough to see the "Choose your setup" screen (no idea if this helps clear fwmp or not but whatever)
### first devmode boot
4. esc refresh power to enter recovery mode
5. Ctrl d and confirm entering developer mode
6. boot from internal disk
7. wait the 5 minutes
8. boot from internal disk again
9. Ctrl alt refresh on the welcome to your Chromebook screen
10. `gsctool -a -o`
11. only press the power button when it says "Press PP button now" once it says "Another press will be required" then you wait. Do not spam it
12. if you did it right then your screen will go black after the last press and get an "update" scare screen
### second devmode boot
13. esc refresh power again
15. Ctrl d to enter developer mode again
16. boot from internal disk again
17. wait 5 minutes again
14. boot from internal disk again
18. ctrl alt refresh
19. run `gsctool -a -I AllowUnverifiedRo:always` and do the pp sequence
20. run `gsctool -a -w disable` and do the pp sequence
21. run `flashrom --wp-disable` and not do the pp sequence because flashrom is not mean
22. boom wp is now disabled
