# dbs-assignment-1

https://dbs-assignment-1-gray.vercel.app/

https://github.com/psagar-cs/dbs-assignment-1#

## Answers to the Reflection Questions

1. The site has a root index.html which is the gallery page — it presents all 25 versions in chronological order, with three designer's notes embedded in the timeline documenting my thinking at each phase. Each version lives in its own folder (e.g. v1/, v2/) and contains two files: an index.html with the page structure and content, and a style.css with all the visual styling. There are no shared stylesheets — each version is fully self-contained so designs don't interfere with each other.

2. When I run git push, GitHub receives the updated code and triggers a webhook to Vercel. Vercel detects the new commit, pulls the latest code from the repository, and redeploys the site automatically. 

3. The idea behind Tastewise is: it takes as input something you like, and then based on that gives cross-domain recommendations for other things you might like. For example, based on the fact that a user likes the author Haruki Murakami, it may suggest a specific music album, movie, or restaurant that the user might enjoy. This is the example that was used to fill the dummy page during this assignment. 

    The process of landing on v25 had 3 phases. 

    The first phase was the exploration phase, where 15 radically different versions were created, each pushing in a completely different direction. After going through all of these versions, I realized that I was drawn to designs that felt serious and considered — editorial, authoritative, a little like a culture magazine or broadsheet. The playful versions felt too flippant for an app about taste. I want it to feel like Tastewise is genuinely weighing your taste and not just casually sorting your personality like a BuzzFeed quiz (which is what some of the versions were making it feel like)
    
    Having figured this out, the second phase was an exploration of different layouts. In the first 15 versions, a common layout was a input-on-top, three-cards-below structure. I wanted to use v16-v20 to explore some layout options, and to ensure that designs put weight on why a recommendation is being made — not just what it is. From this phase, my clear favourite was v19. It has a scroll-snap narrative structure gives each recommendation its own moment — it creates a sense of ceremony that matches what Tastewise is about. Each suggestion had space to breathe, which gave the feeling that each suggestion was seriously considered. The color palette was serious, yet pleasant and tasteful. 

    The final phase narrowed the focus to typography. In v21-v24, I wanted to see how, while retaining the same layout, different type choices shift the feeling. This helped me realize that sans-serif and monospace fonts felt too cold and minimal for what Tastewise is supposed to be — an app about human taste and personal connection. The heavier serifs explored in v21 and v23 swung too far the other way, feeling imposing rather than inviting. v19's original serif choices sit in the right place — warm and considered, but never overbearing. So, v25 (the final deliberate version) was simply a refinement of v19. 

    NOTE: This reflection has heavy overlap with the "Designer Notes" I added in the gallery page, where I wrote my reflections on what I was and wasn't liking about the various iterations. 