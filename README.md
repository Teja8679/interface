//Day-7
interface printable
	{
	public void print();
	}
class A6 implements printable
{
public void print()
{
System.out.println("Hii");
}
}
public class Interface {
	
		public static void main(String[] args)
		{
		A6 obj=new A6();
		obj.print();
		}
		
