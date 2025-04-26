# cs6262-project-1-introduction-to-penetration-testing-solved
**TO GET THIS SOLUTION VISIT:** [CS6262 Project 1: Introduction to Penetration Testing Solved](https://www.ankitcodinghub.com/product/cs6262-project-1-introduction-to-penetration-testing-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;111732&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6262 Project 1: Introduction to Penetration Testing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<strong>The goal of this project: </strong>

Penetration testing is an important part of ensuring the security of a system. This project introduces some of the common tools used in penetration testing, while also exploring common vulnerabilities (such as Shellshock and setUID bit exploits).

&nbsp;

On September 24, 2014, a severe vulnerability in Bash, nicknamed Shellshock, was identified. This vulnerability can exploit many systems and be launched either remotely or from a local machine. In this project, you will gain a better understanding of the Shellshock vulnerability by exploiting it to attack a machine. The learning objective of this project is to get first-hand experience on this interesting attack, understand how it works, and think about the lessons that we can get out of this attack.

&nbsp;

<strong>Environment Setup: </strong>

&nbsp;

<table width="680">
<tbody>
<tr>
<td width="340">Files Provided</td>
<td width="340">Description</td>
</tr>
<tr>
<td width="340">shellshock_server.ova</td>
<td width="340">The VM image (see setup Step 18).</td>
</tr>
<tr>
<td width="340">assignment_questionnaire.txt</td>
<td width="340">Template for final submission.</td>
</tr>
</tbody>
</table>
&nbsp;

This project requires the use of virtual box and multiple VMs.

&nbsp;

<strong>Installing Virtual Box: </strong>

&nbsp;

<ol>
<li>Install VirtualBox if it is not already installed. This project requires the latest version of VirtualBox 6.1.x. Using an earlier version of Virtual Box has been known to cause errors where the project VM freezes, so if you run into this, ensure you are running on at least Virtual Box 6.1.0 or later.</li>
</ol>
&nbsp;

<ol start="2">
<li>Download the Oracle Virtual Box Extension Pack (available for download at the same location as Virtual Box is).</li>
</ol>
&nbsp;

<ol start="3">
<li>Import the Extension Pack under File-&gt; Preferences-&gt; Extensions</li>
</ol>
&nbsp;

<ol start="4">
<li>In Virtual Box go to Tools -&gt; Preferences -&gt; Network.</li>
</ol>
&nbsp;

<ol start="5">
<li>Select the small plus sign in the upper right corner of the network preferences box to create a new NAT network. Select the NAT network and select the small gear below the add button to edit it. In the box that appears, change the name to something related to the project. Then save it and close the preferences.</li>
</ol>
&nbsp;

<strong>Installing the Kali Linux VM (feel free to use any other OS but we recommend using Kali): </strong>

&nbsp;

<ol start="6">
<li>Download the 64bit VirtualBox version of the Kali VM from the link: <a href="https://cdimage.kali.org/kali-2023.3/kali-linux-2023.3-virtualbox-amd64.7z">kali download</a><a href="https://cdimage.kali.org/kali-2023.3/kali-linux-2023.3-virtualbox-amd64.7z">.</a></li>
</ol>
&nbsp;

<ol start="7">
<li>Extract and import the Kali Linux VM to Virtual Box. Once you have imported the VM, you’ll need to go into the VM Settings and increase the number of CPUs if possible, as well as the RAM. Also enable 3-d acceleration and set the zoom level to 300 (it makes it easier to read).</li>
</ol>
&nbsp;

<ol start="8">
<li>Go to the new Kali VM’s settings. In the network tab change “Attached to:” from NAT-to-NAT Network in the Adapter 1 tab. The name of the network should autofill to your newly created network if you only have one, but if you have multiple NAT networks, you’ll need to select the correct one.</li>
</ol>
&nbsp;

<ol start="9">
<li>Repeat the process with the other VM (shellshock_server.ova) which you will download in a later step so that these two VMs can communicate with each other.</li>
</ol>
&nbsp;

<ol start="10">
<li>Start the Kali VM. The default username/password is <strong>kali</strong>/<strong>kali</strong>.</li>
</ol>
&nbsp;

<ol start="11">
<li>Ensure the guest additions are installed. If they are not, go to devices-&gt;insert guest additions CD). Then follow the instructions in the popup window to install the guest additions.</li>
</ol>
&nbsp;

<ol start="12">
<li>In the top Virtual box menu bar of the Kali VM, go to Devices -&gt; Shared Folders -&gt; Shared Folders Settings.</li>
</ol>
&nbsp;

<ol start="13">
<li>Click Machine Folders to ensure it is highlighted. Click the small add folder icon on the right of the screen.</li>
</ol>
&nbsp;

<ol start="14">
<li>Select a path (in “Folder Path”) to a folder on your host machine that will act as the shared folder on the host. Give the folder a name if it does not autofill already. Check the “Auto-mount” box. Check the “Make Permanent” box. Click okay, and you should now see the folder under “Machine Folders”.</li>
</ol>
&nbsp;

<ol start="15">
<li>In a terminal on the Kali VM, run:</li>
</ol>
&nbsp;

sudo usermod -a -G vboxsf $(whoami)

&nbsp;

<ol start="16">
<li>Now logout of the Kali VM and log back in (or just restart the Kali VM). The shared folder should be under: /media/sf_{shared folder name}</li>
</ol>
&nbsp;

&nbsp;

<strong>Vulnerable machine: </strong>

<ol start="17">
<li>Download the project appliance using the link below:
<ol>
<li><a href="https://gtvault-my.sharepoint.com/:u:/g/personal/harshsingh3_gatech_edu/ET-SJfzqnlJEoJ5gFAL4gc8B1n_YS1kXACKdJdAvZQCyMQ?e=U4hzrI">ova</a> sha256sum: 04557c059c367f3828f95a656f2f363c8577ce55d24e834b9c1b4ca4b24a529a</li>
</ol>
</li>
</ol>
&nbsp;

<ol start="18">
<li>Import the downloaded OVA into VirtualBox (File -&gt; Import Appliance). Check the VM’s Network setting. Ensure Adapter 1 is set to NAT Network and the name of the NAT Network is the name you specified when creating the NAT Network in step 5.</li>
</ol>
&nbsp;

<ol start="19">
<li>Try to connect to the VM server from Kali. Start the VM in VirtualBox (as no login is needed, you can use headless start, accessible by selecting the “Headless Start” option under the “Start” drop down menu in VirtualBox). Once you find the IP of the VM in Task 1 below, navigate to the following URL: http://&lt;IP address of the shellshock_server VM&gt;:&lt;http port found in part 1&gt;/cgibin/shellshock.cgi</li>
</ol>
Then you should be able to see the content:

&nbsp;

&nbsp;

&nbsp;

<ol start="20">
<li>Notice that you do not need the password to access the web content hosted on the VM server. Instead of using a real server, it is safer to perform the attack on an emulated Apache HTTP Server VM. <u>To be clear, you will not be logging into the shellshock VM during this project.</u> Once you configure the shellshock VM (by following steps 17-20 above), you will be exploiting it externally, from the Kali VM, by exploiting the Shellshock vulnerability.</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

<strong>Project Tasks (</strong><strong>100</strong><strong> points):&nbsp; </strong>

<strong>Task 1: Network Scanning – (10 points) </strong>

&nbsp;

The first step in any penetration test is to gather information about the network and servers you’ll be exploiting. In this task, you will perform network scanning and answer a few questions based on your findings. On startup, the shellshock VM listens to several ports for incoming messages.

&nbsp;

<ol>
<li>Find the IP address of the vulnerable VM on the NAT network using nmap.</li>
<li>Use nmap to identify all the open ports on the shellshock server and submit the port number which handles the http traffic to the Apache web server on the VM.</li>
</ol>
&nbsp;

<strong>Note: </strong>If possible, please use VirtualBox for this part since in the previous semesters VMware has been known to cause some issues with the network setup and Task 1.

&nbsp;

&nbsp;

<strong>Task 2: Attack CGI Program– (20 points) </strong>

&nbsp;

In this task, you will launch the Shellshock attack on a remote web server. Many web servers enable CGI, which is a standard method used to generate dynamic content on Web pages and Web applications. Many CGI programs are written using a shell script. Therefore, before a CGI program is executed, the shell program will be invoked first, and such an invocation can be triggered by a user from a remote computer.

&nbsp;

To access this CGI program from the Web, you need to first check the server VM is running. Then, you can either use a browser by typing the following URL:

&nbsp;

http://&lt;IP address found in part 1&gt;:&lt;http port found in part 1&gt;/cgi-bin/shellshock.cgi

&nbsp;

or use the following command line program curl to do the same thing:

&nbsp;

$ curl http:// &lt;IP address found in part 1&gt;:&lt;http port found in part 1&gt;/cgi-bin/shellshock.cgi

&nbsp;

For this task, your goal is to launch the attack through this URL, such that you can achieve something that you cannot do as a remote user. For example, you can execute some file on the server, or look up some file located on the server. When you successfully launch an attack, please execute the /bin/task2 program (which needs your GT username as the input) inside the VM. It will generate the submission hash for you.

&nbsp;

For students that want to verify their work, here’s an example correct input/output for /bin/task2:

&nbsp;

$ /bin/task2 g3

Here is your task2 hash:

5fb2eef938755ab61f49c41a7085b0957253ab7fea06728a4b3b80d863c31b31

&nbsp;

<strong>Task 3: Reverse Shell with Metasploit – (25 points) </strong>

&nbsp;

Now you have successfully launched the Shellshock attack, and you can execute commands on the server VM. However, during a penetration test, you likely won’t have time to craft a payload for every exploit you use. And, what if the server was not in fact vulnerable to shellshock. How would you know if your exploit failed because it was wrong, or because there was not a vulnerability?

&nbsp;

That is where Metasploit comes in. Metasploit is a standard in the penetration testing community. It allows pen testers to run precompiled exploits against a host, using predefined payloads. For this project, we’re going to use Metasploit to establish a reverse shell between your machine and the host machine.

&nbsp;

Let us first see how Metasploit works by using it to scan the open TCP ports of the shellshock_server VM. While this is a task better suited to tools like nmap (as seen in Task 1), it serves as a good demonstration of how to use a Metasploit module. If you have used Metasploit before, you can skip this introduction and go directly to the Task 3 assignments section at the end.<strong>&nbsp; </strong>

&nbsp;

<table width="80">
<tbody>
<tr>
<td width="80">msfconsole</td>
</tr>
</tbody>
</table>
<ol>
<li>Begin by opening a new terminal on your Kali VM. In the new terminal type: . After a moment, the Metasploit Framework console (msfconsole) will load. For this project, the msfconsole is the main way of accessing Metasploit. While there are other tools and command prompts associated with Metasploit, the msfconsole is suitable for the entirety of this project.</li>
</ol>
&nbsp;

<ol start="2">
<li>For this example, we’re going to scan the ports of a host. You can use the results from task 1 to ensure Metasploit is behaving properly. In practice using a Metasploit module solely for the purpose of scanning ports on a host is a little overcomplicated, since nmap can do much more and takes less setup, but this does offer a good introduction to using a Metasploit module.</li>
</ol>
&nbsp;

<ol start="3">
<li>A metasploit module is the base of any task performed in metasploit. It consists of Ruby code that is written to perform a certain task (like exploiting a certain vulnerability or scanning a certain kind of system). There are multiple different varieties of modules, but for our purposes we’ll focus on three of them:
<ol>
<li><strong>The Exploit modules: </strong>These are modules written to exploit a certain vulnerability.</li>
<li><strong>The Auxiliary modules:</strong> These are modules written to perform some tasks related to exploiting a system (like scanning). Within the auxiliary modules there are many kinds of modules. We’ll be using the “scanner” modules for this example.</li>
<li><strong>Payloads:</strong> Calling these modules is a little misleading. They are the payloads (for example</li>
</ol>
</li>
</ol>
&nbsp;

&nbsp;

The reason there are so many results is that “scanner” is a class of auxiliary modules (as seen by there being so many modules beginning with “auxiliary/scanner”). So, searching for “scanner” (or “scan”) will give everything at all related to network or vulnerability scanning.

&nbsp;

&nbsp;

That seems a little better. Only 7 results. Since we’re scanning for open tcp ports, let’s use:

<table width="652">
<tbody>
<tr>
<td width="22"></td>
<td width="56">options</td>
<td width="574">. You should see something like:</td>
</tr>
<tr>
<td colspan="3" width="652"></td>
</tr>
</tbody>
</table>
“auxiliary/scanner/portscan/tcp”. To use a metasploit module, you should run the&nbsp;&nbsp;&nbsp;&nbsp; command: use module_name

&nbsp;

&nbsp;

You should now see “auxiliary(scanner/portscan/tcp)” after “msf5” indicating you are using the auxiliary(scanner/portscan/tcp) module.

&nbsp;

<ol start="6">
<li>Now that we’re using the correct module, we must set the correct options. Try running the command</li>
</ol>
&nbsp;

While each of the options is marked as required, most of the pre-filled values work for our purposes. The only one we need to change is RHOSTS. RHOSTS should be the IP address of the host we want to scan. In this case, you should set it to the IP address of the shellshock_server VM, that you found in part 1. You can use the command: set rhosts IP_of_host. Now try running options again and ensure the RHOST option is set to the right IP address.

&nbsp;

<table width="614">
<tbody>
<tr>
<td width="58">Now run</td>
<td width="24">run</td>
<td width="532">&nbsp;and you should see the same list of open ports that nmap showed. While “run” is</td>
</tr>
<tr>
<td colspan="3" width="614">usually used to run auxiliary exploits, the command “check” and “exploit” are often used to check</td>
</tr>
</tbody>
</table>
7.

and run exploit modules.

&nbsp;

Now you’ve seen an example of how to use Metasploit. You’ll follow a similar process when exploiting the shellshock vulnerability.

&nbsp;

<strong>Task 3 Assignments: </strong>

<ol>
<li>Find an exploit module that exploits the shellshock vulnerability on an Apache web server. Once you’ve found the module, place the module name in assignment_questionnaire.txt.</li>
<li>Use show payloads to show the possible payloads for the module. Find a payload that spawns<strong> a reverse tcp shell</strong>. Place the full name of the payload in assignment_questionnaire.txt.</li>
<li>Run the exploit and spawn a reverse shell on the VM.</li>
<li>Run /bin/task3 in the resulting shell, then type cs6262 then your user ID. Report the hash value for your user ID in assignment_questionnaire.txt.</li>
</ol>
&nbsp;

You’ll submit all your answers for this section in assignment_questionnaire.txt. You should keep the reverse shell running after finishing Task 3, as you will need it in Task 4.

&nbsp;

<strong>Task 4: Privilege Escalation – (20 points) </strong>

&nbsp;

<strong>Your goal: </strong>

You aim to upgrade the privilege for your command shell by exploiting the setUID vulnerability. You will run /bin/task4 as the higher privileged user “shellshock_server”, not the default user “www-data”.

<strong>&nbsp;</strong>

<strong>Background: </strong>

In Unix based systems, setUID is access rights flags that determine what users can run a program. For instance, when users want to change their password, they may run the passwd that requires root privilege. The setUID can help the user run the passwd with temporarily elevated privileges. However, if setUID is misused or setUID flags are misconfigured, it can cause a variety of vulnerabilities such as information leakage, unwanted privilege escalation, etc.

&nbsp;

<strong>Assignments: </strong>&nbsp;in your shell. You should see “www-data” which is your user ID. Now, run

<table width="175">
<tbody>
<tr>
<td width="126">As a first step, type</td>
<td width="50">whoami</td>
</tr>
<tr>
<td colspan="2" width="175">/bin/task4 gt_usernam</td>
</tr>
</tbody>
</table>
<ol>
<li>e. You would see a permission denied error. That is because /bin/task4 is</li>
</ol>
configured to allow only the “shellshock_server” user to run it. So, you need to find a way to run task4 as the “shellshock_server” user. A feasible approach is to spawn a shell running as a “shellshock_server” user and run task4 through it.

&nbsp;

Your goal is to find a program which:

<ol>
<li>Hash a higher privilege than the default user.</li>
<li>Can spawn a shell.</li>
</ol>
You may want to ransack /usr/bin for a program which has a higher privilege than the default user and run /bin/task4 gt_username in the shell spawned.

&nbsp;

What is the vulnerable program? What command do you use to search it? What command do you use to spawn a shell with the vulnerable program? And what is the hash value from /bin/task4 gt_username (like /bin/task2)? Please leave your answers in assignment_questionnaire.txt.

&nbsp;

<strong>Task 5: Password Cracking – (25 points) </strong>

&nbsp;

An invaluable part of any penetration test is password cracking. While there may be no known vulnerabilities in a system, a weak password could be just as damaging in allowing an attacker to gain access to a system (or view sensitive information once they gain access). We’re going to look at two kinds of weak passwords in this task: passwords that are too short, and passwords that can easily be guessed via password scraping.

&nbsp;

To begin, start a Meterpreter shell (using a meterpreter shell payload) through the Metasploit shellshock module in Task 3. A Meterpreter shell is different from the reverse TCP shell in Task 3, as it allows you to run Metasploit specific commands on the vulnerable machine (like download). Navigate to

/home/shellshock_server/secret_files/. There are two encrypted .pyc files here. task51.zip is encrypted with zip, while task52.pyc.gpg is encrypted with gpg (a common file encryption tool in Linux).&nbsp; Download these two files (task51.zip and task52.pyc.gpg) to your Kali VM using the meterpreter.

&nbsp;

We already know the developers of this web server are not very security savvy, since they let a shellshock vulnerability plus a setUID exploit give a high privilege shell on their machine. So, chances are they did not pick very secure passwords for these secret files. Your goal in this task is to crack the passwords of these two files using John the Ripper (a popular password cracker) and cewl (a password scraper).

&nbsp;

The command line tools used in Task 5 are in /usr/sbin on the Kali VM. To run them, you can either add /usr/sbin to the $PATH variable or write /usr/sbin/ before each command.

&nbsp;

You should use zip2john and gpg2john to extract the password hashes from the encrypted files. For task51.zip, try running John the Ripper incrementally. Report your John the Ripper command in assignment_questionnaire.txt (whether you also report your the zip2john and gpg2john commands is up to you, but they will not be graded).

&nbsp;

For task52.pyc.gpg, try running John the Ripper incrementally again. Hmm… it seems to run forever. That is because John the Ripper is trying every combination of characters. If the password is too long (among other things), John the Ripper could run for years before it finds it.

&nbsp;

Just because the password is too long to be found incrementally, does not mean it cannot be cracked.

Take a look at the shellshock.cgi page in the browser. It looks like it gives a link to a profile of the authors. If the authors are not great at picking secure passwords, maybe the password is something about them that we can guess from their profile page.

&nbsp;

But, even if the password is on the profile page, it can still take a while to guess by hand. What if the password was kItt3n$ or deVEL0p3r. It would be hard to guess that, even if the word it was based on (like “kittens”, or “developer”) was on the profile page.

&nbsp;

Instead, let us use a password scraper to create a custom wordlist for John the Ripper. For this project, we suggest using cewl. cewl is a simple command line program that comes preinstalled on Kali and creates password word lists off of webpages. Since we want to get every possible password (including if the authors based the password off something on shellshock.cgi, or one of the landing pages), you should run cewl on shellshock.cgi, with the proper settings to ensure it follows the links all the way to profile.cgi (you may need to tune the cewl parameters). Report your cewl command in assignment_questionnaire.txt. Then try running John the Ripper on task52.pyc.gpg with the wordlist (and the default wordlist rules for testing different permutations of the words). Report your John the Ripper command in assignment_questionnaire.txt.

&nbsp;

Once you find the passwords, report them in assignment_questionnaire.txt. Then decrypt the two files (using zip for task51.zip and gpg for task52.pyc.gpg) and run python2.7 task51.pyc gt_username and python2.7 task52.pyc gt_username. Report the resulting hash values for your user ID in assignment_questionnaire.txt.

&nbsp;

<strong>Deliverables: </strong>

&nbsp;

Please use <strong>Gradescope </strong>to submit the assignment files. The link to Gradescope is found in Canvas under

Courses tab -&gt; Gradescope.&nbsp; In Gradescope under active assignments click project 1 to upload your files.

<ul>
<li>txt</li>
<li>txt</li>
</ul>
&nbsp;

&nbsp;

The provided template “assignment_questionnaire.txt” marks where you should add your answers for each question. <strong>Please DO NOT edit anything other than the fields marked for your answers (or student ID) in assignment_questionnaire.txt. </strong>Doing so may result in the autograder failing to process your submission.

&nbsp;

Please note that there is a <u>5-point penalty</u> for not following the format given in assignment_questionnaire.txt.

&nbsp;

You should also include a “README” plain text file explaining how and why each piece of your solution works. Including it makes grading easier if we cannot reproduce your results. You may also include screenshots in your submission to show proof. To include screenshots (optional), upload them to your GT SharePoint drive and add a link in the README.txt file. If you use any outside sources not mentioned in this write-up, then README would be a good place to mention them as well. The README.txt file is a plain text file, and no other formats are accepted.

&nbsp;

<strong>FAQ:</strong>

&nbsp;

<ul>
<li>For this project, students have unlimited submissions on gradescope.</li>
<li>You do not need to log into the shellshock image at any point to complete this project.</li>
<li>For all task binaries, make sure to pass in your GT Username as the argument (e.g.: gburdell3) and beware of extra spaces after your name because that will result in an incorrect hash.</li>
<li>Make sure you are using VirtualBox 6.1.x. (students have completed the project on other versions too, but it sometimes causes issues).</li>
<li>Make sure to assign at least 2 CPUs and 4GB of RAM to your shellshock image for it to function properly.</li>
<li>The objective of this project is to get you familiarized with the absolute basics of penetration testing and therefore we encourage Googling to learn more about the vulnerability, the tools, and the attack concepts.</li>
</ul>
&nbsp;

<strong>Reminders:</strong>

&nbsp;

Please submit the files <u>EXACTLY</u> as requested to Canvas. <u>DO NOT package them up (e.g., as a ZIP file).</u> Any deviations may result in a deduction of your grade.

&nbsp;

There is a <u>5-point penalty</u> for not following the submission format shown.

&nbsp;

<strong>Useful Links and References:</strong>

&nbsp;

<ul>
<li>Shellshock Vulnerability</li>
</ul>
◦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://github.com/carter-yagemann/ShellShock">https://github.com/carter</a><a href="https://github.com/carter-yagemann/ShellShock">–</a><a href="https://github.com/carter-yagemann/ShellShock">yagemann/ShellShock</a>

◦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://en.wikipedia.org/wiki/Shellshock_(software_bug)">https://en.wikipedia.org/wiki/Shellshock_(software_bug</a><a href="https://en.wikipedia.org/wiki/Shellshock_(software_bug)">)</a>

◦ <a href="http://seclists.org/oss-sec/2014/q3/650">http://seclists.org/oss</a><a href="http://seclists.org/oss-sec/2014/q3/650">–</a><a href="http://seclists.org/oss-sec/2014/q3/650">sec/2014/q3/650</a> ● curl

◦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://curl.haxx.se/docs/manpage.html">https://curl.haxx.se/docs/manpage.html</a>

◦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://curl.haxx.se/download.html">https://curl.haxx.se/download.html</a> (curl.exe for Windows)

<ul>
<li>netcat</li>
</ul>
◦ &nbsp;&nbsp;&nbsp;&nbsp; <a href="https://linux.die.net/man/1/nc">https://linux.die.net/man/1/nc</a>

◦ <a href="https://eternallybored.org/misc/netcat/">https://eternallybored.org/misc/netcat/</a> (nc.exe for Windows) ● nmap

◦ &nbsp;&nbsp;&nbsp;&nbsp; <a href="https://nmap.org/book/man.html">https://nmap.org/book/man.html</a>

◦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://nmap.org/book/man-version-detection.html">Service and Version Detection | Nmap Network Scanning</a>

<ul>
<li>Metasploit</li>
</ul>
◦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/">https://www.offensive</a><a href="https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/">–</a><a href="https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/">security.com/metasploit</a><a href="https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/">–</a><a href="https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/">unleashed/metasploit</a><a href="https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/">–</a><a href="https://www.offensive-security.com/metasploit-unleashed/metasploit-fundamentals/">fundamentals/</a>

<ul>
<li>John the Ripper</li>
</ul>
◦ &nbsp;&nbsp;&nbsp;&nbsp; <a href="https://www.openwall.com/john/doc/">https://www.openwall.com/john/doc/</a>

<ul>
<li>cewl</li>
</ul>
◦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://tools.kali.org/password-attacks/cewl">https://tools.kali.org/password</a><a href="https://tools.kali.org/password-attacks/cewl">–</a><a href="https://tools.kali.org/password-attacks/cewl">attacks/cewl</a>

&nbsp;

<strong>Acknowledgment:</strong>

&nbsp;

This Lab was modified from SEED Labs, Copyright 2014 Wenliang Du, under the terms of GNU Free

Documentation License, Version 1.2. The original document can be found at <a href="http://www.cis.syr.edu/~wedu/seed/">http://www.cis.syr.edu/~wedu/seed/</a>

&nbsp;

<strong>Checklist/Rubric:</strong>

&nbsp;

<table width="704">
<tbody>
<tr>
<td colspan="2" width="594">Section</td>
<td width="84">Points</td>
<td width="26">✓</td>
</tr>
<tr>
<td width="37"><strong>1 </strong></td>
<td width="557"><strong>Network Exploration </strong></td>
<td width="84"><strong>10 </strong></td>
<td width="26"></td>
</tr>
<tr>
<td width="37">1.1</td>
<td width="557">Correct first digits of the IP Address of the vulnerable VM.</td>
<td width="84">5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">1.2</td>
<td width="557">Correct HTTP port.</td>
<td width="84">5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37"><strong>2 </strong></td>
<td width="557"><strong>Exploiting the System </strong></td>
<td width="84"><strong>20 </strong></td>
<td width="26"></td>
</tr>
<tr>
<td width="37">2.2</td>
<td width="557">Correct hash value from running /bin/task2.</td>
<td width="84">20</td>
<td width="26"></td>
</tr>
<tr>
<td width="37"><strong>3 </strong></td>
<td width="557"><strong>Spawning a Shell with Metasploit </strong></td>
<td width="84"><strong>25 </strong></td>
<td width="26"></td>
</tr>
<tr>
<td width="37">3.1</td>
<td width="557">Correct exploit module</td>
<td width="84">5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">3.2</td>
<td width="557">Correct payload module (there are multiple correct answers here)</td>
<td width="84">5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">3.3</td>
<td width="557">Correct hash value from running /bin/task3.</td>
<td width="84">15</td>
<td width="26"></td>
</tr>
<tr>
<td width="37"><strong>4 </strong></td>
<td width="557"><strong>Privilege Escalation </strong></td>
<td width="84"><strong>20 </strong></td>
<td width="26"></td>
</tr>
<tr>
<td width="37">4.2</td>
<td width="557">Correct vulnerable program name.</td>
<td width="84">10</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">4.4</td>
<td width="557">Correct hash value from running /bin/task4</td>
<td width="84">10</td>
<td width="26"></td>
</tr>
<tr>
<td width="37"><strong>5 </strong></td>
<td width="557"><strong>Password Cracking </strong></td>
<td width="84"><strong>25 </strong></td>
<td width="26"></td>
</tr>
<tr>
<td width="37">5.2</td>
<td width="557">Correct password for task51.zip.</td>
<td width="84">5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">5.3</td>
<td width="557">Correct hash value from running python task51.pyc.</td>
<td width="84">7.5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">5.6</td>
<td width="557">Correct password for task52.pyc.gpg.</td>
<td width="84">5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">5.7</td>
<td width="557">Correct hash value from running python task52.pyc.</td>
<td width="84">7.5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37"><strong>– </strong></td>
<td width="557"><strong>Possible Deductions </strong></td>
<td width="84"><strong>&nbsp;</strong></td>
<td width="26"></td>
</tr>
<tr>
<td width="37">i.</td>
<td width="557">Incorrect assignment_questionnaire.txt format.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">ii.</td>
<td width="557">Incorrect upload to Gradescope/Canvas.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">2.1</td>
<td width="557">No command given for exploiting the shellshock vulnerability.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">4.1</td>
<td width="557">No command given for finding the vulnerable program.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">4.3</td>
<td width="557">No command given for exploiting the setUID vulnerability.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">5.1</td>
<td width="557">No command given for cracking task51.zip.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">5.4</td>
<td width="557">No command given for scraping the shellshock server webpage.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">5.5</td>
<td width="557">No command given for cracking task52.pyc.gpg.</td>
<td width="84">-5</td>
<td width="26"></td>
</tr>
<tr>
<td width="37">+</td>
<td width="557">Your Submission Includes&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Total:</td>
<td width="84">100</td>
<td width="26"></td>
</tr>
<tr>
<td width="37"></td>
<td width="557">assignment_questionnaire.txt – Answers to questions</td>
<td width="84"></td>
<td width="26"></td>
</tr>
<tr>
<td width="37"></td>
<td width="557">README.txt</td>
<td width="84"></td>
<td width="26"></td>
</tr>
</tbody>
</table>
&nbsp;
