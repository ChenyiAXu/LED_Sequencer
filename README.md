## LED Sequencer
### Components
- **Counter**: 1 x CMOS Decade Counter (CD4017BM)
- **Timer**: 1 x 555 Timer Oscillator (NE555DR)
- **LEDs**: 10 x Red LED (HLMP1301)
- **Resistors**: 12 x 1kΩ Resistor (RC0805FR-071KL)
- **Potentiometer**: 1 x Potentiometer (3386P-1-104LF)
- **Capacitors**: 2 x 1uF Capacitor (GRM21BR71H105KA1)
- **Connectors**: 1 x Pin Header (M20-9990246)
### Schematic Design
Refer to the schematic design for the LED Sequencer:
- ![Schematic Image](https://github.com/ChenyiAXu/Altium_Project/assets/115749117/abd701cd-4b6c-4016-aae6-f6be64e9ce6b)
#### Schematic Annotation and Validation
- **Tools**: Go to `Annotate` -> `Annotate Schematics` for component numbering.
- **Validation**: Validate the PCB project to check for errors.
#### Project Configuration
- **Project Options**: Navigate to `Project` -> `Project Options` -> `Class Generation` and uncheck `Generate Rooms`.
#### PCB Document Update
- **PCB Design**: Go to `Design` -> `Update PCB document` -> `Execute Change`.
#### PCB Dimensions
- **Define Board Shape**: Set board dimensions by going to `Design` -> `Redefine board shape` and set to 60mm x 25mm.
- **Component Placement**: Place components as per the schematic layout.
### Routing the Printed Circuit Board
For PCB routing:
- **Layer Management**: Access `Design` -> `Layer Stack Manager` to configure the PCB layers.
