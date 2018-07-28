# Session3-Ex5

// ب ن ک ضرایب معادله درجه دوم را از ورودی گرفته و ریشه های آن را چاپ کند

package com.personal.ex5
import java.util.Scanner;

public class ex5 {

	public static void main(String[] args) {
		
		Scanner sc= new Scanner(System.in);
		System.out.println("lotfan zarayebe moadele daraje dovom ra vared konid");
		int num1= sc.nextInt();
		int num2=sc.nextInt();
		int num3=sc.nextInt();
		System.out.println("moadele be soorate zir ast:");
		System.out.println(num1 + "x*x +"+ num2 + " x +"+ num3);


		double x1,x2, delta;
		delta=(num2*num2)-(4*num1*num3);
		if(delta<0)
			System.out.println("moadele rishe haghighi nadarad");
		
		else if (delta==0) {
			System.out.println("moadele rishe mozaaf nadarad");
			x1=-num2 / (2 * num1);
			System.out.println("risheye X1= " + x1);
				}
		else {
		System.out.println("moaadele 2 risheye mozaaf darad " );
		x1=(( -num2 +Math.sqrt(delta))/(2*num1));
		x2=((-num2 -Math.sqrt(delta))/(2*num1));
		System.out.println("risheye X1= "+ x1+ "  va risheye X2= " + x2+"  mibashad" );

		}
		
		}

		}

