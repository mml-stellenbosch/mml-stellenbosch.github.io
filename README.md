Maties Machine Learning (MML) is a seminar series and discussion forum with the goal of bringing together people working on machine learning at Stellenbosch University. We plan to come together every second week, with one or more short talks on people's current work or some ML-related topic, followed by an open discussion. The idea is to get to know what others are working on, and to strengthen machine learning research at Stellenbosch.

Jump to:

- [Upcoming talks](#upcoming-talks)
- [Previous talks](#previous-talks-with-slides)
- [Register to the mailing list](#register)


# Upcoming talks

* * *

**9 March 2018**, 13:00-13:45 in K302 (Knowledge Centre, Engineering)

[Emre Yilmaz](https://sites.google.com/site/schemreier/) will be visiting us from Radboud University.

**Language and speaker recognition for semi-supervised bilingual acoustic model training**

In this talk, we describe various automatic annotation approaches to enable the use of a large amount of raw bilingual broadcast data for semi-supervised bilingual acoustic model training. Our research focuses on the Frisian-Dutch code-switching (CS) speech that is extracted from the archives of a local radio broadcaster. Unlike Dutch, Frisian is a low-resourced language with very limited amount of manually transcribed speech data. Using 11 hours of speaker-annotated and transcribed CS speech data as a reference, multiple deep neural network (DNN) acoustic models are trained by merging the manually and automatically annotated (combined) speech data. For automatic annotation, we propose applying language recognition to assign language labels to speech segments at the front-end and using monolingual automatic speech recognition (ASR) resources for transcribing the raw speech segments. Furthermore, speaker diarization and recognition are applied to the raw broadcast data to first assign (pseudo) speaker labels and then link the known speakers appearing in the reference data to these speaker labels. The speaker information is later used for extracting speaker-dependent features and getting alignments using speaker-dependent acoustic models for neural network training. We run ASR experiments on the development and test data of the FAME! speech corpus to quantify the quality of the automatic annotations provided by each approach. The results demonstrate that applying speaker and language recognition improves the automatic annotation quality yielding better bilingual acoustic models with lower recognition errors and higher CS detection accuracy. After increasing the available CS training data using these automatic annotation strategies, we investigate incorporating more speech data from the high-resourced mixed language (Dutch in this case) to enable the use of state-of-the-art acoustic models which outperforms standard DNNs when using much larger amounts of training data. Including around 750 hours of monolingual Dutch training data provides significantly better CS ASR performance compared to a baseline only trained on the manually and automatically transcribed CS training data.

* * *

**23 March 2018**

We will have two (exciting and diverse) talks from Lidia Auret and Arina Britz.

* * *

# Previous talks (with slides)

* * *

**23 February 2018**

- Miguel Smith - _Pathfinding in an emulated Minecraft client_ [[slides](slides/2018-02-23_smith.pdf)]
- Ryan Eloff - _Teaching a robot  to interpret natural language navigation instructions_ [[slides](slides/2018-02-23_eloff.pdf)]

* * *

**9 February 2018**

Willie Brink - _An introduction to MLNs and their use in visual relational learning_ [[slides](slides/2018-02-09_brink.pdf)]

* * *

**7 December 2017**

Rasmus Dall - _Jibo & his voice_

* * *

**10 November 2017**

Ben Herbst - _Tutorial on variational autoencoders_ [[slides](slides/2017-11-10_herbst.pdf)]

* * *

**3 November 2017**

- Francois Kamper - _An empirical study of Gaussian belief propagation and application in the detection of F-formations_ [[slides](slides/2017-11-03_kamper.pdf)]
- Simon Streicher - _Graph coloring: comparing cluster graphs to factor graphs_ [[slides](slides/2017-11-03_streicher.pdf)]
- Clint Lombard - _Dense relative mapping: a novel approach to dense mapping for autonomous robots_ [[slides](slides/2017-11-03_lombard.pdf)]

* * *

**27 October 2017**

- Arnu Pretorius - _Using learning dynamics to understand neural network generalisation_ [[slides](slides/2017-10-27_pretorius.pdf)]
- Shane Josias - _Automated identification of tsetse fly wing vein intersections_ [[slides](slides/2017-10-27_josias.pdf)]
- Ewald van der Westhuizen - _Automatic speech recognition of code-switched speech for South African languages_ [[slides](slides/2017-10-27_vanderwesthuizen.pptx)]
- Greg Newman - _Deep learning for video classification_ [[slides](slides/2017-10-27_newman.pdf)]

* * *

**6 October 2017**

Herman Kamper - _Unsupervised neural feature learning for speech using weak top-down constraints_ [[slides](slides/2017-10-06_kamper.pdf)]

* * *

# Register

We have two mailing lists:

- **[MML]** is our main mailing list, for announcing official Maties Machine Learning events.

    - [Subscribe](https://sympa.sun.ac.za/sympa/subscribe/mml)
    - [Unsubscribe](https://sympa.sun.ac.za/sympa/signoff/mml)

- **[MML-adverts]** is a lightly moderated list for advertising talks, scholarships, jobs and events that might be of interest to the MML community (but are not officially part of MML).

    - [Subscribe](https://sympa.sun.ac.za/sympa/subscribe/mml-adverts)
    - [Unsubscribe](https://sympa.sun.ac.za/sympa/signoff/mml-adverts)
    - To send an email to this list, send it <a href="mailto:mml-adverts [at] sympa [dot] sun [dot] ac [dot] za">here</a>.


