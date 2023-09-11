import java.util.*; 

public class main { 
  public static void main(String[] args) throws Exception { 
    Scanner sc = new Scanner(System.in); 
    System.out.print("Digite o valor de a: "); 
    int a = sc.nextInt(); 
    System.out.print("Digite o valor de n: "); 
    int n = sc.nextInt(); 
    System.out.println("Resultado: "+calculaEle(a,n)); 
    sc.close();
  }

  public static int calculaEle(int a, int n){ 
  if(n==1){ 
    return a; 
  } 
    return calculaEle(a,n-1)*a; 
  }
}
