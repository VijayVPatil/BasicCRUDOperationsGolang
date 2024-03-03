# BasicCRUDOperationsGolang

About the Project:
### Used Gorilla Mux for routing 
1. I have tried to implement basic crud operations in Golang.
2. In place of using an actual database I have used a Fake DB. Used slices of struct to store the data
3. Performed GET, POST , PUT , DELETE and tested it on ThunderClient (VS CODE plugin to test endpoints)


## Run it on Local!
1. Make a Folder-> mkdir <folder_name>
2. Clone the project in the folder.
3. Run the main.go file using the command->  go run main.go (Make sure you have go installed)
4. You will get a firewall pop , accept it
5. The code will run on port :8080  (http://localhost:8080)
6. You can perform
-  TO get all movies
   GET: http://localhost:8080/movies
-  To get a singe Movie    
   GET:  http://localhost:8080/movies/{id}
-  To insert a movie
   POST: http://localhost:8080/movies
-  To update a movie
   PUT: http://localhost:8080//movies/{id}
- To delete a Movie
   DELETE: http://localhost:8080//movies/{id}
