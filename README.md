**Data Title:** Svoboda Diaries Diary Transcriptions and Cargo Data -- ASIS&T "Exploring Collaborative Interpretive Practice" Workshop Version   
**Contact:** Annie T. Chen <atchen@uw.edu>, Camille Cole <clcole5@ilstu.edu> 

## Overview:

The Joseph Mathia Svoboda diaries capture over 40 years of trade on the Tigris, life, politics, and the landscape of Ottoman Iraq through the perspective of a British steamship purser with a rich family history and local connections. Of the 49 JMS diaries that we have in our collection, 3 have been published on the website (https://svobodadiariesproject.org/), with more in progress. Unfortunately, not all of the Joseph’s diaries have survived, and some of those which have are in poor shape.

The published versions of the three diaries (volumes 47-49) are available here: https://www.svobodadiariesproject.org/svoboda-diaries-data/.

## Data and files:

#### annotatable_entries folder: 

This folder contains plain text versions of each day entry in diaries 47-49 of the Svoboda diaries. These files were created by automatically parsing the plain text versions of the diaries into days, and then correcting errors introduced during both the transcription and parsing processes through manual review involving multiple reviewers, in comparison with the original diary images. Within this folder are three folders, "47", "48", and "49", which in turn contain files containing each day entry as follows:

FileID_Year_Month_Day_DayOfTheWeek.txt

The FileID were derived by numbering consecutively from the first day entry of the day starting from 1.

The original diary images are available: https://www.svobodadiariesproject.org/ and https://digitalcollections.lib.washington.edu/digital/collection/iraqdiaries/search.

#### ship_info folder:

This folder contains information about passengers and cargo that was transported by the Euphrates & Tigris Steam Navigation Co. on the ship that Joseph Svoboda served on during the years 1865-1892. This information was manually extracted from typed transcriptions of diaries 4, 7, 8, 9, 11, 12-15, and 17-36, which were transcribed by Margaret Makiya in the 1960s, and are available through the University of Washington library. Diaries 9 and 11 are available only in partial transcription. 

The data set includes every mention of an item that was either loaded, unloaded, or towed (in the case of other boats) by Joseph’s steamship. Where Joseph records a specific amount for a cargo item, that was also noted, as was the generic notation “cargo” or “packages” when he does not specify what kind of cargo was on- or off-loaded. It also notes passengers who embarked and disembarked the ship. Where Joseph noted that passengers boarded or left, but did not record their numbers, this is recorded using the generic notation "yes."

##### cargo.csv variables:

date: date of stop, yyyy-mm-dd    	  
city: location stopped at    
cargo on y/n: cargo (packages or goods) were on-loaded: 1 for yes, 0 for no    	   
cargo off y/n: cargo (packages or goods) were off-loaded: 1 for yes, 0 for no    
packages on #: number of packages on-loaded    	  
packages off #: number of packages off-loaded    
goods-on name: goods that were on-loaded, often along with their amounts    
goods-off name: goods that were off-loaded, often along with their amounts    

##### passengers.csv variables:

date: date of stop, yyyy-mm-dd   	  
city: location stopped at    	  
pass-on y/n: passengers on: 1 for yes, 0 for no    	    
pass-off y/n: passengers off: 1 for yes, 0 for no      
pass-on #: number of passengers who came on        
trip total passengers: total number of passengers that trip  
pass-off #: number of passengers off      
notes: other notes; "1C" indicates first-class cabin; "2C" indicates second-class cabin    

## License:

This work is distributed under an Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license (https://creativecommons.org/licenses/by-nc/4.0/). Users are able to copy and redistribute the material in a non-commercial context, in any medium or form, and remix, transform, and build upon the material as long as they credit the investigator and indicate if changes were made.





