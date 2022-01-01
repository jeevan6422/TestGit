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
   public class MyClass {
  	public static final integer SOME_CONSTANT = 0;     //Good: Constants are not checked.
  	private String firstName;                          //Good.
  	public String FIRSTNAME_OVERRIDE;                 //Bad: Not recommended.
  	public String lastName { get; set; }               //Good.
  	@AuraEnabled public String lastName               //Good. AuraEnabled is not checked
  
  	public String getFirstName() {
    	return firstName;
  	}
  	
 	public void setFirstName(String firstName) {
	 	this.firstName = firstName;
  	}
   }
   
   //Good. This class is considered a 'Data Transport Object' and is not checked
   public class MyClass {
      public String field1;
      public String field2;
   }
    
