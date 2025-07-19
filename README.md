
# I.Project Information 
This project for RYA2025 events , organize by PIF Club .
# II.Project Detail
- [1.Hardware](#1hardware)
  - [a.MainBoard](#amainboard)
  - [b.HBridgeBoard](#bhbridgeboard)
- [2.Firmware](#2firmware)
## 1.Hardware
### a.MainBoard
<img src="https://github.com/user-attachments/assets/4e24b936-ec22-419d-b0bd-f72ebf611ad4" alt="BotView" width="350" height="350">
<img src="https://github.com/user-attachments/assets/412a1918-3cb1-4bc8-9cbd-6986af7856b4" alt="TopView" width="350" height="350">



### b.HBridgeBoard
- Overview
<img width="567" height="338" alt="Image" src="https://github.com/user-attachments/assets/1518b3db-593a-45c9-b425-25c26d6df358" />
<br>

- HBridgeDriver

<br>
<img width="260" height="157" alt="Image" src="https://github.com/user-attachments/assets/eb2ce50a-d7c2-4e32-bd21-db79b9201598" />
<img width="278" height="164" alt="Image" src="https://github.com/user-attachments/assets/475a0d50-f845-4163-b287-7c095d61178a" />
<br>

- HBridgeMCU

<br>
<img width="278" height="138" alt="Image" src="https://github.com/user-attachments/assets/f778ce03-4216-4e64-900d-d100e93105e4" />
<img width="268" height="133" alt="{C7F0B999-A035-4663-996E-05547A0FA0A0}" src="https://github.com/user-attachments/assets/6c83a98b-204e-47b3-9de6-de85341e997a" />


### c.MainSensor 
<img src="https://github.com/user-attachments/assets/bdc9fa4a-2ad8-4877-858b-7a19f4095f17" alt="BotView" width="325" height="175">
<img src="https://github.com/user-attachments/assets/f9227ec6-26be-4efb-ad17-90eb3f811bab" alt="TopView" width="325" height="175">

### d.ServoShield
- Overview
<img width="200" height="198" alt="{E26ED104-2827-4951-8D7C-8456B76CEC80}" src="https://github.com/user-attachments/assets/4bd1958a-ab7c-4899-8db6-606d43f8147e" />
<img width="200" height="198" alt="{BEBFCB29-CAE0-44E9-B002-607E1807A096}" src="https://github.com/user-attachments/assets/29dd4de3-30e0-4e1b-82d9-59a9a8461568" />


- Combine MainBoard and Shield
<img width="624" height="409" alt="{A99C5422-A26A-4F3A-B65A-C8C4BA3ED87B}" src="https://github.com/user-attachments/assets/91d0206e-e931-4871-9f46-5747bbaedaa3" />


## 2.Firmware

# III.Directory Tree 
<pre>
├───1.Documents
├───2.Hardware
│   ├───1.PCB
│   │   ├───1.MainBoard
│   │   │   ├───1.Project
│   │   │   │   └───MainBoard_RYA
│   │   │   │       ├───History
│   │   │   │       │   └───FFFFFFFF9A53FE5D
│   │   │   │       ├───Project Logs for MainBoard_RYA
│   │   │   │       └───Project Outputs for MainBoard_RYA
│   │   │   ├───2.Schematic
│   │   │   ├───3.Layout
│   │   │   │   ├───1.MainBoardLayout
│   │   │   │   └───2.PowerTesttingLayout
│   │   │   ├───4.Mechanic
│   │   │   ├───5.Gerber
│   │   │   └───6.BOM
│   │   ├───2.HBridge
│   │   │   ├───1.HBridgeMCU
│   │   │   │   ├───1.Project
│   │   │   │   │   └───RYA_MotorMCU
│   │   │   │   │       ├───History
│   │   │   │   │       ├───Project Logs for RYA_MotorMCU
│   │   │   │   │       └───Project Outputs for RYA_MotorMCU
│   │   │   │   ├───2.Schematic
│   │   │   │   ├───3.Layout
│   │   │   │   ├───4.Mechanic
│   │   │   │   ├───5.Gerber
│   │   │   │   └───6.BOM
│   │   │   └───2.HBridgeDriver
│   │   │       ├───1.Project
│   │   │       │   └───RYA_MotorDriver
│   │   │       │       ├───History
│   │   │       │       ├───Project Logs for RYA_MotorDriver
│   │   │       │       └───Project Outputs for RYA_MotorDriver
│   │   │       ├───2.Schematic
│   │   │       ├───3.Layout
│   │   │       ├───4.Mechanic
│   │   │       ├───5.Gerber
│   │   │       └───6.BOM
│   │   ├───3.MainSensor
│   │   │   ├───1.Project
│   │   │   │   └───RYA_2025_SENSOR
│   │   │   │       ├───History
│   │   │   │       │   ├───000000001976E237
│   │   │   │       │   ├───000000002AF5241D
│   │   │   │       │   ├───000000007AA6D70D
│   │   │   │       │   ├───FFFFFFFFAF4FCFE6
│   │   │   │       │   ├───FFFFFFFFC1E600D4
│   │   │   │       │   └───FFFFFFFFCFC53860
│   │   │   │       ├───Project Logs for RYA_SENSOR
│   │   │   │       └───Project Outputs for RYA_SENSOR
│   │   │   ├───2.Schematic
│   │   │   ├───3.Layout
│   │   │   ├───4.Mechanic
│   │   │   ├───5.Gerber
│   │   │   └───6.BOM
│   │   └───4.ServoShield
│   │       ├───1.Project
│   │       │   └───RYA_ServoShield
│   │       │       ├───History
│   │       │       ├───Project Logs for RYA_ServoShield
│   │       │       └───Project Outputs for RYA_ServoShield
│   │       ├───2.Schematic
│   │       ├───3.Layout
│   │       ├───4.Mechanic
│   │       ├───5.Gerber
│   │       └───6.BOM
│   └───2.Mechanic
├───3.Firmware
├───4.Report
│   ├───Image
│   └───Video
└───5.Demo
</pre>
