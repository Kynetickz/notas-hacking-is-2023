# Objetivo

I have these 2 images, can you make a flag out of them? [scrambled1.png](https://mercury.picoctf.net/static/75e646e4ad19967ca1811f895fb40465/scrambled1.png) [scrambled2.png](https://mercury.picoctf.net/static/75e646e4ad19967ca1811f895fb40465/scrambled2.png)

# Solucion
```Shell

──(kali㉿kali)-[~/Downloads]
└─$ sudo wget http://www.caesum.com/handbook/Stegsolve.jar -O stegsolve.jar
--2023-05-29 17:49:37--  http://www.caesum.com/handbook/Stegsolve.jar
Resolving www.caesum.com (www.caesum.com)... 216.234.173.1
Connecting to www.caesum.com (www.caesum.com)|216.234.173.1|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: 312271 (305K) [application/x-java-archive]
Saving to: ‘stegsolve.jar’

stegsolve.jar       100%[================>] 304.95K   168KB/s    in 1.8s    

2023-05-29 17:49:44 (168 KB/s) - ‘stegsolve.jar’ saved [312271/312271]

                                                                             
┌──(kali㉿kali)-[~/Downloads]
└─$ sudo chmod +x stegsolve.jar                                            
                                                                             
┌──(kali㉿kali)-[~/Downloads]
└─$ java -jar stegsolve.jar
Picked up _JAVA_OPTIONS: -Dawt.useSystemAAFontSettings=on -Dswing.aatext=true


```


picoCTF{d562333d}
# Notas adicionales

# Referencias