#PyQt5.7 with PyQtchart

```
sudo apt-get install python3-pyqt5
sudo apt-get install qtdeclarative5-dev
sudo apt-get install qt5-default
sudo apt-get install pyqt5-dev
sudo apt-get install pyqt5-dev-tools
sudo apt-get install pyqt5.qsci-dev
```


SIP 4.18:

```
wget https://netcologne.dl.sourceforge.net/project/pyqt/sip/sip-4.18/sip-4.18.tar.gz
tar zxvf sip-4.18.tar.gz

cd sip-4.18
python3 configure.py
make -j 4
sudo make install

```

QtCharts 5.7

```
git clone git://code.qt.io/qt/qtcharts.git -b 5.7
cd qtcharts
qmake -r
make
sudo make install

```

PyQtChart 5.7:

```
wget https://datapacket.dl.sourceforge.net/project/pyqt/PyQtChart/PyQtChart-5.7/PyQtChart_gpl-5.7.tar.gz

tar zxvf PyQtChart_gpl-5.7.tar.gz
cd PyQtChart_gpl-5.7
python3 configure.py --qtchart-version=2.0.1 --verbose
make
sudo make install
```