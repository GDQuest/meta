# GDquest video guidelines

This document is a living tool to help us improve the educational value and the consistency of our video lessons.

The goal is to help us solidify both the form and the substance of our tutorials. We included practical tips about recording.

We're also leaving our guidelines open for fellow tutors to contribute, and for aspiring tutors to draw inspiration from.


<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [GDquest video guidelines](#gdquest-video-guidelines)
    - [We learn when we're engaged in an activity](#we-learn-when-were-engaged-in-an-activity)
    - [Going past step-by-step](#going-past-step-by-step)
        - [Code overviews](#code-overviews)
        - [A middle-ground: pasting code snippets](#a-middle-ground-pasting-code-snippets)
    - [We should teach techniques and concepts over recipes](#we-should-teach-techniques-and-concepts-over-recipes)
    - [Keep the language simple](#keep-the-language-simple)
    - [Video recording](#video-recording)
        - [Video](#video)
            - [Program layout](#program-layout)
            - [Font size](#font-size)
        - [Audio](#audio)
            - [Setting up the microphone](#setting-up-the-microphone)
            - [Drinks](#drinks)
            - [Mouth noises](#mouth-noises)
            - [Warming up](#warming-up)
            - [Take your time](#take-your-time)
    - [Video editing](#video-editing)

<!-- markdown-toc end -->


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

## We should teach techniques and concepts over recipes

> Give a man a fish and you feed him for a day; teach a man to fish, and you feed him for a lifetime.

Although we learn from practice and examples, as tutors, we can help the learners go one step further: learn the general, reusable technique or concept behind the examples.

We're here to teach more than a series of steps to solve a specific problem. We're here to help people learn to solve problems on their own, regardless of the situation they are facing. To help them become independent, not reliant on step-by-step guides. Our videos should help people understand that game creation isn't a linear process and that independent creators don't have strict recipes to follow.

The idea applies to game programming as well: the principles we use and the way we structure our code are more important than the exact implementation we choose.

When you create a tutorial on a given topic, try to offer more than a description of what each line of code does. You can explain the thought process that led you to structure your project in a certain way, mention other potential solutions you could try, their advantages and drawbacks. If you decide to teach a pattern, explain its general form. You can also indicate the limits of your example or the tutorial compared to a real-world scenario. Game code can get complicated and messy once you start to connect systems.

## Keep the language simple

To me, the ability to explain complex topics in fairly simple terms is a sign of mastery and maturity. Mastery because it takes a great deal of experience to boil down a technique or a concept to its essence. Maturity as pride or one's ego can prevent us from making hard-learned knowledge accessible to everyone else.

The domains we teach are hard to learn. Our role as tutors is to ease the students into learning. There are terms we can't work around: a developer must learn about variables, functions, loops, classes, objects, etc. However, there's no need for unending sentences, academic terms, or rare vocabulary in our tutorials. We should make each tutorial as accessible as we can to its target audience.

Depending on the intended audience for a given series, we can assume that the student has a certain amount of experience. The viewer should already be comfortable with all basic programming concepts to follow a video about pathfinding in 3d, or about a programming pattern like State.

It's a balancing act. The idea isn't to dumb down the lesson, but to do our best to keep the form as clean and as fluid as possible so that the learner can focus their attention on the substance.

## Video recording

### Video

When you make a small mistake or need to re-record a sentence, clap in front of the mic. This produces a sharp vertical line on the audio waveform that makes it easy for the editor to find and remove the faulty parts.

You should always record:

- In Full HD, 1920x1080
- Using the NTSC-film framerate, the most common on the web and cameras: 30/1.001 or ~29.97

Your footage should be smooth, not choppy. You should remove anything that can distract the viewer from the tutorial from the screen: notifications, messaging client, etc. Make the program full-screen whenever possible.

Be careful not to wave the mouse cursor as you talk. Put the mouse or stylus down when you're talking and not pointing at anything in particular. The motion can be distracting.

Also, make sure that the sound you record from your internal sound card or speakers doesn't cover your voice. I keep the desktop audio channel at -20db to -30db most of the time in OBS Studio.

#### Program layout

Use one of the default interfaces and, when possible, the default interaction mode for the program covered in the video.

E.g. for Blender 2.80 and up, left click is the default to select and grab objects. As viewers stumble upon videos organically and generally won't watch them in a particular order, the tutorials should stay close to the programs' default settings. There are some exceptions for tools like the shell, vim, or emacs that, once you've learned the basics, you are meant to customize a lot.

Make the program **full-screen** whenever possible. Many programs use the <kbd>F11</kbd> key or a related shortcut for that.

- For Godot, before recording, go to Editor -> Editor Layout -> Default to reset the interface.
- For Krita, I recommend using the Big Paint workspace over the default, as it centers the canvas on screen. It also shows the Layers, color palette, tool options, document overview, brushes, toolbox, and advanced color selector: everything you need to paint is visible on screen.

#### Font size

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

#### Take your time ####

If you're struggling to explain something while recording, clap, and take the time to breathe and to think. Rehearse the complex idea in your mind or in front of the microphone. You can leave the recording running in the meantime. When you're ready, do a clean and confident take. It's easy to edit the long silence out later.

## Video editing

Avoid abrupt cuts in both the audio and the video. You should cut mistakes and long silences or hesitations, but avoid cutting too much between words. Especially if you are editing live footage: too many cuts and the video will feel robotic or sped up. There's a natural rhythm to the human speech that you want to preserve.
