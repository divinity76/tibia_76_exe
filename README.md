# tibia_76_exe
tibia 7.6 exe with lots of debugs/crashes fixed, using ollydbg to debug/patch the crashes.

usage: download https://github.com/divinity76/tibia_76_exe/blob/main/Tibia.exe?raw=true and replace tibia.exe with this one.
this one doesn't debug crash when questing (it basically never ever crash)


it should be compatible with all bots, i didn't really edit anything that should affect bots. it was mostly ignore assertion-fails and and division-by-zero-fixes, where if a div-by-zero happened, it would pretend the answer was 1 instead of error - and the result is now usually a weird graphical glitch (that goes away by walking a little) instead of a crash.

for a year or so, every time i got a debug, i loaded up tibia.exe in ollydbg and tried to fix the crash so it wouldn't crash next time, and it seems i succeeded, because i basically never debug on 7.6 anymore, i can't remember the last time i got a debug. i made this client years ago and shared it among friends, but never really made a public release until a few days ago, after having 3 members of a quest on http://tibiafun.zapto.org die on the black shield quest of debug... unfortunately it seems most members of that OT don't trust me and choose to continue using the unpatched cipsoft client, but at least i tried ¯\\\_(ツ)\_/¯
