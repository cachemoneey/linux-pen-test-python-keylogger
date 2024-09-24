# Penetration Testing Linux Server using Python Keylogger

# Introduction

The purpose of this project was to fill the role of a penetration tester on the red team and install a keylogger on an endpoint of a user with the end goal of retrieving company data and valuable information.
The method we used was to create a keylogger in Visual Studio 2022 in the Python language.
Then we analysed the executable file to validate if it contained anything malicious using the malware detection website Virustotal.com

# Components Utilized
*
    - Hyper V VM
    - Linux Server (Ubuntu 22.04)
    - Virustotal.com malware detection
    - Python script
    - Visual Studio 2022
*
# Live demonstration


# Detailed process of the project

In the initial stages of the project, 


# Containment, Eradication & Recovery
*
    - Isolate affected systems and users from network to stop spread of attack
    - Inform affected user/s their account will be disabled and that they should not log into any devices due to compromised account
    - Deploy security patched and updates to eradicate keylogger
    - Restore systems from clean backups

*
# Post-Incident Activity
*
    - Using the Microsoft 365 Defender XDR portal we investigated the attack incident and followed security remediations
    - Root cause analysis and analysis of the effectiveness of our response as well as measures to prevent incident in future
    - Analysed file using Virustotal.com

*
# Obstacles
*
    - Had issues when first attempt testing and could not decrypt data as we forgot to exclude decryption.py in script

*
# Solutions
*
    - The solution was to exclude decryption file in script that encrypts all files and in future have the code reviewed before running

*
# Improvements

Steps to implement to improve the process of this project in the future:
    - We can create a task and the trigger at logon and we can select the keylogger program as an action to automate the process.
    - We can improve the process by using a more useful programming language that every team member can use in C# language
    - We can test if all file types are encrypted and decrypted












