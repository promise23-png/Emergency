# Emergency Response Simulation

## 👋 Author
Name: Kalkidan Ambaw 
ID: DBU 1501289

#Project Description
This project simulates an emergency response system for a city using C#.  
Different types of emergency units — Police, Firefighters, Ambulance, Rescue Team, and Hazardous Material Unit — are dispatched to handle randomly occurring incidents such as crimes, fires, medical emergencies, flooding, and electrical faults.
The user selects a unit to respond to incidents. If the wrong unit is selected, the system will automatically assign the correct unit but deduct points.

# Features
- Randomly generated incidents and locations.
- Manual unit selection with point rewards and penalties.
- Automatic system correction if wrong unit is selected.
- Dynamic scoring based on response time.

## 🗺️ Class Diagram (Text-Based) 
EmergencyUnit (abstract) ├── Police ├── Firefighter ├── Ambulance ├── RescueTeam └── HazardousMaterialUnit
Incident
Program (Main Simulation)

