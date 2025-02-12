# Datasets

## HCP-trt

Four out of six participants (`P01-03`, `P05`) were scanned for a total of approximately 10 hours of functional data per subject. This `cneuromod` dataset is called HCP test-retest (`HCP-trt`), because participants repeated 15 times the functional localizers developed by the Human Connectome Project. The protocol consisted of seven tasks, described below (text adapted from the [HCP protocol site](http://protocols.humanconnectome.org/HCP/3T/task-fMRI-protocol-details.html)). Before each task participants are given detailed instructions, and are given examples, as well as a practice run. A session was typically composed either of two repetitions of the HCP localizers, or of one resting-state run, and one repetition of HCP localizers.

Stimuli and e-prime scripst were were provided by the Human Connectome Project, U-Minn Consortium (Principal Investigators: David Van Essen and Kamil Ugurbil; 1U54MH091657) funded by the 16 NIH Institutes and Centers that support the NIH Blueprint for Neuroscience Research; and by the McDonnell Center for Systems Neuroscience at Washington University.

The dataset is accessible in datalad [here](https://git.unf-montreal.ca/neuromod/phantom_hcptrt) (access request needed).
The eprime scripts for preparation and presentation of the stimuli can be found in the HCP database: [link to eprime scripts and stimuli](https://db.humanconnectome.org/app/action/ChooseDownloadResources?project=HCP_Resources&resource=Scripts&filePath=HCP_TFMRI_scripts.zip).

### Gambling
Duration: approximately 4 minutes. Participants played a card guessing game where they were told to guess whether the number of a card (represented by a “?” presented for 1500ms on the screen) was above or below 5 (Delgado et al. 2000). They indicated their choice using button press, and following their choice they were shown the correct number. If they guessed correctly they were told they won money ($1.00 - reward condition), if they guessed incorrectly they were told they lost money ($0.50 - loss condition), and if the number was exactly 5 they were told that they neither won or lost money (neutral condition). Note that no money was actually given to the participants and, as such, this task may not be valid but was still included to accurately reproduce the HCP protocol. The conditions were presented in blocks of 8 trials that were either mostly reward (6 reward trials pseudo randomly interleaved with either 1 neutral and 1 loss trial, 2 neutral trials, or 2 loss trials) or mostly loss (6 loss trials pseudo-randomly interleaved with either 1 neutral and 1 reward trial, 2 neutral trials, or 2 reward trials). There were four blocks per run (2 mostly win and 2 mostly loss), and two runs in total.

### Motor
Duration: approximately 5 minutes. This task was adapted from (Buckner et al. 2011; Yeo et al. 2011). Participants were presented a visual cue, and were asked to either tap their left or right fingers, squeeze their left or right toes, or move their tongue to map motor area. Each movement lasted 12 seconds, and in total there were 13 blocks, with 2 of tongue movements, 4 of hand movements (2 right and 2 left), and 4 of foot movements (2 right and 2 left), and three 15 second fixation blocks where participants were instructed not to move anything. There were two runs in total, and 13 blocks per run.

### Language processing
Duration: approximately 5 minutes. Participants either listened to an auditory story (5-9 sentences, about 20 seconds), followed by a two-alternative forced-choice question, or they listened to a math problem (addition and subtraction only, varies in length), and were instructed to push a button to select the first or the second answer as being correct. The task was adaptive so that for every correct answer the level of difficulty increased. The math task was designed this way to maintain the same level of difficulty between participants. There were 2 runs, each with 4 story and 4 math blocks, interleaved.

### Social cognition  
Duration: approximately 5 minutes. Participants were presented with short video clips (20 seconds) of objects (squares, circles, triangles) that either interacted in some way, or moved randomly on the screen (Castelli et al. 2000; (Wheatley et al. 2007). Following each clip, participants were asked to judge whether the objects had a “Mental interaction” (an interaction that appeared as if the shapes were taking into account each other’s feelings and thoughts), whether the were “Not Sure”, or if there was “No interaction”. Button presses were used to record their responses. In each of the two runs, participants viewed 5 “Mental” videos and 5 random videos and had 5 fixation blocks of 15 seconds each.

### Relational processing
Duration: approximately 5 minutes. Participants were shown 6 different shapes filled with 1 of 6 different textures (Smith et al. 2007). There were two conditions: relations processing, and control matching condition. In the relational processing condition, 2 pairs of objects were presented on the screen, with one pair at the top of the screen, and the other pair at the bottom. Participants were instructed to decide what dimension differed in the top pair (shape or texture), and then decide if the bottom pair differed, or not, on the same dimension (i.e. if the top pair differed in shape, did the bottom pair also differ in shape). Their answers were recorded by one of two button presses: “a” differ on same dimension; “b” don't differ on same dimension. In the control matching condition, participants were shown two objects at the top of the screen, and one object at the bottom of the screen, with a word in the middle of the screen (either “shape” or “texture”).They were told to decide whether the bottom object matched either of the top two objects on that dimension (i.e., if the word is “shape”, did the bottom object have the same shape as either of the top two objects). Participants responded “yes” or “no” using the button box. For the relational condition, the stimuli were presented for 3500 ms, with a 500 ms ITI, and there were four trials per block. In the matching condition, stimuli were presented for 2800 ms, with a 400 ms ITI, and there were 5 trials per block. In total there were two runs, each with three relational blocks, three matching blocks and three 16-second fixation blocks

### Emotion processing  
Duration: approximately 4 minutes. Participants were shown triads of faces or shapes, and were asked to decide which of the shapes at the bottom of the screen matches the target face/ shape at the top of the screen (adapted from Smith et al. 2007). Faces had either an angry or fearful expression. Faces, and shapes were presented in three blocks of 6 trials (3 faces and 3 shapes), with each trial lasting 2 seconds, followed by a 1 second inter-stimulus interval. Each block was preceded by a 3000 ms task cue (“shape” or “face”), so that each block was 21 seconds long, including the cue. In total there were two runs, three face blocks and three shape blocks, with 8 seconds of fixation at the end of each run.

### Working memory  
Duration: approximately 5 minutes. There were two subtasks: a category specific representation, and a working memory task. Participants were presented with blocks of either places, tools, faces, and body parts. Within each run, all 4 types of stimuli were presented in block, with each block being labelled as a 2-back task (participants needed to indicate if they saw the same image two images back), or a version of a 0-back task (participants were shown a target at the start of the trial and they needed to indicate if the image that they were seeing matched the target). Each image was presented for 2 seconds, followed by a 500 ms ITI. Stimuli were presented for 2 seconds, followed by a 500 ms inter-task interval. Each of the 2 runs included 10 trials, and 4 fixations blocks (15 secs).

### Resting state
Duration: 15 minutes. In every other session, one resting-state fMRI run was acquired. Participants were asked to have their eye open, be looking at fixation cross in the middle of the screen and be instructed to not fall asleep. A total of five resting-state fMRI runs were acquired per subject.

## Movie-10

This dataset includes about 10 hours of functional data for all 6 participants (`P01-P06`). The participants watched the following movies:
 * [The Bourne supremacy](https://en.wikipedia.org/wiki/The_Bourne_Supremacy_%28film%29). Duration ~100 minutes.
 * [The wolf of wall street](https://en.wikipedia.org/wiki/The_Wolf_of_Wall_Street_%282013_film%29). Duration ~170 minutes.
 * [Hidden figures](https://en.wikipedia.org/wiki/Hidden_Figures). Duration ~120 minutes. This movie was presented twice, for a total duration of ~240 minutes.
 * [Life](https://en.wikipedia.org/wiki/Life_(British_TV_series)) episode 2: "Reptiles and Amphibians".  Duration ~XX minutes. This movie was presented twice, for a total duration of ~XX minutes.

Each movie was cut into a series of ~10 minutes clips. Exact cutting points were manually selected to not interrupt the narrative flow. Fade out to a black screen was added at the end of each clip, and with a few seconds overlap between the end of a clip and the beginning of the next clip. The number of clips presented in a given session varied, and some subjects took short breaks inside a session.

The dataset is accessible in datalad [here](https://git.unf-montreal.ca/neuromod/phantom_video) (access request needed).
The python & psychopy scripts for preparation and presentation of the clips can be found in the following github [repository](https://github.com/courtois-neuromod/task_stimuli).

Bold scans are named as: `func_sub-<participant>_ses-<session>_task-<movie>_run-<seg>`

Stimuli can be found in: `stimuli/<movie>/<movie>_seg<seg>.mkv`
