public class ProductOfArray {

    aram args the command line argumen
    public static void main(String[] args) {
        int [] arr = new int [] {10, 15,20 ,25 ,30 };
        int sum = 1;
       for (int i = 0; i<arr.length; i++) {
       sum = sum * arr[i];
}
         System.out.println("Sum of all the elements of an array :"+
sum);

    }
    
}
