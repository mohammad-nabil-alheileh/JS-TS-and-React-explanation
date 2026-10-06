its an effect to keep the outisde sync with the values in dependeny array 

dependeny array have 3 types :

- nothing : re run on every re-render

- empty array : runs once after the first render

- non empty array : runs once after the first render and whenever values in the array change 

we cleanup the use effect every time before re runing or unmounting 