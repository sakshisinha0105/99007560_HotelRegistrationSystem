# HOTEL REGISTRATION SYSTEM

## INTRODUCTION

Reservation of hotel rooms system contains following features:

 1. Booking
 
 2. Rooms Info
 
 3. Room Service(Menu Card)
 
 4. Payment
 
 5. Record 

## Folder structure ##
| Folder | Description|
| --- | --- |
|MAIN README.md | Introduction about the project |
|  1_Requirements | Description,Reaserch,5W's and 1H,SWOT analysis,High and Low level requirements,Applications |
|  2_Design   |   Flow charts|
|  3_Implementation | Code of the project | 
| 4_TestplanAndOutput | Test plans and analysis |
| 5_Report | Overall explanation of the project in a specified way |
| 6_ImagesAndVideos | images andd videos of output of the project.|
| 7_Other | References |

##  5W's & 1H
![5w1h](https://user-images.githubusercontent.com/98824269/161337925-21dd2ce0-9545-4be9-8ed6-cc92758e9c9a.png)



##  SWOT Ananlysis
![swot](https://user-images.githubusercontent.com/98824269/161337958-8cfb01b4-67f2-42b8-b20b-97ea2ae55f41.png)

#  Requirements

## High Level Requirements
| Id          |  High Level Requirements  |    status  |
| :--        | :--          |   :--     |
| HLR1        | The system should be able to add new booking    | Implemented |
| HLR2        | The system should be able to add room info |  Implemented|
| HLR3        | The system should be able to provide menu card | Implemented |
| HLR4        | The system should have а payment option | Implemented |
| HLR5        | The system should have а record checking option | Implemented |

## Low Level Requirements
| Id          | Low Level Requirements for HLR1   |    status  |
| -----       | -----                             | ------     |
| LLR1.1      | The bill should contain the name of customer   | Implemented |
| LLR1.2      | The bill should contain contact number of customer | Implemented |
| LLR1.3      | The bill should contain address of customer   | Implemented |



| Id          | Low Level Requirements for HLR2   |    status   |
| :--         | :--                               |   :--       |
| LLR2.1      | The system should check the availability of rooms | Implemented |
| LLR2.2      | The system should give option to choose the rooms | Implemented |


| Id          | Low Level Requirements for HLR3   |    status  |
| :--        | :--          |   :--     |
| LLR3.1        |The system should give the list of food items to buy   | Implemented |
| LLR3.2        | The system should give the charges of food items which will be added separately | Implemented |

| Id          | Low Level Requirements for HLR4   |    status  |
| :--        | :--          |   :--     |
| LLR4.1        | The system should be able to show the option for payment methods |  Implemented|
| LLR4.2        | The system should be able to show whether its paid or not  |Implemented  |

| Id          | Low Level Requirements for HLR4   |    status  |
| :--        | :--          |   :--     |
| LLR5.1        | The system should be able to check the records |  Implemented|
| LLR5.2        | The system should be able to show whether it exists or not  |Implemented  |

# TEST PLAN:
## Table no: High level test plan
|Test id |description|Exp I/P |Exp O/P|
|--------|-----------|--------|-------|
|H_01 |Check if the Booking is properly done | Name, phn num, address, check-in, check-out date, room type |allotted room number and customer ID |
|H_02 |Check if room info is given properly |No input|NON -AC and AC rooms ameneties provided.|
|H_03 |Check for payment |cutomer phone number, mode of payment |The bill is provided|

## Table no: Low level test plan
|Test id |description|Exp I/P |Exp O/P|
|--------|-----------|--------|-------|
|L_01 |Checking for whether name number and address is not empty|Name, phn number, address |alloted room number and customer ID |
|L_02 |Check which types of room is available|No input|NON- AC and AC rooms ameneties details provided|
|L_03 |Check if the basic requirements for payment is not wrong | registered phone number, mode of payment  |The bill is generated.|
