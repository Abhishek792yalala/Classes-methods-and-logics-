# Classes-methods-and-logics---

class Java {

  int sid;

  String sname;

  public void alldetails(){

     System.out.println("Student id is: "+sid);

     System.out.println("Student name is: "+sname);

   }

   public void compliments(){

    System.out.println("Thank you my dear student");

   }

}

class Employee{

   int empno;

   String empname;

   public String getName(){

     return empname;

  }

  public int getNo(){

     return empno;

  }

}

class details{

  public static void main(String... args){

    System.out.println("Welcome to Java Programming");

    Java j=new Java();

    j.sid=12;

    j.sname="Abhishek Yalala";

    j.alldetails();

    j.compliments();

    Employee e=new Employee();

    e.empno=23;

    System.out.println(e.getNo());

    e.empname="Neha";

    System.out.println(e.getName());

  }

}

/* for each class separate method is created and it can access the methods that are declared in the class. 

In main method, object is created and the data can be accessed using the object. 

 */
