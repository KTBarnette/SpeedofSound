//
//  main.cpp
//  Lab4 code
//
//  Created by Kyle T. Barnette on 2/8/23.
//
/* Kyle Barnette
 Chapter 4 Lab - The Speed of Sound
 COSC 1337-003 (55111) Katharine Susman
 This Program will allow the user to choose from a menu with three different options: Air, Water, and Steel and calculate how long it will take for sound to travel through the desired length in feet.
 */



#include <iostream>
#include <iomanip>
#include <string>
#include <cmath>
using namespace std;

int main()
{
    // Named constants for speeds of 3 different substances
    const int AIR_SPEED = 1100;
    const int WATER_SPEED = 4900;
    const int STEEL_SPEED = 16400;
    
    // Variables needed to execute the program
    float feet;
    float time;
    char substance;
    bool validInput = true;
    string medium;
    
    // Display what the program does
    cout << "This Program will tell you how long it takes a sound wave to travel a specific distance through a particular medium." << endl;
    
    // Menu to choose a substance
    cout << "Select a substance for the sound to travel through 1, 2, or 3: " << endl;
    // Choice 1 : Air
    // Choice 2 : Water
    // Choice 3 : Steel
    cout << "1. Air" << endl;
    cout << "2. Water" << endl;
    cout << "3. Steel" << endl;
    
    // Get user's menu option
    cin >> substance;
    
    // This will validate the input
    if (substance == '1' || substance == '2' || substance == '3')
    
    // Obtain how far the sound wave will travel
    {cout << "Enter the number of feet the sound wave will travel:" << endl;
        cin >> feet;
    }
    
    
    
    // This will calculate the time it takes for the sound wave to travel through the respected substance
    // This will equate the user's menu option to it's medium
    switch (substance)
    {
        case '1':
            time = (feet / AIR_SPEED);
            medium = "air";
            break;
        case '2':
            time = (feet / WATER_SPEED);
            medium = "water";
            break;
        case '3':
            time = (feet / STEEL_SPEED);
            medium = "steel";
            break;
        default: cout << "You did not enter 1, 2, or 3!\n";
            validInput = false;
        
    }
    

    
    if (validInput)
    {
        // Display the output
        cout << "The sound wave will travel " << feet << " feet through " << medium << " in " << fixed << setprecision(4) << time << " seconds." << endl;
        
        
        
        
        
        
        
    }
    return 0;
}
