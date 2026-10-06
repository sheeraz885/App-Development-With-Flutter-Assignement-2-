

void main() {
  //Q1 Fruist Name
  List fruitsName = ["Apple", "Cheery", "Banana", "Mango", "Orange"];
  print(" Q1 Fruits Name List");
  print(fruitsName);

  print("____________________________________________________");

  // Q2 Adding Numbers In Empty List
  List numbersList = [];
  numbersList.add(10);
  numbersList.add(20);
  numbersList.add(30);

  print(" Q2 Numebers List");
  print(numbersList);

  print("____________________________________________________");

  //Q3 Adding Name in Name Array

  List names = ["Ali", "Ahmed", "Usman"];
  print(" Q3 Names List");
  print("Before Add Name :");
  print(names);
  names.add("Hamza");
  print("After Add Name :");
  print(names);

  print("____________________________________________________");

  // Q4 Adding Numbers In number List

  List numbers = [1, 2, 4];
  print(" Q4 Numbers List:");
  print("Before Add Numbers:");
  print(numbers);
  numbers.addAll([4, 5, 6]);
  print("After Added Numbers:");
  print(numbers);

  print("____________________________________________________");

  // Q5 Add Multipule Colors in Colors List

  List colorsList = ["Red", "Green"];
  print(" Q5 Colors List: ");
  print("Before Add Colors List");
  print(colorsList);
  colorsList.addAll(["Blue", "Yellow", "Black"]);
  print("After Added Colors List");
  print(colorsList);

  print("____________________________________________________");

  //Q6 Adding Multipule Fruits in fruits List

  List fruitsList = ['Apple', 'Banana', 'Mango'];
  print("Q6 frits list: ");
  print("Before Add Fruit List");
  print(fruitsList);
  fruitsList.add('Orange');
  fruitsList.add('Graps');
  print("After Added Fruits List");
  print(fruitsList);

  print("____________________________________________________");

  // Q7 Combining Two Lists
  List list1 = [10, 20, 30];
  List list2 = [40, 50, 60];
  print("Q7 Combines Two Lists: ");
  list1.addAll(list2);
  print("New List :");
  print(list1);

  print("____________________________________________________");

  // Q8 Student Names and Length

  List studentsName = ["Sheeraz", "Faraz", "Jahanzaib", "Ayan", "Fawad"];
  print(" Q8 students Name");
  print(studentsName);
  print("The length of Students Name List is : ${studentsName.length}");

  print("____________________________________________________");

  //Q9 Numbers and Length

  List Num = [20, 40, 60, 80];
  print(" Q9 Numbers List : ");
  print("Before Add Numbers in List");
  print(Num);
  print("The length of Numbers list is : ${Num.length}");
  Num.addAll([30, 50]);
  print("After Add Numbers in List");
  print(Num);
  print("The length of Numbers list is : ${Num.length}");

  print("____________________________________________________");

  // Q10 Shuffle Cities

  List citiesList = ["Karachi", "Hyderabad", "Lahore", "Islamabad", "Moro"];
  print(" Q10 Cities Name List : ");
  print("Before Shuffle Cities List");
  print(citiesList);
  citiesList.shuffle();
  print("After Shuffle Cities List");
  print(citiesList);

  print("____________________________________________________");

  // Q11. Fruit List Challenge

  List fruits = ['Apple', 'Mango', 'Banana'];
  print(" Q11 Fruits Name List : ");
  print("Before Shuffle fruits List");
  print(fruits);
  fruits.addAll(['Orange', 'Grapes']);
  print("After  fruits Add : ");
  print(fruits);
  fruits.shuffle();
  print("After Shuffle fruits List");
  print(fruits);
  print("The length of fruits list is : ${fruits.length}");

  print("____________________________________________________");

  // Q12 Names List Challenge

  List namesList = [];
  //Adding Names by add method
  print(" Q12 Names List: ");
  namesList.add("Abdul Raheem");
  namesList.add("Ammarah");
  namesList.add("Jabees");

  //Adding Names by add method
  namesList.addAll(["Usman", "Afnan", "Hamza"]);
  print(namesList);
  print("The length of Name list is : ${namesList.length}");

  print("____________________________________________________");

  // Q13 Numbers List Challenge

  List num2 = [10, 20, 30, 40];
  print(" Q13 Numbers List: ");
  num2.add(50);
  num2.addAll([60, 70]);
  print("Before Shuffle Numbers List");
  print(num2);
  num2.shuffle();
  print("After Shuffle Numbers List");
  print(num2);
  print("The length of Number list is : ${num2.length}");

  print("____________________________________________________");

  // Q14 Favorite Foods Challenge

  List favFoodsList = ["Chiken Biryani", "Burger", "Chicken Roll"];
  print(" Q14 Fav Foods List: ");
  print("Before Adding 2 moew Fav foods List");
  print(favFoodsList);
  favFoodsList.addAll(["Beef pulao", "Mutton"]);
  favFoodsList.shuffle();
  print("After Adding 2 more Fav foods List & Shuffle List");
  print(favFoodsList);

  print("____________________________________________________");

  // Q15 Student Lists Challenge

  List stdList1 = ["Owais", "Sherry", "Wajahat"];
  List stdList2 = ["Fahad", "Nayab", "Zain"];
  print(" Q15 Stduents List: ");
  stdList1.addAll(stdList2);
  print("Before Shuffle Students List");
  print(stdList1);
  stdList1.shuffle();
  print("After Shuffle Students List");
  print(stdList1);
  print("The length of Students list is : ${stdList1.length}");
  print("____________________________________________________");
}
