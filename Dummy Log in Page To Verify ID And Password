import 'dart:io';

void main() {
  Map<int, Map<String, String>> students = {
    1: {'name': 'Mifta', 'Password': 'Pass123'},
    2: {'name': 'Roshni', 'Password': 'Ay@t'},
    3: {'name': 'Tonima', 'Password': 'Anz1r'},
    4: {'name': 'Tamim', 'Password': 'Af1'},
    5: {'name': 'Uthsho', 'Password': 'Ap@'}
  };

  print('Enter Student ID:');
  int enteredId = int.parse(stdin.readLineSync()!);
  print('Enter Name:');
  String enteredName = stdin.readLineSync()!;
  print('Enter Password:');
  String enteredPassword = stdin.readLineSync()!;

  if (students.containsKey(enteredId)) {
    var student = students[enteredId];
    if (student!['name'] == enteredName && student['Password'] == enteredPassword) {
      print('Login Successful! Welcome, $enteredName.');
    } else {
      print('Invalid Name or Password.');
    }
  } else {
    print('Student ID not found.');
  }
}
