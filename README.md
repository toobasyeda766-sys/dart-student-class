# dart-student-class
Dart Opp student class Example
class Student{
  String name = "Fatima";
  String course = "Mobile Application";
  int marks = 94;

  //Method / Action
  void show_info(){
    print("Name: $name");
    print("course: $course");
    print ("marks: $marks");

}

}
void main(){
  Student s1 = Student();
  s1.show_info();

}
