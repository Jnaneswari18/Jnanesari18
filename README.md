# Jnanesari18
//AREA OF SUQUARE
//SUM OF SIDES OF A SQUARE
public class Main {
    public static void main(String[] args) {
                // TODO code application logic here
        System.out.println("enter a,b,c values:");
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int c=sc.nextInt();
        float s=a+b+c/2f;
        double area=Math.sqrt(s*(s-a)*(s-b)*(s-c));
        System.out.println("sum of sides is:"+s);
        System.out.println("Square root is:"+area);
            }

        }

