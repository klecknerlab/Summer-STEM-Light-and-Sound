Our course is divided into 4 periods per day; each is roughly 75 minutes, and there are snack breaks and/or lunch in between them.  The activities for each day are in sub-folders labelled with the day (number) and session (letter).  The lab activities typically take 2-3 periods.  On days 1-2 we intersperse the lab activities with written worksheets on units and scientific notation, which they need for the speed of light.

Note that in practice the previous day's activities often bleed into the next day.  For example, when we taught this in 2023, they spent the first half of day 4 finishing day 3's worksheet, and didn't finish the speed of light competition until the middle of the last day.  This is fine -- we recommend encouraging the students to finish things on their terms rather than force it.  If they are enjoying the experience and learning things, we consider this a success!

## Day 1

The first day begins with the "This or That" exercise and intro presentation.  We have found this is a good ice breaker, and we finish the first session with a short intro presentation.  If you finish early you can start the first video on the oscilloscopes.

The second session starts with a oscilloscope worksheet that also involves watching a few youTube videos.  Originally we did this as an entire class, but in 2023 we had access to a room where each group has their own computer.  In this case we let the groups move at their own pace and watch (and/or rewind) the videos on their own.

The students should not have finished the oscilloscope worksheet by the end of the second session, but we switch gears for the third session to a units worksheet.  We've found that this works well because they will have now encountered things like nanoseconds, and this typically motivates them to learn more about what this actually means.

We use the fourth session to finish the oscilloscope worksheet.  They typically get through most, but not all of it.

## Day 2

Day 2 is dedicated to measuring the speed of sound using ultrasonic transducers.  We typically start the day by finishing up yesterday's worksheet and then countinuing with the new labs.

> **Note**: if the ultrasonic transducers are too close the groups will interfere with each other.  This usually shows up as beating, since the frequencies of the function generators will be slightly off.

## Day 3

I started with a class exercise to measure the speed of light with a laser pointer.  One pushed the button on the laser pointer and simultaneously started a stopwatch -- the second stopped the stopwatch with a separate button when they saw the light at the end of a long hallway ([stopwatch used](https://stopwatch.online-timers.com/online-stopwatch)).

Interestingly, we "corrected" the reaction time by doing a measurement with a nearby wall instead of a long hallway.  The difference (average of 5 measurements each) was around 60 ms!  (I believe this happens because when the light is closer/brighter you react a bit faster?)  Measuring the hallway resulted in a "speed of sound" of ~2 km/s. It's also quite possible they will obtain a negative speed of light, depending on error.  If you'd like, you can have several groups try this.  The idea is to illustrate two things: 1) you need to control for "reaction time" (also present with electronics!), and 2) the speed of light is really fast, and we need better tools.

After I had them watch a cool Veritasium video: 
https://www.youtube.com/watch?v=pTn6Ewhb27k

This is then followed by the worksheet, which guides them through using photodiodes, LEDs, and laser pointers, as well as measuring the speed of signals in BNC cables (which is about 2/3 the speed of light).  If they have time, they also get a chance to try out the [wavefit program](https://github.com/klecknerlab/wavefit).  If set up properly, this allows the students to find the time dealy between two sine waves by acquiring data through the oscilloscope.  Using this is essential to getting a good speed of light measurement.  (Note: this will probably get pushed to the next day for most groups.)

## Day 4

I start with a brief introduction of the goal of the day: measuring the speed of light, and introducing the competition to do so.  I also give a brief introduction to precision and accuracy, and note that their score will be based on both.  This is detalied in the worksheet for this day, but it is good to explain it as well.  They don't really need to understand the details, apart from the fact that they will be judged on the reproducibility and ultimate accuracy of their measurements.  (As with many things, the older students will get more from this, but that's ok!)

The rest of the morning is dedicated to finishing left over worksheet from day 3, including the `wavefit` examples.

Once this is complete, they can begin designing and executing measurements of the speed of light.  I generally let them try to figure out the best way to do it, although I try to guide them along as needed.  In particular one should pay attention to making sure they understand the difficulties in getting a good signal through the photodiode.  If they modulate too fast (typically 10 MHz or greater), interference may give a stronger signal than the actual light.  They can test this by blocking the photodiode, in which case they will see there is still a signal!  To alleviate this, they can work at lower frequencies and/or try to seperate the cables for the laser and photodiode as much as possible.  You should also be careful about making sure they have some sense of what changing the resistor in the photodiode circuit does.  A large value gives a stronger response, but a lower cutoff frequency.  If they oversaturate this can also distort the signal, which will give systematic error in the wavefit.  Generally the best results are with 100 Ω, but I don't tell them this outright.  (1 kΩ can also work quite well.)

## Day 5

The morning is dedicated to finishing the speed of light measurements, finishing before lunch.  Typically you should expect several percent accuracy and precision, although better results are possible it requires careful attention.  We then compiled their results over lunch (the scores are computed using an inculded spreadsheet).  While they are doing the afternoon activities, one of the instructors made award medals using a laser cutter, and they included each student's names (and the rest of their group), their actual measured speed of light, and a placing.  

The afternoon is used to make a measurement of the wavelength of light, done using diffraction off a ruler at shallow angle.  If done carefully, you should expect their error to be ~10-50 nm.  Make sure the rulers lay flat, as a slight bend can cause a large error due to the small angles!