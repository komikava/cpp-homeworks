#Aircraft Hierarchy Program

## Description
This program demonstrates the inheritance principle by modeling various types of aircraft using multiple class levels. The base class `Aircraft` is inherited by different types of aircraft, including passenger and military planes, with more specialized models further inheriting from these classes.

## Class Hierarchy
1. **Aircraft** (Base class)
   - Attributes: model, maxSpeed, capacity
   - Methods: fly(), displayInfo()

2. **PassengerAircraft** and **MilitaryAircraft** (Level 1)
   - **PassengerAircraft**: Represents civilian passenger aircraft.
   - **MilitaryAircraft**: Represents military aircraft with weapon load attribute.

3. **Boeing** and **Airbus** (Level 2)
   - **Boeing**: A specific type of passenger aircraft.
   - **Airbus**: Another specific type of passenger aircraft.

4. **FighterJet** and **Bomber** (Level 3)
   - **FighterJet**: A type of military aircraft used for combat.
   - **Bomber**: A military aircraft designed for bombing missions.

5. **F16** and **B2** (Level 4)
   - **F16**: A fighter jet model.
   - **B2**: A stealth bomber model.

## Features:
- Inheritance and polymorphism demonstrate the relationships between different types of aircraft.
- Dynamic behavior of each aircraft type via method overriding.
