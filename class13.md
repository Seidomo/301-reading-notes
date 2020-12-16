# SENDING FORM DATA


Sending the form data happens once the for data has been validated on the client side and its ok to submit the form.


## CLIENT/SERVER ARCHITECTURE

The client/server architecture is a web browser that sends and requests to and on a server using HTTP protocol and the server answers the request using the same protocol.

*On the client side defining how to send the data*

the ```<form> ``` elemnt defines how the data is sent.
the tow most important attributes of the submit button 
are  ```action ``` and  ```method```.

``` action ``` attribute defines where the data gets sent

``` method ``` attribute defines how the data is sent

The two common methods are ``` GET ``` and ``` POST ```.

The ``` GET ``` method is used by the browser to ask the server to send back a given resource.

The ``` POST ``` method is the method the browser uses to talk to the server.


*On the server side retrieving the data*

Whichever HTTP method you choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs. 

*A special case sending files*

``` urlencoded ``` this means tha the data has benn encoded into url parameters.

*Be paranoid never trust your user*


All data that comes to the server must be checked.













* [Reference video](https://www.youtube.com/playlist?list=PL4cUxeGkcC9g5_p_BVUGWykHfqx6bb7qK)



* [Reference](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data)