import java.util.Scanner;
public class perfect_number {
    public static void main(String[] args) {
        Scanner in=new Scanner(System.in);
        System.out.println("Enter the number");
        int n=in.nextInt();
        in.close();
        int sum=0;
        int i=1;
    while(i<=n/2){
        if(n%i==0){
sum=sum+i;
}
i++;
    }
        if(sum==n){
            System.out.println(n+" is perfect number");
        }
        else {
            System.out.println(n+" is not a perfect number");
        }
    }
}
