This is a python tool with predefined libraries whuch can crack and identify hashes . 
Hash Buster is Python tool to crack or identify hashes 

Features:- 
1. Automatic hash type identification
2. Supports MD5, SHA1, SHA256, SHA384, SHA512
3. Can extract & crack hashes from a file
4. Can find hashes from a directory

   Installation:- Copy the git code and paste it to terminal using git clone code
                  Go to Hash Buster file using command cd Hash-Buster
                  Run the file by using the command python3 hash.py -h ( for help)
    Usage :-    
Cracking a single hash
You don't need to specify the hash type. Hash Buster will identify and crack it under 3 seconds.
     python3 hash.py -s <hash>
Finding hashes from a directory
   Just specify a directory and Hash Buster will go through all the files and directories present in it, looking for hashes.
     python3 hash.py -d /root/Documents ( Any directory name )
Cracking hashes from a file
Hash Buster can find your hashes even if they are stored in a file like this
pandeyyas@gmailcom:21232f297a57a5a743894a0e4a801fc3
yadav234@gmail.com :d033e22ae348aeb5660fc2140aec35850c4da997 









Note: Hash Buster isn't compatible with python2, run it with python3 instead.
