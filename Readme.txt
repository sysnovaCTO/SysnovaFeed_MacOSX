Installation Procedure :

Install JDK version 1.7 or higher (if not installed) .
You can download and install jdk from here : http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
After installion you can check java version from terminal by typing  “java -version” command.
Open terminal and install Homebrew through this command :
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
Next install GLPK from terminal by typing  : brew install glpk
Copy all library file from link_library folder to /usr/lib/ and  /System/Library/Java/Extensions/
Copy feedDatabase.h2.db file to $HOME (/Users/Username/)

For running the software  :
	In order to run the software , open terminal > go to the directory of the  software and
	run this comand ./run.sh
