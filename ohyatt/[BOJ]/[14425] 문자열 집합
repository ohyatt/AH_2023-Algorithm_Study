import java.util.*;
import java.util.Arrays;

public class Main {
    public static void main(String[] args){
        Scanner stdIn = new Scanner(System.in);
        int N = stdIn.nextInt();
        int M = stdIn.nextInt();
        String[] a = new String[N];
        String[] b = new String[M];
        int total = 0;

        for(int i=0; i<N; i++){
            a[i] = stdIn.next();
        }
        for(int i=0; i<M; i++){
            b[i] = stdIn.next();
        }

        for(int i=0; i<M ; i++){
            String temp = b[i];
            for(int j=0;j<N;j++){
                if(b[i].equals(a[j])){
                    total++;
                    break;
                }
                else continue;
            }
        }

        System.out.print(total);


        stdIn.close();
    }
}
