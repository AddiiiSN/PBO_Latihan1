# ORIENTED OBJECT PROGRAMMING
## Latihan 1

      public class Person {

        //Membuat Attribut Objek
        String Nama,JenisKelamin;
        Integer Umur;

        public static void main(String[] args){


            //Memasukan Objek ke Class Person
            Person person1 = new Person();
            Person person2 = new Person();

            //Memasukan Data Objek Pertama
            person1.Nama ="Anton";
            person1.JenisKelamin ="Pria";
            person1.Umur = 19;

            //Memasukan Data Objek Kedua
            person2.Nama ="Riko";
            person2.JenisKelamin ="Pria";
            person2.Umur = 21;

            //Menampilkan Objek Pada Layar
            System.out.println("Biodata :");
            System.out.println("1. Nama   = " +person1.Nama);
            System.out.println("   Gender = " +person1.JenisKelamin);
            System.out.println("   Usia   = " +person1.Umur + " Tahun");
            System.out.println(" ");
            System.out.println("2. Nama   = " +person2.Nama);
            System.out.println("   Gender = " +person2.JenisKelamin);
            System.out.println("   Usia   = " +person2.Umur + " Tahun");



        }
    }
    
![Screenshot (1)](https://user-images.githubusercontent.com/115928747/196046682-11d3b179-85d5-41bb-a248-9deb1f15bf27.png)
