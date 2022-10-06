# Virtual-function
A virtual function is a member function in the base class that we expect to redefine in derived classes.


Basically, a virtual function is used in the base class in order to ensure that the function is overridden.
 This especially applies to cases where a pointer of base class points to an object of a derived class.

For example, consider the code below:

class Base {
   public:
    void print() 
{
        // code
    }
};

class Derived : public Base {
   public:
    void print() 
{
        // code
    }
};
