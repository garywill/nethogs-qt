0.0.3 first Version with cnx and nslookup.
0.0.2 first Version with Qtcharts (kb/s is ok but not nice).
0.0.1 first version of nethogs-qt. kb/s is buggy.

apt-get install qt5-default qt5-qmake git
git clone https://github.com/qtproject/qtcharts.git
cd qtcharts
qmake
make
sudo make install


To build:
qmake
make

To run:
sudo ./nethogs-qt
