# crackme_itsaunixsystem

This repo contains a small x86 crackme I made at the beginning of 2018. I always preferred smaller crackmes full of clever tricks that "pack a punch" to crackmes that just stack complexity on top of complexity. Hopefully this crackme falls into the former category. 

This is a "CTF style" crackme, so your goal is to obtain the flag hidden inside the executable. Even though it may not seem so at first glance, there is a huge number of username/password pairs that make the crackme print the flag to its standard output. However, it is not necessary to find such a username/password pair in order to get the flag. 

<details> 
  <summary> I understand that a lot of new reverse engineers might get stuck on a certain part of this crackme. If you feel lost, expand this for a small hint. </summary>
   https://en.wikipedia.org/wiki/JIT_spraying
  <details> 
  <summary> Expand me if you still feel lost :) </summary>
   Why would a function return a value if this value doesn't seem to be used?
</details>
</details>

 
