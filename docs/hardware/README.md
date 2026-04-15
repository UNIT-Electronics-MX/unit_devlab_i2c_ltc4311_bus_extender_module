# Hardware

<div align="center">
<a href="./unit_sch_v_1_0_0_ue0107_i2c_extender.pdf"><img src="resources/Schematics_icon.jpg?raw=false" width="200px"><br/>Schematic</a>
</div>

## Technical Specifications

### Electrical Characteristics

<div align="center">

| **Parameter** |            **Description**            | **Min** | **Typ** | **Max** | **Unit** |
|:-------------:|:-------------------------------------:|:-------:|:-------:|:-------:|:--------:|
|      Vcc      | Input voltage to power on the module  |   1.6   |    -    |   5.5   |    V     |
|      Icc      |            Supply current             |    -    |   200   |   300   |    uA    |
|   Ibus(in)    |         Input Leakage Current         |    -    |    -    |   ±5    |    uA    |
|  Ienable(in)  |     Enable Input Leakage Current      |    -    |    -    |   ±10   |    uA    |
|     Iout      |            Output current             |    -    |    -    |   500   |    uA    |
|      Vth      | Bus Input Threshold Voltage VCC= 1.8V |  0.45   |  0.55   |  0.88   |    V     |
|               |               VCC= 2.5V               |  0.65   |  0.75   |  0.85   |    V     |
|               |           VCC= 2.7V to 5.5V           |  0.68   |  0.78   |  0.88   |    V     |
|    Vth_en     |       Enable threshold voltage        |   0.4   |    1    |   1.5   |    V     |
|     fmax      |    Bus Maximum Operating Frequency    |   400   |    -    |    -    |   kHz    |

</div>

## 🔌 Pinout

<div align="center">
    <a href="#"><img src="resources/unit_pinout_v_1_0_0_ue0107_i2c_extender.png" width="500px"><br/>Pinout</a>
    <br/>
    <br/>
    <br/>
</div>    

### Pin & Connector Layout
<div align="center">

| Pin   | Voltage Level | Function                                                  |
|-------|---------------|-----------------------------------------------------------|
| VCC   | 3.3 V – 5.5 V | Provides power to the on-board regulator and sensor core. |
| GND   | 0 V           | Common reference for power and signals.                   |
| SDA   | 1.8 V to VCC  | Serial data line for I²C communications.                  |
| SCL   | 1.8 V to VCC  | Serial clock line for I²C communications.                 |

> **Note:** The module also includes a Qwiic/STEMMA QT connector carrying the same four signals (VCC, GND, SDA, SCL) for effortless daisy-chaining.


</div>

## 📃 Topology

<div align="center">

<a href="./resources/unit_topology_v_1_0_0_ue0107_i2c_extender.png"><img src="./resources/unit_topology_v_1_0_0_ue0107_i2c_extender.png" width="500px"><br/> Topology</a>
<br/>
<br/>
<br/>
| Ref. | Description                              |
|------|------------------------------------------|
| IC1  | LTC4311 I2C Extender                     |
| L1   | Power On LED                             | 
| JP1  | 2.54 mm Castellated Holes                |
| J1   | QWIIC Connector (JST 1 mm pitch) for I2C |
| J2   | QWIIC Connector (JST 1 mm pitch) for I2C |

</div>

## 📏 Dimensions

<div align="center">
<a href="./resources/unit_dimension_v_1_0_0_ue0107_i2c_extender.png"><img src="./resources/unit_dimension_v_1_0_0_ue0107_i2c_extender.png" width="500px"><br/> Dimensions</a>
</div>

# References

- <a href="https://www.analog.com/media/en/technical-documentation/data-sheets/4311fa.pdf">LTC4311 Datasheet </a>
