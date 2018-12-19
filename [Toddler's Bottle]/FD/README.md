# Challenge 1 - [FD]
>Mommy! what is a file descriptor in Linux?
>
>* try to play the wargame your self but if you are ABSOLUTE beginner, follow this tutorial link:
>https://youtu.be/971eZhMHQQw
>
>ssh fd@pwnable.kr -p2222 (pw:guest)


**1.** i started the **ssh session**:

![](https://i.gyazo.com/65a7d4b10b3049f943905e843ad49c8c.png)

**2.** i then checked the files and found a file named that i could access **"fd.c"**

![](https://i.gyazo.com/f6551b22b481bd2971254d9329af51f0.png)

**3.** i checked the code and saw that part of it was subtracting 0x1234

![](https://i.gyazo.com/2c21cb80a1409339a4ed5cfb92d95c10.png)

**4.** i then tried the value **4660** and it worked giving me the flag **"mommy! I think I know what a file descriptor is!!"**

![](https://i.gyazo.com/0d8f4ed33863b7dfcf8cef275fac8eb0.png)
