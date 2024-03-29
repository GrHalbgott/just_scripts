# Just_Scripts

This repository functions as a collection of some helpful and not so helpful but funny small scripts regarding everything from administration/organisation over calculation in GIS and statistics to simply funny stuff.

## Stuff 

<details>
  <summary><b>whisper_transcribe (Python): Transcription using Whisper AI</b></summary>
<br>  

This small script queries OpenAI's Whisper AI and writes the response to file. <br/>
Automated transcription!
  
</details>

<details>
  <summary><b>random_pwd (Python): Generate a random password</b></summary>
<br>  

This script generates a random password for you by using different characters (letters, digits, punctuation). <br/>
The small commandline-tool even talks to you if you put in wrong answers!
  
</details>

<details>
  <summary><b>worktime_calculator (C++): Calculate weirdly unuseful worktimes</b></summary>
<br>  

You can calculate how long a large task consisting of multiple tasks will need to be accomplished depending on helping hands, number of smaller tasks and how much time a small task takes up. Will this ever be useful to anyone?
  
</details>

<details>
  <summary><b>datediff_calculator (Python): Calculate differences between two dates</b></summary>
<br>  

This script can calculate the difference between two dates in multiple time units. Interactive.
  
</details>

<details>
  <summary><b>midi_length_sum (Python): Sum up the length of multiple midi files</b></summary>
<br>  

Well it does what it says. Sums up the seconds and coverts them to a readable time format.
  
</details>


## GIS scripts

<details>
  <summary><b>ohsome_landuse (Batch): Download landuse OSM data from the ohsome-API</b></summary>
<br>  

With the help of this script you can download multiple landuse files at once. <br/>
If you want to adapt it to your application, you should  change the bounding box, the time and the name of the output files (line 2, 3 and 5 of each block). 

</details>

<details>
  <summary><b>roi_extractor (Batch/GDAL): Extract region of interest from GADM (Germany) dataset</b></summary>
<br>

Your input (region) is handled like a variable and gets implemented in the command. By changing "DEU" in the command to your country of interest, you can use the command for every region in the world.<br/>
GADM datasets are found under https://gadm.org/download_country.html.<br/>
This can be implemented for example in a clip operation (next one).

</details>

<details>
  <summary><b>clip (Batch/GDAL): Clip a raster with a shapefile</b></summary>
<br>  

Well it does what it says.
  
</details>

<details>
  <summary><b>dem_diff (Python): Calculate difference between two raster images</b></summary>
<br>  

If you have two raster images of the same area but during different times, you can use this script to calculate the differences between them. <br/>
Adapting it to your application works by chaning paths and file names.

</details>

<details>
  <summary><b>query_ohsome_api (Python): Query OSM data using Ohsome API for a list of aois</b></summary>
<br>  

This python script is the basic template to query OSM data using the Ohsome API. You can specify the list of aois, the filters and the time.

</details>