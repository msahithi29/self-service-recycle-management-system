# self-service-recycle-management-system
This desktop self-service recycle management system consists of multiple units spread across various locations and a centralized station with administrator’s control that monitor these recycling units.  </br>
<b> Centralized Station: </b> </br>
This system can be accessed only by the administrators using their credentials. admin is the username and pwd. Every station monitors a group of machines and can do actions such as:  </br>
● Add machine  </br>
● Remove machine  </br>
● Add/Update Items  </br>
● Machine Status  </br>
● Activate/ Deactivate machine  </br>
● Empty machine  </br>
● Machine Last Empty Date  </br>
● Machine Amount  </br>
● Machine Capacity  </br>
● Machine Item returned count  </br>
● Most Used Machine  </br>
● Usage Statistics  </br>
They can monitor machine within 5 mile radius and also collect statistics about each of their functionality and throughput.  </br>
<b> Self-service machines: </b> </br>
Accepts recycling materials from the customer and provides cash or gift cards in return depending on the weight of items provided by the user and the value of items that are set by station. It can be installed in various locations.   </br>
<b> Key features include: </b> </br>
● Display items with price and weight  </br>
● Accept Items  </br>
● Check out transaction  </br>
● Get Cashback  </br>
Machine has a limit to the amount of items it can collect and the money it can provide.  </br>
<b> Assumptions: </b>  </br>
● Emptying the machine is instantaneous. How each recycling machine is emptied from their physical location is not considered.  </br>
● There is a limit to the amount of cash a machine can hold, but such a limit does not exist for issuing coupons as long as the machine can accept materials.  </br>
<b> Limitations: </b> </br>
● User has to manually enter the weight of the materials he / she wishes to recycle. In real life scenarios, sensors are expected to accurately weigh the same.  </br>
</br>
</br>
12 design patterns were identified out of which 8 are successfully implemented. </br>
State Pattern </br>
Iterator </br>
Builder </br>
Null </br>
Singleton </br>
Decorator </br>
Factory </br>
Strategy </br>

Identitied ones but not implemented: </br>
Mediator pattern </br>
Observer pattern </br>
Abstract factory </br>
Builder pattern (other areas) </br>
Iterator Pattern (other areas) </br>

<h3> How to run the application: </h3> </br>
1. keep the jar and ser file in the same path </br>
2. Navigate to the path and double-click the jar file. Another way is to use the below statement for running the jar file </br>
    Java -jar EcoRe.jar </br>


