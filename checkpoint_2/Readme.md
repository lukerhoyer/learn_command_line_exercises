
If you're not already, please go into the checkpoint_2 directory.

    
Remove the foo/bar/baz directory (do not use cd here...)
    
    pushd foo/ 
    pushd bar/ 
    rmdir baz/ 
    popd 
    rmdir bar 
    popd 
    rmdir foo/
    
Create an empty file named file2.txt
        
    touch file2.txt
    
Let's copy foo/bar/file1.txt to foo/some_other_file.txt

    
    cp foo/bar/file1.txt foo/some_other_file.txt
