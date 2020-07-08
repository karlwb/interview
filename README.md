#### Rules

* Use any language you want.
* Open Book/Internet
* Don't worry about writing tests or validating input. There are no tricks. 
* You can, but don't have to use any external libraries.
* Up to 30 minutes

#### Initial task

* There is a problem with my CSV file (data.csv) which has information about cars.
* Fields in the file are (in order): `model`, `location`, `year`, `VIN`, `make`
* 'Cayman' `model`s 2007 and greater need some modifications:  
  * In the `VIN` field, replace all U with an S
  * The `location` needs to change from 'Chicago' to 'St. Louis', but only if the `VIN` ends with 00001.
  * Print to the screen any changed lines.


#### Modification 1 - Only complete after Initial task

* I also have a TAB delimited file (data.tsv) with the same problem.  The data is otherwise the same. Please make your
  code optionally take CSV or TAB delimited file as input.

#### Modification 2 - Only complete after modification 1

* Optionally print the output lines in comma or tab delimited format, independent of input format.

#### Modification 3 - Only complete after modification 2

* Sort the output by VIN ascending.

