# GDquest video guidelines

This document is a living tool to help us improve the educational value and the consistency of our video lessons.

The goal is to help us solidify both the form and the substance of our tutorials. We included practical tips about recording.

We're also leaving our guidelines open for fellow tutors to contribute, and for aspiring tutors to draw inspiration from.

## We learn when we're engaged in an activity

Until now, our videos have been showing solutions to problems, but we've rarely even tried to engage the viewer directly. Practice is essential to learning. Putting what you learned in your own words, and applying what you're learning, as you're learning it. So is getting sufficient feedback for every step that we take learning a given discipline.

I believe that to learn as fast as we can, we need to:

- **Feel like we're part of the group we strive to be part of**. I think that's why Jesse Shell's "The Art of Game Design" starts by asking the readers to view and call themselves game designers. Just like playing as an avatar in a game, the virtual identity helps us take steps towards becoming a designer, a developer, an artist... and thinking like one of them.
- **Get a lot of feedback for our input**. This is an idea we always apply to UX and game design. Feedback, feeling like our actions are meaningful and produce a tangible result, helps us understand, memorize techniques, and stay engaged and motivated.
- **Practice, and do so at the edge of our abilities**. Learning is incomplete without practice. Theory alone is insufficient to develop skills. Critical thinking, writing, actual programming, and design work are necessary to strengthen our abilities. We also need some challenge to stay engaged. If you've ever been in a state of [flow](http://www.jenovachen.com/flowingames/foundation.htm), there's nothing like it to make fast progress in a given domain.

And more.

The points above are hard to achieve with video lessons. We learn through practice, and when we're critically engaged in an activity. Our videos should push the viewers towards that. We need to go past sharing raw information and facts and help people to want to learn, to practice, and to enjoy the process.

We can do so by multiplying the opportunities for the viewer to engage in learning. **Asking the viewer questions**, by offering **exercises**, **challenges**, and by creating **community projects and events**.

<!-- TODO: write more on viewer questions and quizzes, exercises, challenges, and getting people to take part in community projects. We can take a look at FreeCodeCamp as an example. -->

## Going past step-by-step

Step-by-step tutorials are easy to produce, and they can ease designers who aren't comfortable with programming into the daunting process of creating software. But as soon as we try to cover the reality of development, step-by-step videos tend to dumb it down into a seemingly linear process while design and programming are both nonlinear, creative problem-solving activities.

That is because step-by-step videos are long. The majority of the content shows typing individual lines of code, which shifts the focus towards the implementation details. As we have to write a lot, we end up focusing on writing the code without typos instead of thinking hard about the big picture. Yet, I believe the big picture and general techniques is the part we should teach.

### Code overviews

Commenting on a finished project's structure can be useful to explain high-level abstractions and a program's flow, especially if the lesson is short and to the point. It can help experienced developers or students to expand their library of patterns and solutions that they can apply to their projects.

### A middle-ground: pasting code snippets

To replace code overviews we could shift towards an approach that's half-way through step-by-step and just commenting on the final code. We can achieve that creating start Godot project with only the files required for the tutorial, extracted from a larger project. But more than the assets.

The projects would include:

- Anything that's not relevant to the tutorial but required pre-built and encapsulated. Assets, scenes, scripts...
- Some empty API in place for the scripts that are relevant to the tutorial: properties, the methods' signature, docstrings, all that based on the guidelines, but no individual instructions.

With the API in place, you can quickly explain the class's responsibility and how the interface will help you to solve the problem at hand. It allows you to focus on code structure.

Then paste blocks of code one by one to show a way to implement the solution and flesh out the details.

The tutorials don't have to cover every single line. We can also have pre-built methods or extra objects done and hidden from the viewer. Anything that's not relevant to the tutorial, but required for the demo to work.

## Video recording

### Video

When you make a small mistake or need to re-record a sentence, clap in front of the mic. This produces a sharp vertical line on the audio waveform that makes it easy for the editor to find and remove the faulty parts.

You should always record:

- In Full HD, 1920x1080
- Using the NTSC-film framerate, the most common on the web and cameras: 30/1.001 or ~29.97

The font size should be large enough for the video to read on a tablet, or depending on the video, on a large mobile phone in landscape orientation. If the program supports it, increase the font size to 20pt or more.

For instance, in Godot, I use 20pt for the editor's font and 23pt for the code. Past 20pt, the editor's layout can feel too packed.

### Audio

#### Setting up the microphone

The closer you are to the microphone when you record, the louder your voice will be relative to the sound reflected by your environment. You don't want to eat the mic, but you should place it less than 1m away from your mouth, or closer if possible.

30-40cm is a good middle-ground in case you move a bit when talking: if you place it too close, your movement will cause significant changes in your voice's volume.

The voice should be normalized at around -6db. Use other YouTube videos or one of your recordings with good audio levels for reference. Always check your edit against the reference before exporting it.

#### Drinks ####

Don't drink coffee, tea, or milk when and right before recording. The former can leave your palate dry and provoke mouth noises. Milk tends to stick in your throat and to limit the control of your voice.

You always want to record with a clean palate, stay hydrated, and have a bottle or a glass of water next to you. Sip often when recording to keep your voice level stable.

#### Mouth noises

Mouth noises happen when your mouth is dry, or after drinking coffee, tea, and some other beverages.

If you drank coffee, or anything similar, you'd want to brush your teeth, but also your tongue and palate gently.

Before recording, use the warm up to check if your mouth is producing sounds. If so, you should drink water.


#### Warming up ####

The mouth and vocal folds move thanks to muscles. To articulate to your fullest and to get the most out of your voice, you need to warm up, like before any exercise. At least for a minute or two.

**The longer the recording session, the longer you should warm up**.

Here's a [short vocal warm up](https://www.youtube.com/watch?v=9tXK7cw9mrg) from Julian Treasure's TED talk. You want to warm up your lips, your tongue, and your jaw. The siren exercise then focuses on the vocal cords. To improve pronunciation of specific sounds, add a few [tongue twisters](http://pun.me/pages/tongue-twisters.php): they'll serve both as an exercise and complete your warm up.
