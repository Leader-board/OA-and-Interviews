## Graduate Software Engineer - 2022 intake

### Parameters

* Role: Graduate Software Engineer - 2022 intake
* Location: London, United Kingdom
* Applied: January 26th, 2022
* Sent take-home exam: January 27th, 2022
* Notification of failure: February 15th, 2022

### Take-home entrance exam

I was given a set of PDFs: a "general" exam with four questions to be done in any language, and four files that correspond to four programming languages (Java, C, C++ and Python). The instructions were vague:

> The next step, having reviewed your CV is to run you through a couple of our coding tests.  I have attached a selection of these and we ask you to complete the General test as a mandatory requirement, followed by one or two of the specific language tests.  If you claim a certain language skill on your CV, we'd like to see how strong you are in that language. We are a polyglot environment but do use Go, C, Python, Scala across a lot of the backend. These tech tests are designed to be relatively simple but allow for a thoughtful answer.

What does that mean? Am I supposed to complete one or two of the language-specific tests? At what point do I have to do a certain language to demonstrate my "strength" in that language to you (because I don't know if you're looking to test my "basic" knowledge of Python)? What does "thoughtful" even mean? A lot of ambiguity.

Anyway, I looked at the questions.

* The general entrance exam was straightforward: four LeetCode easies. I finished them off in Java. 
* The Java entrance exam was a little trickier: the first one asking me to implement a linked list library from scratch (which I did purely from memory) and a LeetCode easy.
* The C exam was harder, and cannot be directly compared to LeetCode problems since none of them test algorithmic knowledge as such - these problems look like they would fit in a university exam on C. The first one was related to linked lists, the second one asked me to identify undefined behaviour in C and the third one was something I couldn't properly understand but wanted me to do some bit/byte reversal. Again, not comparable to LeetCode.

I did not attempt the C++ and Python exams, but from what I saw, 

* The first question of C++ appears to be related to OOP but not something I knew how to do; the second was recycled from Q1 of the C exam.
* For Python, the second seems to be something I could do, I didn't know what a Python "generator" was for Q1 (but otherwise appeared straightforward).

So on the day I got the exam, I finished the general, Java and two of the C problems, stopping at Q3 since I was stuck at an ambiguity. I asked the company, who told me to resolve it myself...

The problem however was that I just was not able to get the time to sit down to complete Q3 of the C exam as a result. The issue was that I was hit with a time-consuming university coursework, and that, combined with the generally high module load, meant that I was unable to submit it even two weeks after getting the follow-up answer from the company. It must be noted that this is **not** the fault of the company.

### Notification of failure

Out of the blue (since I was still planning to get done with Q3 at that time when I was able to), it seemed that the company thought that I was done with the test and sent me this:

<blockquote>

Hi Leader

Thanks for completing our tech tests. I'll pass these on to our engineer who marks and them and feedback your results to you either directly or via your agent asap.

_As a heads-up, unfortunately, we don't offer detailed feedback on your results, they have a relatively simple scoring approach with either a No, Ok, Good and Excellent.  We tend to proceed on Ok and obviously, a No would suggest that you would not do well in the coding challenges during the technical interviews.  We don't offer further explanations behind theses tests as whilst they are relatively simple in appearance they have some challenging nuances which require an intelligent answer and it is this that the engineer is looking for.  Where we have discussed tests in the past, we found that these ultimately ended up on the internet and hence rendered the tests void. We do appreciate your time taking these tests but ultimately they are designed to prevent further time being wasted at the face to face interviews, which could easily be longer than 3hrs._

Fingers crossed.

Regards

(recruiter)
</blockquote>

A couple of notes there:

* Does the company really expect new graduates to have an "agent"? Or is this test something that is served for all candidates? I don't know.
* The reasoning between them not providing feedback is interesting. They claim that apparently, providing feedback would cause candidates to leak the questions on the internet? But then I don't need feedback to leak the questions on the internet... Not sure why they make such a claim since it almost looks like they are trying to make up an excuse. 

Anyway, a day I got the actual failure email:

<blockquote>

Hi Leader

Thanks for completing the tech tests.  Your answers have now been marked and unfortunately, they have not been regarded as strong enough to invite you on to the next stage.

Unfortunately, we do not offer any specific details behind your test results.

Sorry but thanks for having a go and your interest in Ava - Unified Security, I wish you all the best with other opportunities.

Regards

(recruiter)

Ava <br>
(email) <br>
(phone number)

</blockquote>

Right. So I failed. But why? At this stage, without having any idea, there are a couple of possibilities:

* I was penalised for not supplying an answer to Q3 of the C section
* I was penalised for something else, such as poor code quality. This would also mean that not completing the test was a good idea, because I would have most likely failed anyway.

But then I remembered that the GDPR was a thing, and invoked it. 

### The GDPR attempt

I decided to immediately use the GDPR route, sending the below to [dpo@avasecurity.com](mailto:dpo@avasecurity.com):

<blockquote>

Hello,

I would like access to all of the recruitment data you have (specifically the ones used to make a decision on my application) with me with respect to the Graduate Software Engineer – 2022 intake role. This includes full details and feedback with respect to the take-home test I did.

This is a formal GDPR request to access this data.

Regards, <br>
Leader Board

</blockquote>

I got this a couple of days later:

<blockquote>

Hi Leader,

Thank you for your email, your request has been received and will be processed shortly.


Kind Regards, <br>
(a human name)

</blockquote>

What happened next was not something I expected from my limited prior experience with the GDPR. About a week after I sent the initial GDPR request email, I got a call from an unknown number (which I missed since I normally keep my phone on silent). I called that number back. 

It was the recruiter, wanting to discuss my GDPR request. The below gives a summary of what he said:

* He noted that it's the first time they got a GDPR request of this nature.
* They noted that they didn't actually have any data on my entrance exam performance; only that they store the final result (which was a "No" in my case). The only other thing they had was some notes when they reviewed my application.
* Repeated what was mentioned when I was told I completed the entrance exam (that they don't offer feedback because they think that it would end up being leaked in the internet). Mentioned that they recycle the same exam for thousands of candidates (!). Apparently, some candidates are so overt that they plagarised entire solutions from the internet, including any typos or errors in that past solution!
* Offered to have the engineer basically look over at my solutions. While he explicitly said that the engineer will not comment on the right answer or even on what they are looking for. Still, that would be something. He then asked whether I would be fine to treat the GDPR request as resolved in that case, to which I agreed. 

Interesting. Now I had to wait to see what the engineer who marked my exam had to say. I got this five days later:

<blockquote>

Hi Leader,

Following our chat last week and your formal GDPR request, the engineering manager who wrote and marks the tech tests has provided the following insight in why you failed the test.  This does not provide you with the answers or our scoring approach but hopefully promotes an insight into where you didn't respond in the direction that we look for.

* General Q2 - think about duplicate elements, and efficiency (it can be made faster by exploiting the sorted nature of the input arrays). Also think about the side effect on the passed arrays
* C Q1 - several things wrong with this one
  * the function prototype on line 23 is wrong, so the head element can never be removed if it is even
  * think about the condition on line 37 , given the assignment immediately preceding it
  * memory leaks
  * no NULL-ing of the next pointer in malloced nodes
  * shoudln't be necessary to malloc or free nodes to solve this
  * and more ...
* C Q2 - there are some missed issues
* C Q3 not answered - the answer to his question about the perceived ambiguity is there in the question itself

If you are happy with this response, please let me know and I will close down the GDPR request.

Many thanks <br>
(recruiter)

</blockquote>

So let's now compare this with some of my commentary:

* Firstly, would I have passed if I did not bother with the C part at all? I mean, they had little to say on the Java side it seems...
* Regarding the general Q2, this stems from a lack of clarity on what you are looking for. It is clear from the feedback that you wanted efficiency. While I did notice this when I was doing the test, I thought you wanted an elegant solution and that's what I did: a crisp one-liner that however was not as efficient. How am I to know that? Given that they did not complain about the other questions in the general test, I infer that they were looking for efficient code and not raw elegancy. 
* Regarding the C bit, at first I thought _fair enough_ because I didn't properly validate my code given the timing issues described earlier. Now looking at the code I wrote:
  * He said that I didn't have to use mallocs or free to solve this. I find this odd because you want me to create a new list... but thinking about this now, OK I think I could have done this without malloc. Fine. 
  * Then they referenced memory leaks. Fair enough, I didn't call ``free``.
  * I'll need to spend more time to comment on the other parts of the feedback for that question. But I see the issue with my approach, and will admit that my haphazardness in this one was detrimental. 
* For Q2 of C, I will need to take a further look to see what else I could be missing. I did test the code they provided, so was a bit surprised to be told that there are more. But it's possible. 
* For Q3, I looked at the question again and cannot agree with the comment. The example still contradicts with what the question wants me to do, and I am still seeing the ambiguity. 

Am I happy with the response? No. But this feedback is definitely better than nothing and indeed would suffice fo the purpose of closing the GDPR request.

### Takeaway

* I did poorly in this test, especially Q1 of the C portion. It seems that they were looking for people with strong C implementation skills - of which mine was a bit rusty and it showed. I think if I didn't bother with trying the C part, I probably could have passed. 
* Strange reasoning for not giving feedback I'd say. I should also mention that in the call, they mentioned that they did provide feedback similar to what I was given to one other candidate. Why did you (the company) then tell me that _no_ feedback could be provided? Only when I invoked the GDPR did you admit that you _can_ provide some feedback. This is disappointing and not something I expect from any company. 
* It does not help anyone when you don't tell what you expect from a candidate, in my opinion.