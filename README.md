# Basic-javaInterface-project
package javapackage;

public class Shembull1{
	public static void main(String args[]) {
		//krijimi i objekteve ne menyre polimorfike duke thirrur interface Libra
		Liber[] lib=new Liber[3];
		lib[0]=new Enciklopedi("Galápagos: An Encyclopedia of Geography, History, and Culture", "Randy Moore", "ABC-CLIO", 2021, 97.00);
		lib[1]=new Roman("Dune", "Frank Herbert","Hugo Award","Penguin", 1966, 8.35);
		lib[2]=new Fjalor("Collins German Dictionary", "Gjermanisht-Anglisht", "HarperCollins", 2014, 99.96);
		
		System.out.println("Paraqitja e librave.\n");
		//paraqitja e objekteve nepermjet nje cikli for-each 
		for (Liber a:lib)
			System.out.println(a+"\n");
	}
}
