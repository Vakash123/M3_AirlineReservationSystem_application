# Test plan
# High_Level
Test Plan | Description | Expected I/P | Expected O/P | Actual O/P | Type of Test 
|:--:|:--:|:--:|:--:|:--:|:--:|
| HighLevel_01| User Input | Login & Password | akash | Login Successful | Valid Test |
| HighLevel_02| UserInput | Login & Password | except "akash" | Invalid Login |Valid test|
| HighLevel_03| Select option | Domestic flight | Will enter into the page | Will enter to the domestic flight form |Valid test|
| HighLevel_04| Select option | International flight | Will enter into the page | Will enter into the international flight form| valid test |
| HighLevel_05| displaying of flights | Click domestic or international flight tab|Will display flight details| Will display flight details |Valid test|

# Low_Level
Test Plan | Description | Expected I/P | Expected O/P | Actual O/P | Type of Test 
|:--:|:--:|:--:|:--:|:--:|:--:|
| LowLevel_01| User Input | From | Add place | will add the details |Save the details in list|
| LowLevel_02| User Input | To |Add destination place| Will store the data |Save the details in list|
| LowLevel_03| User Input | DOB | Add DOB | Will store the data |Save the details in list|
| LowLevel_04| User Input | class | Economic class/Buisness class | will store the data |Save the details in list|
| LowLevel_05| User Input | No of Passengers | Adults, children, infants | Will store the data |save details in list|
| LowLevel_06| Ticket is | >60 | No tickets in flight | Fligh is booked |Unaavaliable|
| LowLevel_07| Ticket is | <60 | Tickets avaliable | tickets are avaliable, Need to book |Avaliable|


