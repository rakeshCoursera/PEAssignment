## Things to Know About the Solution

- **Purpose**: Patient has the visibility rights of the prescriptions and he/she can decide which prescription to show to a Doctor or to a Pharmacist. 
- Using *Select Role* dropdown a user role is changing from the available roles.
- Added console.log at various places to display the behavior of application
- In the application, roles are acting as a user and serving the purpose of the assignment.
- Test the application by Changing the visibility rights of a prescription for the Doctor and Pharmacist on the [codepen.io](https://codepen.io/RakeshKrSharma/pen/JyJmgR). 

In the real world, this application starts from a sign-in page from where we will capture the user related details and then after signing in, on the landing page current role will be selected. Data will be stored in the database server (MongoDB, SQL, Elasticsearch etc.). In this case, Patient can also choose to show the medical details to the particular Doctor and Pharmacist from the available users who's role is either Doctor or Pharmacist. 

Here I only focused to implement the basic purpose of the application in the limited time.