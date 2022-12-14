# YuchenWang Feedback

- Which parts of the lab specification have you found most confusing or difficult to understand? Be specific, and quote any parts of the lab description relevant to your answer (e.g., "modify the PIO/DMA logic analyzer example to record a timestamped trace of an RP2040-ADPS9960 exchange while the BOOT button is pressed.") I will make particular notice of anything that seems underspecified (e.g., words whose meaning is not clear from context, or conflicting interpretations of a deliverable).

  I think all the lab parts are well orgnized this time, but some parts may make me feel confuse. For example, I did the part 4 for slow motion, I did not know which methods I have to use, such as adjusting PIO, Clk. I have no idea of this part, hence I directly used double data array on my PC and then write it double size array back to qtpy 2040 to let it slow down. However, when I did part 7 and 8, I recognied I did mistakes on part4, but I have no time to modify it before the DDL. I believe that it is a better way to have a list that display what languages we have to use, and what components we have to communicate. Especially, if you could give us a result of each parts and some example codes, it would be great to let us know wheter we did correct.

---

- Which lab topics have you found most confusing or difficult to understand? E.g., "serial communication with Python," "aliased bitwise operations," "programming the PIO," etc. Be specific, and describe any lingering areas of confusion and/or anything that has helped you navigate them.

  I am really confused about PIO part, since I never learn any microcontrollers that equip with PIO. When I first time opened the rp2040 datasheet I felt it really different from Arduino. I think we all guess what PIO is through the code of the example, but in fact we don't know and can't use it. All we know is that it is strong. PIO is exclusive to rp2040 and I don't think it should be the center of the experiment and the course. Because this course should introduce some functions of conventional microcontroller to us, after all, this course is not called Introduction to RP2040. So, I would prefer to talk about more general things in the class, like how I write CmakeLists, how I use the SDK, etc. We have no contact with it, it is very difficult for us to master how to use PIO at the very beginning, and the datasheet is very confusing, just like a dictionary, no one is willing to read it often and inquire how to use PIO when not needed.

---

- Which parts of the lab have you found most difficult to implement? Again, be specific, citing any parts of the lab materials & your own code that are relevant to your answer.

  The most difficult part for me is the PIO I mentioned before, the second one is to write CmakeList, and the last one is to input characters into QTPT2040, because many input functions that can be used on Arduino or C cannot be used in this microcontroller, or characters cannot be retrieved normally. Although I like to challenge new things, every time I have to think for a long time because a basic function cannot be used, but it does improve my ability to retrieve information and self-study. I think it would be very helpful if the professor could tell us what functions to use or tell us where to make mistakes before starting the experiment, or show us a Demo of it in class.

---

- What steps have you taken to resolve these difficulties? Any other barriers you have faced to completing this assignment? Mention any students, repos, or other resources you have found helpful in completing the lab so far.

  Every time I encounter a problem, the first thing I do is search on Google to see if anyone has the same problem as me. And when I want to implement some functions, I will go to the official forum to find solutions. Although sometimes it is not applicable to 2040, the basic logic and ideas are the same. I will mimic the code and debug it until it runs. I have to say that what helped me the most was the code uploaded by my classmates. I was amazed that some of my classmates' codes were really good. When I have no idea how to proceed, I will open Git to see the ideas of my classmates. I will find that most of the time, I am only one step away from success, but I may not be the key step. Therefore, the code of the students promote me a lot, and I was able to use CmakeLists and write some complex code from the beginning. I still have to say that I learned something in this class that I didn't learn in my previous Microcontroller class.
