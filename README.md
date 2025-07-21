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

Usage





Goods are placed on the input conveyor.



Robots store items on shelves based on WMS directives.



Upon receiving an order, picking robots scan barcodes/NFC tags and assemble items on the output conveyor.



Completed orders are dispatched from the end of the output conveyor.

Maintenance





Regularly check conveyor belts for wear.



Calibrate robot grippers and sensors monthly.



Update WMS software with the latest inventory data.
