
# Chapter 17: Finding files (find)

## Do More

### Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

### You can put any directory where the . (dot) is. Try another directory to start your search there.

    Lukes-MBP:learn_command_line_exercises $ find . -name "*.txt" -print
    ./checkpoint_2/file2.txt
    ./checkpoint_2/foo/bar/file1.txt
    ./checkpoint_2/foo/bar/some_other_file.txt
    ./checkpoint_3/foo/bar/baz/blah.txt
    ./checkpoint_3/foo/blah.txt
    ./checkpoint_3/temp/blah.txt
    ./checkpoint_4/color_preferences.txt
    ./checkpoint_4/foo/bar/file1.txt
    ./checkpoint_5/foo/bar/file1.txt
    ./checkpoint_5/foo.txt
    ./temp/boy/awesome.txt
    ./temp/fudge/neat.txt

### Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?

    find . -name "*.mov" -print > /Users/lukehoyer/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/temp/fudge/neat.txt
    
