Introduction

In this module, I learned and practiced basic *File Permissions and Ownership Management* Linux commands.

3️⃣ File Permissions & Ownership (Command, Description & Example)


ls -l:
View permissions, owner, and group	
ls -l /home


chmod:
Change file permissions
chmod 755 script.sh


chown:
Change file owner	
chown user1 file.txt


chgrp:
Change group ownership
chgrp admins file.txt


umask:
View or set default file permissions
umask 022
