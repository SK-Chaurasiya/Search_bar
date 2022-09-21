# Search_bar.github.io-
Search bar design with the API

An application programming interface (API) is a way for two or more computer programs to communicate with each other. It is a type of software interface, offering a service to other pieces of software.[1] A document or standard that describes how to build or use such a connection or interface is called an API specification. A computer system that meets this standard is said to implement or expose an API. The term API may refer either to the specification or to the implementation.

A recipe is a set of instructions that describes how to prepare or make something, especially a dish of prepared food.
A meal is an eating occasion that takes place at a certain time and includes consumption of food. The names used for specific meals in English vary, depending on the speaker's culture, the time of day, or the size of the meal.

Meals occur primarily at homes, restaurants, and cafeterias, but may occur anywhere. Regular meals occur on a daily basis, typically several times a day. Special meals are usually held in conjunction with such occasions as birthdays, weddings, anniversaries, and holidays. A meal is different from a snack in that meals are generally larger, more varied, and more filling than snacks



![search](https://user-images.githubusercontent.com/97239651/191457843-469b0a7a-0fad-412b-b69f-e6fd12968cb1.PNG)

This API covers all key use cases related to recipe and food text natural language processing and nutrition analysis. The API employs NLP (Natural Language Processing) which allows for extraction of food entities from unstructured text.


![search bar](https://user-images.githubusercontent.com/97239651/191457836-cd030822-a0bd-4ceb-8261-9b7b337695e5.PNG)


New recipes, resubmission and licensing count
Once you submit a recipe via the API you start paying Edamam a monthly licensing fee for each new analyzed recipe. Sometimes however, you may need to refresh the nutrition data for an already submitted recipe, in case you have lost the nutrition data for example. Submitting a recipe directly will count as analyzing a new recipe, and you will be charged again licensing fee for the nutrition information. To avoid that we’ve implemented a system based on HTTP’s ETag mechanism.


![result](https://user-images.githubusercontent.com/97239651/191458467-f87ac64f-44c5-47b2-9c5b-47c3f634b330.PNG)

