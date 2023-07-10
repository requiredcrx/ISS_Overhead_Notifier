# ISS Overhead Notifier

This program checks if the International Space Station (ISS) is passing overhead and sends a notification email if it is nighttime and the ISS is within a certain range of your location.

## Description

This script uses the Open Notify API to get the current coordinates of the ISS and compares them with your predefined location coordinates. It also utilizes the Sunrise-Sunset API to determine if it is nighttime. If both conditions are met, it sends an email notification using the SMTP protocol.

## Prerequisites

Before running the program, make sure you have the following installed:

- Python 3
- Requests library (`pip install requests`)

## Setup

1. Clone the repository or download the script.

2. Open the script file in a text editor.

3. Provide your latitude and longitude coordinates in the `MY_LAT` and `MY_LNG` variables.

4. Enter your email address in the `my_email` variable.

5. Enter your email password in the `password` variable.

6. Save the changes.

## Usage

To run the program, execute the following command in your terminal or command prompt:


The program will run continuously, checking for ISS overhead during nighttime. If the conditions are met, you will receive an email notification.

## License

This project is licensed under the [MIT License](LICENSE).
