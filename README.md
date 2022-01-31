class Rectangle
{
int length, width;
int rectarea()  //defining  method
{
int area = length*width;
return (area);
}
}
public class rectarea
{
public static void main(String args[])
{
int area;
Rectangle rect = new Rectangle(); // creating objects 
rect.length = 15;
rect.width = 10;
area = rect.length*rect.width;
System.out.println("Area =" +area);
}
}
