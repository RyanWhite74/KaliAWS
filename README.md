# AWS EC2 Kali Machine

This will be a guide on setting up a Kali Linux machine using AWS and accessing the CLI using the app Termius.

At the console home, select "Launch a virtual machine with EC2.”

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/1.png)

Then, search for Kali and select AWS Marketplace AMIs.

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/Untitled%202.png)

Select the first option called Kali Linux and click "Continue" on the next page.

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/PNG%20image.png)

Next, we will leave everything as default, except for clicking on "Create New Key Pair.”

![Untitled]()

Name the key and leave the default selections. Then, click "Create Key Pair" and save the file, as it will be needed for login.

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/PNG%20image%205.png)

Scroll down and click "Launch Instance".

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/PNG%20image%206.png)

On the next screen, you should see a success message. Scroll down to select "View all instances.”

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/PNG%20image%207.png)

You should see your instance with a status of "initializing". Refresh the page a few times and it will say "2/2 checks passed".

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/PNG%20image%208.png)

To move over to Termius, select "Hosts" and add a new host.

![Untitled](https://github.com/RyanWhite74/KaliAWS/blob/main/PNG%20image%209.png)

You can make the alias whatever you want for host name we are going to go back to AWS and select our instance so we can copy the public IPV4 address and set that as our Hostname

![Untitled]()

Next in Termius we will set the username to kali and assign the key we created earlier from our downloads and select save.

![Untitled]()

Then, we can select the host we just created, and we should have an active terminal for our Kali machine.

![Untitled]()
