---
title: "Devin’s Bag-o-Tricks and Other Opinionated Advice"
date: 2022-06-21T00:31:49-07:00
description: "for applying to Software Engineer positions"
categories: ["Software", "Coding"]
dropCap: true
displayInMenu: false
displayInList: true
draft: false
resources:
- name: featuredImage
  src: "img/logos.png"
  params:
    description: "\"Diffraction\" - Some university physics class, probably"
---


## Introduction:

The following 12 points are a combination of advice I got from other engineers and tricks that I learned while applying to L4-equivalent positions at Amazon and Google in January of 2022.

## The List:

### 1. Don’t grind Leetcode.
*	A good coding interview is a conversation. In interviews you should say 10-20 words for every word of code you write. Leetcode is the exact opposite. A good interview is about exploring the prompt from multiple angles, coming up with good ideas, discussing their merits, discussing the  options   within the context of what’s important to your interviewer. And finally, writing code.
*	Leetcode may be useful when you’re learning a topic for the first time and you want to make sure your solution is not totally wrong.
*	Most interview questions I saw would have been rated easy to medium on leetcode. Hard leetcode questions are a waste of time.
### 2. Practice interview with a friend.
* Pick someone you trust, preferably with interview experience.
* Coding while talking is very different from coding or talking.
### 3. Allow your interviewer to guide your approach.
* Take a breather between explanations, let them interrupt you.
### 4. Recursion. 
* Recursion is one of the only tricks in the book. Learn it. Learn it well. This [youtube video](https://www.youtube.com/watch?v=oBt53YbR9Kk) helped me a lot with recursion and dynamic programming. After a while, the patterns all start to look the same.
* Many of the most popular data structures use recursion. Linked lists, trees, graphs, etc.
### 5. Reason by analogy.
* Talk about similar problems that you’ve solved before. Tell your interviewer about how those problems are similar/different, tell them how you solved them. Time is short and even if you don’t solve the prompt perfectly, mentioning similar problems will get you partial credit.
* During my Amazon phone screen, I was struggling to come up with a solution, but as time was running out, realized that the problem was similar to “paint-fill,” a known interview question I had seen previously. I told them about the approach, and started coding. Even though I only wrote ~25% of the solution, they still moved me to the virtual onsite.
### 6. Discuss the context of the problem.
* Talk about how the interview prompt has impacts on actual problems. Being aware of the bigger picture is useful and lets the interviewer know that you’re more than a code monkey.
### 7. Dynamic programming is just a way to do less recursion.
* More often than not, you won’t actually have to implement dynamic programming. Simply mentioning it and discussing the impact on runtime will usually suffice.
* In python, dynamic programming often means adding the @cache decorator to your function.
### 8. Understand the requirements early and reference them often.
* Interview questions are ill-posed by design. Asking questions and figuring out the unstated requirements are important steps on the way to crafting a solution.
* It’s helpful to frame your decisions within the requirements of the prompt. Say something like: “I made this decision to address the requirement to XXX” or “doing this improves the storage requirement to O(N), since storage is our most important metric.”
* This lets your interviewer know you’re thinking about the requirements, gives them context, and lets them correct your understanding of the prompt if they think you’re not on the right course.
* Often, there is a “gotchas” hidden in the examples provided or edge cases that your interviewer wants you to find.
### 9. If the problem involves “arrays of bits”, there’s probably a “trick” that involves casting the array as an integer.
* You can then use the bit-wise operations and, or, xor, etc. operations for a factor of 32 improvement in efficiency.
### 10. If the problem involves a searching for something on a grid, there is often a trick that involves representing the grid as a graph. 
* The problem can then be solved using a corresponding graph-search algorithm (e.g., breadth-first search or depth-first search.)
* See “paint-fill”, for example.
### 11. Discussing the newer features of the language and when they were introduced.
* Not strictly necessary, but this “trivia” this tells the interviewer that you pay attention to the modern developments in your language of choice.
* For me this was python typing. I could easily burn a minute discussing the capitalization of the “List” type hint (capitalized before 3.10).
* Which is something the interviewer probably didn’t know (good, or if they did, better), and gave me more time to think about my solution.
### 12. Salary negotiation will happen regardless if you’re on the boat or underneath it.
* Whether or not your interests are represented is up to you. If you’re fortunate to make it this far, your future salary is set by your negotiating acumen, not the wealth of skills and knowledge that you’ve accumulated to get to this point. 
* Before you pass the interviews, your recruiter will ask you about your “expected compensation”. The correct answer is that you don’t have an “expected compensation”, that you’re more interested in “mutual-fit” and “scope of the responsibilities”. If you tell them a number, you lose. Had I given Google the number I had initially conceived, I would have missed out on hundreds of thousands of dollars. This is especially hard for scientists/engineers who are hard-wired to give numbers when asked. “oh! Numbers! I like those”.
* Negotiating is infinitely easier when you have competing offers. But it’s still difficult. I spent >10 hours reading/learning negotiating theory after getting verbal offers.
* Recruiters can be VERY pushy. Be prepared to resist, write out prepared excuses/responses if necessary.
* Be prepared to feel like an ass. Recruiters will use your natural conflict-adversity against you.
* After you pass the interviews, they’ll ask you again for your expected compensation. You still don’t have to answer. If they keep pushing, you can answer, but make sure you don’t low-ball yourself. Do extensive research (levels.fyi, teamblind.com, etc.). Anchor the conversation high. I gave Google the highest L4 salary reported on levels.fyi as my expected compensation: $350K. Might have still been too low.
* And what do we say when our recruiters offer us 3X our current salary? Answer: It’s a start.
