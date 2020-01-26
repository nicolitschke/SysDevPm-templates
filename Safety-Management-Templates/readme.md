# ISO 26262 - Functional Safety Management
If I estimate the scarcity of Safety Managers for 'ISO 26262 Functional Safety', based on the requests I get per week, then there might be no skilled Safety Managers at all. Also, I regularly hear horrible stories of Safety Manager who didn't even read the ISO standard.

I created the page, because I prefer to drive in safe cars and I want my family and friends to drive with safe cars. If you start with Safety Management, I hope these templates are useful for you. If you're already an experienced Safety Manager you might use the documents as good practice or checklists. Whatever is your experience level: I appreciate your feedback!

Before you check the templates please continue reading. I want to give some hints.

# 0 You need the Standard
As Safety Manager you regularly have to check the exact wording in the standard. Sooner or later somebody will give you a crapy development document and asks whether it fulfills the standard. You shall be able to map the document to the standard and give some advice. 

So buy it. You can buy it online at the [Beuth Verlag](https://www.din.de/de/mitwirken/normenausschuesse/naautomobil/nationale-gremien/72366/wdc-grem:din21:228634304!search-grem-details?masking=true).

The complete standard costs round about 2.000,- EUR. Here is the dumb argumentation, if somebody wants to know the amortization:
- you save 1 safety relevant field return, where the root cause is not clear (otherwise you wouldn't have released it).
- let's say there are 10 specialists who have to contribute to the analysis in some way. 
- Your internal full cost rate is in average at 80,- EUR / person.
- Because the specialists cannot do their regular work and have switching costs, they lose 1hr in addition to the kick-off meeting. 

=> If the kick-off meeting takes more then 1.5hrs, you already saved the costs to purchase the standard. Now put all the additionaly costs on top.


# 1. What to do, if you start Safety Management
- **Read the complete ISO 26262**. If you ever read a book about system development, you will notice, it is almost similar.
- Start with part 10, which gives a high level overview. 
- Then go to part 5 Annex D, figure D.1. This is a high level component view of an item. Print it, think, meditate.
- Then start again from the first page of part 2 to the last page of part 9.
- You need part 11 and 12 only for special occasions.

I don't know of any better way to get an undestanding of the ISO 26262. You can attend seminars, of course. Then you pay a consultat that he copied the standard to a presentation and is reading it to you. **The learning you have to do on your own.**

# 2. How you can use these templates. 
1. Generate the safety case. You can see the different parts and clauses of the ISO 26262 as folders.
2. Perform an impact analysis and evaluate what the project team has to do from safety point of view.
3. Update the safety plan accordingly.
4. During the project you store the artifacts from the development team in the respective folder.
5. Continue with 3, until the series release is confirmed and the safety case is finalized.

# 3. Sources for the Templates and Traceability
I derived the templates from the ISO 26262 (2nd Edition from 2018) standard. Due to licensing, I can only name expected artifacts and the IDs of the respective clauses. If you need a detailed description of artifacts and documents, you can map the ID to the part and clause of the standad. 

I use the following naming convention:
- 2-6.5.1. refers to part 2 of the standard, clause 6.5.1
- 6-C.5.1. refers to part 6 of the standard, clause C.5.1.

# More thoughts
In case you find any issues with these templates or its explanations, this is the repo to issue your request and to fix it.

If you are looking for **more good practices**, you can find it on [www.nicolitschke.com](https://www.nicolitschke.com/good-practice/).

If you need support with Safety Management, [get in touch](https://www.nicolitschke.com/interims/#safety) with me.
