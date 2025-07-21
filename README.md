# Warehouse-Automation
Overview

This project outlines the design and implementation of an automated warehouse system for food items, eliminating human intervention. Goods arrive via a conveyor, are stored by robots on shelves, and are retrieved based on customer orders using barcode/NFC scanning, with final assembly on a secondary conveyor.

System Components





Input Conveyor: Transports goods to the storage area.



Storage Robots: Cartesian robots place goods on slanted shelves.



Picking Robots: Retrieve items from shelves based on order data.



Output Conveyor: Assembles and transports completed orders.



Sensors: Barcode/NFC readers for order processing.



Warehouse Management System (WMS): Coordinates robot tasks and inventory.

Installation





Assemble the conveyor system with a length sufficient to span the warehouse.



Install Cartesian and picking robots with grippers suitable for food packaging.



Integrate barcode/NFC scanners with the WMS.



Connect all components to a centralized control unit (e.g., PLC or Raspberry Pi).





Working Envelope Elements
The working envelope defines the operational space for the robots and conveyors:

Input Conveyor Working Envelope
Length: Spans the warehouse width (e.g., 10–20 m).
Width: Sufficient for goods placement (e.g., 0.5–1 m).
Height: Clearance for robot access (e.g., 0.5 m above conveyor).
Constraints: Avoids interference with robot arms or shelving structure.
Storage Robot Working Envelope
X-Axis (Horizontal): Covers shelf width (e.g., 10–20 m).
Y-Axis (Depth): Extends to shelf depth (e.g., 1–2 m).
Z-Axis (Vertical): Reaches shelf height (e.g., 3–5 m).
Constraints: Limited by gantry frame and clearance for slanted shelves.
Picking Robot Working Envelope
Reach: 1–1.5 m to access the lower end of slanted shelves and output conveyor.
Rotation: 180° for flexibility in picking and placing.
Constraints: Operates within shelf output zone, avoiding conveyor overlap.
Output Conveyor Working Envelope
Length: Matches warehouse length for order assembly (e.g., 10–20 m).
Width: Accommodates bags or baskets (e.g., 0.5–1 m).
Height: Clearance for picking robot (e.g., 0.5 m).
Constraints: Aligns with picking robot’s drop-off point.
System-Wide Envelope Considerations
Slanted Shelves: 5–10° incline for gravity-assisted item movement.
Safety Zones: Restricted areas around moving parts.
Scalability: Expandable by adding conveyor sections or robots.


Usage





Goods are placed on the input conveyor.



Robots store items on shelves based on WMS directives.



Upon receiving an order, picking robots scan barcodes/NFC tags and assemble items on the output conveyor.



Completed orders are dispatched from the end of the output conveyor.

Maintenance





Regularly check conveyor belts for wear.



Calibrate robot grippers and sensors monthly.



Update WMS software with the latest inventory data.

image:
<img width="1465" height="778" alt="لقطة شاشة 2025-07-21 144419" src="https://github.com/user-attachments/assets/dfc5a2f5-a888-4de5-aa60-d97f627073ad" />

