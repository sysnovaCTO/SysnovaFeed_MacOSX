# SysnovaFeed_MacOSX

# SysnovaFeed is a revolutionary free/open-source least-cost feed formulation software by Sysnova Information Systems Limited.

### Installation:
In order for SysnovaFeed to run,
* Install JDK version 1.7 or higher (if not installed) . 
  You can download and install jdk from here : http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html . 
  After installion you can check java version from terminal by typing “java -version” command.
* Open terminal and install Homebrew through this command : ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
* Next install GLPK from terminal by typing : brew install glpk
* Copy all library file from link_library folder to /usr/lib/ and /System/Library/Java/Extensions/
* Copy feedDatabase.h2.db file to $HOME (/Users/Username/)


### Note:
* SysnovaFeed software is a comprehensive free/open-source tool designed to meet the formulation needs of professional nutritionists and feed producers.
* The free/open-source nature of SysnovaFeed also makes it ideal for use in academic institutions and universities.
* SysnovaFeed is user-friendly and simple to download and set up on any desktop or laptop computer.
* SysnovaFeed is customizable and easily allows any nutritionist to enter unlimited numbers of ingredients and formulations.
* SysnovaFeed aims to bring benefits of the free/open-source software movement to the global livestock industry.

### Functional Features:
* Ingredients: SysnovaFeed contains a default nutritional database for major ingredients like maize/corn, wheat, wheat bran, rice, rice bran, soybean
  meal and soybean oil based on well-established USDA (United States Department of Agriculture) nutritional specifications. Users can edit these nutritional
  specifications and add unlimited ingredients.
* Formulations: SysnovaFeed contains default formulations for well-known breeds of commercial layers based on published nutritional standards of 
  breeding companies. Users can edit these formulations and add unlimited new formulations.
* Prices: SysnovaFeed comes with a default set of prices which the user can update to reflect current market rates.

### Technical Features :
----------------------
* SysnovaFeed desktop formulation software is released under an open-source license which means it will never require any license fee.
  SysnovaFeed formulation software has been developed in Java programming language, which supports all computer operating systems (MS Windows, Mac and Linux).
  An Android app will also be released in future.
  All formulation, ingredient and price data is stored in free/open-source H2 database, which is also written in Java and will work in any platform.
  Least-cost optimization is done by free/open-source Gnu Linear Programming Kit (https://www.gnu.org/software/glpk/).
* SysnovaFeed desktop formulation software is released under an open-source license which means it will never require any license fee.
* SysnovaFeed formulation software has been developed in Java programming language, which supports all computer operating systems (MS Windows, Mac and Linux).
* An Android app will also be released in future.
* All formulation, ingredient and price data is stored in free/open-source H2 database, which is also written in Java and will work in any platform.
* Commercial Web-Based Version: A web-based multi-user collaborative version of SysnovaFeed will be released as a commercial product for purchase by large 
  companies with multiple feed mills and nutritionists. 

### References
   -----------

1. Meat & Bone Meal, Distillers Dried Grains Soluble (DDGS), Soybean meal, wheat flour, Wheat Bran & Rice polish values from-
	 Nutrient Requirements of poultry: Ninth Revised Edition, 1994
	 Subcommittee on Poultry Nutrition, NRC
	 ISBN: 0-309-59632-7, 8.5x11, (1994) 
	 https://www.nap.edu/catalog/2114/nutrient-requirements-of-poultry-ninth-revised-edition-1994
	 https://www.nap.edu/read/2114/chapter/1
   
2. Corn, Whole wheat, canola meal, rapeseed meal, corn gluten meal (CGM) value from-
	 Commercial Poultry Nutrition Book, 3rd Edition, S. Leeson & J. D. Summers.
   
3. For all micro ingredients used manufacturer recommended values. 

4. Free/open-source Gnu Linear Programming Kit 
	 https://www.gnu.org/software/glpk/
   
5. h2 database
	 www.h2database.com

