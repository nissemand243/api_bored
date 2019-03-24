  Jeg har implementeret 4 felter der søger efter aktiviteter.
  første felt er en helt tilfældig aktivitet,
  andet felt er en aktivitet baseret på antal deltagere
  tredje felt er en aktivitet baseret på prisen
  fjerde felt er en aktivitet baseret på tilgængeligheden.
  
  Jeg har lige nu et problem med en af mine knapper, den virker ikke og det er en fejl i mit "fadeToogle" der er problemet. jeg ved ikke hvorfor den laver fejlen da det først er efter jeg har "pushet" min kode at den ikke længere virker.


# api_bored
  This is an example of a very simple app using an API. Namely we use pure javascript embedded directly in an HTML file, to get results from an API called <a href="https://www.boredapi.com/documentation">the "bored" API</a>.
  
  The structure of the page is made up of a small jQuery menu - when you click menu items, the page toggles visibility on respective div sections. This is a neat and quick way to build a one-page html app, that is superquick and still easy to overview code wise.  
  
  The API calls are made with the jQuery ajax function. Ajax is short for "asynchronous javascript and xml". In fact the xml part doesn't really apply to many modern applications, since what we see in our response objects is instead JSON. To work with this pice of code, all you need to know is that the $.ajax() parts in the code, means we are requesting data from an external source - here, the bored api - and when we get something in return (.done()), we can use data in the app.
  
  <a href="https://www.w3schools.com/js/js_json_xml.asp">W3C on the difference between JSON an XML</a><br>
  <a href="">Eloquent Javascript on asynchronous programming in.. well, javascript</a>
  
## Handlebars
  We also use a js framework called <a href="https://handlebarsjs.com/">handlebars</a>, to ease json formatting. 
  
  
  Lastly - and really the reason we use handlebars - we use a rather complex css boilerplate, <a href="https://materializecss.com/cards.html"> called materialize</a>, which gives us some rather cool layouts. 
  
  Hence the total project presents a set of meaningful skills and architecture in frontend web-programming. 
  
  

  
