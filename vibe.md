# Intention
A bandwidth calculator

# GUI & Workflow
There are 3 fields on the screen, next to each field there is a dropdown for units displayed

- Size field, default is 1. The unit drop down allows to choose between MB,GB,TB,PB.  Default dropdown is MB
- Bandwidth field, default is 1. The unit drop down allows to choose between Mbps,Gbps.  Default dropdown is Mbps
- Time field, default is not set. The unit drop down allows to choose between Seconds, Minutes, Hours, Days. Default dropdown is Hours

2 fields are required to calculate the third field.  As all fields have a default, as soon as the application starts immidiatly calculate the time required based on the defaults (do not hardcode this)
once any of the 3 fields, or one of the units is changed by the end user, recalculate.

Use Microsoft design standards

# Tecnical
Use a client side language like javascript css and HTML.  Do no require external dependecies or libraries.  I want to open the file in my browser and it should work immidiatly and fast.  I don't want to compile anything.  Store everything in 1 file, even if this is at the cost of a nicer GUI.  one file is a mandatory requirement

Use an appropriate amount of comments in the code so that a junior developer immidiatly understand whats happening
