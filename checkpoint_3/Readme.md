
If you're not already, please go into the checkpoint_3 directory.

    cd checkpoint_3
    
Can you rename foo/bar/file1.txt to foo/blah.txt?

    mv foo/bar/file1.txt foo/blah.txt
        
Let's make a copy of foo/blah.txt and put it in the foo/bar/baz directory.

     cp foo/blah.txt foo/bar/baz/
     
What happens if you touch an existing file. (Hint:  The answer is not nothing...)

    It is replaced
    
Can you copy the foo/blah.txt file to slash temp?

    mkdir temp
    
    (master) Luke
    Lukes-MacBook-Pro:checkpoint_3 $ cp foo/blah.txt temp
    
Can you copy .bash_profile in your home directory to the current directory? (Do not use cd here...)

    cp ~/.bash_profile .
    
What's in foo/blah.txt?

    5000 lines telling me what line they are
    
Can you show me what's in foo/blah.txt one page at a time?

    more/less blah.txt    
