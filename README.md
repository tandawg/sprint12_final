Parcel Tracker

Parcel Tracker is a console application developed in Go for tracking and managing parcels. It utilizes SQLite for data storage and supports command-line interaction. Additionally, Docker is used for containerization.

Features
Parcel Management: Add, update, delete, and view parcel information.
Data Persistence: Uses SQLite to store parcel data.
Command-Line Interface: Interact with the application through the terminal.
Containerization: Docker support for easy deployment.

Getting Started
Prerequisites
Go: Ensure you have Go installed. You can download it from golang.org.
SQLite: The application uses SQLite for data storage.
Docker (optional): For containerization.

Installation:
Clone the repository:
git clone https://github.com/tandawg/sprint12_final.git

cd sprint12_final


Build the application:
go build -o parcel_tracker main.go

Run the application:
./parcel_tracker


Using Docker

Build the Docker image:
docker build -t parcel_tracker .

Run the Docker container:
docker run -it --rm parcel_tracker

Usage
Once the application is running, you can use the following commands:

Add a parcel:
add [tracking_number] [description]

Update a parcel:
update [tracking_number] [new_description]

Delete a parcel:
delete [tracking_number]

View all parcels:
list

Find a parcel:
find [tracking_number]

Exit the application:
exit

Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Thanks to the Go community for their support and resources.
Special thanks to the developers of SQLite and Docker for their excellent tools.
