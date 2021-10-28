# Approach:
Make hour, minute, second hand and adjust it at center to point at 12 in the clock </br>
Find the current time using JavaScript </br>
Use the formulas given below to rotate the hands according to the time </br></br>
# Formulas:
For hour hand, </br>
12 hr -> 360 deg </br>
1 hr -> 30 deg </br>
for h hour = 30h deg </br>
60 min -> 30 deg </br> 
1 min -> 1/2 deg </br> 
for m min -> m/2 deg </br> 
for h hour = (30h + m/2) deg -- (1)
</br> </br>
For minute hand, </br>
60 min -> 360 deg </br>
1 min -> 6 deg	</br>
m minutes -> 6m deg -- (2) 
</br></br>
For second hand, </br>
60 sec -> 360 deg </br>
1 sec -> 6 deg </br>
s seconds -> 6s deg -- (3)

<br />
Link to access: https://divyanshrai00.github.io/Analog-Clock/
