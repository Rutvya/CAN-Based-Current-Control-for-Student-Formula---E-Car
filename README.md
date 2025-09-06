7166CEM_Assignment


Setup :-
1) Load CAN socket module -
sudo modprobe can

2) Create VCAN0 interface -
sudo ip link add dev vcan0 type vcan

3) Make CAN network online -
sudo ifconfig vcan0 up


Instructions to run Application:-

1) Clone the repository -
git clone https://github.coventry.ac.uk/joshir14/7166CEM_Assignment.git

2) Change directory -
cd 7166CEM_Assignment

3) Compile the code -
cmake CMakeLists.txt

4) Build the code -
make

4) Change directory -
cd bin

5) Run Application -
./Application





