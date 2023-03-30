Story 1: In order to track wildlife sightings, as a user of the API, I need to manage animals.

Branch: animal-crud-actions

Acceptance Criteria

[x]Create a resource for animal with the following information: common name and scientific binomial

[x]Can see the data response of all the animals
[x]Can create a new animal in the database
[x]Can update an existing animal in the database
{
    "animal": {
        "common_name": "Asiatic Eplephant",
        "scientific_bionomial": "Elephas maximus Linnaeus"
    }
}
I then created a key and value in header using: Content-Type Value: application/json

[x]Can remove an animal entry in the database
I went to the delete tab in postman and entered /animals/1 in the url and it successfully deleted. I was so successful that I also deleted animals/2 as well because I couldn't tell if it worked lol