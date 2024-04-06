# My User Page

## Introduction

Hello there! I'm *Anthony Chapov*, a Computer Science Student with a passion for AI technologies and challenging classes.


![Alt text](myPicture.PNG)
[LinkedIn](https://www.linkedin.com/in/anthonychapov/)
---
## About Me
[Jump to About Me Section](#about-me)

I am a junior at UC San Diego, currently taking AI & SE classes and striving to gain as much project experience as possible. In addition to exploring new AI technologies, **I enjoy**

  - hiking
  - driving fast cars
  - cooking
  - working out

**My goal** is to become an IT Project/Product Manager, but I am also considering joining the US Marine Corps as an officer if I can't find an entry-level CS job.


---
## Skills (Programming languages)

[Jump to Programming Languages Section](#programming-languages-and-skills)

**My favorite programming language is C++**, and I have a strong preference for it over Python. Why? Well... 

> “Man is sometimes extraordinarily, passionately, in love with suffering...” 
> ― Fyodor Dostoevsky


Here is how I would rank **my skill level/experience with different programming languages** where first is the strongest and last is the weakest skillset: 

  1. C++
  2. Java
  3. MIPS Assembly
  4. JS
  5. Python

When it comes to Python, the most complex code I wrote myself would be a Flask server: 
```app = Flask("Emotion Detector")

@app.route("/emotionDetector")
def emot_detector():
    ''' This code receives the text from the HTML interface and 
        runs sentiment analysis over it using sentiment_analysis()
        function. The output returned shows the label and its confidence 
        score for the provided text.
    '''
    text_to_analyze = request.args.get('textToAnalyze')
    response = emotion_detector(text_to_analyze)

    if response['dominant_emotion'] is None:
        return ('Invalid text! Please try again.')

    # Format the emotion scores
    formatted_scores = ", ".join(f"'{emotion}': {score}" for emotion, score in response.items())
    dominant_emotion = response['dominant_emotion']

    # Printing in the specified format
    return (f"For the given statement, the system response is {formatted_scores}. The dominant emotion is {dominant_emotion}.")```
```

---
Here you can find a link to README.md that includes parts of Lab #1:
[Readme.md](README.md)
 

---
This page includes the following
  - [x] **Headings**
  - [x] Styling text
  - [x] Quoting text
  - [x] Quoting code
  - [x] External Links
  - [x] Section links
  - [x] Relative links
  - [x] Task lists



