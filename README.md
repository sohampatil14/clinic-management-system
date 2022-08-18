# clinic-management-system

A simple clinic management system app using linked list and hashing.

In this application linked list data structure is used to create nodes for doctors and assign the patients to the doctors in order to their appointment time. Both doctor and patients have a unique identification number(ID) which is used located them; and is created using a hash function.

There are two scenarios for patients, either is can be a normal appointment or an emergency. In case of an emergency the patient is given first priority and the other patients are shifted behind. In normal appointment, the patient has to search the doctor using name or ID and book an appointment.

For doctors, they can remove the patient node assigned to them after consultation is complete. The doctors also have function to check the remaining number of patients for consultation and their information.