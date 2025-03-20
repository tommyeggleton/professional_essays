# Your documentation is everything
When you work with people (almost everyone) or make something that people use you should document **everything**.

I also think that you should use a documentation system that allows your team to ask questions in public and that they should be encouraged to do so. 

Yes, it’s definitely more effort up front but like the effort required to keep running kanban or to update and stick to checklists, it’s effort that pays off many, many times over. 

## Some great reasons to document everything

**Good documentation is a conversation with the teams (and maybe yourself) of the past.**

It’s so easy to figure out why a decision was made to do something a certain way and you can have a conversation with the past decision maker. What was true then may not be true now and therefore you can change the process. What was assumed back then may now have been proven not to work which allows you  to change the process too. Sometimes you may have forgotten some aspect which the past decision maker was aware of and that completely justifies the approach that is being taken. Perhaps you now have the time to remove the limitations of the past and allow your team to take a new, more efficient approach. This is excellent, this is institutional knowledge at its absolute best.

**Reading and writing docs makes you a better builder**

You train people to think differently when they read a lot of good documentation. It’s a bit like being a student of art. You have to look at a lot of it and you get better at picking up what’s good and bad, what’s interesting, what’s pertinent. Better yet, the more your people use documentation, the faster they can draft new docs and the easier it is to maintain. 

When you’ve already documented everything as you’ve gone along, writing new docs is easy. You pull out the old ones and change them to reflect your changes. There’s no longer the issue of features documented in different places and in contrary ways. You have a single repository of information and if a reader cannot find a source of information they won’t assume that it doesn’t exist, they’ll assume that either they are looking in the wrong place or the documentation has been put in a strange place. Either way, they’ll be suspicious and they’ll work harder to find it rather than giving up and asking someone else, writing their own poor fragment, or - worst of all - shrugging their shoulders and moving on. 

**Want to handover a project?** 

Obviously the better your documentation the easier it is. It’s so frustrating when a team is handed something that “just works” but no one can explain exactly how or why it was made. Reverse engineering will definitely get you there but it’s a waste of time and there are no perfect archaeologists in business, nuances and intentions will be lost. 

**Do what you need to do but tell us why (and how)**

You can trust a team to use new technology, a different stack, to try things  out as long as they describe where they’ve been and how they’re solving problems they face. If they can make a clear case for a new technology, technique, or cost, then fine. Documenting it will show you where a team is just excited by a shiny new thing and where the team is genuinely bumping into the limitations of an old process or technology.

**Living in public is an indicator of honesty**

Your auditors will love it. Just because you write things down and ostensibly live “in public” doesn’t necessarily mean you’re not a shady group of corporate wrong-doers but it does suggest that you’re not, especially if your business records back up the docs. 

## How to write great documentation and how users and makers can use it better

There are 2 kinds of documentation: 

- Exposition
    
- Exploration
    

**Exposition**

Once a “thing” (a feature, a product, a policy) exists, documenting it makes it real. Almost nothing is totally intuitive. You’ve got to show your work. Better yet, as you’re writing your docs you’ll often realise that something isn’t quite right (more on that later). 

**Exploration - part one: making a plan**

You can use documentation to plan features with customers and engineers. Write what you want to do and then you can all see it and comment on it and make it something valuable. The one holding the pen is the one who gets to make changes but the team can continue to critique and suggest. Ultimately the decision maker decides if it’s good enough to complete. Then the engineers get a go at figuring out how to do the work. Each point can be broken down into a ticket per line/paragraph. Worked examples become automated tests and maps for QAs. Anything that’s ambiguous can be challenged, worked back into the  document, and published as a change OR go back through  the customer approval process. 

When you’re planning your new feature, use the existing  documentation and show what you’re planning to change and why. Use it as a framework, make it very clear where the new logic will sit and what it will change. By being forced to write coherent documentation before the technology is changed you’re pushed to see where the gaps are, what the knock on effects will be, what UI and UX will need to change, and what the training requirements will be. 

**Exploration - part two: a good map of a bad place can take you to a good place**

Thorough documentation shows up the parts of your product that are too complicated. If it’s a faff to document, it’s probably too complicated or inefficient. You get to see where similar problems are cropping up across multiple processes, departments, and technologies. Often root causes of problems present themselves clearly when all the steps are documented and you’re paying attention to those documents.

**Hygienic documentation is happy documentation**

I recommend that you keep your public-facing exposition docs separate from your exploration docs. Your customers (however you define them) don’t necessarily need to see how the sausage is made but they should definitely know  how to cook it. Having both sets available to you and your team will be ridiculously useful.

**Good writing is re-writing**

This is something of a trope in writing circles but it’s absolutely true. Iteration is the secret to success. A  great strategy for generating rock solid docs goes like this: you write some docs to the best of your ability and then you hand the feature over to one or two users at a time, have them read those docs. Then they try to use the feature with you in the room. As they ask questions, work together to make the documentation more informative and easier to digest. Then repeat the process with two new people. This works for customer-facing docs and for internal developer documentation. Do this 3-4 times per feature and you’ll have rock solid docs that’ll make picking things up later a dream. 

**Questions are an invitation to improve your documentation**

When you get asked a question about your work, you should be able to point them to an area  of the documentation that they missed. If that doesn’t exist then now is the perfect time to write it. Then send that to them. If they have follow up questions, adjust the documentation to make it clearer, add examples, or add the missing pieces as required. 

This essay is going to generate criticism and follow up questions. That’s perfect. I’ll make a new copy and improve it by adding the answers. 

**Humans learn through stories**

Use worked examples - nothing cuts through the noise like a show-and-tell story. When you’re showing something to the engineers, tell the story AND show the tables of data. Show what it looked like and then show how it changes. When you’re showing users or customers, tell the story AND show them what they’ll see. Always tell the story.

## Brass tacks - the nitty gritty

Pick a good documentation tool that will let users see changes being made, play back through versions, and leave public comments that can be resolved/folded in/ (Atlassian’s Confluence product does this really well).

Make adding to and tidying up the documentation a part of the new product process. Add it to your team’s checklist and have a rule that a project is not complete until it’s documented.

Your team owns its own documentation standards. Grade the documentation - hold yourselves to that standard and review docs just like code. 

Treat documentation errors as you treat bugs. Ideally you’re swarming and fixing bugs - do the same with documentation.
