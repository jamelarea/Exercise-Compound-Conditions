# Exercise-Compound-Conditions

SLIDE 16, Mark my Words
    
    #include <iostream>
    using namespace std;

     int main()
     {
     int grade;
     
     cout << "Enter the student's grade: ";
     cin >> grade;
     
      if (grade >= 70)
        cout << "Student's mark = A";
      if (grade >= 60 && grade <= 69)
        cout << "Student's mark = B";
      if (grade >= 50 && grade <= 59)
        cout << "Student's mark = C";
      if (grade >= 40 && grade <= 49)
        cout << "Student's mark = D";
      if (grade <= 40)
        cout << "Student's mark = F";
     
     }
  
SLIDE 17, Starting a Band

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        bool musicalFriend = true;

        cout << "What instrument can you play? ";
        string x;
        cin >> x;

        string friendPlays1 = "Guitar";
        string friendPlays2 = "guitar";
        string friendPlays3 = "Drums";
        string friendPlays4 = "drums";

        if (musicalFriend = true) {
            if (x == friendPlays1 || x == friendPlays2 || x == friendPlays3 || x == friendPlays4) {
                cout << "Congratulations! you can join the band" << endl;
            } else {
                cout << "Sorry, you cannot join the band.." << endl;
            }
        }
    }
    
SLIDE 19, Killing Time
    
    #include <iostream>
    using namespace std;

    int main()
    {
        int mins, money;

        cout << "How many minutes before your friend goes with you? ";
        cin >> mins;

        if (mins >= 15) {
            cout << "\nSince your friend is going to arrive for another 15 minutes or more,\nhow much money do you have in change? ";
            cin >> money;

            if (money >= 5) {
                cout << "\nGo buy a coffee" << endl;
            } else {
                cout << "\nConsidering that you don't have enough change to buy a coffee,\ngo for a walk around the town" << endl;
            }
        }
        if (mins < 15) {
            cout << "\nYour friend is going to arrive soon, sit in the food zone and wait";
    return 0;
        }
    }
    
SLIDE 20, Earthquake

    #include <iostream>
    using namespace std;

    int main()
    {
        double magnitude;

        cout << "Enter the magnitude of the earthquake: ";
        cin >> magnitude;

        if (magnitude <= 2.0)
        {
            cout << "The earhquake is MICRO" << endl;
        }
        else if (magnitude >= 2.0 && magnitude <= 3.0)
        {
            cout << "The earthquake is VERY MINOR" << endl;
        }
        else if (magnitude >= 3.0 && magnitude <= 4.0)
        {
            cout << "The earthquake is MINOR" << endl;
        }
        else if (magnitude >= 4.0 && magnitude <= 5.0)
        {
            cout << "The earthquake is LIGHT" << endl;
        }
        else if (magnitude >= 5.0 && magnitude <= 6.0)
        {
            cout << "The earthquake is MODERATE" << endl;
        }
        else if (magnitude >= 6.0 && magnitude <= 7.0)
        {
            cout << "The earthquake is STRONG" << endl;
        }
        else if (magnitude >= 7.0 && magnitude <= 8.0)
        {
            cout << "The earthquake is MAJOR" << endl;
        }
        else if (magnitude >= 8.0 && magnitude <= 10.0)
        {
            cout << "The earthquake is GREAT" << endl;
        }
        else if (magnitude >= 10)
        {
            cout << "The earthquake is METEORIC" << endl;

            return 0;
        }
    }
