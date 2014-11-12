###Get Build Status of a Model
| HTTP Method | URI |
|:--------|:--------|
|GET     |`<rootURI>/GetModelBuildsStatus?modelId=%27<modelId>%27&onlyLastBuild=<bool>&apiVersion=%271.0%27`<br><br>Example:<br>`<rootURI>/GetModelBuildsStatus?modelId=%279559872f-7a53-4076-a3c7-19d9385c1265%27&onlyLastBuild=true&apiVersion=%271.0%27`|


|	Parameter Name	|	Valid Values						|
|:--------			|:--------								|
|	modelId			|	The unique identifier of the model.	|
|	onlyLastBuild	|	Indicates whether to return all the build history of the model or only the status of the most recent build.	|
|	apiVersion		|	1.0									|
