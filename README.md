package JavaExceptions;

public class ExceptionMethod {
    public static void main(String[] args) {
        int[] arr = new int[4];
        try {
            String s=null;
            System.out.println(s.length());
        }
        catch (ArithmeticException e){
            System.out.println("Arithmetic Exception");
        }
        catch (ArrayIndexOutOfBoundsException e){
            System.out.println("Array Index Issue");
        }
        catch (Exception e){
            System.out.println("Parent Exception");
        }
        System.out.println("Show must go on");

    }
}
