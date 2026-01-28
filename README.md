import java.util.Scanner;
public class TUGASAKHIR_NOVALIADAMAICI {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner input = new Scanner ( System.in);
int jumlahSiswa;
String nama;
int nilai;
System.out.print("masukan jumlah siswa :");
jumlahSiswa= input.nextInt();
input.nextLine();
// perulangan for
for ( int i=1; i <= jumlahSiswa; i++) {
	System.out.println("\nData siswa ke -" + i);
	System.out.print("masukan nama siswa");
	nama=input.nextLine();
	System.out.print("masukan nilai assesment awal semester genap 2026");
	nilai=input.nextInt();
	input.nextLine();
	// percabangan bersarang
	if ( nilai >= 80) {
		System.out.println("status kesiapan= sangat siap belajar");
	} else {
		if( nilai>= 68) {
			System.out.println("satus kesiapan = cukup siap belajar");
		} else {
			System.out.println("status kesiapan= perlu pendampingan belajar");
		}
	}
	System.out.println("nama siswa :" + nama);
	System.out.println("nilai :" + nilai);
	i++;
}
System.out.println("\nAssesment awal semester genap tahun 2026 selesai");
input.close();
}
	}
