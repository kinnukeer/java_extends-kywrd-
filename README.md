# java_extends-kywrd-
class Animal{
  void Print()
  {
    System.out.println("parent class");
  }
}
class Dog extends Animal{
  void Print()
  {
    System.out.println("Dog barks");
  }
}
class Cat extends Animal{
  void Print()
  {
    System.out.println("Cat meows");
  }
}
class Main{
  public static void main(String args[]){
    Animal a;
    a=new Dog();
    a.Print();
    a=new Cat();
    a.Print();
  }
}
