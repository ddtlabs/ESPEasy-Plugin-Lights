**Lights**

***An ESPEasy Plugin to Control RGB-WW-CW Lights***

Version 1.04 release notes: [ReleaseNotes.md](ReleaseNotes.md)

--

**Command Syntax:**
   
lights rgb \<rrggbb\> [fading time in s]
```
eg: lights,rgb,ff00ff
eg: lights,rgb,ff00ff,10
```

lights ct \<color temp in Kelvin\> [fade time in s] [brightness in %]
```
eg: lights,ct,3000 
eg: lights,ct,2800 1
eg: lights,ct,5500,10,100
```

lights pct \<brightness in %\> [fading time in s]
```
eg: lights,pct,10
eg: lights,pct,90,5
```

lights on [fading time in s]
```
eg: lights,on
eg: lights,on,5
```

lights off [fading time in s]
```
eg: lights,on
eg: lights,on,1
```

lights toggle [fading time in s]
```
eg: lights,toggle
eg: lights,toggle,5
```

