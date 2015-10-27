##What git concepts were you struggling with prior to the GPS session?

I realized doing my evaluations that I didn't have a good handle on forking repositories. Then through GPS I realized that I didn't fully understand the cooperative aspect of github. 

##What concepts were clarified during the GPS?

My partner and I both didn't realize that the other person was supposed to approve the pull request, but actually walking through the steps we realized that it was a good way to check over the code. When we made mistakes we learned that if you push a new commit, it updates the pull request so you don't have to make a new pull request every time you catch a little bug.

##What questions did you ask your pair and the guide?

I asked the guide about fetch, specifically when you fetch something, but don't merge it, where does that file live? is it on its own branch? Is it a new file in the repository until it is merged? 

We didn't answer that question, but I looked it up and I it can be a way to update remote tracking branches directly. Which is an extra feature in addition to fetch being half of what pull does.

##What still confuses you about git?

* I know Git stores changes to code, and not actual different versions of code. So if I have a hundred different commits, it takes up less space because I don't actuall store 100 different files, I store 100 different sets of instructions to get to those files. To the point, I don't understand the cons of using github vs subversion (which stores the entire file)

* I also still don't fully understand the merging, it seems like git is smart about some merges and not about others. In other words, I doesn't seem like it comapres line for line on every merge request, but I don't fully comprehend where the line of demarcation is. For instance, I have some experience in Java and in Java it doesn't matter where you add your function, but I'm worried if I add my function anywhere but the bottom it might be a hassle because some other code might have previously been on that line. 

* Related to above, the SO article we had to read mentioned that most merge problems come from IDE problems and whitespce problems. I take this to mean keep consistent how many lines are between functions or sections of code. Make sure everyone indents the same amount. I'm including this comment because I'm confused if there is substanitally more little configuration settings that can cause problems.

* When you create a new branch, is that still called 'forking' even though it is more like 'branching?' Forking is a concept, not just a command on git for repositories. A reflection I reviewed called github a repository of repositories, and I thought you could not merge repositories, but I found out you can. Everything has different names though. When you fetch a repository you fetch upstream, which I believe is another input for when the guide says <(remote)>.  So I guess this is a verbose way of saying the vocabulary and remote/local distinctions still confuse me, just not so much in the limited cases we have addressed. [This article](http://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/) helped me grapple with these words a little better.

##How was your first experience of pairing in a GPS?

It was good! I never felt like my partner imposed or did too little. I feel like we cooperated and communicated pretty well. My initial thought was that navigating would be kind of useless on this specific excercise. I thought it'd basically just be reading the instructions, but I actually thought it was pretty helpful to have someone verify that you're doing the right thing. Also sometimes written instructions can be a little ambiguous, or you might look over something or misinterpret a phrase, and so this setup helped prevent that. So I was pleasantly surprised by how effective the division of labor seemed to be.