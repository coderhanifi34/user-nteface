import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        String  userName, sifre;
        Scanner inp = new Scanner(System.in);
        System.out.println("kullanıcı adınız :");
        userName = inp.nextLine();

        System.out.println("sifreniz :");
        sifre = inp.nextLine();

        if(userName.equals("patika") && sifre.equals("java123")){
            System.out.println("giris yaptınız");
        }else{
            System.out.println("bilgiler yanlış");
        }

    }
}
