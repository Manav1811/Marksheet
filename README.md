# Marksheet

package practice;
import java.util.Scanner;
public class Marksheet{
	
		public static void main(String[] args) {

			 Scanner sc = new Scanner(System.in);
			 	int C,C1,ES,F,L,M,E,E1,P;
			    int a,b,x,y,z,r,s,t,q;

			 
			    System.out.println("Enter the grade point of CE144-Object Oriented Programming With C++(THEORY):");
			    C = sc.nextInt();

			    

			    System.out.println("Enter the grade point of CE144-Object Oriented Programming With C++(PRACTICAL):");
			    C1 = sc.nextInt();

			    

			    System.out.println("Enter the grade point of CL144.02A-Environmental Science(PRACTICAL):");
			    ES = sc.nextInt();

			    

			    System.out.println("Enter the grade point of FS102A-Foundation Course(PRACTICAL):");
			    F = sc.nextInt();

			    

			    System.out.println("Enter the grade point of HS205.02A-Liberal Arts(PRACTICAL):");
			    L = sc.nextInt();

			    

			    System.out.println("Enter the grade point of MA144-Engineering Mathematics-II(THEORY):");
			    M = sc.nextInt();

			    

			    System.out.println("Enter the grade point of ME145-Elements of Engineering(THEORY):");
			    E = sc.nextInt();

			    

			    System.out.println("Enter the grade point of ME145-Elements of Engineering(PRACTICAL):");
			    E1 = sc.nextInt();

			    

			    System.out.println("Enter the grade Point of PY143-Engineering Physics-II(PRACTICAL):");
			    P = sc.nextInt();

			    if(C>79)

			    {

			    	a=10;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):AA");

			    }

			    else if(C<80 && C>72)

			    {

			    	a=9;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):AB");

			    }

			    else if(C>65 && C<73)

			    {

			    	a=8;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):BB");

			    }

			    else if(C>59 && C<66)

			    {

			    	a=7;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):BC");

			    }

			    else if(C>54 && C<60)

			    {

			    	a=6;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):CC");

			    }

			    else if(C>49 && C<55)

			    {

			    	a=5;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):CD");

			    }

			    else if(C>44 && C<50)

			    {

			    	a=4;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):DD");

			    }

			    else

			    {

			    	a=0;
			    	System.out.println("CE144-Object Oriented Programming With C++(THEORY):FF");

			    }

			    

			    if(C1>79)

			    {

			    	b=10;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):AA");

			    }

			    else if(C1<80 && C1>72)

			    {

			    	b=9;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):AB");

			    }

			    else if(C1>65 && C1<73)

			    {

			    	b=8;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):BB");

			    }

			    else if(C1<66 && C1>59)

			    {

			    	b=7;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):BC");

			    }

			    else if(C1>54 && C1<60)

			    {

			    	b=6;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):CC");

			    }

			    else if(C1>49 && C1<55)

			    {

			    	b=5;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):CD");

			    }

			    else if(C1>44 && C1<50)

			    {

			    	b=4;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):DD");

			    }

			    else

			    {

			    	b=0;
			    	System.out.println("CE144-Object Oriented Programming With C++(PRACTICAL):FF");

			    }

			    

			    if(ES>79)

			    {

			    	x=10;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):AA");

			    }

			    else if(ES<80 && ES>72)

			    {

			    	x=9;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):AB");

			    }

			    else if(ES<73 && ES>65)

			    {

			    	x=8;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):BB");

			    }

			    else if(ES<66 && ES>59)

			    {

			    	x=7;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):BC");

			    }

			    else if(ES>54 && ES<60)

			    {

			    	x=6;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):CC");

			    }

			    else if(ES>49 && ES<55)

			    {

			    	x=5;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):CD");

			    }

			    else if(ES>44 && ES<50)

			    {

			    	x=4;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):DD");

			    }

			    else

			    {

			    	x=0;
			    	System.out.println("CL144.02A-Environmental Science(PRACTICAL):FF");

			    }

			    

			    if(F>79)

			    {

			    	y=10;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):AA");

			    }

			    else if(F<80 && F>72)

			    {

			    	y=9;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):AB");

			    }

			    else if(F>65 && F<73)

			    {

			    	y=8;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):BB");

			    }

			    else if(F<66 && F>59)

			    {

			    	y=7;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):BC");

			    }

			    else if(F>54 && F<60)

			    {

			    	y=6;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):CC");

			    }

			    else if(F>49 && F<55)

			    {

			    	y=5;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):CD");

			    }

			    else if(F>44 && F<50)

			    {

			    	y=4;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):DD");

			    }

			    else

			    {

			    	y=0;
			    	System.out.println("FS102A-Foundation Course(PRACTICAL):FF");

			    }

			    

			    if(L>79)

			    {

			    	z=10;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):AA");

			    }

			    else if(L<80 && L>72)

			    {

			    	z=9;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):AB");

			    }

			    else if(L>65 && L<73)

			    {

			    	z=8;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):BB");

			    }

			    else if(L<66 && L>59)

			    {

			    	z=7;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):BC");

			    }

			    else if(L>54 && L<60)

			    {

			    	z=6;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):CC");

			    }

			    else if(L>49 && L<55)

			    {

			    	z=5;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):CD");

			    }

			    else if(L>44 && L<50)

			    {

			    	z=4;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):DD");

			    }

			    else

			    {

			    	z=0;
			    	System.out.println("HS205.02A-Liberal Arts(PRACTICAL):FF");

			    }

			    

			    if(M>79)

			    {

			    	r=10;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):AA");

			    }

			    else if(M<80 && M>72)

			    {

			    	r=9;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):AB");

			    }

			    else if(M>65 && M<73)

			    {

			    	r=8;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):BB");

			    }

			    else if(M<66 && M>59)

			    {

			    	r=7;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):BC");

			    }

			    else if(M>54 && M<60)

			    {

			    	r=6;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):CC");

			    }

			    else if(M>49 && M<55)

			    {

			    	r=5;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):CD");

			    }

			    else if(M>44 && M<50)

			    {

			    	r=4;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):DD");

			    }

			    else

			    {

			    	r=0;
			    	System.out.println("MA144-Engineering Mathematics-II(THEORY):FF");

			    }

			    

			    if(E>79)

			    {

			    	s=10;
			    	System.out.println("ME145-Elements of Engineering(THEORY):AA");

			    }

			    else if(E<80 && E>72)

			    {

			    	s=9;
			    	System.out.println("ME145-Elements of Engineering(THEORY):AB");

			    }

			    else if(E>65 && E<73)

			    {

			    	s=8;
			    	System.out.println("ME145-Elements of Engineering(THEORY):BB");

			    }

			    else if(E<66 && E>59)

			    {

			    	s=7;
			    	System.out.println("ME145-Elements of Engineering(THEORY):BC");

			    }

			    else if(E>54 && E<60)

			    {

			    	s=6;
			    	System.out.println("ME145-Elements of Engineering(THEORY):CC");

			    }

			    else if(E>49 && E<55)

			    {

			    	s=5;
			    	System.out.println("ME145-Elements of Engineering(THEORY):CD");

			    }

			    else if(E>44 && E<50)

			    {

			    	s=4;
			    	System.out.println("ME145-Elements of Engineering(THEORY):DD");

			    }

			    else

			    {

			    	s=0;
			    	System.out.println("ME145-Elements of Engineering(THEORY):FF");

			    }

			    

			    if(E1>79)

			    {

			    	t=10;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):AA");

			    }

			    else if(E1<80 && E1>72)

			    {

			    	t=9;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):AB");

			    }

			    else if(E1>65 && E1<73)

			    {

			    	t=8;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):BB");

			    }

			    else if(E1<66 && E1>59)

			    {

			    	t=7;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):BC");

			    }

			    else if(E1>54 && E1<60)

			    {

			    	t=6;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):CC");

			    }

			    else if(E1>49 && E1<55)

			    {

			    	t=5;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):CD");

			    }

			    else if(E1>44 && E1<50)

			    {

			    	t=4;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):DD");

			    }

			    else

			    {

			    	t=0;
			    	System.out.println("ME145-Elements of Engineering(PRACTICAL):FF");

			    }

			    

			    if(P>79)

			    {

			    	q=10;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):AA");

			    }

			    else if(P<80 && P>72)

			    {

			    	q=9;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):AB");

			    }

			    else if(P>65 && P<73)

			    {

			    	q=8;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):BB");

			    }

			    else if(P<66 && P>59)

			    {

			    	q=7;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):BC");

			    }

			    else if(P>54 && P<60)

			    {

			    	q=6;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):CC");

			    }

			    else if(P>49 && P<55)

			    {

			    	q=5;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):CD");

			    }

			    else if(P>44 && P<50)

			    {

			    	q=4;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):DD");

			    }

			    else

			    {

			    	q=0;
			    	System.out.println("PY143-Engineering Physics-II(PRACTICAL):FF");

			    }

			    float x2;

			    x2=(float)((a*3) + (b*2) + (x*2) + (y*2) + (z*2) + (r*4) + (s*3) + (t*1) + (q*2))/21;

			    System.out.println("Your SGPA is:"+x2);

		

	}
}
