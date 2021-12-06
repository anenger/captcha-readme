# Drawbacks of CAPTCHA

## Overview
- CAPTCHA is the most common way to secure a website sign-in against bots today, and this common solution is easily implemented by developers. However, researchers have found significant exploits in CAPTCHA, and a web developer or security engineer striving to make a secure website should not use CAPTCHA as their sole source of protection against bot attacks. In this README, we propose alternative methods of protection that developers should consider using, as well as ways to shore up existing CAPTCHA protection against different types of bot and human-led attacks. We also discuss some problems that a user may run into when they try to utilize a non-CAPTCHA security solution.



## Implementations
### Overview of implementations
- The internet has entered a new age of technology. The advancements in artificial intelligence related hacking has invalidated many of the processes created in the past decade to prevent the abuse of bots on websites. 
- The frequency of bots used to spam, hack, and commit other malicious attacks has increased drastically in the past few years, highlighting the importance to implement actions on your website to slow or stop bots completely.
### When and why to use a CAPTCHA/other security method
- Online polling is an internet utility that should be heavily protected from robots. Computer systems can attack polls and fill them with responses which can swing a poll in one direction. Typically IP addresses are recorded, preventing a user from voting more than once on a poll but bots now have a multitude of ways to get around this. Political polling is very vulnerable to attacks and can have a significant effect on viewpoints based on which way the poll is favoring. Opinions often change and follow the side which the poll is leaning to, especially if the poll is extremely polarized because of bots. Individuals can feel like they are in the wrong and then change their stance accordingly. This is highly important for anyone who is working in the political polling area to address this issue to prevent malicious intent.
- Any web service which requires the user to sign in using a username and password can be attacked by bots. Hackers can code bots to repeatedly try different password combinations at an extremely high rate. The rapid development of artificial intelligence and other technologies is making it increasingly easier to guess passwords. Adding an element which adds another step to the process in which a human needs to complete can slow or stop these attacks on individuals’ accounts and security.
- Comment sections on websites can also be bombarded with comments left by bots. The bots leave the links to websites in the comments which in hand will increase its search engine ranking. Having a barrier to only let humans comment prevents the flood of bots keeps the comment section spam free for human users.
- If a website is used to sell tickets, it can be vulnerable to bots purchasing all of the tickets right when they are released. If you are creating an event, concert, sports game, etc. it is extremely important to keep the payment process secure. Implementing another step into the ticket buying process online will eliminate the abuse of bots to buy out and then resell tickets for an inflated price. 
- The online marketplace is an area that is targeted heavily by bots. Just like tickets, bots can quickly buy up items that are released and completely clear out the supply. In doing this the hackers are able to resell the product for a profit. 
Installations/Applications
If you wish to use CAPTCHA on your website, one of the easiest implementations is reCAPTCHA, offered by Google. To create a secure website, you must take other precautions in addition to utilizing reCAPTCHA. https://developers.google.com/recaptcha/


## Alternative Methods of Protection
### Anti-Spam Honeypot
- By creating an extra hidden field within the form or website that only bots can see, responses with this field completed are able to be automatically discarded. This method is most useful in areas with form submissions, surveys, or other check the box/fill in the blank type responses. This solution is not a complete one as it does not deal with the increased traffic from the bots, just the end submission.
### Anti-Bot Plugins
- If your website is Wordpress-based, there are plugins that work in the background to eliminate bots and their submissions as they occur. To name a few, CleanTalk and Akismet are two of the most popular ones. These plugins are mainly geared towards comments rather than submissions and therefore are more for forums and boards. They work by sending specific parameters of the comments and user to their cloud for analyzing, when this analysis returns it either allows the comment to be posted or blocks it as spam. 
    - CleanTalk
    - Akismet 
### Bot Management
- The most effective new form for combatting bots and spam is through bot management solutions. This involves using machine learning, active verification and other development techniques in layers to distinguish between people, beneficial bots, and malicious bots. This is done in several ways.
    - Analysing header information and web requests that match known malicious bots.
    - An active challenge, something like a reCAPTCHA or checking if the user is able to accept cookies.
    - Using machine learning to match the patterns of the user either to a bot or a person. 
- There are many companies that offer this service if developing it from scratch is outside the scope of your work. DataDome and Netacea are a few of the more prominent ones. 
## Difficulties
- Knowing which solution to choose is difficult in the first place: What if your website upgrades over time, or adds new features that require another type of security? For example, if you’re tasked with adding a comments section to your website some of these security solutions will not work, and you will have to add another layer of security on top of your existing security features.
- User confusion: Some preexisting security features, as well as features you design yourself, may present challenges to users who are unfamiliar with a non-CAPTCHA feature set. The idea of using CAPTCHA or reCAPTCHA is so ingrained in users’ consciousness that using anything else has a high chance of tripping them up.
- Performance: Since CAPTCHA and reCAPTCHA are the most ubiquitous bot prevention paradigms and are maintained by companies on the cutting-edge of web development, they are both easy to implement and do not have as high a load as a self-developed security solution would have. Balancing performance and security is one of the challenges a self-developed bot detector may face, especially on a highly populated website.
## Conclusions
- CAPTCHA is a good first step in combating bots and other web crawlers, but more sophisticated solutions are available and should be used either to replace CAPTCHA or in tandem.
- Ideally, an upgraded CAPTCHA system would potentially be completely in the background, where the user does not need to see or do anything.


