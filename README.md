# webcalc-frontend
A container that contains some dynamic HTML and JavaScript that implements the calculator.
Calculations are exectued by XMLHttpRequest in Javascript to one of the worker(other maths functions) services.
Added validation for json response, error handling, urls and paths to other mathematical functions load in dynamically, added async await.
Proxy urls are tried and removed from available list of urls for calculator, if found to be dead links. 
Includes Dockerfile

