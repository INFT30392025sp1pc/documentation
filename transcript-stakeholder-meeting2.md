
| Time | Speaker                 | Transcript |
|:----      |:-----------------------------|:----------|
| 0:03      | James   | The the idea, right? So just to make sure we're on the same page, so structural engineering department at the University of Australia connects routine examination. |
| 0:14      | James   | On this Truss idea. |
| 0:18      | James   | And the idea is to create randomised exam papers for each student so that they can't coordinate their work. Is sort of what we assumed. |
| 0:30      | James   | And create sort of individual exam papers, so the output. |
| 0:33      | James   | That you want. It's essentially a template. |
| 0:37      | James   | That was provided by Danda. |
| 0:41      | James   | With individualised parameters. |
| 0:45      | James   | So in the case of this trust diagram, it would be P1P2 and all these other variables are randomised within ranges. |
| 0:55      | James   | And then the output is essentially the example with the individualised student identification number and name put in place, like the header and the footer. |
| 1:06      | James   | With a alternative with a changing trust diagram so so you want to be able to modify the trust diagram. |
| 1:16      | James   | And you want to be able to modify the number of parameters and the names of the parameters. This is all stuff that we've kind of assumed the outputs that was determined was apdf. |
| 1:29      | James   | That dander said that that was probably the best output. |
| 1:34      | James   | And then there were a few other. |
| 1:36      | James   | Let's have a look quick look at our requirements down here. |
| 1:42      | Lisa   | And dander said that she did not want us to try to generate an answer key to go with the question. |
| 1:50      | Sisi        | Mm hmm. |
| 1:55      | James   | So the other thing is to be able to generate copies of past papers created. So if you create a paper for myself, James in 2025, you want to be able to go in and access that paper as a historical record. |
| 2:11      | James   | Generate the designated amount of the app so the other stuff was the importing of data. So. |
| 2:20      | James   | What dander seems to be doing now is taking excel sheets. |
| 2:25      | James   | And using them to create a mail merge. The easiest way that we could sort of that we sort of talked about getting the data into an application, whether it's a web application or desktop or something is to do like an import of a CSV file of student information. Does that. Is that still something that you would prefer is that is that the kind of thing that you're after, do you think? |
| 2:53      | Sisi        | We we can clarify from the the last point, yeah. So basically the the outcome of the application we expected would be something like what done that has been doing previously using mail merge. So basically apdf document with the student information plots, the questions and the the trust layout plus the the randomised parameters. So because. |
| 2:54      | James   | Yep. |
| 3:18      | Sisi        | The student information definitely has to be read in from an external source. |
| 3:24      | Sisi        | Well, as the question text not not the not the trust layout and the the the parameters. So we were thinking maybe this information can be supplied by the users who are sort of inputs. |
| 3:43      | Sisi        | Function. So yeah, of course that's easy for. |
| 3:49      | Sisi        | And also for example, don't to download the student list and then yeah can be. |
| 3:55      | Sisi        | Can be uploaded as an Excel and a possibly the question text on either as a user input text or can be read from a Word document. |
| 4:09      | James   | And I was curious as well. I'm sure the others have questions, but I was curious about whether you only wanna focus on this exam question, this type of exam question or whether you're interested in having the application be able to generate other types of exam questions. Is that something that you have in mind at all? |
| 4:35      | Sisi        | Because this has a little bit specialty behind cause given given that this is about related to structure. So yeah, we're we're we're focusing on this type of question but of course. |
| 4:51      | Sisi        | The flexibility. |
| 4:54      | Sisi        | Can be made upon the trust layout that that's why I think you guys been spending some time trying to understand that with standard. So this is just like. |
| 5:07      | Sisi        | A a a version of the trust layout. So that's why I also want to clarify a the parameter. So I had to check with standard and we agreed that. |
| 5:20      | Sisi        | We can sort of fix the parameters to be two sets of parameters, so one is the the angle so you can see that there is a SITA on that trust layout, but there's a potential for for more. |
| 5:38      | Sisi        | Angles to be there, so like alpha beta but but in that particular. |
| 5:45      | Sisi        | Sample. That's only one angle parameter there, and the other sets will be the lengths. So in that trust layout there's L1L2 and L3, so they all belong to the lens parameters. So we can provide you guys with a a range for you to supply. That's why at this stage you don't really have to worry about generating an answer key for the question. |
| 6:12      | Sisi        | But because the the the range of the parameters will are eventually affect the the answer, so that's why we'll give you the range. |
| 6:24      | Sisi        | So for the application you can just only focus on this particular type of question, but in terms of the variation of the trust layouts, we could expect a little bit more flexibility on that. |
| 6:37      | Lisa   | So is it? I'm just thinking here, is it that you would like us to be able to like for the application to go, how many different angles are there going to be and you you input three and then you're like, what are the range of the angles and you input the range and it goes. Thank you. We'll generate a random from that. |
| 6:41      | Sisi        | It. |
| 6:57      | Sisi        | Yes, yes, that's that's the that's the concept, yeah. |
| 6:58      | Lisa   | OK. |
| 7:06      | Lisa   | OK. All right. And is the idea that you would be able to draw the trust layer in the application or just upload an image that it can populate into the? |
| 7:19      | Lisa   | Exam paper. |
| 7:21      | Sisi        | OK, so as a client I think at the basic level we can upload meaning the trust layout will always be predefined or it can be a user input. Of course as an optional if you guys will be able to develop it to be like generated then that would be fantastic, but not it's it's it's additional. |
| 7:44      | Lisa   | OK. All right. Yep. |
| 7:44      | Sisi        | It's optional, yeah, yeah. |
| 7:50      | Lisa   | K. |
| 7:51      | Steven  | I did have a question relating to the provision of the diagrams and of the for I suppose the ranges for the parameters. How long how much lead time should we give you to provide that to us so we can, you know, use that as part of their development. Would it be like something you could generate you already have on hand or would it need a couple of weeks to lead time for that? Or yeah, what kind of timeframes would be looking at there? |
| 8:00      | Sisi        | Mm hmm. |
| 8:14      | Sisi        | Oh, we we have that information ready already, so if you need that, I can talk to Dan. Dan probably provide to you guys with that range by this week. Do you do you need that in this document? |
| 8:16      | Steven  | OK, brilliant. |
| 8:28      | Steven  | Not for this document, but I'm thinking towards, you know, when it comes to development deployment, just the scheduling and all that, but that's. |
| 8:32      | Sisi        | Well, of course. Yeah. Yeah, of course. We we can provide them any time. Yeah. Yeah. |
| 8:35      | Steven  | Alright, thank you. |
| 8:40      | Lisa   | But I guess something that we sort of floated with. |
| 8:46      | Lisa   | Dent. It was like our idea here is that it? The only access to this would be the teaching team. Like this is it for student access. This is for teaching team access. |
| 8:59      | Sisi        | Yep. |
| 9:00      | Lisa   | And that possible future extensions was that it could be utilised for additional subjects. |
| 9:09      | Lisa   | As a possible extension later on. |
| 9:13      | Lisa   | You know, so like if we built it so that there was a functionality to add additional subjects later. |
| 9:21      | Lisa   | Would that be something you could foresee being useful for the teaching team at the university? |
| 9:30      | Sisi        | Of course, I I I would say that definitely we're we we have more courses would benefit from this kind of randomization of numbers. I'm just not sure to which level I mean I mean of course if we're thinking about like as a system then I could be arranged based on courses and then this this is a type of assessment under this course like another assessment under the same course. |
| 9:59      | Sisi        | Or if we have multiple courses and then it's just within the same application, I'm not sure I I guess for for this aspect you guys can give us some suggestion. But so far we're happy that this can be just an application for this particular course. |
| 10:18     | Lisa   | Sure. Only because I guess the follow on question from that is if this is for teaching team for this subject, does the application need to verify that the person using it? |
| 10:33     | Lisa   | Is a member of the teaching team for this subject because we know that there are some tutors who tutor with certain subjects but are still students in other subjects. |
| 10:42     | Lisa   | And so we obviously don't want them having access to exam generated papers for a subject they may be studying. |
| 10:47     | Sisi        | Yep. |
| 10:50     | Sisi        | Yep. |
| 10:51     | Lisa   | Is that something that we should consider? |
| 10:54     | Sisi        | Yeah. Yeah. So for generating the exam questions that has to be limited to only the teacher who's teaching this course. Yeah. |
| 11:05     | Lisa   | Yeah. So that's what we're also thinking that, you know, if dander was running the course, it would be her who would have access to generate the questions. |
| 11:18     | Lisa   | But for example, a tutor may have access to. |
| 11:23     | Lisa   | Access a student's generated exam, but not to generate the exam. |
| 11:29     | Sisi        | Yeah, that sounds good. Yeah. |
| 11:31     | Lisa   | OK. |
| 11:32     | Steven  | Just if I could take a step back from that. |
| 11:35     | Sisi        | Yep. |
| 11:36     | Steven  | Would you require something that requires some kind of login screen or some sort of user authentication tied to single sign on? Perhaps with university or how? Or would it be like a a basic programme that is like we provide a a programme in a file and whoever has it on the desktop runs it? Like what level of security authentication controls would you require for this or do you envisage this needing? |
| 12:04     | Sisi        | Because as as you guys mentioned that actually in terms of the budget it's it's actually little to know for for this project. So I would say that. |
| 12:14     | Sisi        | We're we're not really expecting this to be something huge like I'm having a server or even like a cloud platform, so. |
| 12:25     | Sisi        | As long as it can function well, probably it would be a good idea to have some sort of authentication, but there's no high level expectation on that. |
| 12:39     | Steven  | And when you mention cloud server, perhaps with, is there a requirement that the that we use one of the universities cloud environments or are we able to provision access via a third party not administered by the universities IT teams? |
| 12:56     | Sisi        | If possible that, like the university wants to be better yet. |
| 12:59     | Steven  | OK, go ahead. |
| 13:04     | James   | But out of interest, do you have just in terms of the UI, probably some of our next steps will be prototyping aui for you guys to have a look at. Do you? Do you have like a another application or another programme or another even web application or web page in minds that you think that you thought, oh, I'd, it'd be really great to have this application look like that or I envision it. It's similar to to this. |
| 13:32     | James   | Just so we can go and do some research if if not, that's OK. We can go and find some more applications, but I just thought I'd ask the question. |
| 13:40     | Sisi        | I think I should speaking on behalf of Dan. Don, who's who's potentially be using that. Probably not, but then we'd good to have something simple. |
| 13:52     | Sisi        | But user friendly and given considering that's that's a likely the person who's going to use that is not having a strong technical background. So yeah. |
| 14:03     | Lisa   | Is there anything after having a a review of the document that you feel that we've forgotten about anything that you could think of that we haven't considered? |
| 14:15     | Sisi        | I think it looks good to me. It's just this, possibly some minor specifications about the flexibility of of that application in terms of generating the parameters. I think we general and I will work on that and provide you guys with a short amendments to to that I think but but it's nothing. |
| 14:40     | Sisi        | To this document because it's a little bit too too much details in that, but it will be relevant to later when you guys start implementing, yeah. |
| 14:52     | Lisa   | OK, OK, good. Well, it's nice to know we're on the on the right track anyway, so. |
| 15:00     | Steven  | And I guess to that I would follow up with asking, would you be happy to sign off on this and authorise this is our, I suppose our starting point for the project or would? |
| 15:11     | Steven  | Or would there be anything at all that we might need to just be pretty happy, but is there anything as is that we wanted to modify before you're prepared to sign off? As you know, we can kick off the project and start our planning for that development. |
| 15:27     | Sisi        | Yeah, I think should be fine. Just let me know where to sign. I probably haven't scan. |
| 15:35     | Lisa   | I think it's 1.02.8. |
| 15:37     | Steven  | It's. |
| 15:38     | Sisi        | Is there ah, yes. Yes, I saw this. OK, cool. |
| 15:38     | Thomas          | .10. |
| 15:39     | Lisa   | 01 point 10. |
| 15:44     | Sisi        | Yep, I can do that. |
| 15:48     | Sisi        | Soon is. Do you guys have a deadline for me to to sign this one? |
| 15:54     | James   | When when you're available, yeah, we, we we already submitted the assignment on Monday. |
| 15:56     | Sisi        | OK. Yeah. |
| 15:56     | Steven  | Yeah, yeah. |
| 15:59     | Sisi        | Yeah. Yeah. 'cause. 'cause. I I remember you guys talk about that, that this one's already resubmitted. So yeah, OK, yeah, I'll. I'll get it. I'll get. I will get it done as soon as possible. Yeah, I think it's all good. Just the one minor thing to clarify 'cause, I I recall, I heard James talk about modifying the trust layout. |
| 16:10     | James   | Thank you. |
| 16:24     | Sisi        | I'm not sure how difficult it would be, but at this stage. |
| 16:30     | Sisi        | We're not expecting you guys to do anything with the trust layout. I mean, considering it's an image. So, so I I I think it can all being sort of translated into. |
| 16:47     | Sisi        | The. |
| 16:49     | Sisi        | Machine language is not the correct word, but it's more love. We are taking some key parameters from the image and translating that into something the machine can understand, so nothing to do with. |
| 17:02     | Sisi        | Uh programming? Uh. The machine to to generate figures or modifying the figures. So not not to that level. Yeah, but unless you you guys have time and interested in exploring this further. |
| 17:13     | Lisa   | So if we're completely brilliant, we can. |
| 17:13     | James   | It might have just, it might have just been my language. I think by modifier I meant swap out the image change, change it to a different image for a different exam. |
| 17:14     | Sisi        | Yeah. |
| 17:17     | Sisi        | Yeah, yeah. |
| 17:21     | Sisi        | Well, yeah. Yeah, yeah, yeah, yeah. Yes, yes. Yeah. |
| 17:26     | James   | And then like like Lisa said, I think I think one of the things that we've been talking about is complexity of the assignment. |
| 17:36     | James   | Like and, we were trying to find ways of sort of increasing our complexity without sort of. |
| 17:44     | James   | Pushing. |
| 17:46     | James   | Additional requirements onto the onto you guys, the stakeholders, just because we kind of wanted to. So like the answer key was one that we were interested in the A drawing application was was what Lisa was talking about just just before where we were like what can we can we add something like that in just to sort of increase the complexity of the projects a little bit yeah so so you know if we if we sort of. |
| 18:14     | James   | Like these ideas that they're they're probably not in the critical requirements, but they're probably in our in our minds is like, oh, we'd really like to try that or we'd really like to sort of see if we can pull that off. But yeah, ultimately we kind of have to stick to what to what you guys require, you know, more than anything. |
| 18:31     | Sisi        | If you really wish to explore further, I think what we've been put into like a higher priority as an as an optional requirement would be remember that the one of the critical requirements is generating random parameters. But of course at this stage is like the trust layout provided to students is all the same. It's only the numbers will be. |
| 18:57     | Sisi        | Randomised and. |
| 19:00     | Sisi        | Being delivered as a as a separate table, but eventually if there's possible. |
| 19:05     | Sisi        | See that the could have that randomised numbers on it and then attach to student Question Paper. That will be really. |
| 19:14     | Lisa   | So I mean. |
| 19:14     | James   | Yeah, that's that's an interesting idea. |
| 19:17     | Lisa   | Yeah, I I guess the other thing that we were considering as well is that if we. |
| 19:24     | Lisa   | Drew the trust layout in the programme. We could. |
| 19:31     | Lisa   | Explore the possibility of having options like. |
| 19:35     | Lisa   | To print as is or to print. |
| 19:40     | Lisa   | So with adherence to somebody who may be colour blind. |
| 19:45     | Lisa   | And so have you know, them patterned rather than coloured. |
| 19:50     | Sisi        | Hmm. |
| 19:50     | Lisa   | To identify the areas. Because I mean being colour blind is is quite a big thing, particularly for males, and it shouldn't preclude you from being able to sit an exam so. |
| 20:02     | Lisa   | Whereas an uploaded image, we don't really have that ability to play with it, I guess. |
| 20:09     | Lisa   | Yeah. |
| 20:11     | Sisi        | I mean, these are really good, but I just be cautious what you propose to your client because your client might be interested in everything, but eventually you might not be able to to fulfil that, yeah. |
| 20:25     | Lisa   | Correct. Sorry, but yeah, I will just sort of say like if if we were completely brilliant and we were able to do the drawing aspect, then we might consider that as options. |
| 20:37     | Lisa   | But we we may be overstating our abilities too. |
| 20:38     | Steven  | If. |
| 20:42     | Steven  | If I could perhaps reframe it as. |
| 20:46     | Steven  | This way would would there be any need to consider access and inclusion requirements or access plans have has that ever been a situation where you've had to modify the format of the exam paper to account for somebody's access plan at all perhaps or. |
| 21:23     | Steven  | OK. |
| 21:24     | Sisi        | Can be optional, yeah. |
| 21:25     | Steven  | And the other thing, at least from my was discussing recently, was just regarding supplementary exams. If someone required a supplementary exam, would you require us to be able to produce another exam paper for the same study period for the same student or it? Would there be other arrangements in place for them to take it taking exams that doesn't require this particular paper? If a supplementary was needed? |
| 21:49     | Sisi        | That'd be great. I mean the four, if it's an application, I would expect it to have certain log function to indicate that this unit has already get the paper using this particular trust layout. So if the students requires a so another a different 1 can be generated. |
| 22:07     | Steven  | OK, so thank you. |
| 22:14     | Lisa   | Do you have any questions for us or any other points that you would like to make us aware of or discuss? |
| 22:24     | Sisi        | Good. I mean it's it's great. I'm I'm a bit impressed. 'cause I I know 'cause I'll be. |
| 22:32     | Sisi        | Absent for the first few meetings, so not not sure how you guys were going on with standard, but seems like quite OK. |
| 22:39     | Sisi        | Yeah. |
| 22:40     | Lisa   | We have an awesome team. This is a great team. |
| 22:41     | Sisi        | Yeah. So hopefully you got, you got a good experience like talking to a client. I know 'cause, I I've been a stakeholder for some project before, but it felt like because given my background is it and data analytics, so it don't really feel like communicating as a real client. But hopefully you guys had good experience like talking to an actual client client client. |
| 22:43     | Steven  | Awesome clients. |
| 22:44     | Lisa   | Yes. |
| 23:08     | Lisa   | Yes. |
| 23:08     | James   | I think it was good to talk to someone who didn't have a background in it to try and sort of draw out, you know, like exactly what she wanted. It was also interesting talking to someone who didn't have a lot of hard thoughts on what she wanted. Like, I like to try and yeah, get her to, to be really clear. It was it was difficult because she wanted to check with you about a lot of things and she wasn't sure what the level of application that she wanted. And. Yeah. So it was good. It was, it was fine. |
| 23:08     | Steven  | It was. |
| 23:13     | Sisi        | Yeah. |
| 23:37     | Lisa   | It'll also like, I think she wasn't sure on. |
| 23:42     | Lisa   | The current IT capabilities like can the system even do that these days? Yes, yes it can. |
| 23:51     | Sisi        | Yeah, I think that's that's that's definitely, I mean, I mean it's mimicking the real life situation, right where sometimes you are the ones who have to propose and suggest and then the client will will decide which is a better option. |
| 24:05     | Lisa   | Yes, yes. |
| 24:07     | Thomas          | I like meetings when the client isn't sure what they want because it lets you drive some of the decisions and propose what we wanna do for the project and then they just agree and go, yes, that sounds good and that us linked on the decision making. |
| 24:19     | Lisa   | It it sometimes if somebody comes in with too rigid an idea, there's there's no room for creative thinking or a a different solution. So sometimes having an idea that's half formed allows you to add. |
| 24:39     | Lisa   | Interesting aspects that maybe haven't been considered. |
| 24:43     | Lisa   | Yeah. |
| 24:44     | Sisi        | Agree. No more questions for me. |
| 24:49     | Steven  | I'm good. |
| 24:50     | Lisa   | Oh, not not from me. |
| 24:53     | James   | I'm good. Thank you, cici. Appreciate it. |
| 24:55     | Lisa   | The moment. Thank you. We'll probably think of many more later, I'm sure, but for for the moment, I think we're we're just going to be putting our thinking caps on now. |
| 25:07     | Lisa   | But yeah, if you could send through any your proposed amendments or tweaks, that would be wonderful. |
| 25:15     | Sisi        | Alright, skip, we'll do that and I'll send you guys shortly and as well as a sign that document, yeah. |
| 25:26     | Lisa   | Well, thank you very much for taking the time to meet with us this evening. We do appreciate it. |
| 25:30     | Sisi        | No worries. So good luck. I I know that's the the first study pair is all about doing certain documentation, but just let me know if there is a need to clarify for the OR if you guys have more questions. |
| 25:47     | Lisa   | We built a 100%. Sorry. Thank you very much. Also, is this a good time for you to meet? |
| 25:57     | Lisa   | Is there a better time for you? |
| 25:58     | Sisi        | It's usually Tuesday's not too good on Monday will be better. |
| 26:04     | Lisa   | OK. All right. Just every second Monday, we do have a meeting with CMAC, but if we can make it the opposite Monday, that's fine, but yeah. |
| 26:12     | Sisi        | OK, sounds good. |
| 26:13     | Steven  | I'm sure he'll move it for us, so he'll accommodate our needs. |
| 26:18     | Lisa   | Excellent. |
| 26:18     | James   | Nice, Steven. You're you're good. No other questions. |
| 26:21     | Steven  | I'm good. |
| 26:23     | Steven  | What's the work to do? But yeah, we're good. |
| 26:23     | Thomas          | In Miami, too, thank you very much, Stacy. |
| 26:26     | James   | Thank you, Susie. |
| 26:27     | Sisi        | Alrighty. Thank you guys. Good to meet you. |
| 26:27     | Lisa   | Thank you, cici. |
| 26:31     | Sisi        | Bye. |
| 26:31     | James   | All right, talk to you later. Catch you later. |
| 26:32     | Steven  | See bye. |
| 26:32     | Lisa   | Bye bye. |

