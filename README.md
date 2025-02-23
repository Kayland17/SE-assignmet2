# SE-assignment2
#include<iostream>
#include<string>
void greet_user(){
std::string name;
std::string greeting;

std::cout<<"What's your name? ";
std::getline(std::cin, name);

greeting = "Helo World";

std::cout<< greeting << "," << nanme << "!" <<std::endl;
}

int main(){
greet_user();
return 0;
}
