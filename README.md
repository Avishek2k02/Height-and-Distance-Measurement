# Height-and-Distance-Measurement project
Python (Programming Language), Math functions (for trigonometric calculations), Mathematical Formulas (Trigonometry, Pythagorean theorem), Arduino, Raspberry Pi, Sensors, Electronics, Problem Solving. Design a device that uses the Pythagorean theorem and basic trigonometry to accurately measure the height and distance of object in real- world applications. Measured horizontal distance and angle of elevation to calculate the height or distance of objects. Applied trigonometric functions such as tangent and Pythagorean theorem to compute accurate measurements. Utilized Arduino for automated calculations and results display. Integrated hardware components such as inclinometer/protractor for angle measurement and a tape measure or laser rangefinder for distance measurement. Implemented a user-friendly interface with real-time result display. import math Function to calculate height: def calculate_height(distance, hypotenuse): height = math.sqrt(hypotenuse2 - distance2) return height. 

Function to calculate distance: def calculate_distance(height, hypotenuse):distance =math.sqrt(hypotenuse2 - height2) return distance. Main program: def main(): choice = input("Do you want to calculate height (h) or distance (d)? ").lower() if choice == 'h': distance = float(input("Enter the distance from the object: ")) hypotenuse = float(input("Enter the length of the hypotenuse: ")) height = calculate_height(distance, hypotenuse) print(f"The height of the object is {height} units.")

elif choice == 'd': height = float(input("Enter the height of the object: ")) hypotenuse = float(input("Enter the length of the hypotenuse: ")) distance = calculate_distance(height, hypotenuse) print(f"The distance from the object is {distance} units.")
else: print("Invalid choice. 

https://github.com/user-attachments/assets/3a4e132b-93b8-4142-adc0-c2c69312bad2

![1000003969](https://github.com/user-attachments/assets/0bd517d8-75b7-4155-aeda-d4dc3eec89b9)
![1000003989](https://github.com/user-attachments/assets/f7d76f7b-1548-48bd-ba60-799a45f51cc7)
Please choose 'h' for height or 'd' for distance.")
