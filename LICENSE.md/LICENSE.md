package haftabes;
import java.util.Scanner;
public class artýkyil {
	public static void main(String[] args) {
		Scanner input = new Scanner (System.in);
		int yil;
		System.out.println("Yýl giriniz");
		yil = input.nextInt();
		if ((yil % 4 == 0 && yil %100 != 0)|| (yil %400 == 0)){
		System.out.println(yil + "Sene artýk sene deðil");
	} else
		System.out.println ("devamı kaçırıldı");
	}
		
	}
