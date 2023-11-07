# ToDoList 
Main -> ToDoList
responsible for{
-Interacting with other classes(Tasks, FileManager)
-draw menu
-creation and storing task array
}
Tasks(Task Array){
-construtor
-Overwritten toString to transfor each cell into String (Over writes the Object class)
-markComplete marks tasks as done
-markUncomplete marks previously completed tasks as uncompleted
-editTask edits out task through index
}
FileManager(Task Array){
-creates database .txt if not present
-responsible for writting and reading from db 
}
