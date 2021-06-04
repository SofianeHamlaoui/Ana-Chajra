# Ana Chajra ak chayef ?
## A custom Sudo Warning message

### You can get more of ASCII arts here : [asciiart.eu](asciiart.eu)

![](https://i.imgur.com/kW1UHVp.jpg)

instead of this boring one

```
We trust you have received the usual lecture from the local System
Administrator. It usually boils down to these three things:

    #1) Respect the privacy of others.
    #2) Think before you type.
    #3) With great power comes great responsibility.
```
## Add this to `/etc/sudeors.lecture`
```
$ sudo vim /etc/sudoers.lecture
```
## The shown message
```
          `   `o+             
         -++///.              
   `-`       :-.              
   oso```  `ossss`    ` :so-  
  `:///ss: `sosos:   sso./:`  
  /so:/--`  +ssss/   .-//so:  
   ``  -:-..+ssss+--:--.`:/.  
          .:oosss/-`          
           /sooso             
          -soooo`             
         `oosos:      Ana chajara ak chayef ! ye3ni jit brk
        `/+++++/      n9oulek be careful while using sudo!
       .+/+++++o.             
      `+:``.-.`://-           
     /+/-       `++` 
```

## Add this to `/etc/sudoers`
```
Defaults        lecture_file = /etc/sudoers.lecture    # alternate sudo lecture path
Defaults        lecture = always                       # always display the lecture
```


