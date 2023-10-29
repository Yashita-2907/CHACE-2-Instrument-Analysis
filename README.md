 CHACE-2-Instrument-Analysis
 Lets start of with the very basics: What is CHACE-2?
 CHASE-2 is one of the several observation instruments onboard India’s second mission to the moon, Chandrayaan-2.
 CHandra’s Atmospheric Composition Explorer-2 (CHACE-2), is a quadrupole mass spectrometer on board Chandrayaan 2 orbiter. Its objective is to study the composition of the Lunar Atmosphere and find the relative abundance of compounds like water vapour, hydrogen, nitrogen etc. along with its proportions. In other words, study the pristine lunar exosphere.

#PROBLEM STATEMENT:

•	While sending instruments into deep space, These instruments will encounter various conditions that are drastically different from ones experienced within the earth’s atmosphere.
•	 It is important to know how they will behave under these various operating conditions. 
•	Electronics Temperature is one of the most important factors to consider as the instrument will not function properly if it gets too hot or cold. 
•	Furthermore, operating outside its temperature range could result in a decrease in the lifespan of the instrument.
•	Therefore, it is vital to know in advance the thermodynamic response of the onboard electronics to the various conditions it encounters in deep space. 
Therefore our main objectives in this project is 
•	Understanding how various environmental and operating conditions affect the temperature of an instrument.
•	Demonstrating the use of Machine Learning and Statistical Modelling to predict the thermodynamic behavior of the instruments providing useful data for future missions.

DATASET DESCRIPTION:

•	The dataset that we have chosen to work with today is from ISRO(Indian Space Research Organization).
•	 ISRO has made a lot of research data available on its website. Though it has made its data public, one has to go through a verification process to access any of the datasets uploaded on ISRO’s data science website.
•	It has about 11 rows and 33,509 rows. It has variables like UTC time (Universal Coordinated Time), SR1 Current, SR2 Current, RF Amplitude, Focus1, Focus 2, Filament Current, Filament Voltage, Electronics Temperature, Total Pressure and Power Supply.
•	The data is taken from the Indian Space Science Data Centre (ISSDC) website, where CSV’s of size ranging from ~50-300 rows are available for download. 
•	We then downloaded 100 CSV’s and concatenated them to form the final dataset we will be operating on containing 33,509 rows.




