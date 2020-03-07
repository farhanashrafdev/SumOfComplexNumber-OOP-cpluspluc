#include<iostream>
using namespace std;

class Complex {

 
public: 
	Complex() { real = 0.0; imaginary = 0.0; };
		void operator >> ( Complex & obj) {
			cout << "Enter the real part: ";  cin >> real;
			cout << "Enter the imaginary part: "; cin >> imaginary;
		}
		void operator <<(Complex& obj) {
			cout<< real << endl;
			cout << imaginary << endl;
		}
		void operator ==(Complex & obj)
		{
			cout << "Enter real to campare:"; cin >> obj.real;
			cout << "Enter Imaginary part to campare"; cin >> obj.imaginary;
			if (real == obj.real)
				cout << "Real are equal: " << endl;
			else cout << "Real are not equal: ";
			if (imaginary == obj.imaginary)
				cout << "Imaginary are  equal: " << endl;
			else cout << "Imaginary are not equal:";


		}
		void operator +(Complex& obj)
		{
			cout << "Enter real to ADD:"; cin >> obj.real;
			cout << "Enter Imaginary part to ADD"; cin >> obj.imaginary;
			real += obj.real;	
			imaginary += obj.imaginary;
			cout << "Sum  of Real is : " << real;
			cout << "Sum  of Imaginary is : " << imaginary;
				}
		
	void operator -(Complex& obj)
		{
		cout << "Enter real to Subtract: "; cin >> obj.real;
		cout << "Enter Imaginary part to Subtract: "; cin >> obj.imaginary;
		real += obj.real;
		imaginary += obj.imaginary;
		cout << "Subtraction  of Real is : " << real;
		cout << "Subtraction of Imaginary is : " << imaginary;
					}

private: double real; // real part
		 double imaginary; // imaginary
};
void main() {
	//Declatre ur own onjects and just use operators to call operator overloading

}
}
