# -OOPS-EXP.2
C++ program for real world entity ,demonstrating access specifiers and member functions

#include <iostream>
using namespace std;

class BankAccount {
private:
    int acc_no;
    double balance;

public:
    // Default Constructor
    BankAccount() {
        acc_no = 101;
        balance = 1000.0;
    }

    void Display() {
        cout << "--- Bank Account Details ---\n";
        cout << "Account Number: " << acc_no << endl;
        cout << "Balance: ₹" << balance << endl;
    }};

int main() {
    BankAccount b1; // Creating an object of the class
    b1.Display();   // Calling the member function

    return 0;
}
