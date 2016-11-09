public class javaLevellUP {
    public static void main(String[] args) {
     int a=234/7;
     int b = 543/130;
     int c = 16/10;
     int d = 16%10;
        System.out.println("Сколько полных недель прошло ха 234 дня = "+a);
        System.out.println("прямоугольник с размерами 543 * 130 мм,от него можно отрезать квадратов со сторой 130 мм = "+b);
        System.out.println("Количество десятко в числе 16 = " + c);
        System.out.println("Число единиц в 16= "+d);

        int sum=16;
        int First_sum=sum/10;
        int Second_sum=sum%10;
        int Sum_Sum=First_sum+Second_sum;
        System.out.println("Сумма цифр числа 16 = "+Sum_Sum);

        int sum1=16;
        int First_sum1=sum/10;
        int Second_sum1=sum%10;
        int Sum_Sum1=First_sum*Second_sum;
        System.out.println("Произведение цифр числа 1 и 6 = "+Sum_Sum1);

        int smena=16;
        int First_smena=smena/10;//1
        int Second_smena=smena%10;//6
        int New_First_smena=Second_smena*10;//60
        int itog=New_First_smena+First_smena;
        System.out.println("Число, образованное при перестановке цифр заданного числа 16 = "+ itog);
        
        boolean a = true;
        boolean b = false;
        boolean c = false;
        boolean d = (!a & b);
        System.out.println("Условие:не А и В = "+(!a & b));
        System.out.println("Условие:А или не В = "+ (a|!b));
        System.out.println("Условие:А и В или С = "+ (a&b|c));
        
        //6
        boolean x = false;
        boolean y = false;
        boolean z = true;
        System.out.println("Условие:X или Y и не Z = "+(x | y &!z));
        System.out.println("Условие:не X и не Y = "+ (!x&!y));
        System.out.println("Условие:не (X и Z) или Y = "+ (!(x&z)|y));
        System.out.println("Условие:X и не Y или Z = "+ (x&!y|z));
        System.out.println("Условие:X и (не Y или Z) = "+ (x&(!y|z)));
        System.out.println("Условие:X или (не (Y или Z)) = "+ (x|(!(y|z))));
