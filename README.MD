# Android Project: Walk in Clinics Services App

The application addresses the need for people to know waiting times at nearby walk-in clinics without having to leave their home. It also allows users to know the services offered by nearby walk-in clinics and allow them to check-in/book appointments at the clinic of their choice.


## Purpose

The purpose of this project is to expand on the theoretical work, allowing students to gain practical experience implementing the concepts learned in class. This project is also designed to allow students to learn how to work with their colleagues and develop mobile applications. Learning outcomes range from increased understanding of concepts relating to software engineering, to overall knowledge of programming for android, management and team-relation skills.

The main outcome of the project is the implementation of a walk in clinics services application for android devices. Students are to implement all components of the project, from their design, specification, UML and additional documentation, graphical assets and source code. Students are encouraged to use the available toolset in android studio but should refrain from
copying whole blocks of code from the internet to implement features. Should a group want to use a non-standard tool/API they should request permission before doing so.

---

The app will be conceived with three different types of users in mind. The administrator, the walk-in clinics employees, and the patients. The administrator manages all the possible services that can be offered to patients by walk-in clinics. The walk-in clinic employee creates a profile for the clinic and selects the services offered by the walk-in clinic and the working hours. The patients can search for a walk-in clinic by address/type of service provided or by working hours.

### The administrator can:

1. Create services (at least 5) to be offered by walk-in clinics using the application.
2. Delete / inactivate accounts of walk in clinics and users

### The walk in clinic employee can:

1. Create an account for the walk in clinic
2. Select services provided and the role of person performing the service
3. Enter the working hours of the walk in clinic

* Note that #2 originally stated "rate for each service", and that is acceptable as well.


### The patient can:

1. Create an account
2. Search for a walk in clinic by address/type of service provided/working hours
3. Check in/book an appointment
4. Rate his/her experience at the walk in clinic
5. Show the expected waiting times for walk in clinics based on the number of patients waiting to be seen (assume a fixed time of 15 minutes per patient)
6. Show the rating that each walk in clinic has
7. Show the admin account all registered users to allow him/her to delete user accounts

### Managing Profile Information

The process of completing the service provider's profile information includes:

* Enter address (mandatory field) and phone number (mandatory field)
* Name of the clinic (mandatory field)
* Insurance types (mandatory field)
* Payment methods accepted (mandatory field).

The description used to refer to 

* General description and Licensed (Yes/No), both will be accepted in lieu of Insurance types and payment methods.

The fields above need to be included, and `mandatory field` means that the user must specify a value.

You can include additional fields you find necessary.

### Managing Clinic Working Hours

The clinic user should be able to create/edit/update/delete their availability,
as well as view their own availability.

For example:

```
Clinic is available during the following times:
- Monday 9h00-12h00
- Tuesday 9h00-14h00
- Friday 6h00-12h00
```

Usability is key for this feature!

### Service Provider Search

That is, the app should allow patients to search for a walk in clinic by:

* address
* working hours
* type of services provided

### Booking an Appointment

The application must display the list of available walk in clinics based on
the user search and allow the user to check in/book an appointment.

The application must show the expected waiting time based on the
number of people waiting to be seen (15 minutes per person).

### Rating A Clinic

The patient can rate a clinic by providing a score
between 1 (terrible) and 5 (amazing) as well as provide comment.

This used to (incorrectly) state to rate a service provider, but
the intent was to rate a clinic.  If you provide rating about
a specific service that was provided that is fine, but the intend
was to provide feedback at the clinic level.

Build status
[![Build
Status](https://circleci.com/gh/SEG2105F18/WalkInClinicServices.png?branch = master)

### Reference

The project is guided by Professor Andrew Forward

](https://circleci.com/gh/SEG2105F18/WalkInClinicServices)
