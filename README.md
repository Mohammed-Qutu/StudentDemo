# StudentDemo

## Description
This Java program demonstrates the concept of inheritance by creating a base `Student` class and two derived classes: `ResidentStudent` and `CommuterStudent`. The base `Student` class includes common properties like name and major, while the derived classes add specific attributes, such as dorm costs for resident students and parking costs for commuter students. The program creates instances of these classes and displays the data for each student.

## Author
Written by Mohammed Qutu.

## Requirements
- Java 21.0.2 or later

## Usage
To run the program, compile the `StudentDemo.java`, `Student.java`, `ResidentStudent.java`, and `CommuterStudent.java` files, then execute the `StudentDemo` class. The program will output the data for a generic student, a resident student, and a commuter student.

### Example Output
Name: Jane Smith Major: Computer Science

Name: Joe Maroney Major: Engineering Dorm Cost: 2000.0

Name: Kate Jones Major: Physics Parking Cost: 250.0

### Classes:
- **`Student`**: Base class with common properties like name and major.
- **`ResidentStudent`**: Inherits from `Student` and adds a dorm cost property.
- **`CommuterStudent`**: Inherits from `Student` and adds a parking cost property.

### Key Features:
- Inheritance to manage different types of students.
- Separate attributes for resident and commuter students.
  
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
