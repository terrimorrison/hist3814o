# Blog

I was confused about how to fit the ~ in front of all the lines because it didn’t seem to work for me at first when I was trying it in RegExr. But it worked in DH Box, and my face was *surprised pikachu*. 

That pretty much sums up the rest of my experience. Every time things worked, I thought it was black magic. Some things took me a bit of trial and error, like replacing “to” with a comma in step 5. I ended up having to go backwards because I messed it up and restarting from step 3 because I couldn’t figure out how to fix it. 

I thought Open Refine was so cool. I got my number of unique senders and recipients close to what the workbook says, but I still had a bit too many. There were a few that I wasn’t sure if they could be considered unique or not, so I chose to leave them. 

After I finished that part of exercise 2, I put the spreadsheet into Palladio. This gave a whole new perspective on how the letters are connected. Just seeing the entries in the spreadsheet really doesn’t highlight how the various recipients and senders are interconnected, so using Palladio was pretty eye opening. It definitely shows a bigger picture. That being said, I thought Connect the Dots was cooler, mostly because it was colorful but also because it told me things like degree and centrality. I found Connect the Dots was slightly better at showing the attachments to other senders that the senders had. 

I wasn’t entirely sure what to make of the capstone exercise. It seemed like a lot of gibberish. There were some consistent issues, particularly with it confusing M for some sort of combination on ‘L’ and ‘i’(or another straight vertical character) which I was easily able to replace. There were a lot of apostrophes, which I wasn’t able to replace using sed because it caused a glitch. One issue that I noticed was prevalent was that since someone had initialed on various places throughout the document, the OCR would input random characters that didn’t seem to have a pattern to them. So if I wanted to fix those, I would have to do it by hand. 

There were enough patterns to the OCR errors that I could clean the document up a fair bit, but to make it completely legible I would have to do a lot more by hand, which kind of feels like cheating? But I guess there isn’t a magical solution (or program) to fix everything. 

So in the end I used sed to make big changes to the document, things that were repetitive. I found it somewhat frustrating that I could likely transcribe the document quicker than I could change it with Regex just because the OCR mangled the text so badly. In the second war diary I cleaned up, I mostly transcribed. There was a bit where I was able to use what the OCR produced, but most of it was gibberish. 

(I wasn’t able to save my most of my history for the capstone exercise because of my internet crashing but I used sed to replace whatever character had taken the place of ‘M’ or ‘N,’ especially when it came to the word Matron. I also used it to replace a lot of instances where ‘18’ had been misinterpreted for ‘13.’ I otherwise used it to delete a lot of unnecessary characters like underscores or dollar signs.)


# Reading Response

After struggling with the OCR capstone assignment, I totally get why historians don’t talk about the dirty work. It’s incredibly frustrating. In no way, shape or form is it glamours work. And probably the most frustrating aspect: it doesn’t always work. 

I tried a few different of the war diary .JPGs before I found one that was legible afterwards. My second attempt came out even worse. I was annoyed and frustrated by the end. Nothing was working the way I wanted it to, and I didn’t know how to make it fix itself. So not only was I frustrated with the computer, I was frustrated with myself.

Like we discussed a few weeks ago, people don’t like sharing their unpolished work. This was definitely unpolished. It was more than a bit of a fail, in my opinion, and so I don’t really want to tell everyone about it. 

That being said, I realize that not talking about it is a bad idea. I think I reached the limit of my current abilities to figure out how to fix my attempt at using OCR to transcribe the war diaries. But somewhere out there, there is someone who knows more than I do about it who could probably help me. Asking for help, sharing where I was struggling could help me in the long run because someone will likely have the answers to my problem. 

Katie25 made a good point with [this annotation](https://hyp.is/yW288IYsEemLSwMQ7VvFsw/web.stanford.edu/group/spatialhistory/cgi-bin/site/pub.php?id=93). She wrote, “When we collaborate, we are able to move forward on projects and research more quickly.” Instead of wallowing in self pity, wasting time, I could have asked for help. Someone may have pointed me in a better direction, and I may have been able to get farther than I did with the exercise. 
