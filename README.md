// # Mininet

public abstract class People {
	private String name;
	private int age;
	
	//constructor 
	public People(String name, int age) {
		this.name = name;
		this.age = age;
	}

	//accessor
	public String getName() {
		return name;
	}
	public int getAge() {
		return age;
	}
	//method
	public abstract void displayProfile();
}
