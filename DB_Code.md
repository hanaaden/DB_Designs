Table Expense [headercolor: #175e7a] {
	id integer [ pk, increment, not null, unique ]
	user_id integer
	Expense_name varchar
	Expense_amount varchar
	"Expense_category " varchar
}

Table Users [headercolor: #175e7a] {
	id integer [ pk, increment, not null, unique ]
	Name varchar
}

Table Category [headercolor: #175e7a] {
	id integer [ pk, increment, not null, unique ]
	Category_name 
}

<img width="930" height="404" alt="image" src="https://github.com/user-attachments/assets/46497b8f-36e2-42f9-9bc1-83de1aa5279e" />
