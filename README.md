# algorithins-and-programming-car-directory
Write a complete C or C++ program to implement a car service directory. Structure contains name and surname of the owner, car id, model, registration date and next service date as day, month, year and phone number of the car owner. Your program should have the following menu. Write necessary functions for the menu:

Menu:
1- Add a new car to directory
2- Delete a car from the directory
3- List available cars in the directory
4- Search a car: 
     A – Search according to car id
     B – Search according to owner_name 
5- Update car information
6- Sort according to car id
7- Sort according to owner_name
8- Quit

struct date
       {
       int day, month, year;
       };
struct car
       {
       
       int ID;
       char owner_name[20], owner_surname[20], model[20];
       struct date reg_date, ns_date; 
       }car_directory[100];
