#### Points: 20

#### Description: Upon further investigation on compromised machine, suspicious portion of network traffic file was found with an encrypted file. Find out whats in the file....

#### _Write-up_

In this challenge, I was given a zip file name easxnalysis.zip. After extract the zip file, I get time_heist.pcapng file and flag.zip password protected zip. 

Above show I used the wireshark to open the time_heist.pcapng file. After using filter “tcp.stream eq 41” I found a HTTP protocol which related to login and I found the email and password. I try to use the password on the flag.zip and I got to extracted the zip file. After extracted, I get a flag.txt file.

#### The flag of this challenge is uniklctf20{7h15_15_7o0_345y_f0r_y0u}

