# TestGit
This is for testing git
new redme added{
  "status": <status_code>,
  "timestamp": "2021-03-23T18:25:55Z",
  "message": "Success",
  "path": "<relative_url>",
  "result": {
		"stepStatus": "Completed",
		"logList": [
			"Initiating Dataset creation / Deployment request",
			"Creating the new Deployment with labelName SriNcQa-0416",
			"Creating the deployment.",
			"Creating the deployment iteration.",
			"Feature Migration Deployment saved.",
			"Feature Migration Deployment Iteration saved."
@IsTest
public class Foo  {
   public static testmethod void testSomething() {
   	  Integer result = 1 + 2;
      System.assertEquals(3, result); 				//Good: result is checked with an assertion.
   }
}


@IsTest
public class Foo  {
   public static testmethod void testSomething() {
   	  Integer result = 3 + 4;						//Bad: result is not checked.
   }
}
   
