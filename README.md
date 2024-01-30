# modulo-4





CREAR UN PROGRAMA QUE INGRESES UNA ORACION Y MUESTRE CUAL ES EL CARACTER QUE MAS SE REPITA.


package com.educacionit;
import java.util.Scanner;
public class contador_de_letras {
	
	public static void main(String[]args) {
	
	Scanner palabra = new Scanner (System.in);
	System.out.println("ingresar texto : ");
	String texto = palabra.nextLine();
	System.out.println("que letra desea averiguar: ");
	char letra = palabra.next().charAt(0);
	int contador = 0;
	for(int i = 0 ; i < texto.length(); i++) {
		if( texto.charAt (i) == letra) {
			contador ++;
		}
	}
	System.out.println("veces que se repite la letra  " +  letra + "  es  " + contador + " veces en el texto ");
	}
}



( UTLIZAMOS EL METODO SCANNER CREAMOS EL STRING Y METODO CHAR UTILIZAMOD EL BUCLE FOR YA QUE DESEAMOS VERIFICAR LA LONGITUD Y JUNTO CON EL CHAR NO ASEGURAMOS QUE LEA TODO DESDE 
LA PRIMERA LETRA Y ASI MISMO CON EL BUCLE VAMOS VIENDO UNA POR UNA , SI EL CONTADOR  COINCIDE CON LA LETRA  LA MISMA VA INCREMENTANDO Y AL FINAL DE LA EVALUACION DEL TEXTO 
NOS MOSTRARA CUANTAS VECES SE TOPO CON EL MISMO CARACTER)

