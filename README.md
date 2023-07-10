# AWS EC2 Kali Machine

This will be a guide on setting up a Kali Linux machine using AWS and accessing the CLI using the app Termius.

At the console home, select "Launch a virtual machine with EC2.”

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled.png)

Then, search for Kali and select AWS Marketplace AMIs.

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%201.png)

Select the first option called Kali Linux and click "Continue" on the next page.

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%202.png)

Next, we will leave everything as default, except for clicking on "Create New Key Pair.”

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%203.png)

Name the key and leave the default selections. Then, click "Create Key Pair" and save the file, as it will be needed for login.

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%204.png)

Scroll down and click "Launch Instance".

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%205.png)

On the next screen, you should see a success message. Scroll down to select "View all instances.”

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%206.png)

You should see your instance with a status of "initializing". Refresh the page a few times and it will say "2/2 checks passed".

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%207.png)

To move over to Termius, select "Hosts" and add a new host.

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%208.png)

You can make the alias whatever you want for host name we are going to go back to AWS and select our instance so we can copy the public IPV4 address and set that as our Hostname

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%209.png)

Next in Termius we will set our username to kali and assign our key we created earlier from our downloads and save our host.

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%2010.png)

Then, we can select our host, and we should have an active terminal for our Kali machine.

![Untitled](AWS%20EC2%20Kali%20Machine%20352560c3c72b4d0a94484f17aa35c4b0/Untitled%2011.png)
