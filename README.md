# Fieldbus networks

Tasks/Projects from WUT course "Fieldbus Networks Design"

---

## 1. Modbus RTU CRC 

Tabular implementation of the **CRC-16 algorithm** used in Modbus RTU communication. CRC (Cyclic Redundancy Check) is an error-detection code widely used in serial and industrial protocols to ensure data integrity.
Program inputs byte compination (up to 256 bytes) and number of repetitions and returns calculated CRC sum and time of execution.

Compilation and launch using GCC:
```bash
g++ -O2 modbus_rtu_crc.cpp -o modbus_rtu_crc
.\modbus_rtu_crc
```
