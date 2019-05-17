# ChatBot_FlightTicketBooking

Here is ChatBot for flight tickets booikng based on Flights information and availablity and dates 
chat bot will communicate with user to understand the requirement and will return the available flight services 
and helps to booking the ticktes.

```
__Flow of Chat Bot:__
  ->greetings from BOT and takes the input from user
  ->takes to the entity by undertanding the converation in this case entity is "Get_tickets".
  ->BOT asks for from/departure , To/Destination location and dates of travel.
  ->and it will give additional optionas like cheap/connection flights or fast no cannection flights 
  ->and finally ask for identity card number in this case iD number is "123456"
  ->after taking all inputes it will return the matched flights.
  ->and asks for confirmation to book flights which user wanted.
  ->and fillay give referance no. of booking confirmation.
```
# HoW To Use Chat Bot For flight booking :

    Please place the json DB file in root folder
    change/edit the entities and Params as per you requirement.

```
$ Run ChatBot_FlightTicketBooking/Chatbot_v2.ipython Notebook.
```

```
BOT: Hey there  i am  Flight Ticket booking Chat Bot 
 
 I can help you with finding Flight tickets
              ✈ ✈ ✈ ✈
User: help me to find flight tickets
BOT:  Sure Please enter Departure location(chennai/Tirupathi/Bangalore/Delhi/cochin) 
User: chennai
BOT:  Please Enter Destination location (Singapore/Mudurai/Mumbai/Hyderabad/jaipur)
User: singapore
BOT:  Please Enter Date of travel in format: DD/MM/YY available dates : 22/08/2019 ; 23/08/2019 ; 24/08/2019;25/08/2019;26/08/2019
User: 22/08/2019
BOT:  choose connection type cheap or fast?
User: cheap
BOT:  Please enter your ID min 6 digits
User: 123456
Some Flights matching for You... => 

1) ABC Airlines
2) XYZ Airlines
Please shoose the flight for booking
2

 Congratulations **** Your Flight:2) XYZ Airlines Booked succesfully. 
 Referance NO. for your booking : =>  2) 1290231,53523,4324656,78867,2426475,78675

BOT: action: Get_Tickets
**User: dance show
**Sorry, my knowledge is limited only to Flight Booking and Cancellation..
**User: movie
**Sorry, my knowledge is limited only to Flight Booking and Cancellation..
User: flight tickets
BOT: Sure Please enter From location(chennai/Tirupathi/Bangalore/Delhi/cochin)
User: bangalore
BOT: Please enter To Location(Singapore/Mudurai/Mumbai/Hyderabad/jaipur)
User: mumbai
BOT:  Please Enter Date of travel in format: DD/MM/YY available dates : 22/08/2019 ; 23/08/2019 ; 24/08/2019;25/08/2019;26/08/2019
User: 24/08/2019
BOT:  choose connection type cheap or fast?
User: fast
BOT:  Please enter your ID min 6 digits
User: 123456
Some Flights matching for You... => 

1) Bangalore Airlines
2) Spicejet Airlines
Please shoose the flight for booking
1

 Congratulations **** Your Flight:1) Bangalore Airlines Booked succesfully. 
 Referance NO. for your booking : =>  1) 1289245,862342,97897,4242867,786868,98243
BOT: action: Get_Tickets
```
