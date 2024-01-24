[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
/*# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus

* Name: Josh Leon
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {
private:
    std::string model;
    int year;
    std::string color; 
    
public:

    
    void getModel()
    {
        std::cout << "Please enter the model of your car: " << std::endl;
        std::cin >> model;
    }

    void getYear()
    {
        std::cout << "Please enter the year of your car: " << std::endl;
        std::cin >> year;
    }

    void getColor()
    {
        std::cout << "Please enter the color of your car: " << std::endl;
        std::cin >> color;
    }

    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }


};

int main() {
    Car myCar;

    myCar.getYear();
    
    myCar.getModel();
    
    myCar.getColor();
    
    myCar.displayDetails();

    return 0;
}

