

Keyloggers are programs that capture your key strokes.
They can be used to keep logs of everything you press on the keyboard but on the 
flip side it can be used for malicious purposes as well.

The keylogger that I've made is a basic keylogger with not much functionality as the ones available in market today.
It captures your keystrokes and saves them in a file "keylogger.txt".

It then sends the contents of the file(i.e. the keystrokes) to your email id.

With some extra lines of code, it can also send the keystrokes at regular intervals.
But that is a project for another time.

I have not made it executable so one has to explicitely call it.

SYNTAX : python keylogger.py

[NOTE: You need to press esc key to exit out the keylogger.]

You need to have pynput , smtplib and ssl installed.

While python comes with the library smtplib and ssl preinstalled.
You can install pynput with :
pip install pynput

# Key Logger

## Objective

The Key Logger project aimed to establish a understanding of the CyberSecurity field and Ethical Hacking. The primary objective was to explore how keyloggers operate, how they can be detected, and the potential security implications they pose. By developing a keylogger, I aimed to learn about system vulnerabilities, the importance of securing user input, and the methods used by malicious actors to harvest sensitive information. The project was approached with an ethical mindset, strictly for educational purposes and to enhance my skills in identifying and mitigating cybersecurity threats. Through this experience, I hoped to gain practical knowledge of cybersecurity measures and best practices to contribute positively to the field of information security.
 
### Skills Learned

- Development of critical thinking and problem-solving skills in cybersecurity.
- Programming Languages: Proficiency in Python which is commonly used for developing keyloggers.
- Operating System Internals: Understanding of how operating systems handle input devices and system events.
- Keyboard Event Handling: Knowledge of how to capture and interpret keyboard events.
- File Handling and Data Storage: Skills in storing captured keystrokes securely and efficiently.
- Security and Ethical Considerations: Awareness of legal and ethical implications of keylogging and ensuring its use for legitimate and educational purposes.
- Networking Basics: Understanding how data can be transmitted securely if the keylogger is designed to send logs remotely.
- Encryption Techniques: Knowledge of encrypting logged data to prevent unauthorized access.
- Stealth Techniques: Understanding methods to hide the keylogger's presence from users and security software (for educational exploration only).
- Cross-Platform Development: Familiarity with developing applications that work across different operating systems (optional but beneficial).
- Debugging and Testing: Proficiency in testing and debugging code to ensure it functions correctly and securely.
