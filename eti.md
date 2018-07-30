## Eti Chaudhary

#### We verify HARDWARE using SOFTWARE 
We call it **HARDWARE VERIFICATION**
**Don’t run away just yet!**
Let’s take it step by step. (**OR** you may simply watch the video at the end)
Look at the image below. Have you seen such types of diagrams in your life? (If not, you are a lucky one!)

![](https://lh6.googleusercontent.com/lk0zBUx3i6rSYFxoE6XjnYfRyl1ixBEovvztrC5um26Kb8R05ujCOLA-WdVvx0nkIF4qFkjz9385TgmWLWfRu3HYlNx8_LBxvqcIGFan_1O2SP7f9QIdumHwqifHq--GxX6RhEkz =350x150)

Well, it’s called a **circuit**, and electronic devices are built on them.
*These circuits are supposed to work in certain ways to achieve certain things.*

But who designs them? Well, Humans. And what are humans best at? *Making errors.*

*So, how do we make sure that these circuits do what they are supposed to do? How do we make sure that there won’t be any surprises?*
Well, this is what Hardware Verification wants to guarantee.

#### Why should you care?
Well, for starters, we are currently living in a world where we cannot survive without computers. They are used in all walks in life, from personal use to commercial; from businesses to scientific research. But what *IF* the computer hardware itself is faulty? It is safe to say that it will cause havoc, if anything!
A small proof? Well, here's an NY Times article on a hardware bug found in Intel Chips in 1994. 

https://www.nytimes.com/1994/11/24/business/company-news-flaw-undermines-accuracy-of-pentium-chips.html

The bug was found for floating point unit (a.k.a. decimals), such as,  *1/824633702441.0* was being calculated incorrectly. This could be verified by calculating the value of : 
*(824633702441.0)(1/824633702441.0)*
which should have been equal to one. However, the Pentiums, when tested on a number of software such as Excel, Windows Calculator etc., returned *0.999999996274709702* for this calculation.

A more dramatic example found was the following, 
*x=4195835, y=3145727 and z=x-(x/y) y*
The value calculated should have been 0 but on the Pentium is was *256*! (Yes exactly!)

If you go through the article, it will be pretty clear the scale of consequences these bugs can have!
*So who's here to save the day?* **VERIFICATON!!**

#### How is Verification trustworthy?
It is now common knowledge, that software built these days, are tested by testers (again human). However, testing doesnot provide a guarantee of a bug free software. But, thankfully, verification does.

Consider, a large fruit bearing tree, having a whole lot of branches. Now, some of these branches have spoiled fruits, that one wants to remove *(equivalent to bugs in our case)*. If a person is asked to do so without any equipment, he/she can only spot out the fruits visible from underneath and well, also won't be able to reach everywhere. So what happens? Some stale fruits are removed while others remain undiscovered. This is basically what happens in testing. 

Now, equip the person with a ladder tall enough to reach all corners. Now, assuming that the person does a perfect job, all stale fruits are removed.
The second case is that equivalent to verification, with the guarantee that the person is perfect backed up by the theoretical concepts on which verification tools are built.

#### **Verifying Software v/s Verifying Hardware. Why the difference?**

Well, Software Verification has had a whole lot of limelight to itself and is equally important. But, what works amazingly for software does not necessarily work that well for hardware, unless you have a lot of free time on your hand (it's pretty slow). Also, things get ugly. Consider the circuit below and think about who might have the patience to verify it manually?

![Image result for digital circuit diagram](http://www.digital-design.com/images/Schematic.jpg =450x250)

#### **How to verify hardware using software?**
To put it in the simplest way possible, we get the software equivalent of hardware designs and then apply our verification tool on these software.
Consider the scenario where kids want to ask their dad for some permission. Well, they can't do it directly. So what they do is they get their mums to do it. Mums act as the channels and make their lives easier.
On a similar note, verification tools being software components cannot verify hardware. So, whats our intermediary? The software equivalent of the hardware!

**Why do we specifically produce software equivalents?** Well, mostly because the verification techniques for software are much more advanced and improved and hence, give us more efficient results!

**Once we have this translated version available, our tools performs the verification on it. And voila! The hardware is verified.**(Permission Granted!)

<div style="text-align:center;width:800px;height:450px;"><iframe src="https://gallery.moovly.com/embed/c923ddb1-99cb-4ca1-997a-89a356e47cf9" width="800" height="450" frameborder="0" allowfullscreen></iframe>
 <a href="https://gallery.moovly.com/video/c923ddb1-99cb-4ca1-997a-89a356e47cf9" target="_blank" rel="noopener noreferrer"><br/>Verifox : Hardware Verification</a> 
- <a href="http://www.moovly.com" target="_blank" rel="noopener noreferrer">Made with Moovly</a></div> 
