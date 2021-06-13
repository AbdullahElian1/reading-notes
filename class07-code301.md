# How I explained REST to my brother

1- Who is Roy Fielding?

He helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does.

2- Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?



3-What is the HTTP protocol that Fielding and his friends created?

 when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

4- What does a GET do?

GET is used to request data from a specified resource.

GET requests can be cached

5-What does a POST do?

POST is used to send data to a server to create/update a resource.


6- What does PUT do?

PUT is used to send data to a server to create/update a resource. the difference between put and post , calling the same PUT request multiple times will always produce the same result

7- What does PATCH do?

to do a partial update.