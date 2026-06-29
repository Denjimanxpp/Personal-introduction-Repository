# Personal-introduction-Repository
Working code with Cin and Cout. 
Use the type “int” to hold numbers. Don’t worry about names this week. Kudos if you can figure it out yourself. 
Create a program that executes your information (introduction of who you are)
Name (First Last)
Goals in Life
Current Interests
Dreams
Where you expect to see yourself in the next 1,3,5, and 7 years.

What I did for my code is that I used Var instead of using the standard library character out because I thought it would be better to use Var instead of the character out for not writing the std::cout<<" what I need to write"; so on and so forth. 
It was the same thing as writing hello world but I needed to declare the var and to print the var to the screen. 
I also needed to make sure that the code was able to end each line with a semi colon and to return the value with a zero. 

Also included the variables to also have integers to number each section on what they needed. 

This is the code:

#include <iostream>
int main() 
{
    int x=1;
    std::string Name = ". My name is Jaydin Colon. ";
    std::cout << x;
    std::cout <<Name; 
    int y=2;
    std::cout << y;
    std::string goals=". My goals are to become a data analyst and to learn more about programming. And to also learn about Ai. ";
    std::cout << goals;
    int w=3;
    std::cout << w;
    std::string interests=". I'm interested in guitars, Avenged Sevenfold, and programming. ";
    std::cout << interests;
    int v=4;
    std::cout << v;
    std::string dream=". My dream is to just be happy in life. ";
    std::cout << dream;
    int u=5;
    std::cout << u;
    std::string years=". I see myself in 5 years in the Marine Corps and also working as a data analyst. ";
    std::cout << years;
    return 0;
}