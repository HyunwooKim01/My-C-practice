#include <iostream>
#include <cmath>
using namespace std;

class Line {
public:
	Line();
	void setTwoPoints();
	double getLineLength();
	int sx = 0, sy = 1;
	int ex = 0, ey = 1;
};
Line::Line() {}
void Line::setTwoPoints() { 
	cout << "시작점 좌표 두개를 입력하시오.: ";
	cin >> sx >> sy;
	cout << "끝점 좌표 두개를 입력하시오.: ";
	cin >> ex >> ey;
}
double Line::getLineLength() {
		return sqrt(pow(ex - sx, 2) + pow(ey - sy, 2));
}

int main()
{
	Line myline;
	myline.setTwoPoints();
	cout << "myline의길이는" << myline.getLineLength() << " 입니다. \n";
	
}
