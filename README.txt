# Assignment 3 NET4005

**Description

Sending secure application messages between Client-Sever

**Getting Started

***Executing program

To run the server file use:
            -java rsvserver and this will run the server section of the file
            -sample format:
                        -'java myfileserver.java'
            -The sever will run and output a message "Reservation server is running..."
To run the client file use:
            -java rsvclient can do 3 various tasks:
                -listing available seats
                -reserving seats
                -listing passengers
            -required:
                -task 1(listing all available seats):
                        -ip address of server/localhost
                        -'java rsvclient list localhost'
                        -this display the current available seats in both economy and business class
                -task 1(reservation of seats):
                        -ip address of server/localhost
                        -seat class
                        -passenger name
                        -seat number
                        -'java rsvclient reserve localhost business Darien 1'
                        -this display the current available seats in both economy and business class
                -task 1(listing all passengers):
                         -ip address of server/localhost
                         -'java rsvclient passengerlist localhost'
                         -this display the current available seats in both economy and business class

## Contributors
Xindong Lin