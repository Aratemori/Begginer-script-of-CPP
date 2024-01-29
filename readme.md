# This is just my first(beginner) script on C++

```C++
#include <iostream>

using namespace std;

int main() {

	string course;

	cout << "\n\n\t\t\tWhat I do with computer?(reboot ; shutdown ; none): ";
	cin >> course;

	if (course == "reboot") {
		cout << "Okay!" << endl;
		system("shutdown -r now");
		return 0;
	};

	if (course == "shutdown") {
		cout << "Okay!" << endl;
    		system("shutdown -h now");
    		return 0;
	};

	if (course == "none") {
    		return 0;
  	};
}
```
