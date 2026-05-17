🚶‍♂️ Commuting Decision System
🚀 Overview

This project evaluates whether a user can commute based on:

Distance to travel
Weather conditions (rain)
Available transport options (bike, car, ride-share app)

It demonstrates how conditional logic can be used to model real-life decision-making in Python.

🎯 Features
1. Distance-Based Logic

The program divides commuting into 3 distance categories:

0 or falsy distance → Not possible to commute
≤ 1 mile → Walking (only if not raining)
1–6 miles → Cycling (requires bike + no rain)
> 6 miles → Requires car or ride-share app
2. Weather Consideration
If it is raining, walking and biking conditions become restricted.
3. Transport Availability Check
Bike → Used for short-medium distance
Car → Used for long distance
Ride-share app → Alternative for long distance
🧾 Input Variables
distance_mi = 3
is_raining = False
has_bike = True
has_car = False
has_ride_share_app = False
⚙️ Logic Flow
Check if distance is valid (non-zero)
Evaluate distance range:
≤ 1 mile → walk condition
1–6 miles → bike condition

6 miles → car/app condition

Apply weather restrictions
Print final decision (True or False)
🧪 Example Output
True

or

False

depending on conditions.

🧠 Concepts Used
Conditional statements (if, elif, else)
Boolean logic (and, or, not)
Real-world decision modeling
Edge case handling (falsy values)
📌 Learning Outcome

After completing this project, you understand how to:

Break problems into conditions
Use logical operators effectively
Build real-life decision systems using Python
