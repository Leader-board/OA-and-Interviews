## Quant Trade Developer
### Parameters

* Applied: May 4, 2023
* Phone interview: May 23rd, 2023
* Third stage take home exam/group task: June 29, 2023
* Notification of failure: June 30, 2023

### Entrance exams

Exactly the same as described [here](../../2021-22/Tibra/Quant Trader - Junior.md). Though, they did reset the HackerRank entrance exam so that I could take it using my normal HackerRank account, rather than being forced to create a separate account...

Also: a question (about the personality test) asked to them got no response.

### Proceeding to the phone interview

A few days after finishing the entrance exam, I got this:

<blockquote>
Hi Leader,

Congratulations! We're pleased to advise that after reviewing your online testing results, you are progressing to the next stage of our assessment process. This stage is a 30-minute phone interview, for us to get a better understanding of your suitability for the role.
To schedule the interview, please click on the link below and select a suitable time to speak with one of our Talent team members:

Schedule an interview

Please have a pen and paper handy during the interview, and ensure that your computer can run Microsoft Teams to connect to the meeting.

Kind regards,

Tibra Recruitment Team <br>
Tibra Global Services Pty Ltd <br>
www.tibra.com <br>
108 Lawrence Hargrave Drive, Austinmer NSW 2515, Australia <br>
PO Box 3061, Austinmer NSW 2515, Australia
</blockquote>

So I didn't fail the entrance exams this time - interesting. I opened the form - there were options from next week. I chose a Tuesday, the second earliest date possible. Note that I'm several hours away from them as I'm GMT +3, so from their perspective I chose a slot towards the end of the day.

### The phone interview

The phone interview was via Teams, camera off on both sides. It started with a discussion on what the role is, and clarifying things such as salary (AUD$ 120,000 per year), visa sponsorship, training and more. Fine to me. Then the brain-teasers:

* Jim has twice as many sisters as brothers. Jane, Jim's sister, has the same number of brothers as sisters. How many siblings are there?

Got this fully right.

* You have a right-angled triangle with perpendicular side lengths of 10 and 15. What is the area of the largest square that fits into the triangle, whose sides are parallel to the perpendicular sides of the triangle.

This is where I surprisingly screwed up. The problem was that I somehow solved the problem thinking that we were looking for a **rectangle** instead of a square, giving the answer 37.5 instead of 36. What was even stranger was that the recruiter accepted it as if it was correct, telling me to explain and moving on after that!

After that, there was a brief explanation of what would come next, and then time for my questions. That was it.

### Proceeding to the third stage

After realising the blunder I made with the second question (and frustrated that the recruiter did not point out my mistake to me at any step), I thought that my chances of moving forward was slim. It was hence a surprise when I got to know that I actually managed to move on to the next stage:

<blockquote>
Hi Leader,

Thank you for participating in the phone interview.

I would like to progress you to the next stage being a group strategy task.

This will take approx. 3.5 hours – 2 hours to work on a data set, 1.5 hours to present your findings to a Tibra technical lead and work on a group task with another candidate.
Would you be available on Thursday 29th June, 3:00pm - 6:30pm AEST for the group task?

If this time does not work for you, can you please send me through your availability.

Kind regards,
[recruiter name]
</blockquote>

OK, this is interesting in many ways. What's in this stage?

<blockquote>

You will be sent the data set at 3:00pm AEST. The goal of your research over the 2 hours from 3:00pm AEST, is to explore the data and discover any relationships from the signals to the asset with the intention of trading the asset. Be prepared to present the outcomes of your investigation to Romen and your partner. The exercise that you will do afterwards will be a group exercise, where you will join this meeting at 5:00pm AEST, and Romen will give you the details after the presentation.

Please ensure you have a jupyter notebook environment with a Python 3 kernel and Teams installed on your device to share your screen. Please ensure that your device is able to share the screen, as on some PCs / Macs this functionality can be temperamental.
</blockquote>

and

<blockquote>
Below is some further information in regard to the group task.
* The goal of the 2 hours is for you to work individually to understand, explore the data and its relationships to discover any relationships from the signals to the asset with the intention of trading the asset.
* One clue that I can give here is that the goal of financial analysis in trading is almost always to gain useful insights about an asset and to predict its behaviour.
* If you have experience with pandas/python analysis this is preferable but not a requirement.
* When you join the meeting you will present your findings, only needs to be brief, no PowerPoint required.
After the presentation our Tibra interviewer will provide you with instructions for the group component that you will work on with the other candidate.
</blockquote>

So, to summarise, we have

* an individual data analytics task of two hours, and
* a group task - they seemed to be tight-lipped there. I've never had such a task for an interview before.

### The third stage

This was via Teams. At first I struggled to join since it wasn't letting me for some reason, but managed to work around it by using the web version. 

* The first part consisted of my being given a dataset (a few hours before it was actually scheduled to start) and asked to find any relationships from the dataset with the intention of trading the asset. Now, the file only contained the stock price and eight signals (without a description on what the signals were), so I had to reason solely on the values (i.e, the trends) when performing the analysis. I more or less did it using just correlations.
* After that, I (and the partner - I was first) had to present their analysis. And [interviewer] seemed to not like the way I used correlations. According to him, he thought that it was a mistake and thought I didn't know what a predictive power function was. Now, I do know that correlations have their limitations, and he correctly pointed out that (for instance) a quadratic model cannot be properly handled using correlations (but can with a predictive power). But I personally didn't agree with the assertion that my usage of correlations was improper - after all, you need a ML model if you take the predictive power route. TLDR; yes predictive power is better, but correlations isn't "useless"
* The partner on the other hand also used correlations, but took a more ML-like approach by showcasing things like PCA. As I suspected, that in itself didn't lead to any useful signals. 
* Then came the group task part. It was an extension of the first phase - this time to actually implement a backtesting strategy to find a PnL (profit and loss). I didn't like this section. This is a task that (in my opinion) is best done individually - after all, each person may have their own approaches and you can only choose one (within 40 minutes). Hence it was more of my "assisting" the partner, who did the bulk of the work - I felt that I couldn't showcase what I knew. That being said, my parter was no slouch and was clearly more experienced in ML than I am. 
* And then came the time for questions. The questions my partner asked were coincidentally the same as mine, so I didn't have anything extra to ask.

### Notification of failure

Happened the next day. For me, it was a case of my looking at my watch, seeing the first few words, and going back to sleep, in resignation of the fact that I've failed as usual yet again...

<blockquote>

Hi Leader,

Thank you again for your application for our Quant Trader Developer position and for participating in the group strategy task interview. <br>
Unfortunately, on this occasion we will not be progressing you to the next stage as you did not meet the requirements for the role. <br>
It’s a fiercely competitive industry, and we receive around 6,000 applications annually. Ultimately, we offer less than 1% of applicants a position due to the technical demands of the role. <br>
Thank you for the time you have taken for the recruitment process with Tibra, I wish you all the best with your future plans!

Kind regards, <br>
[recruiter]
</blockquote>

My prior experience with them has been that they are not receptive to asking feedback. I still decided to try, and as a pleasant surprise, got this:

<blockquote>

Hi Leader,

Thank you for your email. <br>
In terms of feedback, I can provide some improvement points:
* developing a deeper understanding of statistical analysis, modelling and knowledge of the pandas library.
* then as an extension to this focusing on breaking problems down with these in mind.
  Hope this helps.

I would suggest applying again after 12 months. When you reapply, we would have a discussion around what you have worked on during that time and what further experience you have gained through work or further studies.

It has been great speaking with you and I wish you the best with your future plans.

Kind regards,

[name]

</blockquote>

Better than nothing, but still rather vauge in that they didn't expand on the points mentioned. I tried to get that clarified:

> That does help, but can you expand on whether I was penalised on the first (i.e, the data analytics part), second (i.e, the group task part) or both? Thanks in advance.

I got this:

> Both aspects are taken into consideration. Unfortunately, in this instance there were other candidates (outside of your direct partner) that you were assessed alongside throughout the interview process that demonstrated higher competency in the areas required.

So, to sum it up: I was incompetent. 

### Takeaway

* This is yet another instance of a take-home exam failure, which is something that has continued to elude me. I'm not sure on what more I can do to avoid getting screwed every time I have to take one of these tests, and it's not like I hear others struggle to get past these tests. 
* Their Glassdoor page seems to be pretty concerning, with comments on the low salary, poor working hours, "company in decline" and more, going as far as some alleging company pressure to provide positive reviews. In fact, it's the second most concerning set of reviews I've seen, only behind [TPP](../../2021-22/TPP/Graduate Software Developer.md). They disclosed that the base salary is AU$ 120,000. That's actually pretty good on the surface (when converting to euros for instance) - of course that doesn't take into account cost of living differences and I don't know how well their competitors pay. They also said that they offer relocation assistance and such. However, if the company is really as bad as the Glassdoor reviews say, they (Tibra) have done a good job in masking that from the interviews, because unlike TPP, I didn't get the impression that the company was that bad. In fact, I'd say that they did actually OK - while the lack of a response in the first part was unnecessary - and waiting a month for the take-home exam was rather long - they actually managed to give meaningful - if brief - feedback. That's better than many companies - but then I should note that they refused to provide feedback when I failed in 2020-21. Whether that's because they changed their feedback process since then, or because I managed to progress further in 2023-24, is not something I know.
* I'm still not entirely sure how they seem to be only company that offers visa sponsorship - at least in theory.