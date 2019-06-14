
MS3-EmployeeRecord-API



GitHub URL:   https://github.com/abadit2007/ms3.git
url sys api :   ms3-employeerecord-api.us-e2.cloudhub.io/api/EmployeeRecord
this System API has the four CRUD database operation:
Create/Post: it used for posting or inserting records in to the database.

Read/Get: it is used for fetching records from database. for this operation used to to retrieve data by EmpId or by using 
                 query parameters to list all the data from different joined tables.

Update/Put: used to update the records in the database tables

Delete: used to delete the record from database table


=============================================
the is the  input data but I did some some changes on the Type for address and communication as addtype and comtype
{
	"Identification": {
		"FirstName": "Bob",
		"LastName": "Frederick",
		"DOB": "06/21/1980",
		"Gender": "M",
		"Title": "Manager"
	},
	"Address":[ {
		"Addtype": "home",
		"number": 1234,
		"street": "blahblahSt",
		"Unit": "1 a",
		"City": "Somewhere",
		"State": "WV",
		"zipcode": "12345"
	}],
	"Communication": [{
			"comtype": "email",
			"value": "bfe@sample.com",
	  		"preferred" : "true"
		},
		{
			"comtype": "cell",
			"value": "304-555-8282"
		}
	]
}


======================================================
