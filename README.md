# SecondHOPE
SecondHope - A connection line for Surrogate, Doctor and Intended Parents

Team Member:
  Janki Rathod(0864129),
  Krima Patel(0859652),
  Mohana Reddy(0688824)

Second Hope, we have three modules –

1)Surrogate Module –
    o   If a person chooses to become a Surrogate, she can fill up the application form online, which includes various details on her             personal data, health information.
    o   A surrogate needs to be healthy enough and also she should satisfy all the medical conditions and concerned government laws before         taking any responsibility.

 2)Intended Parents Module –
    o   Parents will get a list of available surrogates, among the available, the Intended Parents can choose surrogate.
    o   Parents can consult with doctor to get some idea about surrogate and surrogacy process.

3)Doctor Module –
    o   Doctors will give approval to surrogate after verifying and checking all details from the application form and all the health             related reports, which were submitted during the application. 

Database: SurrogacyDB
Application Folder: Surrogacy

Config Changes:
Refer web.config file for connection string. Use below code that needs to be changed.
<connectionStrings>
		<add name="SurrogacyDBConnection" connectionString="Data Source=localhost\JENISDBSERVER;Initial Catalog=SurrogacyDB;UID=sa;PWD=Devi@2612" />
	</connectionStrings>
	
  
