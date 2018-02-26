# Process Notes Module 2

**Goals:** Sonify data from the War of 1812.
*My model didn’t work out how I wanted so I decided to take data from the war of 1812 and then sonify it.*

**Step 1:** 
Collect data about the battle sites of the war of 1812.
I used the website www.warof1812.ca/battles.htm
I wrote down a list of battles and then googled each location.
This website had the titles and some of the locations. I used Wikipedia because it gave the actual location and then the latitude and longitude. I then google searched the latitude and longitude that way I could make sure it was accurate. I created a spreadsheet with all the information that way I could make sure it was accurate. 

**Step 2:** 
I began the next step which was to create a parameter map but in order to do this I needed to have coordinates with decimals. Therefore I had to convert the DMS coordinates (degree, minutes, seconds) to decimal degrees. I found a website that did this conversion for me. I double checked most of thee to make sure that the location was accurate. 

https://www.fcc.gov/media/radio/dms-decimal

I saved this information in Google Docs because I did not want to lose any information (yay for the cloud!)
I then found a website that could give me all this information (the decimal coordinate) so therefore I did not need to convert all the data. 

https://tools.wmflabs.org/geohack/geohack.php?pagename =Cooks_Mills,_Welland&params=42_59_47_N_79_10_44_W_region:CA-ON_type:city
 
When you click on a latitude/longitude in wikipedia it actually brings you to this website. It shows all the information about that location. 
I therefore just copy and pasted the decimal degree into the spreadsheet side by side with the battle location.

I used the first converter to double check that the decimal degree matched the first DMS coordinate (to prove that it was accurate).
It was accurate and therefore I kept using it. 

I then emailed the prof to confirm that all this information was accurate.

**Step 3:**

I followed step by step the information to then sonify this data.
https://github.com/shawngraham/hist3812w18/wiki/How-do-I-sonify-the-data-I-created-in-Module-1%3F

This step was the *longest* because it took me many different tries and combinations.

**Pitch Input**

For voice 1 I used the data from lines 1-13 (from the spread sheet) *I was able to use the negative numbers*
Because the coordinates had two numbers (because one for latitude and one for longitude) I actually had double the data then what I thought. 
Voice 2 was data from lines 14-24 and then voice 3 was data from 25-38.

*TOTAL NOTES in each voice*

Voice 1 -22 notes

Voice 2- 24 notes

Voice 3- 28 notes

Voice 1: 40.5084, 86.8417, 43.255278, -79.071667, 44.322083, 76.16986, 9.198206, 76.441497, 42.126111, -83.257222, 42.331389, -83.045833, 43.165, 79.055833, 45.083333, -73.366667, 45.083333, -73.366667, 42.942222, 78.926389, 41.913611, -83.378333

Voice 2: 44.7, -75.483333, 43.6525, -79.381667, 41.346111, -83.115278, 43.216667, -79.75, 43.1942, 79.5624, 36.834444, -76.341667, 43.1032256,-79.1833301, 42.2, 81.2, 42.566667, -81.883333, 43.95, 76.116667, 45.158548, -73.930860717,

Voice 3: 44.9432136,-75.0713357, 43.7348637,-76.1521046, 42.75, -81.7, 43.055833, -79.046944, 43.051667, -91.141389, 43.06, -79.106667, 45.861111, -84.630556, 43.941389, -80.091389, 38.941389, -76.93, 38.904722, -77.016389, 39.263056, -76.58, 44.695278, -73.458333, 42.996389, -79.178889, 29.945556, -89.96166722

**Pitch Mapping**

I set the range from 1-88

During my first attempt I left the data as the standard data that comes on the website. 
During my second attempt, I added the exact same data from voice 1’s pitch input into pitch mapping and the same for voice 2 and 3. 

Therefore the data looked like: 

Voice 1: 40.5084, 86.8417, 43.255278, -79.071667, 44.322083, 76.16986, 9.198206, 76.441497, 42.126111, -83.257222, 42.331389, -83.045833, 43.165, 79.055833, 45.083333, -73.366667, 45.083333, -73.366667, 42.942222, 78.926389, 41.913611, -83.378333

Voice 2: 44.7, -75.483333, 43.6525, -79.381667, 41.346111, -83.115278, 43.216667, -79.75, 43.1942, 79.5624, 36.834444, -76.341667, 43.1032256,-79.1833301, 42.2, 81.2, 42.566667, -81.883333, 43.95, 76.116667, 45.158548, -73.930860717,

Voice 3: 44.9432136,-75.0713357, 43.7348637,-76.1521046, 42.75, -81.7, 43.055833, -79.046944, 43.051667, -91.141389, 43.06, -79.106667, 45.861111, -84.630556, 43.941389, -80.091389, 38.941389, -76.93, 38.904722, -77.016389, 39.263056, -76.58, 44.695278, -73.458333, 42.996389, -79.178889, 29.945556, -89.96166722

I set the “mapping using” to division for all 3 voices.
I tried playing around between the three options but I did not notice a difference

**Duration Input**

For duration input I followed the same steps as before and inputted the same numbers. I kept the “input set” as custom.

Voice 1: 40.5084, 86.8417, 43.255278, -79.071667, 44.322083, 76.16986, 9.198206, 76.441497, 42.126111, -83.257222, 42.331389, -83.045833, 43.165, 79.055833, 45.083333, -73.366667, 45.083333, -73.366667, 42.942222, 78.926389, 41.913611, -83.378333

Voice 2: 44.7, -75.483333, 43.6525, -79.381667, 41.346111, -83.115278, 43.216667, -79.75, 43.1942, 79.5624, 36.834444, -76.341667, 43.1032256,-79.1833301, 42.2, 81.2, 42.566667, -81.883333, 43.95, 76.116667, 45.158548, -73.930860717,

Voice 3: 44.9432136,-75.0713357, 43.7348637,-76.1521046, 42.75, -81.7, 43.055833, -79.046944, 43.051667, -91.141389, 43.06, -79.106667, 45.861111, -84.630556, 43.941389, -80.091389, 38.941389, -76.93, 38.904722, -77.016389, 39.263056, -76.58, 44.695278, -73.458333, 42.996389, -79.178889, 29.945556, -89.96166722

**Duration Mapping**
For duration mapping I changed the range from 0-9 and then added the same data once again to this.

Voice 1: 40.5084, 86.8417, 43.255278, -79.071667, 44.322083, 76.16986, 9.198206, 76.441497, 42.126111, -83.257222, 42.331389, -83.045833, 43.165, 79.055833, 45.083333, -73.366667, 45.083333, -73.366667, 42.942222, 78.926389, 41.913611, -83.378333

Voice 2: 44.7, -75.483333, 43.6525, -79.381667, 41.346111, -83.115278, 43.216667, -79.75, 43.1942, 79.5624, 36.834444, -76.341667, 43.1032256,-79.1833301, 42.2, 81.2, 42.566667, -81.883333, 43.95, 76.116667, 45.158548, -73.930860717,

Voice 3: 44.9432136,-75.0713357, 43.7348637,-76.1521046, 42.75, -81.7, 43.055833, -79.046944, 43.051667, -91.141389, 43.06, -79.106667, 45.861111, -84.630556, 43.941389, -80.091389, 38.941389, -76.93, 38.904722, -77.016389, 39.263056, -76.58, 44.695278, -73.458333, 42.996389, -79.178889, 29.945556, -89.96166722


I left the scale the same. 

I then played it.
*it was garbage.*

I decided to try and change the instruments to make it sound somewhat better. I tried several different variations. 

**Attempt 1**

-Voice 1 piano

-Voice 2 piano

-Voice 3 piano

**Attempt 2**

-Voice 1- piano 

-Voice 2 -voice (oohs)

-Voice 3 -vibraphone

*this attempt still was not very long at all*

Decided to play with tempo.

Tempo at 27bmp

**Attempt 3**

-Voice 1 -synth drum

--Voice 2 -synth drum

-Voice 3 - vibraphone

Tempo 158bpm

**Attempt 4**

-Voice 1 synth strings

-Voice 2 synth strings

-Voice 3 synth strings

Tempo 158 bpm

**Attempt 5**

-Voice 1 synth strings

-Voice 2 synth strings

-Voice 3 marimba

Tempo 158 bpm

**Attempt 6**

-Voice 1 synth drum

-Voice 2 synth drum

- Voice 3 marimba 

***

I attempted to save this file and upload it to Garage band. But once in Garage band the instruments that I have picked are lost. 

The instruments translate to: 

-Steinway Grand Piano for voice 1, 

-Epic Cloud Formation for voice 2 and 

-Fingerstyle Bass for voice 3.

All the sound changes that I had made were essentially lost. 

I continued to work in Music Algorithms to try and change instruments and look for a better sounding instrument. 

Tempo 86
-Voice 1 synth drum

-Voice 2 synth drum

-Voice 3 marimba

***
-Voice 1 classical guitar

-Voice 2 piccolo

-Voice 3 bass

***
-Voice 1 harp

-Voice 2 piccolo

-Voice 3 bass

*this one was my favourite

*When you upload to garage band on a Mac it has standard instruments and does not let you change them*


I went back and tried to change the duration mapping information (“mapping using”)
Voice 1 modulo
Voice 2 division
Voice 3 logarithmic

Still nothing worked.

I change the range to 0-8

I changed the instruments again

-Voice 1 harp
-Voice 2 piccolo
-Voice 3 woodblock
-Tempo 42

I then decide to download MuseScore (I thought I would be able to upload the music there but actually it just turns the music into music notes). 

I turned my computer off and the next day continued and when I came back I realized I had a tab open with Music Algorithms but it was the app version so it looked different from the website. I played around with the information and found a way to sonify it a lot better but I was unable to download the file from there. Thus, I added all the information back to the original website and ended up with this. 

***
# Final Data 
*In this file (Module2/Notes/ProcessNotes), there are screenshots with all the information in the proper sections. I have written in here but the images were easier to follow along. This data is all the information that soeone would need to inpuot into each section to get the exact same outcome that I did.*

## Pitch Input

**Voice 1**

Note Count: 22

Input Set Custom

Input: 40.5084, 86.8417, 43.255278, -79.071667, 44.322083, 76.16986, 9.198206, 76.441497, 42.126111, -83.257222, 42.331389, -83.045833, 43.165, 79.055833, 45.083333, -73.366667, 45.083333, -73.366667, 42.942222, 78.926389, 41.913611, -83.378333

**Voice 2**

Note Count: 24

Input Set Custom

Input: Voice 2: 44.7, -75.483333, 43.6525, -79.381667, 41.346111, -83.115278, 43.216667, -79.75, 43.1942, 79.5624, 36.834444, -76.341667, 43.1032256,-79.1833301, 42.2, 81.2, 42.566667, -81.883333, 43.95, 76.116667, 45.158548, -73.930860717,

**Voice 3**

Note Count: 24

Input Set Custom

Input: 44.9432136,-75.0713357, 43.7348637,-76.1521046, 42.75, -81.7, 43.055833, -79.046944, 43.051667, -91.141389, 43.06, -79.106667, 45.861111, -84.630556, 43.941389, -80.091389, 38.941389, -76.93, 38.904722, -77.016389, 39.263056, -76.58, 44.695278, -73.458333, 42.996389, -79.178889, 29.945556, -89.96166722

## Pitch Mapping

**Voice 1** 

Mapping Using: Logarithmic

Range 1-88

Output: 83,88,83,29,83,87,78,87,83,3,83,6,83,87,83,42,83,42,83,87,83,1

**Voice 2** 

Mapping Using: Logarithmic

Range 1-88

Output: 76,79,82,84,85,86,87,88,88,88,87,87,86,84,82,80,77,74,70,65,58,50,35,1

**Voice 3** 

Mapping Using: Logarithmic

Range 1-88

Output: 88,51,88,50,88,42,88,46,88,1,88,46,88,37,88,45,87,49,87,49,87,49,88,53,88,46,86,15

## Duration Input

**Voice 1**

Input Set: Custom

Input: 40.5084, 86.8417, 43.255278, -79.071667, 44.322083, 76.16986, 9.198206, 76.441497, 42.126111, -83.257222, 42.331389, -83.045833, 43.165, 79.055833, 45.083333, -73.366667, 45.083333, -73.366667, 42.942222, 78.926389, 41.913611, -83.378333

**Voice 2**

Input Set: Custom

Input: 44.7, -75.483333, 43.6525, -79.381667, 41.346111, -83.115278, 43.216667, -79.75, 43.1942, 79.5624, 36.834444, -76.341667, 43.1032256,-79.1833301, 42.2, 81.2, 42.566667, -81.883333, 43.95, 76.116667, 45.158548, -73.930860717,1,1

**Voice 3**

Input Set: Custom

Input: 44.9432136,-75.0713357, 43.7348637,-76.1521046, 42.75, -81.7, 43.055833, -79.046944, 43.051667, -91.141389, 43.06, -79.106667, 45.861111, -84.630556, 43.941389, -80.091389, 38.941389, -76.93, 38.904722, -77.016389, 39.263056, -76.58, 44.695278, -73.458333, 42.996389, -79.178889, 29.945556, -89.961667

## Duration Mapping

**Voice 1**

Mapping Using: Logarthimic 

Range: 0-6

Output: 6,6,6,2,6,6,5,6,6,0,6,0,6,6,6,3,6,3,6,6,6,0

**Voice 2**

Mapping Using: Logarthimic 

Range: 0-6

Output: 6,3,6,2,6,0,6,2,6,6,6,2,6,2,6,6,6,1,6,6,6,3,5,5

**Voice 3**

Mapping Using: Logarthimic 

Range: 0-6

Output: 6,3,6,3,6,3,6,3,6,0,6,3,6,2,6,3,6,3,6,3,6,3,6,4,6,3,6,1

## Scale Option

**Voice 1**

Scale by: Whole Tone

Key: C#/Db

Output: 83,87,83,29,83,87,79,87,83,3,83,7,83,87,83,43,83,43,83,87,83,1

**Voice 2**

Scale by: Whole Tone

Key: C#/Db

Output: 77,79,83,85,85,87,87,87,87,87,87,87,87,85,83,81,77,75,71,65,59,51,35,1

**Voice 3**

Scale by: Whole Tone

Key: C#/Db

Output: 87,51,87,51,87,43,87,47,87,1,87,47,87,37,87,45,87,49,87,49,87,49,87,53,87,47,87,15

## Play

Tempo: 40bpm

*If this data is all entered correctly then all the information will display the same information and the music will sound the same as what I have created*

***

I then wanted to work with this file in Garage band but it was not working. I converted the file from MIDI to an MP3 using https://www.zamzar.com/uploadComplete.php?convertFile=mid&to=mp3

I then emailed the link to myself and opened it on an Ipad. I followed this guide on how to upload iCloud files to Garage Band. https://midnightmusic.com.au/2016/10/how-to-import-audio-files-into-garageband-for-ipad/

Then, I added the track twice. The first time without edits (tempo 158), the second time the same track (that was a tempo of 158) and the third time a tempo of 102. I then used Garage Band’s FX feature and created the “DJ-like” sound affects that appear 10 seconds into the song. 

***It did not turn out as long as I would have liked but it did work and that is the most important part.***





