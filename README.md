# Lab-9.30
#include <iostream>
using namespace std;

int main() {
  
  double average;    // holds the grade average

	cout << "Input your average:" << endl;
	cin >> average;

  if (average == 100)
    cout << "Invalid data" << endl;
  else if (average >= 90)
		cout << "A" << endl;
	else if (average >= 80)
		cout << "B" << endl;
  else if (average >= 70)
    cout << "You pass" << endl;
  else if (average >= 60)
    cout << "You pass" << endl;
  else if (average <=59)
    cout << "you fail" << endl;
  
  

}
