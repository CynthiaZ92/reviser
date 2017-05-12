Reviser
=======

This repository contains the following artifacts:

- Test application and scripts for performance measurements
- The experimental results shown in the paper
- The technical report on Reviser

In order to use Reviser, you also need to check out the modified versions of Heros and Soot:

- https://github.com/StevenArzt/soot
- https://github.com/StevenArzt/heros

Note that we did not include the JUnit, Soot, and abc versions we ran Reviser on for space
reasons. The respective commit dates are available in the experimental data, such that you
can easily download them on your own.

# Build Tips: 

- Using eclipse will make the build more convenient and easier.
- Java Version: recommand 1.7 and below (avoid unnecessary trouble)
	Getting low version of Java: using 
		$ brew tap caskroom/versions
		$ brew cask install java7
- Need to modify junit test class in order to run test, including: sootcp(library location, jre location (1.7) and so on)
		
		
	
