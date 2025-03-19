**Experiment 6**

Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system. 

Experiment

Command to be used:

1. getent passwd operator1

2. sudo useradd -m -s /bin/bash operator1

3.  getent passwd operator1

4.   sudo passwd operator1

5.   cat /etc/passwd | grep operator1

6.   sudo useradd -m -s /bin/bash operator2

7.   sudo useradd -m -s /bin/bash operator3

8.    sudo passwd operator2

9. sudo passwd operator3

10. sudo usermod -c "system operator 1" operator1

11.  cat /etc/passwd | grep operator1

12.  sudo userdel operator3

13.  sudo userdel -r operator3

14.  cat /etc/passwd | grep operator3


![WhatsApp Image 2025-03-19 at 20 51 15_89135422](https://github.com/user-attachments/assets/8f235ade-f875-4aa8-ad62-df6f2a525367)


![WhatsApp Image 2025-03-19 at 20 51 03_239ebab6](https://github.com/user-attachments/assets/3ea36751-b53c-401b-a85f-e84d49b95235)

