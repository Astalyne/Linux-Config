The Public ID address is : 3.122.93.173
Port is 2200
http://3.122.93.173
http://ec2-3-122-93-173.eu-central-1.compute.amazonaws.com/



Config:---
Created the user Grader and gave it super user privileges-----
Then entered the user grader to the SSH login--
disabled password Authentication--


Modified the port from 22 to 2200 and added it to the firewall through UFW commands---
Cloned the catalog app rep----
Configured Apache and created a config file----
For the database, postgresSQL was used---


To SSH as Grader----

.rsa file key:
-----BEGIN RSA PRIVATE KEY-----
Proc-Type: 4,ENCRYPTED
DEK-Info: AES-128-CBC,F93206842A909FA0F92FD5989E8C41A3

ZiGRsnkGg6UvtmhxHXPEYX5VBGRl5xqAeUR7o3dFNNL0kbvesToP35Ixso0r3+Q0
2E0Uw9PPP5bnyyKPeZbE3lPYCvghPC6rQo4k936AtZoGRHEniu3xvLcEXtwcd6E+
3pvH3tyPhf7sCPUd2EKzevwkmUATWJpq7Mu1eIpLeSwbX7JDzArE7nOQO7iES0ab
WDpQdno2m2SKPPgVqNNpMAd+G6X6UE7vlZYbJkFRHARB46fXHDXPN2aEMdj8ZIih
3hNSRsB1CUYWqHp3Zb0p2TSou1x3ipE0V8gdGREI2e+6V0BVdYnnun0q1Bb8+Mcs
T5JMz9nXRvftXhd5aIjrQW7Jt5zxVQkPhOvoq+rlb6vudUxFYxe85Mi7R2GhWk5/
Rn9Vwnkg6+Ppt1XikRjS62XGBlFy653yGHWI3kXOmHvxzh2fqf7zzJRzqja6N05I
Ga+FrtrTzgOuYmZ0vAzVl1NOh+pbHqYCCop0T2C5hIn4sLo829zvjxUMurz3hSFj
VuDB3Tn1u41EpYcT2cyPq7O31fXGM130mFaHEo3/NbcGJczEgadrGVlos8fjSSMy
mUnwRr6takR1hFD9F+K7GY2qjrjGHnrTFxsVCijT0vCAdmhgtL1kLrcbVupY5NKZ
vt9WXO3/nXP3390vvKH3hi84XXOqO/kPJczeRd2xUTtAY8x/vmQAdc0WS7qOanHf
vBQie52Uy247VcqOoyoFmFrwAHlWCgybsKgKppA55/1YJ481DPWvwGB0EekiVI8x
2PYhl4ADHsUnaSq7k2pdXpsnkZvzjz8hyO0nEM/bVMa8/6BjgzAu3udra7WQ2ZP/
v61H+pkkI5rVAkbWPeevHQgm9hs7aKrOVmbahujGPu9Ss8thpdvHb/qgisDfyqsm
+IsKD0wmVqeenVRQnECYFGNwlP9ejcKnPTZNbZ5lrpcfhNTfavI3Q8YwylWnusUb
PAYPRiHnkRlTb5a+MLzJEZHaLwolru4x9LOivmrjmv3A/sSD8TyH3fY1IePZPxyK
fLpMYZjeMuoazFIyccUn5fLEoQyYeExBr/T7KcH3yvEbN/Qg03x7PuzxwbMxnUwk
3OxoTZk58EV5EhHAn8EE3SwtCibwm9X1IpYLoHNYrk5b/tlocikDKnLdzIyhAZim
8zKPzGOLiJ8jbUs0ZA24bn8VJeJBo54WrTkNDzhkZwbS6Vhr7qwKjzufgOkiE1T7
DjteooCJS3VFhqQ5iWH53cDi2iaMA8OMMK+L6U5rdbwq0O/BJXkkeB/SBmBBhanm
lKZD5KMDoeNNZDt5CiR7/tV0n4AM0+cnnCeYF75Q+cv5k1GZl85OEHcpJIGGxN0X
264bzckA6bgaO8HNLf1T5otEIu+MMMZOyK2cHefeODFrw078WaIBO9uZ0SxJVVbn
/cyLVU9CMxPIjxOkkjQaRhbQYMiT1U7WuUyCu3N7yiTSYqd/SuESHh77d3zv0i+n
dPLf/elefre9b3G5InqUAgnKk4LXXi5hwvoBcvaPTGT+x6acN944a9dBzhJZweTE
E5AJGE7Ps3BBRXCn+xpT7ZH9Ia815djEfnrwDrd7y7f1xjhNrnvXr3su4OJGYr8h
-----END RSA PRIVATE KEY-----
-----
.rsa.pub key:

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDTGe5Q11bxEyr+N98vgk5zIljwyhxk53k0xws2Obe0ZJlqGC9Ra1azZDTZaRC1m/+6EIQsYEXBdTJRGRdt2XtILBC/nkUQZg/2kPqXwomnfJW69vWtDkJtEN9fBzFmYYo4x+2OJAZeuJm2jUwqT1sYKkKnVtaMVQzF9i7A5oSFi7SlABLeHjk+zs3Yw/vDrk9YPWALs4/2sW1ACwEIo7NHZ6cqbB7uNXVfhcYzmdhWHOXV/XTGFBrX7FS7iJqQ47Lz979l71cScR+Y2FzBTRw6+L99xDWO5gAmMyTnz0US2AazHO6f7BVoZ4OuToTaw1ZkOqQsnqbJqmUhgaf62qgH vagrant@vagrant



---
Third party resources used:
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
helped a lot in forming a concept of the steps to do
https://www.digitalocean.com/community/tutorials/how-to-create-a-sudo-user-on-ubuntu-quickstart
