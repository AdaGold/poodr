## Chapter 2
#### Designing Classes with a Single Responsibility
>A class should do the smallest possible useful thing.

>Applications that are easy to change consist of classes that are easy to reuse.

>How can you determine if the `Gear` class contains behavior that belongs somewhere else? One way is to pretend that it's sentient and to interrogate it. If you rephrase every one of it's methods as a question, asking the question ought to make sense. For example, asking "Gear, what is your ratio?" seems perfectly reasonable..."Gear, what is your tire size?" is just downright ridiculous.

**Depend On Behavior, Not Data**

Hide instance variables. [[Code example](https://github.com/skmetz/poodr/blob/master/chapter_2.rb#L61)]

Hide data structures. [[Code example](https://github.com/skmetz/poodr/blob/master/chapter_2.rb#L123)]
