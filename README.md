# PLC_SCL_RFID_Scanner_Control
Implementation SCL code to control RFID scanners in different cases  

![FactoryIO Baner](images/Banner.jpg)

<p align="left">
  <a href="https://docs.factoryio.com/manual/parts/sensors/#rfid-reader">
    <i><font color="blue" size="3">[Source]</font></i>
  </a>
</p>

# About

The RFID reader allows reading and writing data from RFID tags, using a communication model based on a single command sent by the controller. RFID tags are detected at a distance of up to 0.5 meters in front of the reader, and each reader is only able to correctly detect one tag at a time. Operation of the reader is based on executing commands, which are controlled by the corresponding tags. <br>

For the organization of data transmission and collection, two user data structures had to be created. The first structure "Scanner_Read_Data" stores the data that the program enters when the RFID tag is scanned, and the structure "Scanner_Write_Data" stores the data that will be written to the tag when it is scanned. <br>

Structures allow the relevant data to be written to a separate PLC database to which the middleware application has been connected. The databases "Scanners_db_Read" and "Scanners_db_Write", are databases that store the data read by the scanner and those that should be written to the label. <br>

Programs are fully tasted, presentation in links below: <br>
<strong> Reading_Data </strong> - https://youtu.be/bo97D2VGU4o <br>
<strong> Writing_Data </strong> - https://youtu.be/xN_iXLZe4jQ <br>

# Tools

<div align="left">
  <a href="https://www.siemens.com" target="_blank" rel="noreferrer"> <img src="https://images.crunchbase.com/image/upload/c_lpad,h_170,w_170,f_auto,b_white,q_auto:eco,dpr_1/mky0fkibqswnxfbvhk3i" alt="python" width="40" height="40"/> </a>
  <img width="12" />
  <a href="https://factoryio.com/" target="_blank" rel="noreferrer"> <img src="https://europe1.discourse-cdn.com/standard20/uploads/factoryio/original/1X/cc7f98b5e86ab15071a0e830568aa12e2c1f872c.png" alt="python" width="40" height="40"/> </a>
</div>
<br>
<strong> TiaPortal </strong> <br>
<strong> S7-PLCSIM Advanced </strong>

# Flow Diagram

<img src="images/Flow_Chart.jpeg" alt="Flow_Diagram" width="800"/>

# Docs

<img src="images/Docs.png" alt="Flow_Diagram" width="800"/>
