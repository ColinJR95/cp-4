# cp-4
bool and logic
  bool b;
  b = false;
  b = true;
  ! // means not
  || //means or
  && //means and 
Look up truth table- 
|| // if a is true and b is false this sign will make it go true.
&& //if a is true and b is false then it will be false. 
when you have !a it is asking for the opposite of what a is.. so if a is true then !a is false. 

comparison operators remember to not confuse them with equals 
    ==
    !=
    <
    >
    <=
    >=
Example
{    
    int x = 3, y=5;
    if (x < y) // this is the condition
              // if the condition is true, then it will read the next line 
    cout << "blah";
}

int main()
{
  int x, y;
  cout << "first number: ";
  cin >> x;
  cout >> " second number: ";
  cin >> y,
  if( x == y) 
  {
  cout << "equal";
  }
  else if( x < y)
  { 
      cout << " second is bigger";
  }
return 0;


//NEW Example

int t;
cout << "temperature?";
cin >> t;
if( t > 85)
{
  cout << "too hot";
}
else if( t > 65 && t <= 85)
{
cout << "just right";
}
else if( t < 40 )
{
  cout << "hypothermia";
}
  if (t > 110)
{
  cout << "heat stroke";
}
return 0;

MORE COMPLICATED CODE:

int age;
cout << "what is your age?"
cin >> age;
if (age < 13)
{
  cout << "go play outside"<< endl;
}
else if(age < 18)
{
  cout << "come back when you have moeny" << endl;
}
else 
{
  cout <<" NIGERIAN PRINCE HAS MONEY. What is you SSN?"
  char ssn[9];
  cin >> ssn;
  cout << "thanks!" << endl;

return 0;

  
if ( b ==c) //you are comparing memory addresses. 

#include <cstring>

strcmp(x,y) // this stands for string compare. 
            //this is all happenind from the ASCII table 

ACTIVITY 

Write- input, logic, output
  //check if an interger is even
  //check if word come before the metter m/M in the dictionary
  //check if character is digit
  //check if character is capital or lowercase letter
  
SOLUTION:

int x; 
cin >> x;
if( x % 2 == x)
{
  cout << "even";
}
else
{
  cout << "odd";
}

SOLUTION FOR DIGIT:

char c;
cin >> c;
if( c >= '0' && c <= '9')
{
  cout << "digit";
}

SOLUTION FOR LAST COMMENT:

char c;
cin >> c;
if( c >= 'A' && C <='Z')
{
  cout << "capital"; //majiscule 
}
else if( c >= 'a' && c <= 'z')
{
  cout << "lowercase"; // miniscule 
}

SOLUTION FOR CHEING IF WORK COMES BEFORE LETTER m/M

char word[20]
cin >> word;
if((strcmp(word, "m") < 0 && strcmp(word, "a") >= 0) //remember capital and lowercase are in two separate dictionaries
|| (strcmp(word, "A") >= 0 && strcmp(word, "M") <0))
{
  cout << "before m/M";


//digits --->capital---->  lowercase //in the ASCII table 

int gal1, gal2, mi1, mi2;
cout << "gallons?";
cin >> gal1;
cout << "Miles?";
cin >> mi1;
cout >> "2nd car gallons?";
cin >> gal2
cout << "miles?";
cin >> mi2;
if( mi1/gal1 < mi2/gal2)
{
  cout <<"first is more efficient";
}
else if( mi1/gal1 < mi2/gal2)
{
  cout << "second more efficient";
}
else
{
  cout << "equal";
}

NEW LESSON
    //everytime you hit the wordbreak, it willgo to the end of the code. 
int x;
cin >> x;
switch(x)
{
  case 1:
  //code
  break;
case 5:
//code
break;

CONDITIONAL OPERATOR  ?: //LOOK THIS UP


  
            

  
  
