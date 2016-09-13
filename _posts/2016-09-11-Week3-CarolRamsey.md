What did you do this past week?

This past week, I learned that my expectations for the course work were incorrect, in both time and difficulty. You could say I learned a great deal in this area. :) I also learned about lazy, eager and tile caches, hard-coding vs. pre-populating values and the tradeoffs between file size, memory and speed. I was fascinated by how the simplicity of calculating a single Collatz value became an interesting problem to solve, by adding the max of a range of values and the resource constraints.

What's in your way?

My greatest obstacle is time.

What will you do next week?

Here is my plan for improving my performance in this class: 1) Start the projects earlier. 2) Work with a tutor. 3) Find more time (no TV, spend less time on other classes, etc.).

Tip of the Week

(This is my own tip, for something different to write. Let me know if that isn't OK.)

I've been reading the Javascript book and it reminds me of when Javascript first came out. Web site applications had been limited to posts of form data, with very limited client-side logic. (Just so you know, I'm pretty old and this was in the 90s.) I was working for a consulting company, our client was US Bank and our goal was to write a web application front-end for multiple mainframe systems used by the call center representatives.

A programmer on our team wrote the client-side form validation. Javascript's functionality was so new and exciting, he took advantage of every feature to build complex field validation, especially around dates. His code accepted these date formats: 01/06/2016, January 6, 2016, January six 2016, Jan 06 2016, 01062016, 06 Jan 2016, 1/6/16, Janrurary: 6: 2016, etc. (I exageratte some, but not by much.) He wrote hundreds of lines of code. All imaginable cases were handled. If a non-deterministic case occured, he asked the user which date was correct. It was all very clever.

This code make the client angry. The code was pulled and replaced with about 5 lines of code that the customer wanted. (This was a relief, really, because the QA guy hadn't figured out how to test the code in less than three days.)

The client wanted this format for dates: MMDDYYYY. This required the fewest keystrokes overall, even with extra 0s for MM and DD. Call center representatives were evaluated every day, by the second. For large, consolidated banks which dealt in huge volumes, lost seconds across tens of thousands of calls cost significant money. The thought of someone typing out the date in English words or stopping to answer a question to clarify which date, made the client's eyes get real big, as if he just saw a car crash.

My tip is to know the business context for the lines of code. Whatever is going on around the project can impact which lines of code work best.
