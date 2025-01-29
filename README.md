# Born2beroot

We had to create a minimal debian or rocky installation in a virtual machine.
The project feels quite old, obsolete and quite honestly boring.

In the past i set up minecraft server on my own home pc, a secondary pc i use as a server and even an older laptop before i had a server.
Setting up your own OS in a secure manner with or without graphical interface is not that hard, when you have guides to follow.

I think the intention of this project is quite lost due the circumstances and nature of it.
The project could be left out of the core and almost nothing would change.

I would introduce a similar but bigger project with proper infrastructure, graphical interface and terminal operation, aswell as shell scripting.
If its combined with something that feels useful, students would be more inclined to do their own things and learn it properly instead of following one of the many guides online.

---
The more complicated parts about born2beroot was setting up your own monitoring.sh script, that runs on every terminal at set times.
With a root cronjob that was easily done!
Writing the script and understanding it, instead of copy pasting was the real challenge.
Even setting up the bonus, which was a wordpress website and any additional service, exclusing nginx and apache, selected by oneself was in itself pretty easy.
The computer on campus didn't allow port forwarding standard ports, we had to remap and forward different ports, which was easily done thanks to the virtual machine.
I used [netdata](https://github.com/netdata/) as an extra service. It displayed in a website the entire machines resource usage in realtime.


### Evaluation

To evaluate, you had to get the shasum of your virtual drive (.vdi file) and push it into the vogsphere.
On evaluation it would've been compared that you didn't manipulate or change anything on your virtual machine.

### That did not work. You could still change anything and everything without the shasum changing (weird virtualbox handling?). This project was not properly tested. Anyone could've cheated at any point and nobody would've been able to tell. If you managed to changed the .vdi drive for a differnet shasum.

Quite the disappointing project in itself, okay for newbies to find out about virtual machines, virtualization layer and linux minimal setups without a graphical interface, command line only operations.
