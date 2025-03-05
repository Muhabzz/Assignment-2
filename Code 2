#2
class Animal {
  private String name;

  public Animal(String name)
   {
      this.name = name;
  }

  public String getName() 
  {
      return name;
  }

  public void eat() 
  {
      System.out.println(name + " is eating.");
  }
}

class Mammal extends Animal 
{
  public Mammal(String name) 
  {
      super(name);
  }

  public void walk() 
  {
      System.out.println(getName() + " is walking.");
  }
}

class Dog extends Mammal 
{
  public Dog(String name) 
  {
      super(name);
  }

  public void bark() 
  {
      System.out.println(getName() + " barks: Woof Woof!");
  }
}

public class Main2 
{
  public static void main(String[] args) {
      Dog myDog = new Dog("Buddy");
      myDog.eat();
      myDog.walk();
      myDog.bark();
  }
}
