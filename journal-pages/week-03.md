---
layout: default
---

# Week 03

[← Back to Home](../index.md)

## Documentation 

## Activity 1: Explore with cURL

![alt text](<../assets/week-03/Screenshot 2026-03-20 153737.png>)

![alt text](<../assets/week-03/Screenshot 2026-03-20 154508.png>)

## Activity 2: Weather Visualisation

![alt text](<../assets/week-03/Screenshot 2026-03-20 155217.png>)

### Activity 3: Design and Execute a Data Protocol

In pairs, design a data protocol: a set of rules for translating a live data source. This is the analogue equivalent of an API: a defined set of rules for requesting and receiving data.

![alt text](../assets/week-03/IMG_6611.jpeg)
![alt text](../assets/week-03/IMG_6613.jpeg)

Our protocol included the tasks of checking how many tables have been talking at a time window of every 10 seconds. Each table that had at least one person speaking could be represented with a tally marking.

Below shows an image of how the activity turned out for my group:
![alt text](../assets/week-03/IMG_6613.jpeg)

Below is a picture of the sheet that my group had gotten from another group:
![alt text](../assets/week-03/IMG_6611.jpeg)

When time is up, compare your output with what the designers intended. Did you interpret the rules as they expected? Where was the protocol ambiguous? What surprised you about the result?

The instructions was ambiguious with the data collection method,  this group had mentioned to use lines on paper. My team had iterpreted this task as drawing lines ofpaper in accordance to the sounds we were hearing.


### Independant Study

(Cat API)


![cat image](https://editor.p5js.org/nrid934/full/4r3r1iOOy)


<iframe
  src="https://editor.p5js.org/nrid934/full/4r3r1iOOy"
  width="400"
  height="400">
</iframe>

![alt text](<../assets/week-03/Screenshot 2026-04-02 215024.png>)

Code lines:

let catImg;

function preload() {
  catImg = loadImage("https://cataas.com/cat/says/hello?fontSize=60&fontColor=red");
}

function setup() {
  createCanvas(600, 600);
  imageMode(CENTER);
}

function draw() {
  background(220);
  image(catImg, width/2, height/2, 600, 600);
}

----

Perhaps if I were to develop this again next time, I would like to add more customisability, to potentially allow others to customise the text.