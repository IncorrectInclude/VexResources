# What I'm currently searching for

Granted, I have different use cases
than other people, but I just want to write down
what I'm looking for, and perhaps one day I will
solve my problems, and help other people.

## Looking for

I want a better way to handle events. The brain 
has the method that takes a void pointer which is 
okay, I guess, not the best implementation, imo. But, 
the controller buttons, or the limit switch, does not
even have this. I just want a way to pass state around. 
I want to know what happened? What is the status quo?
I want to be able to know those two things without them 
being globals. I 
don't want to have to worry about synchronization just 
to handle events. I don't want to have to write a method
for ever single event that happens, when that method
doesn't even get passed state. 
Events are handled differently in almost
every single library I've ever used, but none of them
spawn a new thread for each event. Please, just let me 
handle events from the main thread, without re-implementing
code that the people at vex already wrote.

