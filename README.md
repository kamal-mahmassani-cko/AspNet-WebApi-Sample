 
 Create:
 
    curl -v -X POST http://peeps.azurewebsites.net/api/persons -d "{\"Name\": \"Gilberto\", \"Phone\": \"4253499816\", \"Address\": \"123 Main St\"}" --header "Content-Type: application/json"
 
 Read all:
 
 
 Update:
 
    curl -v -X PUT http://peeps.azurewebsites.net/api/persons/4253499816 -d "{\"Name\": \"Gilberto S\", \"Address\": \"123 Main St\" }" --header "Content-Type: application/json"
 
 Delete:
 