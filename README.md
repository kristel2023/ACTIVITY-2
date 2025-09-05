# ACTIVITY-2
#include <iostream>
#include <string>
using namespace std;

int main() {
    // Declare variables to store user input
    string fullName, courseYearSec, birthday, motto;

    // Get inputs from the user
    cout << "Input Full name: ";
    getline(cin, fullName);

    cout << "Input Course, Yr. & Sec.: ";
    getline(cin, courseYearSec);

    cout << "Input Birthday: ";
    getline(cin, birthday);

    cout << "Input Motto/Motivation in Life: ";
    getline(cin, motto);

    // Display the collected information
    cout << "\n===== PERSONAL INFORMATION =====" << endl;
    cout << "Full Name          : " << fullName << endl;
    cout << "Course, Yr. & Sec. : " << courseYearSec << endl;
    cout << "Birthday           : " << birthday << endl;
    cout << "Motto in Life      : " << motto << endl;
    cout << "================================" << endl;

    return 0;
}

