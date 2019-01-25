# MetricChanger

Requirements : .NET Framework 4.6.1 

What is it used for ?
I have a slow-ish ADSL (10Mbs down, 1Mbs up) so downloading video games / large software takes a while, but i'm lucky enough to have 
unlimited 4G, so i can download slightly faster. Obviously i found out about ForceBindIP (it allows to force a software to use a specific
interface) but it doesn't seem to work well with Steam or Battle.net (sometime it would just change to the interface with the lowest metric).
So what i used to do is set the metric of my 4G lower than my ADSL and use ForceBindIP bound to my ADSL to launch my web browser, so that 
i could download my games and still be able to browse the internet without issues.
So now i can do all that from one place !

Changing metric require an elevation (i used netsh to do so), you could launch as admin to avoid getting the prompt everytime.
The software doesn't need to stay open, once you've changed the metric it will stay the same until you change it, same for ForceBindIP.
To change interfaces order, click and drag it at the position you want it to.
Also to avoid any issues, i'd recommend setting metrics back to automatic once you're done.


There's probably a lot of things to improve, if you have any ideas / suggestion please feel free to tell me as i used this project to practice using C#.
