 
// Complie command
 gcc -Wall versfs.c `pkg-config fuse --cflags --libs` -ggdb -o versfs


// once in directory, run this to create a mount point
./versfs $cwd/source-dir $cwd/mount-point

// see active processes, kill if needed
 ps aux | grep mdhulipala19 | grep versfs


// once done, unmount
fusermount -u $cwd/mount-point 


// Write commands

 cat > sample.txt

 //enter text

press Ctrl+D

cat sample.txt

//You should see the message you typed. 

You can add text to a file using the same process but use " cat > sample.txt" at the start instead. 