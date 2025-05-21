Network Scanner
Table of Contents
Description
Installation
Usage
Output
Dependencies
Contributing
Description
A simple Python-based port scanner that allows you to scan open ports on a specified IPv4 address within a given port range. The scanner validates IP addresses, scans the specified ports, and displays open ports along with their associated protocols.

Installation
Clone this repository:
git clone https://github.com/Kairos-T/Network-Scanner/tree/main
cd Network-Scanner
Install the dependencies:
pip install -r requirements.txt
Usage
Run the script with the following command:
python networkscanner.py
Follow the prompts to enter the IPv4 address and port range you want to scan.

The script will display a list of open ports along with their associated protocols.

To exit the program, enter 'exit' when prompted for the IP address.

Output
The script outputs a list of open ports on the specified IP address along with their associated protocols.

Sample Output:

image

Dependencies
Python 3.x
Python pyfiglet library
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
