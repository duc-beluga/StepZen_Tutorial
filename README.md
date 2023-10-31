# StepZen_Tutorial
A simple three-step tutorial for converting REST APIs into GraphQL using StepZen using Google Books API.

**First Step** Install StepZen CLI: ``npm i -g stepzen`` (``yarn global add stepzen``)

**Second Step** Introspect the REST API: ``stepzen import curl 'https://www.googleapis.com/books/v1/volumes?q=harry+potter&country=US'``

**Third Step** Start GraphQL server: ``stepzen start``

![image](https://github.com/duc-beluga/StepZen_Tutorial/assets/98554622/561041c4-5056-46aa-8a89-0c228f57bb88)

Reference:

[Google Books API](https://developers.google.com/books/docs/v1/using)

[StepZen Youtube Tutorial](https://www.youtube.com/watch?v=T7QZEmug_Wc&ab_channel=StepZen%2CanIBMCompany)
