# Debugging-Game


    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
      int i = 1, j = 1;
      while (i <= 5)
      {
        j = 1;
        while (j <= i)
        {
          cout << "*"; 
          j++;
        }
        cout << endl;
        i++;
      }

    }
  
  /////////
  
      #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
      int y, x = 0;
      cout << "Enter a number you want the table of: " << endl;
      cin >> y;
      while (cin.fail())
      {
        cout << "Invalid command enter the number again: " << endl;
        cin.clear();
        cin.ignore(1000, '\n');
        cin >> y;
      }
      while (x <= 10)
      {
        cout << y << " x " << x << " = " << y * x << endl;
        x++;
      }

    }
                                                     
  /////////                                
                                                     
    #include<iostream> 
    #include<string> 
    using namespace std;
    int main()
    {
      int y, z = 1;
      cout << "enter a number you want the factorial of: " << endl;
      cin >> y;
      while (cin.fail() || y <= 0)
      {
        cout << "invalid command enter the number again: " << endl;
        cin.clear();
        cin.ignore(1000, '\n');
        cin >> y;
      }

      for (int x = 1; x <= y; x++)

        z = z * x;
      cout << "factorial is: " << z;

    }
                               
  /////////

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
      int x = 0;
      int sum = 0;
      do
      {
        x++;
        if (x % 9 == 0)
        {
          cout << "\nNumber is " << x << " ";
          sum = sum + x;
        }

      } while (x <= 200);
      cout << endl;
      cout << "\nThe sum is " << sum << endl;

    }
                                        
  /////////

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
      int x = 0;
      int sum = 0;
      do
      {
        x++;
        if (x % 9 == 0)
        {
          cout << "\nNumber is " << x << " ";
          sum = sum + x;

        }

      } while (x <= 200);
      cout << endl;
      cout << "\nThe sum is " << sum << endl;
    }

  /////////
                      
    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
      for (int x = 20; x <= 24; x++)
      {
        if (x %2 =0)
          cout << x << " - even" << "\n";
        else
          cout << x << " - odd" << "\n";
      }

    }
                      
  /////////

    #include <iostream>
    using namespace std;
    int main()
    {
      cout << "Hello User!! This is the program that takes 3 subject marks and display the average\nThe marks should be from 0-100" << endl;
      cout << "Enter Marks for 1st Subject" << endl;
      double s1, s2, s3;
      int average;
      cin >> s1;
      //first if statement
      if (s1 >= 0 && s1 <= 100 && !cin.fail())
      {
        cout << "Enter the marks for 2nd Subject" << endl;
        cin >> s2;
        if (s2 >= 0 && s2 <= 100 && !cin.fail())
        {
          cout << "Enter the marks for 3rd Subject" << endl;
          cin >> s3;
          if (s3 >= 0 && s3 <= 100 && !cin.fail())
          {
            average = (s1 + s2 + s3) / 3;
            cout << "Your average is " << average << endl;
          }
          else
          {
            cout << "Incorrect command" << endl;
          }
        }
        else
        {
          cout << "Incorrect command" << endl;
        }

      }
      //first else
      else
      {
        cout << "Incorrect command" << endl;
      }

    }

  /////////
                                       
    #include <iostream>
    using namespace std;
    int main()
    {
      string m;
      cout << " Do you want to go to the expo? type Y for yes and N for no" << endl;
      string mall;
      cin >> mall;
      if (mall == "Y" || mall == "y")
      {
        cout << "Enjoy" << endl;
      }
      else if (mall == "N" || mall == "n")
      {
        cout << "Unfortunately its mandatory, you have to go" << endl;

      }
      else
      {
        cout << "Incorrect command" << endl;

      }
    }
  
  
  
                               


