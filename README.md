# Tehran-Neighbourhoods
Simple Js Mock Data Api for Tehran Neighbourhoods

### 450+ Neighbourhoods Names...



## what it this?
this file will provide you an Array of Objects that each one includes **name** , **district** , **longitude** , **latitude** and finally **prefered zoom level** of the Tehran Neighbourhoods, this file is returns a promise that you can use it in your React or any other Javascript based Projects.



## Data shape for fullDetailed.js file
```
const neighbourhoods = [
  ... someData
  { district:1, name:'اقدسیه' , lat: '51.4821938', lng: '35.7940794', d_zoom: '16' },
  ... someMoreData
]
```

------------------------------------------------------

## Data shape for neighbourhoods.js file
```
const neighbourhoods = [
  ... someData
  { district: 5 , name:'فردوس' }
  ... someMoreData
]
```

if you miss some place on mock api, please create an issue for that and give me the cordinates of that place with the name , or fork it and notify me by your changes to merge to the main file.


## How to get location???
-----
* (1) => open google map
* (2) => search for a place for example the term 'تجریش'
* (3) => on the address bar google will give you this link
`
https://www.google.com/maps/place/Tajrish/@35.8046536,51.4313206,17z/data=!3m1!4b1!4m5!3m4!1s0x3f8e05e3ccd6da15:0x6db7ae606c32cce9!8m2!3d35.8046493!4d51.4335093
`
* (4) => could you find the cordinates ???
* (5) => that is this part: `@35.8046536,51.4313206,17z`
* (6) => first digit `35.8046536` is i guess longitude 
* (7) => second digit `51.4313206` is i guess latitude
* (8) => last digit `17z` is the zoom level that you currently looking at map
* (9) => easy peasy

that is what i basically does for all location , nothing fancy and as working with locations some of them is not exactly matching the neighbourhoods , but as i said some of them, although it works find if you just use those locations for centering that map and use your percise locations lat and lng for your markers, just dont trust on those lat and lng's for putting markers on your map. ( i will fix those as times goes on by the way... )


Enjoy it!<br/>
**Free for ever!**
