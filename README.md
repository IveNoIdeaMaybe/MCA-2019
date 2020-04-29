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

### Task 2 

here are the respective wavelenghts and spectograms of my three songs - this is just a section, you can click on them to see the
full waveform/spectogram. 

**Upbeat Party**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/upbeatsmallwave.png" style="width:500px;height:300px;">
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/upbeatsmallspecto.png" style="width:500px;height:300px;">

**KIRK**

<a href="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirkwave.png"> 
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirksmallwave.png" style="width:500px;height:300px;"> </a>

<a href="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirkspecto.png"> 
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/kirksmallspecto.png" style="width:500px;height:300px;"> </a>



**Ketsa**

<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/ketsasmallwave.png" style="width:500px;height:300px;">
<img src="https://github.com/IveNoIdeaMaybe/MCA-2019/blob/master/data/ketsasmallspecto.png" style="width:500px;height:300px;">


























