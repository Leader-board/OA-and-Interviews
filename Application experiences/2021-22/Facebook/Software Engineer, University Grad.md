## Software Engineer, University Grad

### Parameters

* Role: Software Engineer, University Grad
* Location: London, United Kingdom
* Applied: August 17, 2021
* Notified to Round 1 interview: September 29, 2021
* Round 1 interview: October 11, 2021
* Notification of failure: October 12, 2021

### Prelude

Historically, I've never been able to get a reply from Facebook despite this being my fourth successive year of attempts. The route though which I managed to get the attention was non-standard.

I did the HackerRank entrance examination for the “Facebook EMEA Virtual Coding Challenge 2021” event, butchering that LeetCode medium (technically 2-D DP, though there was a O(1) loophole) in about 12 minutes (so about a quarter of the allocated 50 minutes). Hence I was confused when I ended up being rejected from the event (because if not HackerRank, what else?). Some time later, (recruiter) (a recruiter at Facebook) sent this email:

<blockquote>
From: (recruiter) <br>
Sent: 22 September 2021 18:19 <br>
Cc: (recruiter) <br>
Subject: Facebook - Thank you!

Hi there!

Thanks so much for signing up to our Crush Your Coding Interview Workshop. We really hope you found it useful and engaging.

I am very sorry for the issues with the sign-up link, if you weren’t able to attend we do have two other crush your coding interview workshops available for you to attend: <br>
•	12th October https://crushyourcodinginterviewworkshop12oct.splashthat.com/ <br>
•	28th of October https://crushyourcodinginterviewemea-oct28th2021.splashthat.com/

If you did manage to attend, at Facebook we are constantly looking to improve, so we would really appreciate your feedback on the event - feedback is a gift! With this in mind, please could you take 2 minutes to fill out this survey:
https://forms.gle/HodfgCsGfbdBnt4U7

We also have opened up our Software Engineering Intern & Graduate opportunities. If you would like to find out more about the roles we have available at the moment please go to facebook.com/careers.

Much appreciated,

(recruiter)
</blockquote>

So I sent this, partially out of confusion:

<blockquote>
Dear (recruiter),

I don’t recall signing up for this particular one (though I might have forgotten); rather I applied for the “Facebook EMEA Virtual Coding Challenge 2021” event, but failed despite getting a full mark in the HackerRank exam in about 10 minutes:
![img.png](../../../media/facebook1.png)
Is this connected with the issue you mention in any way? I ask because I found the rejection puzzling given that the criteria mentioned was only the HackerRank score, which I believe I did reasonably well in by completing in approximately 22% of the time limit. Thanks in advance.

Regards, <br>
Leader
</blockquote>

She came back:

<blockquote>
From: (recruiter) <br>
Sent: 23 September 2021 10:50 <br>
To: Leader Board <br>
Subject: Re: Facebook - Thank you!

Thank you Leader and apologies for the confusion, you have not been taken forward for the coding challenge but you are welcome to sign-up for these events.

Kind regards,

(recruiter)
</blockquote>

That didn't answer my question. So I resent my question:

<blockquote>
From: Leader Board <br>
Date: Thursday, 23 September 2021 at 08:52 <br>
To: (recruiter) <br>
Subject: RE: Facebook - Thank you!

Dear (recruiter),

Is there a reason why I’ve not been selected <i>despite</i> completing the coding challenge, with a full score, in 22% of the time? Thanks in advance.

Regards, <br>
Leader
</blockquote>

She replied:

<blockquote>
Hi Leader,

Thank you for your email.

I am afraid we do not give feedback on at this stage; we received a very high volume of applicants for a limited number of places for our event, and therefore we do have to take some tough decisions in our process. However, this does not affect your chances at interviews for a position here at facebook and we would very much encourage you to apply.

Kind regards,

Regards, <br>
(recruiter)
</blockquote>

So she didn't want to answer the question - this is a major source of frustration I have with companies not willing to even tell me why I've failed from something. At least she invited me to apply to Facebook - which I already did more than a month back...

But then she came back again a day later and formally started the process, asking me to answer questions such as my expected month and year of graduation and similar. I've never gotten this far before! After that, I was invited for Round 1 interview - this would end up being my first ever interview of this nature. 

Note: I didn't get an automated confirmation email after applying, noting since I've seen queries about it.

### Round 1 interview

This was with (interviewer) and on a Zoom-based platform, using a Coderpad link which didn't allow for any form of compilation. Unfortunately, I did sign a NDA and hence full description of the questions cannot be provided. 

* The first question was a LeetCode Medium that was an array-based DFS problem. I got this one fully.
* The second question was linked to (but not exactly) LRU Cache - I solved this one by chaining hashmaps and treemaps.

I did find the questions hard to understand though. For instance, the first question was framed in a way that made it hard for me to understand what you wanted _me_ to do - the input/output was undefined for me for instance which made it weird personally. Is this something that Facebook expects? I don't know. Plus, I felt that she was struggling to understand my approach for Q2 - I was trying to explain it to her but she seemed fixated on something else. In the end, she just asked me to code it...

### Notification of failure

Was by email a day later, explicitly mentioned that feedback cannot be provided. For those interested, here is the failure email:

<blockquote>
Hi Leader,

Thank you for taking the time to interview for the Software Engineering position. After careful consideration, we have decided to not move forward with your candidacy at this time.

We value the time you have taken to find out more about careers within Facebook. You will be contacted if we find that your qualifications match any additional roles that you've applied to. Until then, we’d encourage you to continue checking back on our careers page for future opportunities. I am afraid we are unable to give any further feedback.

All the best, <br>
(recruiter) <br>
Facebook Recruiting Team
</blockquote>

What a joke. Messages like these do not help me at all. Yet you ask me to provide feedback...

### Takeaway

* The non-standard way I managed to not get ghosted in my fourth attempt should be noted.
* With a failure that didn't tell me why I failed, I had no idea on what I missed. I looked at other users' interviewing experiences and some did say that they got through with only solving one question out of two. That made me wonder - what did I miss? Communication challenges could be a part, but I started digging into that second question later and realised I may not have given a perfectly optimal solution. My solution was O(log _n_) time and O(_n_) space - however I think there was a O(1) time option available.
* The bug stems from a conceptional blunder on linked lists. I thought that accessing a specific element in a linked list is O(_n_). This is correct indeed - but what I missed is that given a hashmap, you _can_ access a specific element in constant-time (which was a solution in the original LRU Cache problem)! The root cause of my error was my forgetting that I could have used linked lists from first principles instead of relying on Java's linked list library. 