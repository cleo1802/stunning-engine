# stunning-engine
#include <iostream>


using namespace std;

int main()
{

    cout << "Machine Problem 1" << endl;


    double adultprice, childprice, adultsold, childsold, sold, gross, percentage, donated, net;
    string name;


    cout << "Movie name: ";
    std::getline(std::cin, name);
    cout << "Adult Ticket Price: ";
    cin >> adultprice;
    cout << "Child Ticket Price: ";
    cin >> childprice;
    cout << "Number of adult tickets sold: ";
    cin >> adultsold;
    cout << "Number of child tickets sold: ";
    cin >> childsold;
    cout << "Percentage of gross amount to be donated to charity: ";
    cin >> percentage;
    cout << endl;

    cout << "Ticketing System" << endl << endl;

    cout << "Movie name: " << name << endl;
sold = childsold + adultsold;
    cout << "Number of Tickets sold: " << sold << endl;
gross = (childprice * childsold) + (adultprice * adultsold);
    cout << "Gross Amount: " << gross << endl;
    cout << "Percentage of Gross Amount Donated: " << percentage <<endl;
donated = gross * percentage/100;
    cout << "Amount Donated: " << donated << endl;
net = gross - donated;
    cout << "Net Sale: " << net << endl;
}

