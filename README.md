# java-developer
Technical evaluation for Java developer candidates

# Feature Request App
Build the backend of an application that allows the user to manage "feature requests". No need to build UI as part of this exercise.
A "feature request" is a request for a new feature that will be added onto an existing piece of software. Assume that the user is an employee at WCF who would be entering this information after having some correspondence with a client that is requesting the feature. The necessary fields are:
* Title: A short, descriptive name of the feature request.
* Description: A long description of the feature request.
* Client: A selection list of clients (use "Client A", "Client B", "Client C")
* Priority: Undetermined, Critical, Major, Trivial are possible values for priority.
* Status: The following are the possible statuses for the feature request
  * Open: The feature request is new and it is waiting to be looked at. 
  * In Progress: The feature request is assigned to somebody to be worked on. 
  *	Awaiting Verification: The work was completed and waiting for verification. It is typically assigned to a QA person for verification.
  *	Closed: The feature request is completed
  *	Rejected: Some feature requests are not worked on and they can simply be rejected.
* Target Date: The date that the client is hoping to have the feature.
* Product Area: A selection list of product areas (use 'Policies', 'Billing', 'Claims', 'Reports'). 
* Assignee: The person who needs to work on the feature request.
# Tech Stack
No need to have any UI implemented as part of this exercise. Java is the language we want you use. You can choose any version of Java. Data should be stored in a relational database, we prefer Hibernate but you can use whatever you like. You might want to write some test classes to test your application and you are free to choose JUnit, TestNG or something similar.
# Guidelines
Build your own public repo on GitHub, and call it whatever you like. Build your solution in your repo, and include a README.md file that contains some instructions and notes about design choices you made that you want us be aware while reviewing your code.
One of the major goals in this project is to see how you fill in ambiguities in your own creative way. There is no such thing as a perfect project here, just interpretations of the instructions above, so be creative in your approach.
We want to be respectful of your time and set realistic expectations for submission. Do not worry about how UI will interact with the backend. Just assume that it is part of our framework and start writing your code using Java service classes. For example, you might start with FeatureRequestAppService class as the entry point to the backend services you will provide for this application.
Thank you for your time. We are excited to review your project!
