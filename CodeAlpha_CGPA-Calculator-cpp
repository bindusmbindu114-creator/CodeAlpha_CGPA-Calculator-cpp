#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    int n;
    float grade, credit;
    float totalCredits = 0;
    float totalGradePoints = 0;

    cout << "Enter number of courses: ";
    cin >> n;

    cout << "\nEnter grade and credit hours for each course:\n";

    for (int i = 1; i <= n; i++) {
        cout << "\nCourse " << i << ":\n";

        cout << "Enter grade point: ";
        cin >> grade;

        cout << "Enter credit hours: ";
        cin >> credit;

        totalCredits += credit;
        totalGradePoints += grade * credit;
    }

    // Calculate GPA
    float gpa = totalGradePoints / totalCredits;

    // For one semester, GPA is the CGPA
    float cgpa = gpa;

    cout << "\n-----------------------------\n";
    cout << "Total Credits       : " << totalCredits << endl;
    cout << "Total Grade Points  : " << totalGradePoints << endl;
    cout << fixed << setprecision(2);
    cout << "Semester GPA        : " << gpa << endl;
    cout << "Overall CGPA        : " << cgpa << endl;
    cout << "-----------------------------\n";

    return 0;
}