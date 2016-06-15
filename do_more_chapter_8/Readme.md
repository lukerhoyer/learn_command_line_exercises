
# Chapter 8: Moving around (pushd, popd)

## Do More

### Use these commands to move around directories all over your computer.

### Remove the i/like/icecream directories and make your own, then move around in them.

    Lukes-MacBook-Pro:temp $ ls
    A new Hope              Indeed it is            boy
    Attack of the Clones    It's pretty great       deserves
    Goodbye now             Revenge of the Sith     every
    How fun                 The Empire Strikes Back fudge
    I agree                 The Phantom Menace      good
    
    (master) Luke
    Lukes-MacBook-Pro:temp $ pushd Revenge\ of\ the\ Sith/
    ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/temp/Revenge of the Sith ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/temp
    
    (master) Luke
    Lukes-MacBook-Pro:Revenge of the Sith $ popd
    ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/temp
    
    (master) Luke
    Lukes-MacBook-Pro:temp $
    
### Explain to yourself the output that pushd and popd print out to you. Notice how it works like a stack?

    It shows where you are going, and where you just were so as to keep
    accurate information logged for later review.

### You already know this, but remember that mkdir -p will make an entire path even if all the directories don't exist. That's what I did very first for this exercise.


    
