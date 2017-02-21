# d3stryr-3stripes-php
PHP implementation of d3stryr-3stripes
# Usage (with local captcha support):
## Step-by-step instructions:

1) Click "Download ZIP"

2) If you are on a Mac this will save the zip to the Download folder.

3) Unzip the file you just download.

4) Open the folder you just unzipped.

5) Move the d3stryr-3stripes.php file to your home folder on your mac. The home folder is normally the folder with your username.

6) Open up a terminal window.

7) Type (or copy & paste) the following command below and then hit enter:

```
php -v
```

8) If the output of the command shows you a number larger than 5.4 after PHP then you are good to go. For the really dumb sneaker heads: 5.5 is larger than 5.4

9) However, if you are running a version less than 5.4 (say 5.3) then I'm not sure if it will or will not work. But you can proceed and pray.

10) Type (or copy & paste) the following command below into the terminal window and then hit enter:

```
echo '127.0.0.1 dev.adidas.com' | sudo tee -a /etc/hosts > /dev/null && echo DONE
```

11) It will prompt you for your password. Enter it in. It will not show you your password as you enter it in. But if you enter it in correctly then you should see:

```
DONE
```

12) Step #10 only has to be done once and never again if you enter your password in correctly.
13) Type (or copy & paste) the following command below into the terminal window and then hit enter:

```
php -S 127.0.0.1:8000
```

14) Now open a browser window and navigate to:
15) http://dev.adidas.com:8000/d3stryr-3stripes.php
16) When you are done. Just close the terminal window.
17) If you want to run the script again just follow from steps 13.

_If you run into issues with captcha loading and you are CERTAIN the site-key is correct then your issue is likely with the domain that you are using: dev.adidas.*_
For step #10 consider using a variation of dev.adidas.com in the command if you are from a different locale:
<pre>
Locale:
   AT : dev.adidas.at
   AU : dev.adidas.com.au
   BE : dev.adidas.be
   BR : dev.adidas.com.br
   CA : dev.adidas.ca
   CL : dev.adidas.cl
   CO : dev.adidas.co
   CZ : dev.adidas.cz
   DE : dev.adidas.de
   DK : dev.adidas.dk
   ES : dev.adidas.es
   FI : dev.adidas.fi
   FR : dev.adidas.fr
   IE : dev.adidas.ie
   IT : dev.adidas.it
   MX : dev.adidas.mx
   NL : dev.adidas.nl
   NZ : dev.adidas.co.nz
   PL : dev.adidas.pl
   RU : dev.adidas.ru
   SE : dev.adidas.se
   SK : dev.adidas.sk
   GB : dev.adidas.co.uk
</pre>

You would then have to use the same local in step #15
For instance for UK:
Step 10)

```
echo '127.0.0.1 dev.adidas.co.uk' | sudo tee -a /etc/hosts > /dev/null && echo DONE
```

Step 15)
http://dev.adidas.co.uk:8000/d3stryr-3stripes.php
One more example for RU:
Step 10)

```
echo '127.0.0.1 dev.adidas.ru' | sudo tee -a /etc/hosts > /dev/null && echo DONE
```

Step 15)
http://dev.adidas.ru:8000/d3stryr-3stripes.php

If you want add all locales:

```
echo '127.0.0.1 dev.adidas.at'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.at
echo '127.0.0.1 dev.adidas.com.au' | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.com.au
echo '127.0.0.1 dev.adidas.be'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.be
echo '127.0.0.1 dev.adidas.com.br' | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.com.br
echo '127.0.0.1 dev.adidas.ca'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.ca
echo '127.0.0.1 dev.adidas.cl'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.cl
echo '127.0.0.1 dev.adidas.co'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.co
echo '127.0.0.1 dev.adidas.cz'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.cz
echo '127.0.0.1 dev.adidas.de'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.de
echo '127.0.0.1 dev.adidas.dk'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.dk
echo '127.0.0.1 dev.adidas.es'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.es
echo '127.0.0.1 dev.adidas.fi'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.fi
echo '127.0.0.1 dev.adidas.fr'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.fr
echo '127.0.0.1 dev.adidas.ie'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.ie
echo '127.0.0.1 dev.adidas.it'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.it
echo '127.0.0.1 dev.adidas.mx'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.mx
echo '127.0.0.1 dev.adidas.nl'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.nl
echo '127.0.0.1 dev.adidas.co.nz'  | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.co.nz
echo '127.0.0.1 dev.adidas.pl'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.pl
echo '127.0.0.1 dev.adidas.ru'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.ru
echo '127.0.0.1 dev.adidas.se'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.se
echo '127.0.0.1 dev.adidas.sk'     | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.sk
echo '127.0.0.1 dev.adidas.co.uk'  | sudo tee -a /etc/hosts > /dev/null && echo DONE dev.adidas.co.uk
```
# Please direct all questions/problems about the script to the following thread:
# [http://bit.ly/FuckNikeTalkFAQ](http://bit.ly/FuckNikeTalkFAQ)

# If no one answers your question in the above [thread](http://bit.ly/FuckNikeTalkFAQ) after reposting your question 5 or more times then see if the forum below has your answers:
# [http://bit.ly/d3stripesQA](http://bit.ly/d3stripesQA)

