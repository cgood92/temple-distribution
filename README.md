# temple-distribution

If you follow the instructions/video below, in just 5 minutes you'll be able to:
1. Use AI to help you write a code script.
2. Run that script to produce a graph.
3. And all of this for free, without downloading anything.

Even if you're not a software engineer, you can follow the steps below and this video to write a script in no time at all.

Video tutorial of steps below: https://youtu.be/8vF2j8dQCao

## The challenge

Take a look at this site: https://churchofjesuschristtemples.org/temples/chronology/.

It has a list of temples and when they were dedicated.  Which year had the most dedications?  Which had the second?

A very simple computer program could figure this out.  But, you're not a software engineer, so how do you start?

## AI to the rescue

ChatGPT is available for free - without even an account (limited features with no account though).  Although if you want an account, it's free and I highly recommend it.

Steps:
1. Go to https://churchofjesuschristtemples.org/temples/chronology/, and copy the first 5 lines of temple dedications.
2. Go to https://chat.openai.com/.
3. Type in a prompt similar to the one below (can copy/paste if you want):
  ```plaintext
  I want to write a python script, but don't know how to do it.

I want to copy and paste a bunch of temples and their dedication years, and
I want to grab the date each temple was dedicated, and makes a graph
for how many temples were dedicated each year.

Here's a few lines of temples, just for example:

---
1	St. George Utah Temple	6–8 April 1877	Daniel H. Wells
2	Logan Utah Temple	17–19 May 1884	John Taylor
3	Manti Utah Temple	17 May 1888	Wilford Woodruff
4	Salt Lake Temple	6–24 April 1893	Wilford Woodruff
5	Laie Hawaii Temple	27–30 November 1919	Heber J. Grant
  ```
3. Here's what ChatGPT gave me for the result: https://chatgpt.com/share/678dd680-80e8-8009-911c-785469e9925f, which:
   - Includes some code
   - An explanation of what the code does
4. I copy the code ChatGPT gave me.
5. Then, I go to this website that runs code for free online: https://python-fiddle.com/examples/matplotlib.
6. Replace the sample code they have with what ChatGPT gave you.
7. Add in the whole list of temples from: https://churchofjesuschristtemples.org/temples/chronology/.
8. Click the "play" button, and view the graph below.
9. Get rid of the first several lines of temples, so that you can have a proper view.

## Next steps

Using the bottom lists of https://churchofjesuschristtemples.org/temples/chronology/, which year had the most announced temples?
