# Oops2
package mypackage;
class Nation{
	int Population;
	String language;
	double Gdp;
	boolean hindu=true;

public void display(int Population,String language,double gdp) {
	System.out.println("population is:"+Population);
	System.out.println("language is:"+language);
	System.out.println("gdp is:"+gdp);
	
}
}
class Panjab extends Nation{
	
	int Population=550000;
	String language="panjabi";
	double gdp=5.34;	
}
class Gujrat extends Nation{
	int population=350000;
	String lanaguage="gujrati";
	double gdp=10.34;	
	
}


public class Oops03 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Panjab panjab=new Panjab();
		panjab.display(panjab.Population,panjab.language,panjab.gdp);
		Gujrat gujrat=new Gujrat();
		gujrat.display(gujrat.population, gujrat.lanaguage, gujrat.gdp);
		

	}

}
