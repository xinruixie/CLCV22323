# what's the difference between a variable, a parameter, and an argument?
A variable is a name/object that symbolically represents a value and stores it in memory. The value represented can be of various data types, such as a number, a string, a list, etc.
A parameter is a variable that is defined in the function signature, and it serves as the recipient of input values when the function is called. 
An argument is a specific value that is passed to a function when it is called, and it is assigned to the corresponding parameter within the function.
To give a concrete example, see the demo below: 
```
def cities(input):
  output = input + "is beautiful."
  return(output)

listcities = ["Chicago", "New York Cities", "Los Angeles", "Washington", "Las Vegas"]

for city in listcities:
    new = cities(city)
    print (new)
```
Here, "listcities", "output" and "new" are all variables; "input" is the parameter; and "city" is the argument passed in the "cities" function in the for loop, and those city names in listcities are actual values passed.

# Digital Tool Critique
## Pleiades
### permanence and sustainability
A  
The website is powered by plone & python, a fairly famous and reliable system. It also receives funds and supports offered by participating universities such as UNC and NYU, and grants (2006-2014) from the U.S. National Endowment for the Humanities. Besides, it is lead by a group of scholars to ensure regular updates and posts (most recent in Sep 25, 2023, very fresh).  
### openness or restriction of their data
A  
It uses the Creative Commons Attribution 3.0 License, which is a open data license. It also provides open API, so overall quite accessible. There is also a comphrehensive page about its various download forms and related items.
### functionality of their interface and interaction with their data
A  
Basically very clear and user-friendly. The website has many intuitive visualization tools such as the map, and the search bar， participate， and help section are also easy to find to ensure smooth interaction. Categorization looks also fine. However, if you want to contribute to the database or access ancient resources, an account is required. 
### connectivity across resources (under the principles of Linked Open Data)
A  
Used unique URI, and also got the valid https. Many contents can also direct to other URIs (e.g., Pleiades+ pairs Pleiades URI with GeoNames URIs), including directly searching them in the search bar. 

## Orbis
### permanence and sustainability
A-  
Published by Stanford University Libraries, so its basic operation should be ensured. However, it seems that it has not been updated for a long time (at least on the front end), since the most updated info in many sections are nearly 10 years ago. I don't know if this may cause some issues in the future. Personal website of Elijah Meeks also needs to be updated: it's 404 not found now. 
### openness or restriction of their data
A  
A very obvious CSV export button on the right side of the website, and the actual export procedure is also clear-cut. Also got license issued by CC BY-NC 3.0.
### functionality of their interface and interaction with their data
A  
Excellent, even interesting visualization maps and fine graphic design. As a new user, the website is easy to use and the design actually encourages you to explore it as you want. Tutorial section is very easy to find, too. 
### connectivity across resources (under the principles of Linked Open Data)
A  
Unique, valid, and identifiable http URI. Also has a list of organized URI in sections like media and news. 
