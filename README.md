# Hello_World

## .important-READ_FIRST
The following information is of a classified nature, and what follows will be divulged according to **PoLP** -Principle of Least Privilege.

- who == [ZeroTrustAccess](https://github.com/zerotrustaccess) -not my real name.
- what == This is where I will document my journey through learning about cybersecurity, and my transition from **beginner** to **not-so-beginner**. I'm ready to leave the desolate life behind of working in the *Withering Industrial Wasteland* and discard my "blue collar". Instead, I'm embracing my **binary roots**, and beginning my career in Tech--for a very deep and **personal reason**.
- [goals](https://github.com/zerotrustaccess/cyber/blob/main/goals.md)

# .updates

## .update 1.1.2 -Project Update
### Still unfinished

Life is hectic. I started the Honeypot Project in Late January, and we're going into the third week since it began and it still isn't finished. This project is based off a lab video from Josh Madakor that spans just under an hour, but my detailed documentation, fighting through Aure changes, and finding time to get back to the project have left me severely delayed in my progress. 

it's also interesting to note that last week, I fired up the VM again and tried to resume the project, but the logging wouldn't work. After a long session of troubleshooting, I found that I had to delete the **failed_rdp.log** file from the C:/ProgramData folder on the Vm, otherwise, the script in Powershell ISE would fail to run, and the new logs wouldn't generate and save to the existing file. I thought they might, but my experience proved otherwise.

Again, this week, my home-lab session was cut short when I again experienced log issues.

When trying to query the RDP failed log via geo on the Logs Analytics Workspace, I was able to retrieve the now sorted logs from a week ago, but not any logs currently generating from today. I found there was a connection issue first with my VM that caused me to restart it several times, and then a connection issue in Azure with LAW to my VM. I wasnt able to troubleshoot further and get it running again, so back another time, we go. 

## .update 1.1.1 - **Education update**
### TryHackMe Progress - Pre Security
January 21,2024

I haven't documented my progress so far on my progress through **TryHackMe**, but I think it would be beneficial to add on here since it's a big component of my cybersecurity adventure. As of right now, I have the intentions of enrolling and completing the **SOC 1** on TryHackMe, and make my way through as much as possible. I'm currently nearing the end of the **Pre Security** path, which is a pre-requisite, of sorts, for the SOC 1 path.

![screenshot of current progress from tryhackme](https://github.com/ZeroTrustAccess/Cyber/blob/main/images/tryhackme1.png)

I intend to create an entire separate documentation series on my learning through TryHackMe, so long as it doesn't slow me down. The goal here is to switch jobs and get into the cybersecurity field, not get stuck in learning purgatory.


## .update 1.1 - **First Project!**
### Microsoft Azure Honeypot
January 21,2024

[Click here to go to the Project!](https://github.com/ZeroTrustAccess/Honeypot/blob/main/README.md)

For the better-part of a week, I have been chipping away at beginning and documenting my first **Cybersecurity Project**.

I've been looking to get my first project up and going for quite a while. Life gets busy, but I finally completed the setup adn documentation of the first step in the process: **Creating/Setting up a Virtual Machine**. While I've used VMs before, I had never used Azure, or done any of this on my own. I've also been learning more and more about how to use github. I'm finally starting to understand the basics and markdown syntax for linking files. It's actually been really fun!

The readme is now updated with the link to the repository containing the first step in this project. I'm excited to set-up my first **honeypot** and watch the dangers of the internet play out. It's going to be interesting to see how much and from where my VM is attacked from. I plan to use this experience to do this again with another Honeypot set-up I've seen on YouTube, which features a graphical map that shows in real time, malicious actors attacking my VM.

## .update 1.0
### Genesis. Where I'm starting from.

While my tech.journey has been a lifelong endeavor, **officially** we could say my journey began with my taking the **Google Cybersecurity Professional Certificate** on Coursera. This introduced me to what cybersecurity was as a career, and it seemed to align with my goals. 


