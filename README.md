# Classes-and-Objects
 PROGRAM FOR CLASSES AND OBJECTS                           

class Computer{
	int ram;
	void speedhigh() {
		ram=16;
	}
	void speedlow() {
		ram=4;
	}
	void ramstatus() {
		System.out.println("The content of ram is:"+ram);
	}

}
public class Class {

	public static void main(String[] args) {

Computer c1=new Computer();
Computer c2=new Computer();
c1.speedhigh();
c2.speedlow();
c1.ramstatus();
c2.ramstatus();
	}
}

OUTPUT:
The content of ram is:16
The content of ram is:4

