# Ahoy Macropad PCB Production Guide
The following brief instructions are for JLCPCB, and the instructions are formatted for JLCPCB Guidelines

## Instructions
1. Navigate to [JLCPCB](https://jlcpcb.com/)
2. Upload the *ahoy_pcb-gerber.zip* file
    - Keep most specifications in default (unless you know what you are doing)
    - The following can be changed to your preference:
        - PCB Color (only green or black)
        - Quantity
        - Remove Order Number
    - @todo add full specifications 
3. Enable SMT Assembly
    - Be sure to follow JLCPCB SMT guidelines
    - Choose "Assemble bottom side" 
    - For now, select "Added by JLCPCB" for the tooling holes. 
        - This will be changed in a future revision of the PCB
4. After clicking next, upload the *ahoy-pcb-bom.xlsx* BOM file in the BOM prompt and the *ahoy_pcb-bottom-pos.csv* CPL file in the CPL Prompt. 
5. After clicking next, validate the parts chosen. Validate that 17 parts are confirmed. 
    - @todo add BOM list in REDME
6. After validating, save to cart and order
