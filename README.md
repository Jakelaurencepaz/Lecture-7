# Nested-If-HOMEWORK
Task 1

        #include<iostream>
        using namespace std;

        int main()
    {
    int number = 75;
    cout << "enter the students grade : " << endl;
    cin >> number;

    if (number >= 70) {
        cout << "the student's grade is a A";
    }
    else {
        if (number <= 70) {
            cout << "the student's grade is a B";

        }
    }
    }









Task 2

    #include<iostream>
    #include<string>
     using namespace std;

     int main()
      {
    bool musicalFriend = true;
    string friendPlays = "guitar";
    string yesNo;

    cout << "What intrument do you play?" << endl;
    cin >> friendPlays;

    if (friendPlays == "guitar") {
      cout << "do you want to join the band?" << endl;
      cin >> yesNo;

      if (yesNo == "yes") {
        cout << " welcome to the band" << endl;
      }
      else
        cout << " okay thank you for participating" << endl;

    }else{
      cout << "okay bye" << endl; 
    }


     }
     
     
  Task 3 
  
  
  
  
