# read-1
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author DUMP
 */
 import java.util.Scanner;
public class pe2 {
    public static void main(String[]as){
        Scanner kb = new Scanner(System.in);
        String x = kb.next();
	int a1 = 1;
	int a2 = 1;
	int a3 = 1;
	int a4 = 1;
	int a5 = 1;
		
		if(x.charAt(0)==x.charAt(1)){
			a1++;
			if(x.charAt(1)==x.charAt(2)){
				a1++;
				if(x.charAt(2)==x.charAt(3)){
					a1++;
					if(x.charAt(3)==x.charAt(4)){
						a1++;
						System.out.print(a1+x.substring(0,1));
					}else{
						System.out.print(a1+x.substring(0,1));
						System.out.print(a5+x.substring(4));
					}
				}else{
					System.out.print(a1+x.substring(0,1));
					if(x.charAt(3)==x.charAt(4)){
						a4++;
						System.out.print(a4+x.substring(3,4));
					}else{
						System.out.print(a4+x.substring(3,4));
						System.out.print(a5+x.substring(4));
					}
				}
			}else{
				System.out.print(a1+x.substring(0,1));
				if(x.charAt(2)==x.charAt(3)){
					a3++;
					if(x.charAt(3)==x.charAt(4)){
						a3++;
						System.out.print(a3+x.substring(2,3));
					}else{
						System.out.print(a3+x.substring(2,3));
						System.out.print(a5+x.substring(4));
					}
				}else{
					System.out.print(a3+x.substring(2,3));
					if(x.charAt(3)==x.charAt(4)){
						a4++;
						System.out.print(a4+x.substring(3,4));
					}else{
						System.out.print(a4+x.substring(3,4));
						System.out.print(a5+x.substring(4));
					}
				}
			}
		}else{
			System.out.print(a1+x.substring(0,1));
			if(x.charAt(1)==x.charAt(2)){
				a2++;
				if(x.charAt(2)==x.charAt(3)){
					a2++;
					if(x.charAt(3)==x.charAt(4)){
						a2++;
						System.out.print(a2+x.substring(1,2));
					}else{
						System.out.print(a2+x.substring(1,2));
						System.out.print(a5+x.substring(4));
					}
				}else{
					System.out.print(a2+x.substring(1,2));
					if(x.charAt(3)==x.charAt(4)){
						a3++;
						System.out.print(a3+x.substring(3,4));
					}else{
						System.out.print(a3+x.substring(3,4));
						System.out.print(a5+x.substring(4));
					}
				}
			}else{
				System.out.print(a2+x.substring(1,2));
				if(x.charAt(2)==x.charAt(3)){
					a3++;
					if(x.charAt(3)==x.charAt(4)){
						a3++;
						System.out.print(a3+x.substring(2,3));
					}else{
						System.out.print(a3+x.substring(2,3));
						System.out.print(a5+x.substring(4));
					}
				}else{
					System.out.print(a3+x.substring(2,3));
					if(x.charAt(3)==x.charAt(4)){
						a4++;
						System.out.print(a4+x.substring(3,4));
					}else{
						System.out.print(a4+x.substring(3,4));
						System.out.print(a5+x.substring(4));
					}
				}
			}
		}
        
    }
}
