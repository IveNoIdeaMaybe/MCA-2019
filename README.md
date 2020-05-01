# Music Curation and Analysis
## Jazz and Thomas 'Fats' Waller 

### A lab portfolio by Ryan Shaw 

## Week 1 

The theme of my dataset is Jazz music, more specifically Thomas “fats Waller. The innovator of the Harlem stride style he laid the groundwork for modern jazz piano. Other than the piano he was a proficient violinist, organ player and singer. Two of his most well known compositions “aint misbehavin” and “honeysuckle rose” have been inducted into the Grammy Hall of Fame. Fats copyrighted over 400 compositions before his death in 1943, more than 10 copyrighted compositions for every year he lived.  I have chosen jazz and more specifically fats for my dataset as the music is one of the most unpredictable and difficult to play. The complicated scores will be interesting to encode and might shine a light upon shortcomings of digital systems when dealing with such a varied and deep genre. <br>

## Notated data </strong><br> 
There is quite a lot of notated data for my chosen topic, however as many of jazz’ pioneers and innovators were not classically trained they would often play instruments in a way that was difficult to express on sheet paper therefore there were many new additions made due to the new style played by theses musicians. 

## Acoustic data </strong><br>
There is a plethora of acoustic data that can be found on all the major streaming services and on physical representations, cd’s etc. However jazz is quite a bit more rare today than half a century ago and therefore recordings are much more prevalent than real life interaction. 

## Descriptive data </strong> <br>
Since Fats Waller was such an innovator there is widespread descriptive data on him and his work. Not to mention the two compositions that are in theGrammy Hall of Fame there are full in depth biographies on websites such as the encyclopedia britannica. There is a lot of information on the multiple biographies and studies into the life and accomplishments of Fats Waller including who he worked with and influenced. This kind of data lends itself to being able to create a playlist of similar artists of the time. However mostly because of the time he was active the best information we can get is from the original recordings and packaging which includes information such as who he worked with on the piece. Furthermore because it is a somewhat a specific genre there are plenty of compilations of artists which were made before the digital age but readily create a profile of Fats by who he is commonly placed with. A product of the time his recordings are not compiled into albums but limited to vinyl records therefore there is a hard stop on how long a piece could be. Modern efforts have digitised his more popular works into best of’s etc.


# Week 2: Notated Music 

Here i have uploaded a a MuseScore file containing 21 bars of Fats Waller's <a href="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/effervescent%20.mscz">
<i>Effervescent </i> </a> 

version of Effervescent  by Fats Waller. I found this sheet 
music on a compilation called <i>Rhythmic Piano solos</i>.The source that I used is linked
<a href="https://imslp.org/wiki/Effervescent_(Waller%2C_Fats)"> here
 </a>
 

# Week 3: Encoding notates music 

<a href="https://ivenoideamaybe.github.io/MCA-2019/verovio.html"> Here </a>
is my encoded version of <i> Effervescent </i> after it has been 
transformed into an MEI file through Verovio.


# Week 4: Basic Analytics 

## Generating data with jSymbolic

|description   |Value   |         
|---|---|
|Number of Pitches   |37   |     
|  Number of Pitch classes  |   12|  
|   Range|   57| 
|   Strong Tonal centres|   2|
| Mean Pitch  |65|
|Mean Pitch Class|4.958|
|Most Common Pitch|65|
|Most Common Pitch class|5|
|Interval between most prevalent pitches|7|
|Pitch variability|11.32|
|Most Common Melodic Interval|2|

These are rather abstract in terms of understanding exactly what they are referring too therefore in the efforts of keeping a clean table i will list definitions below in the order they are shown above:

**Number of Pitches**: The number of unique pitches which occur at least once in the piece.

**Number of Pitch classes**: The nunmber of pitch classes which occur at least once in the piece.

**Range**: Difference in semitones between the highest and lowest pitches.

**Strong Tonal centres**: Number of isolated peaks in the fifths pitch histogram.

**Mean Pitch**: Mean MIDI pitch value, averaged out across all outched notes in the piece. Set to 0 if there are no pitches notes.

**Mean Pitch class**: mean The pitch class that occurs most frequently compared to other pitch classes. A value of 0 corresponds to C, and pitches increase chromatically by semitone in integer units.

**Most Common Pitch**: MIDI pitch value of the most frequently occurring pitch.

**Most Common Pitch class**: The pitch class that occurs most frequently compared to other pitch classes. A value of 0 corresponds to C, and pitches increase chromatically by semitone in integer untis.

**Interval between Most Prevalent Pitches**: Absolute value of the difference (in semitones) between the pitches of the two most frequently occurring pitches.

**Pitch variability**: Standard deviation of the MIDI pitches of all pitched notes in the piece. Provides a measure of how close the pitches as a whole are to the mean pitch.

**Most Common Melodic Interval**: Number of semitones corresponding to the most frequently occurring melodic interval.

You can access the MIDI file used <a href="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/effervescent%20.mid"> here 
 </a>

### Task 2 

**Pianoroll**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/pianoroll.png" alt="Piano roll" style="width:500px;height:500px;">

Here the Piano roll shows the length and pitch of the notes against time showing trends towards high points and low points and how they 
are typically gradually worked towards. Interestingly it does not look as if F is far and beyond the most played note but looking at the histogram adds this information. 

**Histogram**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/histogram.png" alt="Histogram" style="width:500px;height:500px;">

Here without time playing a factor we can see more clearly the most popular notes and chords of the piece. in Conjunction with the jSymbolic most common pitch being 65, this is equivalent to the F4 shown here to be nearly doubly as frequent as all other notes excluding three. Also the compressed nature of the most played notes aligns with the small number of only 2 strong tonal centers. 

**Scattergraph**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/scatter.png" style="width:500px;height:500px;">

This is my favourite dataset visualisation as it shows the nature of Jazz music most clearly. The old style time signiture of 2/2 promotes fast playing and this is what we see here. With a strong trend of high pitch notes being played fast envoking excitement coupled with the relatively slow whole beats at a lower pitch gradually making the tone more serious right before it jumps back up to the higher registers. 

# Week5 
<b>
 
* Title 
* Composer 
* Genre 
* Encoder 
* Date of encoding 
* Availability/Copyright 
* Original publisher 
* Date of publication 
* Location of publication 
* Source 
</b>

Here linked is the mei file for <a href="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/eff.mei">
 <i>Effervescent </i> with this scheema applied</a> however I have forgone the genre signifier as ive encluded it in a subtitle 
 because it is such an integral part of the piece.


# Week 7 Curation Challenges 

I have not changed the mei file a massive amount from last week as I included all of the information that 
I believe is neccisary or that i could find solid proof for. For example I could not find the full book information 
which the piece is republished in however I have included a link to the url in the html. Furthermore I have no included the 
extent or duration of the piece because what is presented is not the whole work. so a duration timestamp would only be confusing. 
Mainly ive added css to get the layout of the page clear and concise. You can see this <a href="https://ivenoideamaybe.github.io/MCA-2019/myMeta.html"> webpage here </a> with
the piece on show through Verovio as well as all of the information stated above, and some more within the code. 




# Week 8 Music as Sound 

## Task 1 

present the three chosen songs and relative metadata in a table 


**Table** 

|Artist |Title |Album |Genre | Year released  |Source |Copyright |Format|Kbps|Sample rate (Hz)|Duration (minutes)|
|-------|------|------|------|---------------|------|-----------|------|----|----------------|------------------|
|Scott Holmes |Upbeat Party | Inspiring and Upbeat Music |Pop, Soundtrack, Indie-Rock |2019 |<a href="http://freemusicarchive.org/music/Scott_Holmes/Inspiring__Upbeat_Music/Scott_Holmes_-_Upbeat_Party">The Free Music Archive</a> | CC BY-NC 4.0 |mp3 |320 |44100 | 2:24 |
|K.I.R.K |Yoga | 825 Literature	 |Hip-Hop, Spoken Word	 |2018 |<a href="https://freemusicarchive.org/music/Jay_Kirk/825_Literature/yoga_master">The Free Music Archive</a> | CC BY-NC-ND 4.0	 |mp3 |320 |44100 | 2:38 |
|Ketsa |Enclosed | Raising frequency |Soundtrack, Ambient Electronic, Downtempo, Instrumental |2019 |<a href="https://freemusicarchive.org/music/Ketsa/Raising_Frequecy/Enclosed">The Free Music Archive</a> | CC BY-NC-ND 4.0	 |mp3 |192 |44100 | 3:31 |




### Task 2 

here are the respective wavelenghts and spectograms of my three songs - this is just a section, you can click on them to see the
full waveform/spectogram. 

**Scott Holmes**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/upbeatsmallwave.png" style="width:500px;height:300px;">
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/upbeatsmallspecto.png" style="width:500px;height:300px;">

**K.I.R.K**

<a href="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirkwave.png"> 
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirksmallwave.png" style="width:500px;height:300px;"> </a>

<a href="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirkspecto.png"> 
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirksmallspecto.png" style="width:500px;height:300px;"> </a>


**Ketsa**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/ketsasmallwave.png" style="width:500px;height:300px;">
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/ketsasmallspecto.png" style="width:500px;height:300px;">

### Task 2.2

A lot of the time looking at computational analysis is difficult to read because we have no context however by seeing the waveform and spectogram side by side we are able to understand what each is telling us with a much better comprehension. By using a spectrogram (with log spaced frequency spectogram it illuminates the specific keys or notes that are being used or hit, we can see this much more clearly in Ketsa's piece as it is predominantly electronic whereas the differentiations are not as clear with K.I.R.K's song as it is more vocal and so there is a lot more noise essentially rather than pinpointing keys capable through a computer 

# Week 9: Extracting Meaning from Audio


## Task 1: Extract features 

#### For this week we had to transform three songs to analyse them in a different way. Ive used the same songs from last week, from top to bottom the visualisations are ordered: Spectrogram, Mel Frequency Cepstral Coefficients and Chromgrams. 

**Scott Holmes**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/upbeatweek9.png" style="width:500px;height:500px;">

**K.I.R.K**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/kirkweek9.png" style="width:500px;height:500px;">

**Ketsa**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/ketsaweek9.png" style="width:500px;height:500px;">

## Task 2: Computing and visualising histograms

### Task 2.1: presenting histograms

#### Histograms from spectograms


|Scott Holmes          |  K.I.R.K                  |    Ketsa         |
|---------------------|-------------------------|----------------|
![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/upbeatspectohist.png) |![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/kirkspectohist.png )|![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/Ketsaspectohist.png )|

### Histograms computed from chromagrams
 
|Scott Holmes          |  K.I.R.K                  |    Ketsa         |
|---------------------|-------------------------|----------------|
![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/upbeatchronohist.png) |![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/kirkschronohist.png )|![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/Ketsaschronohist.png )|

### Histograms computed from MFCCs
 
|Scott Holmes          |  K.I.R.K                  |    Ketsa         |
|---------------------|-------------------------|----------------|
![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/upbeatmelhisto.png) |![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/kirksmelhist.png)|![](https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week9/Ketsamelhist.png)|

## Task 2.2 Comparing the histograms

#### I am going to compare the MFCCs from each song. Ive chosen to compare the mel frequency cepstral coefficient histograms because they are strikingly similar and this is not to be expected. Nevertheless it is the slightness of differences which represent a lot which is interesting. with MFCCs recording tone quality or character. This has made MFCC's very popular in speech recognition software. Something further strange is that no two of my songs are similar but each join up in different windows. Such as Scott Holmes and Ketsa in the first window whilst K.I.R.K and Ketsa are more alike on the 16th window. I believe this is because they all contain a variation of instruments and vocals meaning at certain points they are more akin. Particularly the 5th and 18th window are quite unique between the three. 

# Week 10 

## task 1  Similarity in Python

<img align="right" width="700" height="700" src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week10/matrix.png">



--- 
## task 2 Transcription in MuseScore and SonicVisualizer

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week10/week10notated.png" style="width:200px;height:200px;">

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/week10/week10midi.png" style="width:200px;height:200px;">






