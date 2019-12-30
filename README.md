# Time_hack_device
Inspired by David Eagleman, this device will hack your time perception

Note on the beginning: I am totally lame with electronics, if you find this project complicated, please let me know how to improve it. I consider it to be a small miracle that it actually works.

Theory and background story:

David Eagleman is one of my favorite author writing about his endeavours with studying brain.
Besides his great books which i recommend to read for everyone, you can some of his explanations on the web, as video lectures and talk.
In one of those talks, he sumarises how they studied the time perception in brain. Unfortunatelly, i could not find the lecture i saw, instead i found that Michael from V-sauce made short digest. At about 4:38 You can wath this here:
https://www. youtube. com/watch?v=BTOODPf-iuc

This inspired me for my very first project with ATTINY85 so i tried to figure out how to do it.
I am not even slightly good in programming C so it is a mess and it took some time and effort to realise that i am complicating things more than they deserve, but finally it worked. My idea was:

How it works

You are pressing the button several times,
how many times - it is choosen randomly, but let say 15 at least.
the light flashes with some delay after you pressed the button, for the set up rounds, it is around 100ms (actually i set it to 150).
Your brain learned, that these events occures at the same time, so you start to ignore the delay.
After some presses was executed, the delay time changes to very short. I gave it 10ms, since i was not sure if the program itself is not
putting there another delay by executing commands. (It is because i know about these microcontrollers almost nothing, but i am going to learn it.)

And you will see that you get very weird feeling about what happened, you will feel like the flash happened before the press.

I have to say, that it will need more experimenting and more setting all up. But the concept work.


