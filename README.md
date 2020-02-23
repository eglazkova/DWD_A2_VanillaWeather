# Vanilla Weather project 

This is my third assignment for the Dynamic Web Development class in ITP, NYU. The course focuses on the fundamentals of building "full stack" web applications. This week I should make responsive web application that works with an API.

<a href="https://ibb.co/PmbZ5Ds"><img src="https://i.ibb.co/98f9qZm/Screenshot-2020-02-23-at-11-15-55.png" alt="Screenshot-2020-02-23-at-11-15-55" border="0"></a>
<a href="https://ibb.co/GcGXLty"><img src="https://i.ibb.co/4PCcGYz/Screenshot-2020-02-23-at-11-15-40.png" alt="Screenshot-2020-02-23-at-11-15-40" border="0"></a>


<!-- It is good practice to add an about or summary -->
## About
The concept of the final app is simple — it shows you the weather in your area, depending on the geolocation. It also displays the corresponding image and a brief description: "cloudy", "it's raining", etc. You can switch between Celsius and Farenheit by clicking on the degrees.
Important thing to note: to build this I followed the video tutorial by [Dev Ed](https://www.youtube.com/watch?v=wPElVpR1rwA). In terms of my studies, it is also important to note, that there wasn't any previous github repository based on this one. Following along this tutorial is a good exercise for beginner like me because of the few reasons.

1. It gives another chance to practice CSS styling and get the result before getting too frustrated.
2. It introduces the interactive elements real fast and again, results are there before you get desperate.
3. It helps to practice ARROW FUNCTIONS.
4. In general, the code is modern and based on the things that we discussed in class, and it was really useful to me to get the sence of how to implement new concepts all at once, starting from HTML DOM getElementById() Method to fetch().
5. The API used in a tutorial is a very simple one, which again, is a great thing to get results fast.
6. The tutorial also introduces Skycons JS library, which is simply fun, nice and easy to use. 

# Notes & Process

Initially, I had bigger plans for this assignment. First of all, I had some experience of working with APIs for my previous class at ITP (Introduction to computational media). I made the app that searches for the latest New York Times articles with the key word from the user. There is [the code in p5 web browser](https://editor.p5js.org/eglazkova/sketches/IcsvOlnQ_). So, I felt myself somewhat an expert and decided to work on one more NYT API, [the community API](https://developer.nytimes.com/docs/community-api-product/1/overview). This API is still in beta, and it gives you the UGC (more specifically — user comments) on the specific article. Important note — NYT asks you to generate your own key to use the API base URL. Of course, that wasn't the hardest part for me. What stopped me at this point was the necessity to get the "mechanics" behind the app and then to implement it in code. This API gives the comments on the specific article, however, I wanted the user to serach for the key word, then to receive most popular articles on this subject, then to see the comments on each of them. That already means using 3 of NYT APIs.

<a href="https://ibb.co/2sfx2Wf"><img src="https://i.ibb.co/QC1LBp1/Screenshot-2020-02-22-at-17-40-45.png" alt="Screenshot-2020-02-22-at-17-40-45" border="0"></a>

Second "big idea" was to use [Telegram API](https://core.telegram.org/). It has a really friendly documentation, however, the most readable part of it is dedicated to working with Bots.

<a href="https://ibb.co/gmnTsJ8"><img src="https://i.ibb.co/VJKSXTG/Screenshot-2020-02-22-at-13-15-47.png" alt="Screenshot-2020-02-22-at-13-15-47" border="0"></a>

I spent a great deal of time researching and thinking of the possible applications (most importantlty — outside of Telegram!), and found out, first of all, that there are surprisingly many Telegram channels and groups in English. So, I was thinking about a few things, basically:

1. The "out of the bubble" app (I am working on something related to that for UX/UI class) — that sends you push notification about the cool content from someone or somewhere in the world on the random subject that you would never look for. There is a [somewhat similar project on music](https://musicgeeks.co/) that used to be free of charge. 
2. Something like "I don't wanna be a stalker" app. That's a questionable concept but I was told by my friends for a few times that they sort of track their "exes" on Telegram and other messengers, which is, well, unhealthy. Blocking the person, however, is also unhealthy (remember "Black mirror"?). Besides, people don't always want to deprive others of the chance to fix the relationship — they just want to control themselves better when it's hard to focus on the other things naturally. That made me think of the app where you can totally block yourself from the specific user (no search, no contact, no tracking) until THEY reach out.

3. And finally, searching for the data visualisation APIs, I found [a very intriguing one](https://timedoor.io/). 

<a href="https://ibb.co/LP4pN2D"><img src="https://i.ibb.co/RSLHjVG/Screenshot-2020-02-23-at-13-27-40.png" alt="Screenshot-2020-02-23-at-13-27-40" border="0"></a>
<a href="https://ibb.co/nDfx3yZ"><img src="https://i.ibb.co/SK0FQgW/Screenshot-2020-02-23-at-13-54-22.png" alt="Screenshot-2020-02-23-at-13-54-22" border="0"></a>

This one is not free, however, and demands a really strong understanding of working with data, I guess. But I loved it anyway.

So, I spent some time messing around all of the mentioned above ideas in code, and realised that working with APIs is a big deal since all of them are different, and demands solid understanding of what's going on both in your HTML and JS files. I ended up working on one more weather app, and caled it "Vanilla" for a reason that this is, yes, a very vanilla version of this exercise. However, I am glad that I feel much more comfortable about arrow functions now. I also have at least a few drafts of code that may probably lead me to the final project for this class. And I kind of forced myself to follow "git init, git add., git commit" prosedure (not sure that did everything correctly, though, but still).


<a href="https://ibb.co/FhSSLds"><img src="https://i.ibb.co/vc776Ms/Screenshot-2020-02-23-at-13-53-49.png" alt="Screenshot-2020-02-23-at-13-53-49" border="0"></a>


<a href="https://imgbb.com/"><img src="https://i.ibb.co/zRDYfmg/Screenshot-2020-02-22-at-21-04-09.png" alt="Screenshot-2020-02-22-at-21-04-09" border="0"></a>

### Design

I didn't really get to the sketching part here, because I only customized colors, font-family and layout in general — to make it look more vanilla.

### Deployment

This project is deployed on [Glitch](https://glitch.com/~eglazkova-dwd-a2-vanillaweather). It needs you to allow your geolocation to display properly. Please use Google Chrome web browser.

## Built with

* [VS Code](https://code.visualstudio.com/)
* [Glitch](https://glitch.com/)

## Questions

I was wondering what this message in my VS editor means 😳 

<a href="https://ibb.co/YTK9Cff"><img src="https://i.ibb.co/CsXdcVV/Screenshot-2020-02-22-at-12-43-34.png" alt="Screenshot-2020-02-22-at-12-43-34" border="0"></a>

## References

*[Dev Ed weather app tutorial](https://www.youtube.com/watch?v=wPElVpR1rwA)
