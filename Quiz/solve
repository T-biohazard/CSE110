
package quiz;

public abstract class Employee {
     String name;
    String Id;



 Employee(String name,String Id){
        this.name=name;
        this.Id=Id;
    }
   
    
    abstract double salary();
        

    @Override
    public String toString(){
        return ""+name+""+Id;
    }

   
   
}





package quiz;


public class FullTime extends Employee {
   double  basicPay;
    double medicalAll;
    double houseRent; 


FullTime(String name,String id,double  basicPay,double medicalAll,double houseRent){
 super(name,id);
    this.basicPay=basicPay;
    this.medicalAll=medicalAll;
    this.houseRent=houseRent; 


     @Override
    public double salary(){
        return houseRent+medicalAll+basicPay;
    }
    
    @Override
    public String toString(){
       return " "; 
    }
    }
   
    
    
    
    
 class Quiz{
    public static void main(String[] args){
    Sacnner in=new Scanner(System.in);
    ArrayList <Employee> list=new ArrayList <Employee> ();
    System.out.println("Fulltime:");
    for(int i=0;i<2;i++){
       Employee obj=new Fulltime(in.nextLine(),in.nextLine(),in.nextDouble(),in.nextDouble(),in.nextDouble());
       in.nextLine();
       list.add(obj);
    }
     System.out.println("Parttime:");
    for(int i=0;i<2;i++){
       Employee obj=new Parttime(in.nextLine(),in.nextLine(),in.nextDouble());
       in.nextLine();
       list.add(obj);
    }
    
    for(Employee el:list){
      
      System.outprintln(el);
      el.salary();
    }
    
    
    }
 }
 
 
 
 
  package quiz;

public class PartTime extends Employee {
     double basicpay;
     

 
PartTime (String name,String id,double basicPay){
        super(name,id);
        this.basicPay=basicPay;}


 @Override
    public double salary(){
        return basicPay;
    }
    
    @Override
    public String toString(){
       return " "; 
    }

    }
    

