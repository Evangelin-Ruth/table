## EXPERIMENT 05:CREATE A TABLE FOR THE GIVEN DATA
## AIM:
To write a program that would print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee'. The output should be as follows:

Name           Year of joining              Address  
Robert               1994                64C- WallsStreat    
Sam                  2000                68D- WallsStreat  
John                 1999                26B- WallsStreat  
## PROCEDURE:
1. Import required packages.
2. Create a class named Employee
3. Declare main method with the signature "public static void main(String[] args)".
4. Create methods to pass data for each employee
5. Print the details as output on display.
6. End the program.

## PROGRAM:
```
class Employee
{
    String Name;
    int Year;
    String Address;
    Employee(String nam,int years, String addr)
    {
        Name=nam;
        Year=years;
        Address=addr;
    }
    void Sam()
    {
        System.out.println(Name+ "\t\t\t" +Year + "\t\t\t" +Address);
    }
    void Robert()
    {
        System.out.println(Name+ "\t\t\t" +Year + "\t\t\t" +Address);
    }
    void John()
    {
        System.out.println(Name+ "\t\t\t"+Year + "\t\t\t" +Address);
    }
}
class Employee_details
{
    public static void main(String args[])
    {
        System.out.println("Name\t\t" + " Year of Joining\t\t" + "Address" );
        Employee e=new Employee("Sam\t", 2000, "68D-WallsStreet");
        e.Sam();
        Employee e1=new Employee("Robert", 1994, "64C-WallsStreet");
        e1.Robert();
        Employee e2=new Employee("John", 2002, "70F-WallsStreet");
        e2.Sam();
    }
}
```
## OUTPUT:
![image](https://github.com/Evangelin-Ruth/table/assets/94219798/3916ce57-e920-4f21-a282-cdbafdd74def)
## RESULT:
Thus, a progra that would print the information of employee is created and executed successfully.


