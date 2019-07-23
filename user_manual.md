# Hamptons Hospital Electronic Health Records System User Manual

Hi, and welcome to the Hamptons Hospital Electronic Health Records
(EHR) System User Manual! If you want to help improve this manual,
[create a github account](https://github.com/join) if you don't
already have one, sign in to [github](https://github.com/), then go
[here](https://github.com/JasonMFry/hamptons_hospital_ehr_user_manual/edit/master/user_manual.md),
make changes, and finally click "Propose File Change" at the bottom
of the page. 

This user manual is for all members of the Hamptons Hospital who
need to use the EHR system. Our EHR is powered by
[OpenMRS](https://openmrs.org/), and this user manual is largely
based on OpenMRS' [user
manual](https://wiki.openmrs.org/display/docs/Using+the+Reference+Application).

## Getting Started

Before you can use the EHR system, you'll need to login. Below is
everything you need to know to log in, change your password, help if
you forget your password, and log out.

### Logging In

Before you can log in to the EHR you need someone else to create a
username and password for you. Your supervisor should know who to
ask to create a user for you, if you don't already have one.

Once you have a username and password, navigate to [the login
page](http://10.0.0.41:8080/openmrs/login.htm), input your username
and password, select a location (some locations have access to
certain information and actions that other locations don't, so pick
the location that most closely corresponds to where you are), and
click "Log In".

### Changing Your Password

The first thing you should do after logging is to change your
password. Please protect our patients, our co-workers, and our
hospital by choosing a strong password. I highly recommend
navigating to [random word
generator](https://randomwordgenerator.com/) and let it generate 3-5
random words for you as your password. You will need to include a
number and a capital letter.

To change your password, click on your username. This will create a
button called "My Account", click on that, then click on the large
button called "Change Password". After you have changed your
password, you are ready to use the EHR system!

![Changing your password](images/changing_password.png)

### Forgot Your Password?

If you forgot your password, that's ok, we can reset it. However, it
may take several hours, so do your best to remember your password.
Unfortunately, our EHR system does not yet allow non-administrator
users to reset their passwords directly. In order to have your
password reset, contact your system administrator.

Clicking the "Can't Log In?" button on the login screen will display
a pop-up box prompting you to contact your local administrator,
which isn't very helpful :)

![Resetting your password](images/reset_password.png)

After you've had the system administrator reset your password, you
should follow the instructions in [Changing Your
Password](#changing-your-password).

### Updating Your Personal Profile

At this time, the only thing you can update in your personal profile
is your password and your preferred language. We've already
discussed changing your password, so if you want to change your
language, follow these instructions, and consult the image in
[Changing Your Password](#changing-your-password).

 1. Towards the top right of the page, click on your username next
    to the person icon.
 1. Click ‘My Account’ when it appears in the dropdown.
 1. Change your languages as necessary.

## Working with Patients

### Creating a Patient

To create a new patient, follow these steps:

 1. Log into the OpenMRS system.
 1. Click on the 'Register a patient' box. If you don't see this
    box, you may not be authorized to register a new patient.
    Contact your supervisor.
 1. Enter a name for this new patient, or identify the patient as an
    unidentified patient.
 1. Select a gender for your patient.
 1. Enter in the patient's birth date, or a rough estimate of how
    old they are.
 1. Enter in the patient's home address.
 1. Enter in the patient's phone number.
 1. Enter in as few or as many of the patient's relatives, including
    their name and relationship.
 1. Click the confirm button on the left side of the screen.
 1. Confirm that your entries are accurate.
 1. Click the green 'Confirm' button and your patient will be
    written to the database.

If you leave a required field blank, you will not be able to move on
to the next section, so make sure you enter something in all the
required fields.

### Editing a Patient's Information

This section is about w to edit demographic information about a
patient that already exists in the system, including name, gender,
birth date, and contact information. 

First you will need to navigate
[home](http://10.0.0.41:8080/openmrs/), which you can do by clicking
the Hamptons Hospital logo in the top left of the screen, or
navigating their directly by going to
http://10.0.0.41:8080/openmrs/. Once you're on the home screen, you
should see a box called Find Patient Record. Click on this box.

![Find patient record](images/find_patient_record.png)

![Edit patient](images/edit_patient.png)

 1. Click on "Edit" next to the patient’s name and date of birth.
 1. You will be taken to the “Demographics” page where you can edit
    the patient’s name, gender, and date of birth.
 1. Edit the patient’s name if desired.
 1. Select  “Gender” from the list under “Demographics” on the left
    side of the page.
 1. Edit the patient’s gender if desired.
 1. Select  “Birthdate” from the list under “Demographics” on the
    left side of the page.
 1. Edit the patient’s birth date or estimated age in years and
    months if desired.
 1. Click “Confirm” at the bottom of the list under “Demographics”
    on the left side of the page.
 1. You will be presented with an overview of the demographic
    information for the patient and given the option to either
    confirm or cancel the changes.
 1. Click either the “Confirm” button or “Cancel” button to finish
    editing the patient’s demographics and return to the patient
    overview screen.

![Confirm edit patient](images/confirm_edit_patient.png)

Note: The “Save Form” and “Exit Form” buttons can be used to close
the form at any time.

Editing Contact Information:

![Edit contact information](images/edit_contact_info.png)

 1. Click on "Show Contact Info" next to the patient’s name and date
    of birth.
 1. The patient information section at the top of the page will be
    expanded to display the patient’s contact information.
 1. Click “Edit” next to the patient’s telephone number.
 1. Edit the patient’s address if desired.
 1. Select  “Phone Number” from the list under “Contact Info” on the
    left side of the page.
 1. Edit the patient’s phone number if desired.
 1. Click “Confirm” at the bottom of the list under “Contact Info”
    on the left side of the page.
 1. You will be presented with an overview of the demographic
    information for the patient and given the option to either
    confirm or cancel the changes.
 1. Click either the “Confirm” button or “Cancel” button to finish
    editing the patient’s demographics and return to the patient
    overview screen.

![Confirm edit patient2](images/confirm_edit_patient2.png)

Note: The “Save Form” and “Exit Form” buttons can be used to close
the form at any time.

### Patient Overview screen

The Patient Overview screen has a lot of good information in it, but
most of it is simple enough that it doesn't warrant an entire
section in this manual. If, however, you'd like more information,
please go to the OpenMRS [wiki
page](https://wiki.openmrs.org/pages/viewpage.action?pageId=221053347)

### Scheduling an Appointment

There are two ways to schedule an appointment: from the patient
overview screen or from the OpenMRS home screen. This section will
explain both options.

To schedule a new patient appointment from the patient overview screen:

 1. On the right side of the screen under General Actions, click
    Schedule Appointment.
 1. At the bottom of the screen under the heading Schedule a New
    Appointment, begin typing in the Select Service Type box to
    search for the type of appointment, or click View all types to
    select the service type from a list.
 1. Select an appointment date by clicking the calendar icon in the
    date selection box on the left and picking a date from the
    calendar popup.
 1. Optionally, create a time frame to search for available
    appointment times by clicking the calendar icon in the date
    selection box on the right and picking an end date from the
    calendar popup.
 1. Select the desired time block from the list of results by
    clicking on the corresponding entry in the table of time blocks.
 1. Click Next at the bottom of the screen.
 1. Optionally, enter any desired additional notes for the health
    care provider.
 1. Click Save at the bottom of the screen to schedule the appointment.

To schedule a new patient appointment from the EHR home screen:

 1. On the OpenMRS home screen, click Appointment Scheduling.
 1. Click Manage Appointments.
 1. Search for the patient to schedule an appointment for by typing
a name or patient ID into the search bar.
 1. Select the desired patient by clicking that patient's entry in
the results table.
 1. Follow the instructions for a new patient appointment from the
patient overview screen starting from step 2.
