## Uttaran Sinha
### It's not science if it's not safe

Once my father told me that the difference between knowledge and science is that science gives us **control and guarantees**. Without reasoning and conceptual understanding, knowledge is, as my father would say, astrology !!

### Why is a computer science masters student bothered about something not being science?

From kindergarden, I was taught that asking why and how should be a second nature to  a prospective engineer. Yet, as I see now, we are suppossed to believe things on the premise of *It works so why bother how is works?*

Calculating 763837 * 237493 is a pain....let a machine do that instead. We're 100% sure that whatever the machine answers is actually the right answer. **How?** Because we all know how to multiply and we can check that the machine is multipying based on the rules we know.

Do you know how we differentiate between a dog and a cat?.....umm...well we can't explain it (in terms of rules like in multiplication) but we can tell which is which. 
Wait....**Mind-blowing idea**, Let a machine figure it out instead. We feed it tons of images of both dogs and cats, say which is which, and when a new image comes it **should** classify correctly.
 Very well, it does, now what? Can you explain how the machine is doing it?
Um...no, but who cares if the machine is 99% accurate, right?....sadly, this is astrology and someday our future generation will laugh at us for believing in this.

### Examples?
![](https://camo.githubusercontent.com/a0bdf77aee0dad32f0ad545d79768fd7d80ddff5/687474703a2f2f692e696d6775722e636f6d2f52565a645a4f682e6a7067)
The Image on the left side is an 8 right? You can look at it 1000 times and say its an 8. Good, so does our machine learning algorithm. (with 0.999 confidence)
Now lets look at the image on the right. Still an 8 right? Yes, to a human eye. However the machine thinks its a 5 (with 0.999 confidence). 
**WHAT? Oh my god!!!**...yes I know...
Now the obvious question is, these images are generated, surely they won't occur in real life scenarios.
**The problem is, they do!!!**
 
### Ok, so what to do?
Lets think what we would do if this happenned to a child who has only seen one or two dogs and can't say that an unseen animal is a dog or cat or none?
Well, make him/her see more of dogs and cats and hope he/she **generalises**. So even if a dog is brown and another dog is white, the child knows that color doesn't matter. In scientific terms, the child becomes **invariant** to color when distinguishing between a dog and a cat.
But color is not the only thing....big dog, small dog, fluffy dog, hairless dog and so so many varieties of dogs....but they are all dogs.
We humans do a terrific job at recognising a dog no matter what type it is. But sadly, we don't know how.

In this context, color is called **perturbations** and the property that we hope to achieve is **robustness**.
In real world scenarios we face perturbations like exposure, camera angle, pictures of different resolutions etc. We want our machine to be robust against all of these changes.

We might not be able to explain the machine, but we might be able to say when the machine will fail and when it surely won't. Hopefully this takes care of the *guarantees* part. We have a lot of work to do in the *control* part though.
### Formally speaking

My work is **to verify safety of deep neural networks under a specific set of pre-conditions** so that maybe the greatest thing computer science ever invented seems like *science* after all.
Hopefully someday we will have self-driving cars that I'll trust as much (if not more) as if I were driving it.
