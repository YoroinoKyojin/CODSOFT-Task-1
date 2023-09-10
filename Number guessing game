#include<iostream>
#include<cstdlib>
#include<time.h>
using namespace std;

int main()
{
    std::cout<<"----------You know, we can make our mundane lives more interesting by playing games-------------";
    std::cout<<"\n";
    std::cout<<"----------So why not we play a game where the system decides a number and our task is to guess the number------------";
    std::cout<<"\n";
    std::cout<<"----------So what are we waiting for let's dive in! :)------------------";
    std::cout<<"\n";
    int number;
    int N;
    std::cout<<"Enter max limit : ";
    std::cin>>N;
    srand(time(0));
    number=rand()%N;
    int k;
    std::cout<<"Please enter number of trials";
    std::cin>>k;
    std::cout<<"Game starts";
    std::cout<<"\n";
    std::cout<<"\n";
    int i, guess;
    for(int i=1;i<=k;i++)
    {
        std::cout<<"Please guess the number : ";
        std::cout<<"\n";
        std::cin>>guess;
        if(guess==number)
        {
            std::cout<<"You win the game. You chose the right number";
            std::cout<<"\n";
            break;
        }
        else if(guess>number && i!=k)
        {
            std::cout<<"Your guess is higher than the number. Please try again\n";
        }
        else if(guess<number && i!=k)
        {
            std::cout<<"Your guess is lower than the number.Please try again\n";
        }
        else if (i == k) 
        {
        std::cout<<"You have exhausted the given number of trials";
        std::cout<<"\n";
        std::cout<<"The number was";
        std::cout<<"\n";
        std::cout<<number;
        break;
        }
    }
    return 0;
}
