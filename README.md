# COP2334-1-Pearson-Module-5-Revel-Quiz-5.5.1
This is a GitHub repository link for the Pearson Module 5 Revel of Quiz 5.5.1.

//This basic interface program is created for a library management system.

//Header files
#include <iostream>
using namespace std;
//Function prototypes
int main() {
  char choice;
//Display the menu
  do
    {
      cout << "Enter A to add a book, S to search, or E to exit: ";
      cin >> choice;

      if (choice == 'A' || choice == 'a')
      {
        cout << "Add a book" << endl;
      }
      else if (choice == 'S' || choice == 's')
      {
        cout << "Search for a book" << endl;
      }
    }
    while (choice != 'E' && choice != 'e');
}
