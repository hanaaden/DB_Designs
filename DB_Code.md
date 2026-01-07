```sql
Table Expense [headercolor: #175e7a] {
	id integer [ pk, increment, not null, unique ]
	user_id integer [ default: not Null ]
	category_id integer
	amount decimal
	description text
	expense_date date
	created_at timestamp
	updated_at timestamp
}

Table Users [headercolor: #175e7a] {
	id integer [ pk, increment, not null, unique ]
	Name varchar
	email varchar [ unique ]
	password varchar
	created_at timestamp
	updated_at timestamp
}

Table Category [headercolor: #175e7a] {
	id integer [ pk, increment, not null, unique ]
	name varchar
	created_at timestamp
	updated_at timestamp
}

Table budget [headercolor: #175e7a] {
	id integer [ pk, increment, not null, unique ]
	user_id integer
	amount decimal
	period varchar
	updated_at timestamp
	created_at timestamp
}
```

<img width="511" height="580" alt="image" src="https://github.com/user-attachments/assets/bf05abcb-8b77-4b8d-9112-8fb87966b5d7" />


