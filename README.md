# Smile With Us

### What it does

Our project gives people a shoulder to rely on, by allowing them to talk about what happened and how they feel. We present breathing exercises and techniques to calm them down in case of tense situations. We are able to record their verbal responses to several questions while maintaining a conversation-type feel. Then, we use an API to classify the responses in which emotion is portrayed using Convolutional Neural Networks. To run the project on your local system, you will have to obtain both Komprehend AI and YouTube Data V3 API Keys, and appropriately replace the current placeholders for them in the final.html, settings.cfg, and views.py files. Then, run python manage.py runserver in the highest self-care directory and open the link provided in the terminal. 

Depending on which emotion is most prominently portrayed (happy, sad, angry, bored, or fear), we base
the video and song recommendations to counter their negative mood using their desired content preferences. We use an API key from YouTube Data V3 to embed the video recommendations onto the website. 

On the user's very first visit, they put in their favorite television shows, sports teams, artists, and YouTubers which then get saved. For every subsequent visit, the user is recommended videos and songs based on their preferences and current mood/emotion. 

### UI Details and Choices for the Site

**Start Page (2nd page)**
- The background was chosen because it's serene and open to calm the nerves. The still water especially provides a sense of calmness
- Dialogues remain at 20% opacity to allow users to enjoy the background view unblocked
- If the mouse is hovered over the dialogues, then there's a 100% opacity for the words to read
- We had lots of spaces on the UI between dialogues to simulate the kind of therapist-person session
- The recorded questions are also a means to make it feel more realistic like a therapeutic sessions
- Therapist and person sessions usually are more of the person talking than the therapist, so the website acts perfectly in that sense_
- The questions shown on the page are common therapist questions and are scientifically proven to help better someone's mental health by letting out the users' inner feelings & emotions

**Breathing (3rd page)**
- Used blue color, space, and mountains because it evokes a sense of calmness
- Proven that the color of blue and sea green (as the color of the breathing ball) helps in destressing_
- The inhale & exhale ball also feels very realistic as it is like how a human really breathes (fast at the beginning and then it slows down to a stop)
- Has a 2-minute timer for breathing and then redirects the user to the last page

**Final Page (4th page)**

A general overview:
1. What is mental health
2. Why is mental health important & why not to ignore it
3. What steps need to be taken in order to keep a mental well being
4. How this applies to yourself, as well as, family and friends
5. Who are trusted individuals or adults to talk to
6. National Suicide Prevention Lifeline description

## How we built it

We built this web application using the Django Framework and we coded it using Python, JavaScript, HTML, and CSS. We used a YouTube Data V3 API to embed the video and song recommendations on the website. We also used an Emotion Analysis API to figure out which emotions were portrayed by the user when they were talking about their day and how they felt. 

## Accomplishments that we're proud of

Implementing a fully functioning web application with a variety of features for a great cause -- betterment of the mental health of all its users. 

## What's next for Smile With Us

In the near future, we hope to improve our web application by including a login page (username/password) to be able to track the user's progress. Essentially, we hope to be able to track growth and how the user's emotions/mood for every session is generally improving. Furthermore, instead of embedding individual songs on the website, we plan to implement a Spotify API and generate a whole playlist for each session the user has on the website. 

## Final Thoughts
"One life. Protect it." Mental health is a real issue and our website is a means to take care of it. The amount of work and effort we put into this just comes to show how seriously we and others take it. So don't feel ashamed to talk about your mental health to other trusted individuals and safeguard your mental well-being.
