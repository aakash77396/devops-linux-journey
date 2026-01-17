Virtualization
1) Bare-Matel : Direct hardware par run hota hai
2) Hosted : os ke upar ex:- virtualBox, parallels for mac

BootLoaders: GRUB(GRUB is the program on linux system that load and manages the boot proces)

states of process in linux?
sleeping
running
kill
stuck
zombie
stops

Commands: instruction for linux
top: all running process show
df -h: all disk size
cd /:Root folder
ls :List show
cd:change directory
pwd:show current location
mkdir:make adirectory
rm: remove files
rmdir: remove directory
cat:see in the files
zcat: see in the zip files
touch:new file create.    touch newfile.txt
head:first 5 lines show
tail:last 5 lines show
tail -f:last upcoming lines or logs
less:files ko chhote chhote page me show krta hai
more: files ko bade bade page me show krta hai

cp:copy files        cp newfile.txt devops/
here newfile.txt is source

mv: move files,rename files name
wc: no. of lines,words,bits
vi,vim:editor in unix and linux os( for insert press i then bahar aane ke liye press esc then :wq enter)
ln:hard-link,soft-link(shortcut) 
soft-link: if the original source is deleted then shortcut is also deleted. ln -s /home/ubuntu/file.txt softfile-link
hard-link: if the original source is deleted then shortcut is not deleted. ln  /home/ubuntu/file.txt hardfile-link
cut:string cuting cut -b 1-4 myfile.txt here b for bit 1 to 4
tee:take i/p,o/p and didplay on the scrn
echo:print anything in file if file is not present then they create also.  echo "hey! this is devops-txt" > devops-file.txt
sort:sort a/c to alphabatic
clear: to scrn clear
diff: diff between two files   diff demofile.txt hellofile.txt


