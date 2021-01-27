Regarding my career, I’ve decided to go all in. Not on the standard paths that many people compete on (raising up the corporate ladder or starting a company), but on quenching my curiosity by learning new things. I'm sure exciting opportunities will come along the way.

How do I go about this? I will decide one topic that I want to extensively learn about each week, and spend all my free time trying to learn more and frame my thoughts on that topic. At the end of the week, I will either write on the topic or make a video explaining the things that I learnt. I'm essentially trying to master the meta skill of learning new concepts quickly and using them.

Criticisms: I can't just learn and forget about things. They will serve no purpose. 
Responses: 

### Week Jan 10 - Jan 16

Topic: Data Privacy

Data and Goliath


- Cell phone location data (from towers, not GPS) can be used to predict where you will be 24 hours later within 20 meters. This is possibly better than your self prediction, because it doesn't have to rely on limited human memory or limited cognitive capacity. Earlier, doing this was super hard (you had to hire a private investigator).
- Governments can use this data to create lists of people at protests (possibly adding who were nearby and not part of the list)
- Cell phone companies [sell your data](https://www.govtech.com/network/Wireless-Carriers-Face-200M-Fine-for-Selling-Location-Data.html) without users consent to third parties. And there are companies that buy this data to build profiles of each of us.
- Some companies claim too "track any phone number in the world", which is plausible. This is possible using SS7 technology, by sending specific requests [2]. We're told that only governments are given access, but we can't trust that governments would not use it for bad purposes. 
- More data is stored than what meets the eye. Facebook stores how much time you see each post, every ad that you click on, etc., Amazon kindle tracks how much time you spend on each page in each book. 
- It's just meta data, so we don't have to worry about it so much -- is a flawed argument. There's so much you can say about the person using meta data, especially given that they can use population level statistics to make inferences. They can accurately estimate our spouse, children, close friends, medical problems you have, were you part of the protest, etc., all from just the meta data. 
- Google's know more about you than yourself. It can predict what we're talking about. We have no rights to delete this information. 
- You Twitter can reveal what time you wake up, you friend list can reveal your sexual orientation, etc.,
- When tracking individuals alone, data might be more important. But when we're tracking at the population level, meta data becomes far more important. 
- Storage has become cheaper, so corporations are saving as much information as possible. 
- It's possible to detect people through their typing styles. 
- Correlating multiple databases makes surveillance much more powerful. 
- There's a history of anonymous datasets being deanonymized by researchers. So anonymizing is not good enough. 
- What are cookies and how are they use to track you on the internet?

  - Each time you search something on the web, cookies are downloaded to your browser which contains pages you visited, what you added to your shopping cart and other info you provide. 
  - This is used to remember your cart when you comeback to the website (unless you locally delete your cookies). While this was supposed to be internal to a website, third party cookies allow tracking across websites. 
  - When we visit a website, there are lots of cookies which are downloaded (dictionary.com once downloaded upto 200). These cookies come also from ad banners. 
  - When we visit a new website with a ad banner from the same ad network, they use the cookies to deliver you targetted ads.
  - You can disable them in chrome settings! But website creators will still have ways around.
- There's nothing stopping companies from handing over your cloud data to the government when it requests for it, even in countries which have poorer privacy protection laws. If they suddenly delete data, I have no recourse. If they get hacked and all my data is public, I have no recourse. 
- The FBI or NSA can force companies to give up your data. Companies can sell your data at will. In either case, the customer has no recourse. 
- In surveillance state, we need to be constantly thinking about how each action we take could affect us and put us on lists (looking for disease symptoms might up your insurance premiums). And the minorities maybe targeted far more than others (eg. Muslims).
- Social media platforms have the power to influence election outcomes. If they make "i voted" badge from users more recommended if they're democrats, it's easy to tilt the election in the direction they want. And because their algorithms are hidden, no-one would ever know that they did this. 
- Identity theft is a thing. Identities are obtained through hacks on websites. So when you register on new websites, it better to use an alternative email account with a false name. Using your real name, and putting answers to security questions on a random website isn't a good idea.
- As long as our personal data is going around on the internet, and websites don't delete that information, we're always vulnerable to risks. and the hackers getting hands on that data.
- "If you're not doing anything wrong, you don't have anythign to hide" -- clearly misses the point. There's nothing wrong about singing in the shower, making love or searching for a new job without telling our employer. 
- One mistake you can when you're 10 can haunt you for life; or even a false accusation if this data is being stored forever.
- It's the algorithms that are doing it, not humans. The algorithms can still process information, base future decisions and discriminate based on it.
- Director of National Intelligence, James Clapper, lied to the senate on "collecting data from 100s of thousands of civilians", he defends himself saying that he didn't lie because "collect" means "retrieving information" inside NSA.
- The data with companies is not safe. (i) they might change privacy policies tomorrow, (ii) hacker to break in, (iii) the organization could share your data with a third party or the government. 
- Using surveillance for common infractions is much easier than rare event. In the case of rare events, you have a lot of false positives. 
- There's no evidence that adding more data about innocent civilians aids our search of terrorists, if anything it only increases the false positives. 

  - NSA gave FBI 1000s of tips post 9/11. All of them turned out to be false positives.
  - One was harmless taxi driver was convicted from all that phone data. 
  - We have an adversarial terrorist, who is trying to avoid the system. So commercial recommender system tools will massively fail at this.
  - There's no evidence that mass surveillance performs better than targeted surveillance.
  - More than being ineffective tools to find terrorists, they turn out to be effective tools to oppress minorities. 
  - There's an unfair balance between attack vs defense
- 

Data mining:

- Good for targeted ads, detecting financial fraud or even identifying protestors. Bad for detecting terrorists, because (i) we don't have enough positive samples, (ii) they are trying to avoid detection (adversarial) and (iii) each false positive prediction is expensive to validate.

Internet security:

- Attacker always have an advantage. They just need to find just vulnerability; while the defense needs to fix every.
- Types of attacks: targeted (you need to ensure your security is high), mass (you need to ensure you have better security than you neighbors)
- Even though you have perfect encryption, it needs to be implemented in code, run on a computer with hardware, OS and other softwares. It needs to be operated by a person and be on a network and has a password. All of these introduce vulnerabilities.
  - It might be easier to attack the server and read data in .txt than eavesdrop and try to decrypt from the communication channel.
- Every piece of commercial software has 100s of vulnerabilities, science of programming is just not good enough to produce flawless software. 
- "zero-day" vulnerabilities for softwares are unpublished vulnerabilities that no one is protected against.
  - NSA finds and stockpiles these vulnerabilities to eavesdrop on target systems; instead of helping companies making their software more secure.
- Giving backdoor access just to one party it not possible. It makes the device vulnerable to other people exploiting this feature.
-  These zero-day vulnerabilities that government sponsored programs use, can cause collateral damage. Stuxnet's target was Iran but it accidentally affected 50,000 computers in other countries.



Principles:

- security privacy tradeoff:
  - People argue that there's always a tradeoff between security and privacy. That if we want things to be more secure, we need to give up privacy.
  - It is not always true. Example: door locks improve security and privacy.
  - 

My views:

- Software by Apple is not easy to hack by unsophisticated hackers because of the level of security. It is easier for sophisticated hackers because finding a bug for one iPhone is enough to exploit all iPhones in the world because they run the exact same software unlike Android.

Question:

- How easy is it to steal the password you type into your bank website if you're on a unsecure network that's eavesdropping the communication?

On whatsapp's policy:

- Sharing last seen information is a horrible horrible idea. It can be used to correlate things with a lot of databases. It can be given to governments for mass survel. You just need to be in the wrong place at the wrong time to be screwed. 
- Q: is whatsapp giving up the location data too? 
- Will whatsapp be sharing all data from now on, or is it just historical data? 



[1] Data and Goliath
[2] Tobias Engel: SS7: Locate. Track. Manipulate.
[3] https://www.wsj.com/video/how-advertisers-use-internet-cookies-to-track-you/92E525EB-9E4A-4399-817D-8C4E6EF68F93.html

