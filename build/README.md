
It is a breeze.js javascript library fork for Nodejs with fully functional supports of OData services (V2, V3, and partially V4).

* 0.1.19
  a quick fix (not necessary appropriate) for the data property of a complex type with null dataType when parsing the returned entities from v4 service

* 0.1.18
  a fix for creating an array (complex type) for a data property but dataType is empty
  added html error information passing

* 0.1.17
a very minor change for the url parameter string joining

* 0.1.16
added a field/member isCollection in DataProperty

* 0.1.15
added a fix for adding function type into the EntityManager when EntityType is the input parameter data type of function

* 0.1.14
treats function is a special type of EntityType

* 0.1.13
fixed for function type parsing

* 0.1.12
added function type parsing support

* 0.1.11
README reworded

* 0.1.10
fixed a bug for missing handler

* 0.1.9
fixed a bug in creating change requests for the adapter

* 0.1.8
fixed the missing breeze.debug.js file
