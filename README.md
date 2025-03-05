# Assignment-2
Assignment 2 Visual Programming ( Java ) 

# 1 )
interface Animal 
{
  void sound();
}

interface Pet 
{
  void showAffection();
}

class Dog implements Animal, Pet 
{
  @Override
  public void sound() {
      System.out.println("The dog barks : Woof Woof!");
  }

  @Override
  public void showAffection() 
  {
      System.out.println("The dog wags its tail.");
  }
}

public class Main 
{
  public static void main(String[] args) {
      Dog myDog = new Dog();
      myDog.sound();
      myDog.showAffection();
  }
}
