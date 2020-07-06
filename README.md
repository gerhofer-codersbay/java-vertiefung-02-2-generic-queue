Implementiere eine generische Queue. Du kannst dir auf [Tutorialspoint](https://www.tutorialspoint.com/java/java_generics.htm) ansehen wie man Generics implementiert.

Die queue sollte folgende Methoden besitzen: 
* public int length() 
    * returniert die Anzahl der Elemente in der Queue
* public T dequeue() 
    * returniert das erste Element der Queue und löscht es aus der Queue
    * wirft eine QueueEmptyException falls die Queue leer ist
* public void enqueue(T element) 
    * fügt der Queue ein Element hinzu

Teste deine Implementierung *ausführlich* mit Unit Tests. Verwende mindestens einen MyStack<Integer>, MyStack<String> und MyStack<Bill>.
Bill darf dabei eine ganz simple Klasse zur Repräsentation einer Rechnung sein. 

