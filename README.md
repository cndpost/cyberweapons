Organization of this repo

   This is is just a map of some of the repos collected and stored under its own repo name. The
     Original name has not been changed and code not changed but faithfully saves as it is from its source

   Here is just an explanation of the repos related to this category. 

   Each directory is independently collected and not related to other directories


Hive  - Downloaded from wikileaks.org and supposedly to be an infrastrure framework used by CIA for infiltration.

Routersploit - How to control someone's home router and make it as a spy device

        Instruction downloaded from :
        
        https://null-byte.wonderhowto.com/how-to/seize-control-router-with-routersploit-0177774/
        
        Source code downloaded from :
        
        https://github.com/threat9/routersploit

        Summary of the usage (on ubuntu. For other platforms, see original instruction in above link):
        
        1. install python and depencies
            apt-get install python3-pip requests paramiko beautifulsoup4 pysnmp
        
        2. install routersploit (tested once, it seems not working on regular ubuntu yet):

           git clone https://github.com/cndpost/routersploit
           
           cd routersploit
           python3 -m pip install -r requirements.txt
           python3 rsf.py
          
        3. Then, the rest of the commands is done inside rst command line windows. (To be tested on ubuntu)