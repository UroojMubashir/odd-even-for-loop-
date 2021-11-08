#include <iostream>
using namespace std;
int main()
{
	for (int i = 20; i <= 24; i++) {
		if (i % 2 == 0) {
			cout << i << "-even" << endl;
		}
		else {
			cout << i << "-odd" << endl;
		}
	}
}
