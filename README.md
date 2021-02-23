# CTFLearn
Easy challanges:
*************************************************************************************************************************************************************
'''1-See if you can leak the whole database. The flag is in there somwhere… https://web.ctflearn.com/web4/'''
Solution:
' OR '1' = '1
Flag:
th4t_is_why_you_n33d_to_sanitiz3_inputs
************************************************************************************************************************************************

'''2-Just take the Ls. Check out this zip file and I be the flag will remain hidden. https://mega.nz/#!mCgBjZgB!_FtmAm8s_mpsHr7KWv8GYUzhbThNn0I8cHMBi4fJQp8'''
1-download the file 
2-open kali linux write the following commands 

root@kali:~/Downloads# unzip The\ Flag.zip 
'''then try to open the PDF file , you will recognaize that it's locked ! so let's search for the password '''
root@kali:~/Downloads# cd The\ Flag/
root@kali:~/Downloads/The Flag# ls
'The Flag.pdf'
root@kali:~/Downloads/The Flag# ls -a
 .   ..   .DS_Store  'The Flag.pdf'   .ThePassword
root@kali:~/Downloads/The Flag# cd .ThePassword/
root@kali:~/Downloads/The Flag/.ThePassword# ls
ThePassword.txt
root@kali:~/Downloads/The Flag/.ThePassword# cat ThePassword.txt 
Nice Job!  The Password is "Im The Flag".

'' now we have the password , open PDF and you will get the flag '''
***********************************************************************************************************************************
''3-In the computing industry, standards are established to facilitate information interchanges among American coders. Unfortunately, I've made communication a little bit more difficult. Can you figure this one out? 41 42 43 54 46 7B 34 35 43 31 31 5F 31 35 5F 55 35 33 46 55 4C 7D'''

if we convert the hex to ASCII you will get ABCTF{45C11_15_U53FUL}
the the falg is CTFlearn{45C11_15_U53FUL}
************************************************************************************************************************
'''4-Where do robots find what pages are on a website?

Hint:

What does disallow tell a robot?'''
solution:
https://ctflearn.com/robots.txt  you will 
get User-agent: *
Disallow: /70r3hnanldfspufdsoifnlds.html
then navigate to https://ctflearn.com//70r3hnanldfspufdsoifnlds.html you will find the flag 

*************************************************************************************************************************************************
'''5-Not much to go off here, but it’s all you need: Wikipedia and 128.125.52.138'''
go to wikipedia
search for this ip 128.125.52.138
click on diff
you will find the falg cNi76bV2IVERlh97hp
*******************************************************************************
''6-There are so many different ways of encoding and decoding information nowadays... One of them will work! Q1RGe0ZsYWdneVdhZ2d5UmFnZ3l9'''

use base 64 decoder to decode Q1RGe0ZsYWdneVdhZ2d5UmFnZ3l9
then this is the flag
CTF{FlaggyWaggyRaggy}
*************************************************************************************
'''7-Here is a file with another file hidden inside it. Can you extract it? https://mega.nz/#!qbpUTYiK!-deNdQJxsQS8bTSMxeUOtpEclCI-zpK7tbJiKV0tXYY'''






