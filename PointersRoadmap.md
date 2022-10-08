# Pointers
### **What are pointers?**
- Pointers in C are easy and fun to learn. Some C programming tasks are performed more easily with pointers, and other tasks, such as dynamic memory allocation, cannot be performed without using pointers. So it becomes necessary to learn pointers to become a perfect C programmer. Let's start learning them in simple and easy steps.
### **Types Of Pointers**  </br>
There are majorly four types of pointers, they are:
- Null Pointer
- Void Pointer
- Wild Pointer
- Dangling Pointer 
### **Let's Have a Deeper Knowledge**
> PASSING ARRAYS BY USING POINTERS
- A whole array cannot be passed as an argument to a function in C++. You can, however, pass a pointer to an array without an index by specifying the array’s name.

 ## **CPP Program to demonstrate passing an array to a function is always treated as a pointer-**  </br>
#include <iostream> </br>
using namespace std;
</br> 
// Note that arr[] for fun is </br>
// just a pointer even if square  </br>
// brackets are used  </br>
void fun(int arr[]) // SAME AS void fun(int *arr)  </br>
{ </br>
    unsigned int n = sizeof(arr) / sizeof(arr[0]); </br>
    cout << "\nArray size inside fun() is " << n; </br>
} </br>
 
// Driver Code </br>
int main() </br>
{ </br>
    int arr[] = { 1, 2, 3, 4, 5, 6, 7, 8 }; </br>
    unsigned int n = sizeof(arr) / sizeof(arr[0]); </br>
    cout << "Array size inside main() is " << n; </br>
    fun(arr); </br>
    return 0; </br>
} </br>

### **OUTPUT** </br>
Array size inside main() is 8 </br>
Array size inside fun() is 1 </br>
> Roadmap For Learning Pointers
 - First learn about the basics of Pointers 
 - Then start solving Questions </br>
 Link for solving basic questions on pointers is given below-
 ##### [Pointers Questions](https://www.codesdope.com/practice/cpp-pointers/)
 - After solving sufficient questions move to Class Pointers.
 
 > Use of Pointers in Data, Structures and Algorithm
 - Pointers are the variables that are used to store the location of value present in the memory. A pointer to a location stores its memory address. The process of obtaining the value stored at a location being referenced by a pointer is known as dereferencing. It is the same as the index for a textbook where each page is referred by its page number present in the index. One can easily find the page using the location referred to there. Such pointers usage helps in the dynamic implementation of various data structures such as stack or list. </br>
 > Why do we need Pointers in C </br>
 - Optimization of our code and improving the time complexity of one algorithm. Using pointers helps reduce the time needed by an algorithm to copy data from one place to another. Since it used the memory locations directly, any change made to the value will be reflected at all the locations. </br>
Example: </br>
- Call_by_value needs the value of arguments to be copied every time any operation needs to be performed.
- Call_by_reference makes this task easier using its memory location to update the value at memory locations.
### When you're done with it try to have a good grasp on other topics as well and BE CONSISTENT!!
## HAPPY HACKING 💻 🧑‍🎓!
