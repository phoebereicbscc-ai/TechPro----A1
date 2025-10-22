public class Main {
	public static void main(String[] args) {
		
		Motorcycle m = new Motorcycle();
		m.make = "Yamaha RZ350";
		m.color = "Yellow";
		
		System.out.println("Calling showAtts...");
		m.showAtts();
		System.out.println("---");
		
		System.out.println("Starting engine...");
		m.startEngine();
		System.out.println("-");
		
		System.out.println("Calling showAtts...");
		m.showAtts();
		System.out.println("---");
		
		System.out.println("Staring engine...");
		m.startEngine();
	}
}
     class Motorcycle {
    String make;
    String color;
    boolean engineState = false;

    void startEngine() {
        if (engineState) {
            System.out.println("The engine is already on.");
        } else {
            engineState = true;
            System.out.println("The engine is now on.");
        }
    }

    void showAtts() {
        System.out.println("Make: " + make);
        System.out.println("Color: " + color);
        System.out.println("Engine state: " + (engineState ? "on" : "off"));
    }
  }
