# Flannery - Human-Form-Recognition
Repository detailing the data architecture used for the Human Form Recognition data.

## Context description
Most machines used in a plant hire have cameras monitoring its suroundings for the presence of any humans. Whenever a human gets to close proximity with a machine it will trigger an alert advising both the driver and the passerby. Accessing these alerts is extremely useful for Site Managers, to assess the safety of their workers and prevent any injuries or eventual casualties. Hence, the goal of this project is make this data acessible and facilitate site monitoring.

## Established success metrics
Several exploration sessions were organised with sales team members and site managers, to understand their requirements around which information is necessary and when it is needed by.

After extensive discussions, it was decided that this project will create value when:
1. A list of incursions is available, displaying time, coordinates, severity and channel (camera).
2. A video of each incursion is available upon request.
3. Each person is only able to access their respective data.

## Data architecture

