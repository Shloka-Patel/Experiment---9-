# Experiment---9 

### Aim 

### Theory 

### Software Used 
Visual Studio Code <br> 

### Code 

(A) <br> 
```
// Program to illustrate pointers. 

#include <bits/stdc++.h> 
using namespace std;
void geeks()
{
    int var = 5;

    int* ptr;                  // Declaring pointer variable. 

    ptr = &var;

    cout<<"Value at ptr = "<<ptr<<"\n";
    cout<<"Value at var = " <<var<<"\n";
    cout<<"Value at *ptr = "<<*ptr<<"\n";

}

// Driver Program 

int main()
{
    geeks();
    return 0;
} 
```

(B) <br> 
```
// Program to create one-dimensional array of pointers. 

#include <iostream> 
using namespace std; 

int main() 
{
    int* p=new int[7];  // Creating an array 

    for (int i=0; i<5; i++)  // Initializing the aray p[]
    {
        p[i]=10*(i+1);
    }

    cout<<*p<<"\n"; 
    cout<<*p+1<<"\n";
    cout<<*(p+1)<<"\n";
    cout<<2[p]<<"\n";
    cout<<p[2]<<"\n";
    *p++;

    cout<<*p;                 // Pointing to next location. 

    return 0; 
}
```

### Output 

(A) <br> 
![](https://github.com/Shloka-Patel/Experiment---9-/blob/main/Output_9A.png) 

(B) <br> 
![](https://github.com/Shloka-Patel/Experiment---9-/blob/main/Output_9B.png) 

### Conclusion 
