# marks
public class Main
{
	public static void main(String[] args) {
	    
	    int a = 30;
	    if (a>=0 && a<=32){
	        System.out.print("f");
	       }
	       else if (a>=33 && a<=39){
	           System.out.print("d");
	       }
	       else if (a>=40 && a<=49){
	           System.out.print("c");
	       }
	       else if (a>=50 && a<=59){
	           System.out.print("b");
	       }
	       else if (a>=60 && a<=69){
	           System.out.print("A-");
	       }
	       else if (a>=70 && a<=79){
	           System.out.print("A");
	       }
	       else if (a>=80 && a<=100){
	           System.out.print("A+");
	       }
	       else {
	            System.out.print("Absent");
	       }
	}
}
