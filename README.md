# Ankur-s  Q1.
#include <iostream>
using namespace std;

int main()
{
    int a = 5, b = 10, temp;

    cout << "Before swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    temp = a;
    a = b;
    b = temp;

    cout << "\nAfter swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    return 0;
}
Q2.#include <iostream>
using namespace std;

int main() {    
    float n1, n2, n3;

    cout << "Enter three numbers: ";
    cin >> n1 >> n2 >> n3;

    if(n1 >= n2 && n1 >= n3)
        cout << "Largest number: " << n1;

    if(n2 >= n1 && n2 >= n3)
        cout << "Largest number: " << n2;
    
    if(n3 >= n1 && n3 >= n2)
        cout << "Largest number: " << n3;
  
    return 0;
}
Q3 
#include <iostream>
using namespace std;

int main() {
    int year;

    cout << "Enter a year: ";
    cin >> year;

    if (year % 4 == 0) {
        if (year % 100 == 0) {
            if (year % 400 == 0)
                cout << year << " is a leap year.";
            else
                cout << year << " is not a leap year.";
        }
        else
            cout << year << " is a leap year.";
    }
    else
        cout << year << " is not a leap year.";

    return 0;
}
Q4.#include <iostream>
using namespace std;

int main() {
    int n, t1 = 0, t2 = 1, nextTerm = 0;

    cout << "Enter the number of terms: ";
    cin >> n;

    cout << "Fibonacci Series: ";

    for (int i = 1; i <= n; ++i) {
        // Prints the first two terms.
        if(i == 1) {
            cout << t1 << ", ";
            continue;
        }
        if(i == 2) {
            cout << t2 << ", ";
            continue;
        }
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
        
        cout << nextTerm << ", ";
    }
    return 0;
}
Q5#include <iostream>
using namespace std;

int main() {
    int i, n;
    bool isPrime = true;

    cout << "Enter a positive integer: ";
    cin >> n;

    // 0 and 1 are not prime numbers
    if (n == 0 || n == 1) {
        isPrime = false;
    }
    else {
        for (i = 2; i <= n / 2; ++i) {
            if (n % i == 0) {
                isPrime = false;
                break;
            }
        }
    }
    if (isPrime)
        cout << n << " is a prime number";
    else
        cout << n << " is not a prime number";

    return 0;
}
Q6.// C++ code to demonstrate star pattern
#include <iostream>

using namespace std;
 
// Function to demonstrate printing pattern

void pypart(int n)
{

    // Outer loop to handle number of rows

    // n in this case

    for (int i = 0; i < n; i++) {
 

        // Inner loop to handle number of columns

        // values changing acc. to outer loop

        for (int j = 0; j <= i; j++) {
 

            // Printing stars

            cout << "* ";

        }
 

        // Ending line after each row

        cout << endl;

    }
}
 
// Driver Function

int main()
{

    int n = 5;

    pypart(n);

    return 0;
}
Q7.// C++ program to find second largest
// element in an array
 
#include <bits/stdc++.h>

using namespace std;
 
/* Function to print the second largest elements */

void print2largest(int arr[], int arr_size)
{

    int i, first, second;
 

    /* There should be atleast two elements */

    if (arr_size < 2) {

        printf(" Invalid Input ");

        return;

    }
 

    // sort the array

    sort(arr, arr + arr_size);
 

    // start from second last element

    // as the largest element is at last

    for (i = arr_size - 2; i >= 0; i--) {

        // if the element is not

        // equal to largest element

        if (arr[i] != arr[arr_size - 1]) {

            printf("The second largest element is %d\n", arr[i]);

            return;

        }

    }
 

    printf("There is no second largest element\n");
}
 
/* Driver program to test above function */

int main()
{

    int arr[] = { 12, 35, 1, 10, 34, 1 };

    int n = sizeof(arr) / sizeof(arr[0]);

    print2largest(arr, n);

    return 0;
}
#include <bits/stdc++.h> Q8
using namespace std;
string ltrim(const string &);
string rtrim(const string &);
vector<string> split(const string &);
 * Complete the 'rotateLeft' function below.
 * The function is expected to return an INTEGER_ARRAY. * The function accepts following parameters:
vector<int> rotateLeft(int d, vector<int> arr) {
vector<int> rotateLeft(int d, vector<int> arr) {

int main()

    ofstream fout(getenv("OUTPUT_PATH"));
    ofstream fout(getenv("OUTPUT_PATH"));
    string first_multiple_input_temp;

    getline(cin, first_multiple_input_tempù);
    getline(cin, first_multiple_input_tempù);
    vector<string> first_multiple_input = split(rtrim(first_multiple_input_temp))
;
    vector<string> first_multiple_input = split(rtrim(first_multiple_input_temp));

    int n = stoi(first_multiple_input[0]);

    int n = stoi(first_multiple_input[0]);
    int d = stoi(first_multiple_input[1]);

    string arr_temp_temp;

    getline(cin, arr_temp_temp);

    vector<string> arr_temp = split(rtrim(arr_temp_temp));
    vector<int> arr(n);

    for (int i = 0; i < n; i++) {
        int arr_item = stoi(arr_temp[i]);

        arr[i] = arr_item;
    vector<int> result = rotateLeft(d, arr);

    for (size_t i = 0; i < result.size(); i++) {

        fout << result[i];

        if (i != result.size() - 1) {
            fout << " ";
    fout << "\n";

    fout.close();
    return 0;
    }

string ltrim(const string &str) {

    s.erase(

        s.begin(),

        find_if(s.begin(), s.end(), not1(ptr_fun<int, int>(isspace)))
        find_if(s.begin(), s.end(), not1(ptr_fun<int, int>(isspace)))


Q9.#include <bits/stdc++.h>
using namespace std;
string ltrim(const string &);

string rtrim(const string &);

 * Complete the 'gradingStudents' function below.
 * The function is expected to return an INTEGER_ARRAY.
vector<int> gradingStudents(vector<int> grades) {
int main()

{

    ofstream fout(getenv("OUTPUT_PATH"));
    string grades_count_temp;
    getline(cin, grades_count_temp);
    int grades_count = stoi(ltrim(rtrim(grades_count_temp)));
    vector<int> grades(grades_count);
    for (int i = 0; i < grades_count; i++) {

    vector<int> grades(grades_count);
    for (int i = 0; i < grades_count; i++) {
    for (int i = 0; i < grades_count; i++) {
        string grades_item_temp;

        getline(cin, grades_item_temp);

        getline(cin, grades_item_temp);
        int grades_item = stoi(ltrim(rtrim(grades_item_temp)));

        grades[i] = grades_item;
    vector<int> result = gradingStudents(grades);

    vector<int> result = gradingStudents(grades);
Q10.
#include <bits/stdc++.h>
using namespace std;

 * Complete the 'camelcase' function below

 * The function is expected to return an INTEGER.
 * The function accepts STRING s as parameter.
int camelcase(string s) {
int main()
{
    ofstream fout(getenv("OUTPUT_PATH"));

    string s;
    getline(cin, s);

    int result = camelcase(s);

    fout << result << "\n";

    fout.close();
    return 0;
}
