**Experiment 4**

Create the /home/consultants directory. Add write permission to the consultants group. Use the symbolic method for setting the appropriate permissions.  Forbid others from accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions. Change the default umask for the operator1 user. The new umask prohibits all access for users that are not in their group. Confirm that the umask is changed. 

Experiment

Command to be used:

1.sudo mkdir -p /home/consultants

2.sudo chmod g+w /home/consultants

3.sudo chmod 770 /home/consultants

4.ls -ld /home/consultants

5.sudo mkdir -p /home/consultants

6.sudo groupadd consultants

7.sudo chown :consultants /home/consultants

8.sudo chmod g+w /home/consultants

9.sudo chmod 770 /home/consultants

10.sudo usermod -K UMASK=007 operator1

11.umask 007

12. umask
![WhatsApp Image 2025-03-19 at 20 26 09_ee219b2f](https://github.com/user-attachments/assets/d0ffd116-d1a3-467b-922a-df3669633f6f)


![WhatsApp Image 2025-03-19 at 20 26 30_d6cdcded](https://github.com/user-attachments/assets/db8c6017-a351-499f-8354-a70574131a9d)

![WhatsApp Image 2025-03-19 at 20 31 07_e0a43d46](https://github.com/user-attachments/assets/472a95a8-944b-45b7-89f2-6a05843c0a97)


