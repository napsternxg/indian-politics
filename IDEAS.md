# Ideas


## Keep track of changes in major indian official political websites via Wayback machine
* List of major indian websites: https://www.india.gov.in/my-government/whos-who/mlasmlcs


## Create a dataset of Indian politicians with their social media and campaign handles
* Follow the format of https://github.com/unitedstates/congress-legislators
* Get list of current MLA and MP
* For cabinet and government ministers use: https://www.india.gov.in/my-government/whos-who/council-ministers

```js
/**
Get the links to social media accounts of all ministers via this JS code on that page
We need to filter out generic pages. 
*/

$(".view-content td a")


```


## Generate a name gender database using MLA information
* https://www.india.gov.in/my-government/indian-parliament/lok-sabha
* For each MLA (LS and RS) we get their name, father, mother, and spouse name. 
* We also get their image
* Each name is prefixed with Mr. , Smt. Kumari, Shri, etc. 
* We can process these to get a dataset of names and their genders
* We also get name of their state/constituency and hence can infer the regional origins of their names. 
