Conversation and Computation
==============

NYU ITP, Spring 2015

####_"And the question is when is the last time that you had a great conversation, a conversation which wasn’t just two intersecting monologues, which is what passes for conversation a lot in this culture. But when had you last a great conversation, in which you overheard yourself saying things that you never knew you knew. That you heard yourself receiving from somebody words that absolutely found places within you that you thought you had lost and a sense of an event of a conversation that brought the two of you on to a different plane. …a conversation that continued to sing in your mind for weeks afterwards?"_ - John O’Donohue

#Description

Technology is becoming a part of every conversation we have. What influence does it have, and how might it be further leveraged to create new possibilities? This class explores various ways conversation may be analyzed, generated, and affected by computation. Specifically, we will study methods of linguistic analysis (LIWC, LSM, sentiment analysis) and body language analysis (face tracking, expression detection, Kinect). We will experiment with conversation automation (markov chains, chatbots, email scripting, social media APIs), and building software apps (Google Hangout apps, browser extensions, Skype API, Twilio API, webRTC) and physical devices (Arduino, RPi) for augmenting and affecting conversation. Finally, we will look at more public interventions, involving performance and text displays. The class will be based around three month-long projects, complemented by readings and shorter research exercises. This will be further contextualized by conversation analysis ideas from sociology and psychology, performance studies, other artists working with these themes.

#Evaluation
Grades will be determined according to the following breakdown:
* Project 1 20%
* Project 2 20%
* Project 3 20%
* Conversation log 15%
* Participation and attendance 25%

Please see ITP's statement on [Pass/Fail](http://help.itp.nyu.edu/academic-policies/pass-fail) which states that a "Pass" is equivalent to an "A" or a "B" while anything less would be considered a "Fail".

###Projects
This class is divided into three "parts" or general areas of inquiry. We will have three 3-4 week projects over the course of the semester, one for each part. You are expected to push your abilities both technically and conceptually to make original, thoughtful work. There will be check-ins during the duration of each project to discuss and review progress.

###Conversation log
As this class is about conversation, we will regularly engage in and push ourselves in conversation. So we are not just working theoretically. Each person will keep a "conversation log". As a class, we will generate prompts for conversations. Each week, we will choose one prompt as a class and you will have a conversation that you reflect on and respond to in a post in the conversation log.

###Participation
Attendance is mandatory. Please inform me via email if you are going to miss a class. Habitually showing up late for class or an excessive number of absences will adversely affect your grade.

This class will be participatory, you are expected to participate in discussions and give feedback to other students both in class and participate with their projects. There will also be occasional assigned readings.



#Syllabus

####Week 1 (1/28): Introduction
* History of compuation and conversation
  * Christopher Strachey's [1952 love letter generator](http://www.alpha60.de/art/love_letters/), [more](http://www.gingerbeardman.com/loveletter/), and more in [Rhizome's Queer History of Computing](http://rhizome.org/editorial/2013/apr/9/queer-history-computing-part-three/) 
* [Metaphors We Live By](http://www.amazon.com/Metaphors-We-Live-George-Lakoff/dp/0226468011), George Lakoff
* [Speaking Code](http://mitpress.mit.edu/books/speaking-code-0), Geoff Cox and Alex McLean
* [Slackers film](https://www.youtube.com/watch?v=jB4xlYKAVCQ), Richard Linklater - [description](http://en.wikipedia.org/wiki/Slacker_%28film%29)
* Tools
  * [programmableweb.com](http://www.programmableweb.com/) - giant list of APIs and resources 
  * [kimonolabs.com](http://www.kimonolabs.com/) - easy tool for turning any website into an API
  * [temboo.com](http://temboo.com) - simple APIs for many services in many languages
  * [IFTTT](https://ifttt.com/channels)
    * https://github.com/cido/ifttt-channel-extensions - create custom IFTTT channels
   * [Twitter](https://dev.twitter.com)
       * [Processing examples with Twitter4J](https://github.com/lmccart/AppropriatingInteractionTechnologies/tree/master/ProcessingTwitterExamples)
   * [Snapchat](http://gibsonsec.org/snapchat/fulldisclosure/) - [Unofficial Python API](https://github.com/niothiel/snapchat-python)
   * [Yo](http://dev.justyo.co/)
   * [NYTimes](http://developer.nytimes.com/docs)
   * [Twilio](https://www.twilio.com/docs/api) lets you work with phones

* __[Assignment 1](https://github.com/lmccart/itp-convo-comp/wiki/Assignments#assignment-1-due-24) (DUE 2/4)__

##Part 1: Language analysis and automation

####Week 2 (2/4): Linguistic analysis
* **John Rothenberg ([Sosolimited](http://sosolimited.com)) guest lecture**
* Sentiment analysis
* LIWC / LSM
* Social media APIs
  * [Twitter breakup prediction](http://motherboard.vice.com/read/what-our-breakups-look-like-on-twitter) 
* [Conversation analysis](http://en.wikipedia.org/wiki/Conversation_analysis), [tutorial](http://homepages.lboro.ac.uk/~ssca1/intro1.htm)
* Tools
  * [LIWC](http://liwc.net) available for [javascript and python](https://github.com/chbrown/lexicons)
  * [Sentiment analysis](http://en.wikipedia.org/wiki/Sentiment_analysis)
  * [natural](https://github.com/NaturalNode/natural) includes tokenizing, stemming, classification, phonetics, tf-idf, WordNet, string similarity.
  * [everything but the chat](https://github.com/lmccart/everything-but-the-chat) combines a little bit of everything above.
  * [corpora](https://github.com/dariusk/corpora) is a collection of words and phrases by category.
* Survey
  * [FB Demetricator ](http://bengrosser.com/projects/facebook-demetricator), Ben Grosser

####Week 3 (2/11): Generation and automation
* [Computing Machinery and Intelligence](http://www.loebner.net/Prizef/TuringArticle.html), A.M. Turing and [Chinese Room thought experiment](http://en.wikipedia.org/wiki/Chinese_room), John Searle
* [Gmail scripting](https://developers.google.com/apps-script/reference/gmail/)
* Text messages
* [Postcard API](https://lob.com/blog/how-to-send-postcards-as-effortlessly-as-email)
* Dataclysm??
* Survey
  * Love automation
    * [BreakupText](https://itunes.apple.com/us/app/breakuptext/id674333306?ls=1&mt=8)
    * [MakeupText](https://itunes.apple.com/us/app/makeuptext/id681601569?ls=1&mt=8)
    * [OkCupid auto-spammer](https://github.com/shawn-simon/okspam)
    * [BroApp](http://jezebel.com/i-tried-broapp-and-it-did-not-turn-me-into-an-awesome-b-1536966006)  
    * [Romantimatic](http://romantimatic.com/)
 
####Week 4 (2/18): Generation and automation (cont)
* **[Darius Kazemi](http://tinysurversions.com) guest lecture**
* Markov chains
* Bots
  * [About a Bot: Hoax, Fake, Performance Art](http://journal.media-culture.org.au/index.php/mcjournal/article/viewArticle/814), Tania Bucher 
  * [Closed Bots and Green Bots: Two Archetypes of Computational Media](https://gist.github.com/tullyhansen/7621632), Mark Sample
  * [Taxonomy of Twitter Bots](https://gist.github.com/tullyhansen/7621632) and [Twitter Bot family tree](http://www.samplereality.com/wp-content/uploads/2014/06/hansen-bot-taxonomy.png), Tully Hansen
* Survey
  * Christopher Strachey's [1952 love letter generator](http://www.alpha60.de/art/love_letters/), [more](http://www.gingerbeardman.com/loveletter/), and more in [Rhizome's Queer History of Computing](http://rhizome.org/editorial/2013/apr/9/queer-history-computing-part-three/)
  * [Darius Kazemi](https://twitter.com/dariusbots)
  * [everyword](https://twitter.com/everyword)
  * [On Kawara tribute](https://twitter.com/On_Kawara)
  * [Horse_ebooks](http://www.newyorker.com/magazine/2014/02/10/man-and-machine-2)
  * [Pentametron](http://www.npr.org/2013/02/16/172031066/pentametron-reveals-unintended-poetry-of-twitter-users), Ranjit Bhatnagar

####Week 5 (2/25): Visualization and display
* Conversation / language viz
* Public text displays
* Survey
  * [A More Perfect Union](http://music.columbia.edu/~luke/projects/index.shtml?id=perfect), R. Luke Dubois
  * [Graffiti Research Lab](http://www.graffitiresearchlab.com/blog/)

##Part 2: Physical augmentation and alternatives

####Week 6 (3/4): Augmentation apps
* Google Hangout apps
* Browser extensions
* Skype, Twilio, webRTC
* Survey
  * [Speaking Exchange](http://ablersite.org/2014/06/05/speaking-exchange/)
  * [Talk Therapy](http://www.chris-reilly.org/art/talk-therapy/), Chris Reilly
  * [A Hole in Space](http://alltheartever.tumblr.com/post/103284895404/a-hole-in-space-kit-galloway-and-sherrie), Kit Galloway and Sherrie Rabinowitz 1980
  * [The Radio as an Apparatus of Communication](http://alltheartever.tumblr.com/post/108065923059/der-lindberghflug-the-lindbergh-flight-by), Bertolt Brecht 1929

####Week 7 (3/11): Physical analysis
* Body language
* Face tracking 
* Expression detection
* Technical:
  * [Computer Vision for Artists and Designers](http://www.flong.com/texts/essays/essay_cvad/) by Golan Levin 
  * [Face Tracking Notes](https://github.com/kylemcdonald/AppropriatingNewTechnologies/wiki/Week-2) for Appropriating New Technologies / Face as Interface workshop
  * [Eye Tracking Notes](https://github.com/kylemcdonald/AppropriatingNewTechnologies/wiki/Week-5) for Appropriating New Technologies
  * [Computer Vision in Interactive Art](https://docs.google.com/document/d/1Yky5TpKrxNDQzD7sXQ8gGpYFTsQhac1PrjYLQ3X_zJQ/edit?usp=sharing), Kyle McDonald
  * [Computer Vision: Algorithms and Applications](http://szeliski.org/Book/) by Richard Szeliski
  * [OpenCV-Processing book](https://github.com/atduskgreg/opencv-processing-book/blob/master/book/toc.md) in progress by Greg Borenstein includes a great ontology of computer vision. He's also responsible for [Making Things See]
(https://github.com/atduskgreg/Making-Things-See-Examples) which focuses on Kinect.

####Week 8 (3/25): Physical augmentation and alternatives
* Devices / objects
  * [Let's Chat!](http://fathom.info/latest/8400), Lee Cusack 
  * [How are We Going to Talk After This?](http://www.chris-reilly.org/art/how-are-we-going-to-talk-after-this/), Chris Reilly
  * [Linguaphone of Tremulous Communion](http://www.chris-reilly.org/art/linguaphone-of-tremulous-communion/), Chris Reilly
  * [Krzysztof Wodiczko](http://www.pbs.org/art21/artists/krzysztof-wodiczko/)
* Physical feedback
* Sign language
  * [Pushing Science’s Limits in Sign Language Lexicon](http://www.nytimes.com/2012/12/04/science/sign-language-researchers-broaden-science-lexicon.html?pagewanted=1&_r=2&hp&adxnnlx=1355343233-SxIlOSHbDOJCM8VPk75NTg&), NYT 
  * [Signed Languages Can Do So Many Things Spoken Languages Can't](http://www.theguardian.com/commentisfree/2014/oct/20/signed-languages-can-do-so-many-things-spoken-languages-cant?CMP=twt_gu), The Guardian
* Braille 
* [The Conservatism of Emoji](http://thenewinquiry.com/essays/the-conservatism-of-emoji/), Kate Crawford and Luke Stark
* Physical correspondence, [mail art](http://en.wikipedia.org/wiki/Mail_art)
  * [MoMA Mail Art exhibit](http://www.moma.org  /interactives/exhibitions/2014/analognetwork/) 
  * [On Kawara](http://en.wikipedia.org/wiki/On_Kawara)

##Part 3: Public and performance

####Week 9 (4/1): Performing conversation
* Erving Goffman, Harold Garfinkel
* Scripts, cues, prompts, improv
* Survey
  * [Somebody App](http://somebodyapp.com/), Miranda July
  * [Acting Stranger](http://www.actingstranger.com/), Andrew Schneider
  * [Rejection Line](http://rejectionline.com/), Jonah and Chelsea Peretti 2001
  * [Inbox Full](https://www.youtube.com/watch?v=XdfIXkwvU1Y), Molly Soda

####Week 10 (4/8): Public conversation
* Online social dynamics
  * [Online abuser dynamics](https://soundcloud.com/eyebeamnyc/new-topics-in-social-computing-online-abuser-dynamics) with Erin Kissane, Sydette Harry and Melissa Gira Grant, moderated by Joanne McNeil
* Anonymity
  * [Why Facebook and Google's Concept of Real Names is Revolutionary](http://www.theatlantic.com/technology/archive/2011/08/why-facebook-and-googles-concept-of-real-names-is-revolutionary/243171/), The Atlantic
  * [“Real Names” Policies Are an Abuse of Power](http://www.zephoria.org/thoughts/archives/2011/08/04/real-names.html), danah boyd
  * [The Facebook Bully](https://medium.com/message/the-facebook-bully-d7a16f6ede38), Joanne McNeil

####Week 11 (4/15): Protest
* Survey
  * [TXTmob](http://www.appliedautonomy.com/txtmob.html)
  * [FireChat](http://www.theverge.com/2014/10/16/6981127/firechat-messaging-app-accidental-protest-app-hong-kong) 
  * [Notes from OWS](https://nplusonemag.com/online-only/occupy/notes-from-an-occupation/)

####Week 12 (4/22): Final project presentations
