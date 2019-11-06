BaiTap 1

package baivi;

import java.util.Scanner;

/**
 *
 * @author Asus
 */
public class BaiVi {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
        float x1,x2,y1,y2;
        Scanner sc = new Scanner(System.in);
        System.out.println("Nhap x1 ");
        x1 = sc.nextFloat();
        System.out.println("Nhap x2 ");
        x2 = sc.nextFloat();
        System.out.println("Nhap y1 ");
        y1 = sc.nextFloat();
        System.out.println("Nhap y2 ");
        y2 = sc.nextFloat();
        
        float KC = (float) Math.sqrt((x1-x2)*(x1-x2)+(y1-y2)*(y1-y2));
        System.out.println("Khoảng cách là " + KC);
        // TODO code application logic here
    }
    
}


