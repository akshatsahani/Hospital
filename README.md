# Hospital

The provided Java code represents a simplified Hospital Management System with a class hierarchy that demonstrates key Object-Oriented Programming (OOP) concepts. Here's a brief description of the code:

Person Class: The Person class serves as a base class for both patients and doctors. It encapsulates common attributes such as name and age, which are inherited by subclasses.

Patient Class: The Patient class is a subclass of Person and extends it by adding patient-specific attributes like patientID and diagnosis. This class represents individual patients with their personal information and medical conditions.

Doctor Class: The Doctor class is another subclass of Person and includes a doctorID attribute. It also maintains a list of patients assigned to the doctor's care. Doctors can add patients to their list.

HospitalManagementSystem Class: This class serves as the entry point and demonstrates the use of the Patient and Doctor classes. It creates instances of doctors and patients, assigns patients to doctors, and displays relevant information.

Key OOP Concepts Illustrated:

Inheritance: The Patient and Doctor classes inherit common attributes and methods from the Person class, promoting code reusability and modeling an "is-a" relationship.

Encapsulation: Data is encapsulated within classes, making it accessible only through getter methods. This ensures data integrity and controlled access.

Polymorphism: The toString() method is





