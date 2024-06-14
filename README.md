# The RBI Agile Engineering Maturity Model (AEMM)
Many agile (Scrum) product teams have a good understanding about their problem space. 
- However (our) experience shows, that many of them still need ideas where to start improvements related to engineering practices. 
- (Our) Experience also shows, that even though deficits are often mentioned or expressed by the teams, in many cases there is no reaction by stakeholders like POs or management. So it is important to make the deficits transparent and to create a broader understanding.

## Summary and Background
For this purpose, the team of Agile Engineering Coaches here at Raiffeisen Bank International (RBI) Head Office has created the Agile Engineering Maturity Review.
This review is done based on a simple questionnaire. The questionnaire supports the description of the engineering capabilities of a product team and gives an indication of their maturity. The questionnaire covers the areas of CI/CD, DevOps, Test and Test Automation. 
To do a (self-)evaluation with or within a product team, the team selects the answer that describes their current way of working best und thus puts itself into a maturity bucket.
  
It is strictly a self-evaluation process by and/or for the team, the framework just provides some guidance and structure to assure, that all of the relevant areas are covered.
This review process gives a baseline after the first self-evaluation. It helps the teams to create a common understanding about their way of working, and it also helps to figure out where to start any improvement activities.
The self assessment is in no way calibrated. This means that the results of one team cannot be compared to the results of another team - especially in terms of "better" or "more advanced" due to different set-ups and aspects of different teams. 

**Do not use this tool to compare and rank teams** 

Comparing and/or ranking teams is a meaningless exercise and besides this, will immediately make sure that teams won't feel safe to answer honestly! Also sooner or later competition will come into play and product owners or managers will try to put their teams into the spotlight in order to get more budget, better reputation, more higher managment attention, You name it.
 
 It is also important, that the AEMM is just another tool to help teams improve. It usually will start discussions around important engineering topics, but to create actual improvments the teams typically have to invest time and effort.

Change is not happening linearly and there is no single path. 
Team context, business needs and boundary conditions all need to be observed - and as always, the most important thing is to start with *something*, experiment, collect feedback, adapt and start all over!

Improvement is always possible - considering this, it is clear that there is no end-state of an improvement journey. Even if a team scores itself top on all dimensions of the review it doesn't mean that it has achieved an optimal state of engineering capabilities. This state simply does not exist.

Conversations must be focused on capabilities and goals and not on maturity scores - if real change should happen.

# How it is done in detail
- The self assessment is done by the teams together with Engineering Coaches, who guide through the questionnaire. 
- If it is the first iteration, Engineering Coaches explain also the context:
  - What is the assessment all about?
  - How does it work?
  - What happens with the data? Discussing this explicitly is very important!

- The questionnaire consists of a lot of topics related to engineering practices.
- For each topic, a set of descriptions - which reflect certain levels of maturity - is provided. 
- The team selects the description, which describes best their way of working and thus puts itself into a maturity bucket for each topic. 
- Descriptions and the respective buckets are classified as **Crawl, Walk and Run**. A general guidance for the buckets is:
  - **Crawl** means: the team is using a structured process 
  - **Walk** means: the teams is familiar with modern software engineering practices and applies the practices in their daily work
  - **Run** means: the team is on top of their game and in addition they are also sharing their knowledge and experience and help the whole organization to improve
- If even the **Crawl** bucket description doesn't reflect the team's way of working, a **-** is used.
- Comments can be added by the coach for each topic if the team feels the necessity.

It is helpful if two coaches work with the team on the self-assessment as it is hard to facilitate the process and take notes at the same time! 
Usually it is good, if 2 members from the product team participate in the self-assessment, one to cover DevOps and CI/CD and one for Testing and Test Automation. This is due to the fact that typically the detailed knowledge is spread among the team members and there is no single "expert".

# How long does it take?
The duration of the self-assessment depends on multiple variables:
- How many team members are involved in the assessment?
- How much time is used for discussion?
- How good is the team's joint understanding of their way of working?
- How familiar and experienced are the coaches with the process and the content of the questionnaire?

All in, we typically plan for 2 hours for the first assessment. 
For a bigger team, this is certainly on the lower end and does not give a lot of time for discussion. 
Subsequent assessments are typically faster, it is also possible to skip discussions about specific topics in that case.

# What to do after the self-assessment?
- The heatmap generated by the Excel sheet on the first worksheet shows an overview immediately
- In RBI's case, Engineering Coaches prepare a set of improvement recommendations (usually five) 
- Another 30 minutes meeting is scheduled with the team where coaches explain the recommendations and also collect feedback about the process
- It is up to the team to decide if they follow up on the recommendations
- One follow-up could be a presentation of the results to a product owner or management in order to agree to have some backlog-items out of the self-assessment


# What are our experiences? - Tips and tricks...
- It is super important to explain to teams the context of the self-assessment. The teams need to understand that this is not an *audit*, but it is for them to help them improve.
- Teams also usually have a lot of questions, what will happen with the results. It is again very important to emphasize that the data is only available to the teams and not to management (unless they explicitely want to). 
- Psychological safety is key. If the teams feel uncomfortable, the whole process is really unpleasant and stressful. Team members will get defensive quickly. Results may be completely useless.
- The questionnaire does not strive for perfection, but is a very useful tool to stimulate discussion. We have experienced sessions, where it became clear to the team that they don't even have a common understanding about their own way of working. This can be eye-opening!
- Teams, who are early on the maturity journey and with less exposure to topics like DevOps/CI/CD are often quite interested and appreciate some guidance. Some are not.
- It is really hard to separate the technical topics from general agility topics. Means: Teams who struggle with their agile set-up will struggle likely even more with agile engineering topics. 
- It is up to the team to decide what their goals are. Not all teams need Spotify-like engineering muscles - or at least not immediately. Means: Strive for a "Run" maturity only, if the team needs it.
- With teams, who are open and confident and feel safe, a great and very useful conversation can emerge. In this case it can be a brilliant learning experience for all people involved, including coaches.
- A lot of good conversation can happen, if the whole team is doing the assessment together. But it will take a lot of time and effort. Also, it is difficult to steer the meeting in this case. Sometimes it may be better to streamline a bit and limit the number of people. We had good meetings with one developer and one tester , who together were fully knowledgeable about the team's way of working.
- It is good practice to follow up with the teams regularly and discuss any activities they might have started or any experiments they might have done. This may also provide a lot of useful insights about potential underlying problems that keep teams from improving on engineering side. To do the re-assessment after something like 1 year after the last assessment may be a good guidance.


# Useful hints
- Two coaches in the review meeting are good practice. Facilitating and note-taking at the same time doesn't work.
- Try to keep the pace, use time-boxing per question/main chapter. If the review meeting takes too long it is hard to keep focus.
- Every single line in the sheet could be discussed for hours. This is not rocket science and high precision is not the goal and also not a benefit.
- The self-assessment must be done with engineers. Don't include Product Owners or Engineering Managers during the actual assessment. You want to have the engineers talking, not the POs (or Scrum Masters) (or managers). POs tend to talk a lot :-D.
- If agile coaches (for the setup of the agile process, meaning Scrum) are working with the team, get in touch with them. There is always a lot of overlap!
- Many engineering problems are related to architecture, organization, team structure and understanding of agility. Some of these areas are not even in scope of the AEMM, whereas the negative side-effects might be very well visible in the AEMM results. Don't even try to fix everything!  

# Version history
20-03-2023 AEMM template Excel sheet updated to improve simplicity and clarity based on our experiences. Some redundancies have been removed.

14-06-2024 Another update to the AEMM Excel sheet with some cleanups and the addition of metric collection (DORA metrics) as a capability
