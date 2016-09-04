LUIS
==============
LUIS is a service for language understanding that provides intent classification and entity extraction.
In order to use the SDK you first need to create and publish an app on www.luis.ai where you will get your appID and appKey and input their values when prompted by the sample applications.

The SDK
--------------
The SDK can be used in 2 different ways with a separate sample for each way.
- One way to use it is synchronously by calling the functions "predict" and "reply" that are present in the "LUISClient" and receiving the response as a returned object from the class "LUISResponse".
- Another way is asynchronously by creating 2 callback functions "onSuccess" and "onFailure" and passing them to the "predict" and "reply" functions to be called asynchronously in the cases of the request success or failure.

Sample Application
--------------
The sample application allows you to perform the Predict and Reply operations and to view the following parts of the parsed response:
- Query
- Top Intent
- Entities
- Dialog status and prompt

License
=======

All Microsoft Cognitive Services SDKs and samples are licensed with the MIT License. For more details, see
[LICENSE](</LICENSE.md>).


