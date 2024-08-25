#include <iostream>
using namespace std;

int main() { 
    int num = 1; 
    int number; 
    int total = 0; 
    
    cout << "Loop Number is: " << num << endl;
    cout << "Total is: " << total << endl;
    while (num <= 5) { 
        
        cin >> number; 
        cout << "User wants to add " << number << " to Total " << total << endl;
        total += number; 
        cout << "New Total is: " << total << endl;
        num++; 
        cout << endl;
        cout << "New Loop Number is " << num << endl;
        
    } 
    cout << "New Loop Number is not <= 5.  Loop has ended." << endl;
    cout << endl;
    cout << "Your total is " << total << endl; 
	return 0;
