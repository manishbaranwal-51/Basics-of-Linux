Introduction

In this module, I learned and practiced basic *Search and Filter* Linux commands.

4️⃣ Searching & Filtering (Command Description Example)


find	
Search for files/directories	
find /home -name "*.txt"


locate	
Quickly find files (uses database)
locate passwd


grep	
Search inside files for text patterns	
grep "error" /var/log/syslog


grep -r	
Recursive search inside directories	
grep -r "function" /etc


wc	
Count words, lines, and bytes	
wc -l filename.txt


sort	
Sort lines in a file
sort names.txt


uniq
Remove duplicate lines
uniq list.txt


cut	
Extract columns from text
cut -d':' -f1 /etc/passwd