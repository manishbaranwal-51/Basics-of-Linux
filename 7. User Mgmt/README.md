Introduction

In this module, I learned and practiced Basic command of *User Management* in Linux.

7️⃣ User Management (Command, Description & Example)

sudo:
Run command as superuser	
sudo apt update


who:
Show who’s logged in
who


users:
Show currently logged users	
users


adduser:
Add a new user	
sudo adduser devuser


passwd:
Change password for a user	
passwd devuser


deluser:
Delete a user
sudo deluser testuser


usermod:
Modify user account	
sudo usermod -aG sudo devuser


groups:
Show groups user belongs to	
groups devuser