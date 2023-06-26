# cope.io
## _A video-based therapy platform._

This platform enables clients/patients to request an appointment with a therapist online. This platform can also help therapists manage their appointments with their patients. cope.io will organise the schedule of each patient's session, which will be submitted as a request to the counsellor they have selected. 
The system has three profiles- the administrator, the therapist, and the patient. The system admin will populate the list of therapists with their specialities, details, and system credentials. Patients can browse cope.io to find a doctor specialising in their needs. Patients can check the counsellor's weekly schedule to help them pick a day and time for the appointment and submit their request. After this, therapists can view all their appointments and sessions.

  1. Admin can:
  
  
    - add, edit and delete the therapist records
    
    - schedule new and remove sessions
    
    - view patient details
    
    - view bookings of patients
 
 
  2. Therapists can:
  
  
    - view their appointments and scheduled sessions
       
    - view details of patients
    
    - edit account settings

    - delete their account

    
  3. Patients/Clients can:
  
  
    - create and account and make appointments online
        
    - view their old bookings

    - edit account settings

    - delete their account
    
    
    
Admin, doctors and patients all require the same login credentials.

  
-----------------------------------------------


## How to get started

1. Make sure you have Node, npm and XAMPP installed.

2. In the command line of the main folder, run the command: 
```sh
npm i express socket.io nodemon
``` 
to install Express.js, socket.io, and nodemon

3. cd into the 'frontend' folder and run the command:
```sh
npm start
```

4. In the command line of the main folder, run the command:
```sh
npm start dev
```

5. Open your XAMPP Control Panel and start Apache and MySQL.

6. Copy the 'cope-online-therapy' folder and paste it into the XAMPP's "htdocs" directory.

7. Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin

8. Create a new database naming edoc.

9. Import the provided SQL file ('SQL_Database_edoc.sql').

10. Open cope.io in a browser. i.e. http://localhost/cope-online-therapy/. The project should now be running.



Database name: 'edoc'

## Built-in user accounts 

ADMIN EMAIL:		admin@edoc.com

ADMNIN PASSWORD:	123


THERAPIST EMAIL:		doctor@edoc.com

THERAPIST PASSWORD:	123


PATIENT EMAIL:		patient@edoc.com

PATIENT PASSWORD:	123