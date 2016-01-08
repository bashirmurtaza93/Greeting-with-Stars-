#include<iostream>
#include<string>


using std::cout;
using std::cin;
using std::endl;
using std::string;
int main() {




	cout << "Please enter your first Name" << endl;

	//read the name
	 int pad= 1;
	string name;
	cin >> name;
	cout << " How many spaces?" << endl;
	cin >> pad;

	// build the message that we intend to write
	const string greeting = "Hello, " + name + "!";

	//the number of blanks surronding the greeting

	

	// the number of rows and columns to write

	const int rows = pad * 2 + 3;
	const string::size_type cols = greeting.size() + pad * 2 + 2;

	// write a blank line to seperate the output from the input.
	cout << endl;

	//write rows rows of output
	// invariant : we have  written r rows so far

	for (int r = 0; r != rows; ++r) {

		string::size_type c = 0;

		// invaraint we have written c characters so far in the current row

		while (c != cols) {

		// is it time to write the greeting

		if (r == pad + 1 && c == pad + 1) {
			cout << greeting;
			c += greeting.size();
		}

		else {
			// are we on the border
			if (r == 0 || r == rows - 1 || c == 0 || c == cols - 1)
				cout << "*";
			else cout << " ";
			++c;
		}


	}

		cout << endl;


	}


		return 0;



	}
