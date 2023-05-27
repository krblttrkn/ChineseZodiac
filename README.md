# ÖDEV :
## Çin Zodyağı Hesaplama :
* Java ile kullanıcıdan doğum tarihini alıp Çin Zodyağı değerini hesaplayan program yazınız.
* 4000 bin yıldır kullanılan bir astroloji çeşididir. Çin astrolojisi ve insanları 12 değişik burç ve sembollerle tanımlar.Çin Zodyağı bu 12 burcun eşit aralıklarla (10 derece genişliğinde) sıralandığı bir hayvan halkasıdır ve yıldızlarla pek bir ilgisi yoktur.
* Çin Zodyağı hesaplanırken kişinin doğum yılının 12 ile bölümünden kalana göre bulunur.
* Doğum Tarihi %12 = 0 ➜ Maymun
* Doğum Tarihi %12 = 1 ➜ Horoz
* Doğum Tarihi %12 = 2 ➜ Köpek
* Doğum Tarihi %12 = 3 ➜ Domuz
* Doğum Tarihi %12 = 4 ➜ Fare
* Doğum Tarihi %12 = 5 ➜ Öküz
* Doğum Tarihi %12 = 6 ➜ Kaplan
* Doğum Tarihi %12 = 7 ➜ Tavşan
* Doğum Tarihi %12 = 8 ➜ Ejderha
* Doğum Tarihi %12 = 9 ➜ Yılan
* Doğum Tarihi %12 = 10 ➜ At
* Doğum Tarihi %12 = 11 ➜ Koyun

```
import java.util.Scanner;

public class ChineseZodiac {
    public static void main(String[] args) {
        int year, remainder;
        Scanner input = new Scanner(System.in);

        System.out.print("Doğum Yılınızı Giriniz : ");
        year = input.nextInt();
        remainder = year % 12;

        switch (remainder) {
            case 0:
                System.out.print("Çin Zodyağı Burcunuz : Maymun");
                break;
            case 1:
                System.out.print("Çin Zodyağı Burcunuz : Horoz");
                break;
            case 2:
                System.out.print("Çin Zodyağı Burcunuz : Köpek");
                break;
            case 3:
                System.out.print("Çin Zodyağı Burcunuz : Domuz");
                break;
            case 4:
                System.out.print("Çin Zodyağı Burcunuz : Fare");
                break;
            case 5:
                System.out.print("Çin Zodyağı Burcunuz : Öküz");
                break;
            case 6:
                System.out.print("Çin Zodyağı Burcunuz : Kaplan");
                break;
            case 7:
                System.out.print("Çin Zodyağı Burcunuz : Tavşan");
                break;
            case 8:
                System.out.print("Çin Zodyağı Burcunuz : Ejderha");
                break;
            case 9:
                System.out.print("Çin Zodyağı Burcunuz : Yılan");
                break;
            case 10:
                System.out.print("Çin Zodyağı Burcunuz : At");
                break;
            case 11:
                System.out.print("Çin Zodyağı Burcunuz : Koyun");
                break;
            default:
        }
    }
}
```
# Patika Profilim
<a href='https://academy.patika.dev/profile'><u>Patika Profilim</u></a>