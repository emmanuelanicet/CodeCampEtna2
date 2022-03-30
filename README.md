# Défi Etna 

Première partie : API 

- Authentification admin 

- Historique emargements 

- liste étudiant en retard, absent et présent par jour 
trié par leur status 

	routes : 

	retard 
	absent
	
- accès historique d'un étudiant (assiduité) 

- donner un état "justifié" aux retards ou absence 

```
{
"student(tous)": [
	{
	"id": 1,
	"username": "ezzine_a",
	"status": "absent",
	"hours": "Monday-Saturday 9AM–9PM, Sunday Closed",
	"created_at": "2022-03-05T07:36:13.000000Z",
	"updated_at": "2022-03-05T07:36:13.000000Z"
	},
	{
	"id": 2,
	"username": "anicet_e",
	"status": "present",
	"hours": "Monday-Saturday 9AM–9PM, Sunday Closed",
	"created_at": "2022-03-05T07:36:13.000000Z",
	"updated_at": "2022-03-05T07:36:13.000000Z"
	}
]

"status(absent)": [
	{
	"id": 1,
	"username": "ezzine_a",
	"status": "absent",
	"hours": "Monday-Saturday 9AM–9PM, Sunday Closed",
	"created_at": "2022-03-05T07:36:13.000000Z",
	"updated_at": "2022-03-05T07:36:13.000000Z"
	}]	
}
```

