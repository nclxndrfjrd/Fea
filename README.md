# FeaThe simulation is for a building with different roof types. The reports each should only include this. because this is the format for CFD analysis.

boundary
  conditions ****

  
   
    
    
    Type

    

    
    
    
    ASSIGNED TO

    

    
   
   
    
    Velocity Normal(10 km/h)

    
    
    Surface:420

    Surface:423

    Surface:424

    Surface:432

    Surface:442

    Surface:565

    Surface:587

    Surface:601

    Surface:684

    Surface:688

    
   
   
    
    Velocity Normal(0  km/h )

    
    
    Surface:430

    Surface:433

    Surface:587

    Surface:592

    Surface:601

    Surface:688

    
   
   
    
    Velocity Normal(10  km/h )

    
    
    Surface:1455

    
   
   
    
    Velocity Normal(0  km/h )

    
    
    Surface:1457

    
   
  
   

  
#### **RESULTS**

  
#### **Inlets
  and Outlets******

  
   
    
    
   
   
    
    inlet 1

    
    
     

    
     
      
      inlet
      bulk pressure

      
      
      0.0 
      dyne/cm^2

      
     
     
      
      inlet
      bulk temperature

      
      
      0.0 
      C

      
     
     
      
      inlet
      mach number

      
      
      0.0  

      
     
     
      
      mass
      flow in

      
      
      0.0 
      g/s

      
     
     
      
      minimum
      x,y,z of opening

      
      
      0.0  

      
     
     
      
      node
      near minimum x,y,z of opening

      
      
      57233.0  

      
     
     
      
      reynolds
      number

      
      
      0.0  

      
     
     
      
      surface
      id

      
      
      1137.0  

      
     
     
      
      volume
      flow in

      
      
      0.0 
      cm^3/s

      
     
    
    
   
   
    
    inlet 2

    
    
     

    
     
      
      inlet
      bulk pressure

      
      
      -58240000.0
      dyne/cm^2

      
     
     
      
      inlet
      bulk temperature

      
      
      28.9200
      C

      
     
     
      
      inlet
      mach number

      
      
      0.007921

      
     
     
      
      mass
      flow in

      
      
      -121466.0
      g/s

      
     
     
      
      minimum
      x,y,z of opening

      
      
      1258400

      
     
     
      
      node
      near minimum x,y,z of opening

      
      
      -121466.0
      g/s

      
     
     
      
      reynolds
      number

      
      
      -100825000.0
      cm^3/s

      
     
     
      
      surface
      id

      
      
      -100825000.0
      cm^3/s

      
     
     
      
      total
      mass flow in

      
      
      -58240000.0
      dyne/cm^2

      
     
     
      
      total
      vol. flow in

      
      
      28.9200
      C

      
     
     
      
      volume
      flow in

      
      
      0.007921

      
     
    
    
   
  
  
#### Field Variable Results

  
   
    
    
    Variable

    

    
    
    
    Max

    

    
    
    
    Min

    

    
   
   
    
    cond

    
    
    0.0002563 W/cm-K

    
    
    2.04 W/cm-K

    
   
   
    
    dens

    
    
    0.0012047 g/cm^3

    
    
    2.707 g/cm^3

    
   
   
    
    econd

    
    
    0.0 W/cm-K

    
    
    0.02563 W/cm-K

    
   
   
    
    emiss

    
    
    0

    
    
    1

    
   
   
    
    evisc

    
    
    0.0 g/cm-s

    
    
    0.198240 g/cm-s

    
   
   
    
    gent

    
    
    0.0316228 1/s

    
    
    0.0316228 1/s

    
   
   
    
    press

    
    
    -58420000 dyne/cm^2

    
    
    0.0 dyne/cm^2

    
   
   
    
    ptotl

    
    
    -58420000 dyne/cm^2

    
    
    0.0 dyne/cm^2

    
   
   
    
    scal1

    
    
    0

    
    
    0

    
   
   
    
    seebeck

    
    
    0.0 V/K

    
    
    0.0 V/K

    
   
   
    
    shgc

    
    
    0

    
    
    0

    
   
   
    
    spech

    
    
    0.837 J/g-K

    
    
    1.255 J/g-K

    
   
   
    
    temp

    
    
    26.7 C

    
    
    29.0 C

    
   
   
    
    transmiss

    
    
    0

    
    
    0

    
   
   
    
    turbd

    
    
    0.0001815 cm^2/s^3

    
    
    0.6120 cm^2/s^3

    
   
   
    
    turbk

    
    
    0.0 cm^2/s^2

    
    
    92.5 cm^2/s^2

    
   
   
    
    ufactor

    
    
    0

    
    
    0

    
   
   
    
    visc

    
    
    0.0 g/cm-s

    
    
    0.0001817 g/cm-s

    
   
   
    
    vx
    vel

    
    
    -18450.0 cm/s

    
    
    26850.0 cm/s

    
   
   
    
    vy
    vel

    
    
    -19320.5 cm/s

    
    
    24050.5 cm/s

    
   
   
    
    vz
    vel

    
    
    -1610.0 cm/s

    
    
    22410.0 cm/s

    
   
   
    
    wrough

    
    
    0.0 cm

    
    
    0.0 cm


    some parameters there should be change. Such as the wind, the heat since that is the roof, also each results should be different mosyly on the inlet and outlet results as well as the field variable results. In there, the wind resistance and heat resistance should be added. Also in the Material type right it like this

    **Study Setup
    
    Settings
    
    General
    
    Contact Tolerance
    
    1.00 mm
    
    Remove Rigid Body Modes
    
    No
    
    Mesh
    
    Average Element Size (% of model size) - Solids
    
    10
    
    Scale Mesh Size Per Part
    
    No
    
    Average Element Size (absolute value)
    
    -
    
    Element Order
    
    Parabolic
    
    Create Curved Mesh Elements
    
    Yes
    
    Max. Turn Angle on Curves (Deg.)
    
    60
    
    Max. Adjacent Mesh Size Ratio
    
    1.5
    
    Max. Aspect Ratio
    
    10
    
    Minimum Element Size (% of average size)
    
    20
    
    Adaptive Mesh Refinement
    
    Number of Refinement Steps
    
    0
    
    Results Convergence Tolerance (%)
    
    20
    
    Portion of Elements to Refine (%)
    
    10
    
    Results for Baseline Accuracy
    
    von Mises Stress
    
    Properties
    
    Density
    
    7.850E-06 kg / mm^3
    
    Young's Modulus
    
    210000.00 MPa
    
    Poisson's Ratio
    
    0.30
    
    Yield Strength
    
    207.00 MPa
    
    Ultimate Tensile Strength
    
    345.00 MPa
    
    Thermal Conductivity
    
    0.056 W / (mm C)
    
    Thermal Expansion Coefficient
    
    1.200E-05 / C
    
    Specific Heat
    
    480.00 J / (kg C)
    
    Mesh
    
    Type
    
    Solids
    
    Nodes
    
    2921271
    
    Elements
    
    1764973
    
    **

    include this at the very start of each report. But it should differ since we have different material types and configuration each report.

    Sim ID	Roof Profile	DOE Set	MXene Condition	Report File Name (.docx)
Sim 01	Standard	Set 1.1	Without MXene	Report_Sim_01_Standard_Set1.1_Without_MXene.docx
Sim 02	Standard	Set 1.1	With MXene	Report_Sim_02_Standard_Set1.1_With_MXene.docx
Sim 03	Standard	Set 2.1	Without MXene	Report_Sim_03_Standard_Set2.1_Without_MXene.docx
Sim 04	Standard	Set 2.1	With MXene	Report_Sim_04_Standard_Set2.1_With_MXene.docx
Sim 05	Standard	Set 3.1	Without MXene	Report_Sim_05_Standard_Set3.1_Without_MXene.docx
Sim 06	Standard	Set 3.1	With MXene	Report_Sim_06_Standard_Set3.1_With_MXene.docx
Sim 07	Standard	Set 4.1	Without MXene	Report_Sim_07_Standard_Set4.1_Without_MXene.docx
Sim 08	Standard	Set 4.1	With MXene	Report_Sim_08_Standard_Set4.1_With_MXene.docx
Sim 09	Standard	Set 5.1	Without MXene	Report_Sim_09_Standard_Set5.1_Without_MXene.docx
Sim 10	Standard	Set 5.1	With MXene	Report_Sim_10_Standard_Set5.1_With_MXene.docx
Sim 11	Standard	Set 6.1	Without MXene	Report_Sim_11_Standard_Set6.1_Without_MXene.docx
Sim 12	Standard	Set 6.1	With MXene	Report_Sim_12_Standard_Set6.1_With_MXene.docx
Sim 13	Standard	Set 7.1	Without MXene	Report_Sim_13_Standard_Set7.1_Without_MXene.docx
Sim 14	Standard	Set 7.1	With MXene	Report_Sim_14_Standard_Set7.1_With_MXene.docx
Sim 15	Standard	Set 8.1	Without MXene	Report_Sim_15_Standard_Set8.1_Without_MXene.docx
Sim 16	Standard	Set 8.1	With MXene	Report_Sim_16_Standard_Set8.1_With_MXene.docx
Sim 17	Standard	Set 9.1	Without MXene	Report_Sim_17_Standard_Set9.1_Without_MXene.docx
Sim 18	Standard	Set 9.1	With MXene	Report_Sim_18_Standard_Set9.1_With_MXene.docx
Sim 19	Design 1	Set 1.1	Without MXene	Report_Sim_19_Design1_Set1.1_Without_MXene.docx
Sim 20	Design 1	Set 1.1	With MXene	Report_Sim_20_Design1_Set1.1_With_MXene.docx
Sim 21	Design 1	Set 2.1	Without MXene	Report_Sim_21_Design1_Set2.1_Without_MXene.docx
Sim 22	Design 1	Set 2.1	With MXene	Report_Sim_22_Design1_Set2.1_With_MXene.docx
Sim 23	Design 1	Set 3.1	Without MXene	Report_Sim_23_Design1_Set3.1_Without_MXene.docx
Sim 24	Design 1	Set 3.1	With MXene	Report_Sim_24_Design1_Set3.1_With_MXene.docx
Sim 25	Design 1	Set 4.1	Without MXene	Report_Sim_25_Design1_Set4.1_Without_MXene.docx
Sim 26	Design 1	Set 4.1	With MXene	Report_Sim_26_Design1_Set4.1_With_MXene.docx
Sim 27	Design 1	Set 5.1	Without MXene	Report_Sim_27_Design1_Set5.1_Without_MXene.docx
Sim 28	Design 1	Set 5.1	With MXene	Report_Sim_28_Design1_Set5.1_With_MXene.docx
Sim 29	Design 1	Set 6.1	Without MXene	Report_Sim_29_Design1_Set6.1_Without_MXene.docx
Sim 30	Design 1	Set 6.1	With MXene	Report_Sim_30_Design1_Set6.1_With_MXene.docx
Sim 31	Design 1	Set 7.1	Without MXene	Report_Sim_31_Design1_Set7.1_Without_MXene.docx
Sim 32	Design 1	Set 7.1	With MXene	Report_Sim_32_Design1_Set7.1_With_MXene.docx
Sim 33	Design 1	Set 8.1	Without MXene	Report_Sim_33_Design1_Set8.1_Without_MXene.docx
Sim 34	Design 1	Set 8.1	With MXene	Report_Sim_34_Design1_Set8.1_With_MXene.docx
Sim 35	Design 1	Set 9.1	Without MXene	Report_Sim_35_Design1_Set9.1_Without_MXene.docx
Sim 36	Design 1	Set 9.1	With MXene	Report_Sim_36_Design1_Set9.1_With_MXene.docx
Sim 37	Design 2	Set 1.1	Without MXene	Report_Sim_37_Design2_Set1.1_Without_MXene.docx
Sim 38	Design 2	Set 1.1	With MXene	Report_Sim_38_Design2_Set1.1_With_MXene.docx
Sim 39	Design 2	Set 2.1	Without MXene	Report_Sim_39_Design2_Set2.1_Without_MXene.docx
Sim 40	Design 2	Set 2.1	With MXene	Report_Sim_40_Design2_Set2.1_With_MXene.docx
Sim 41	Design 2	Set 3.1	Without MXene	Report_Sim_41_Design2_Set3.1_Without_MXene.docx
Sim 42	Design 2	Set 3.1	With MXene	Report_Sim_42_Design2_Set3.1_With_MXene.docx
Sim 43	Design 2	Set 4.1	Without MXene	Report_Sim_43_Design2_Set4.1_Without_MXene.docx
Sim 44	Design 2	Set 4.1	With MXene	Report_Sim_44_Design2_Set4.1_With_MXene.docx
Sim 45	Design 2	Set 5.1	Without MXene	Report_Sim_45_Design2_Set5.1_Without_MXene.docx
Sim 46	Design 2	Set 5.1	With MXene	Report_Sim_46_Design2_Set5.1_With_MXene.docx
Sim 47	Design 2	Set 6.1	Without MXene	Report_Sim_47_Design2_Set6.1_Without_MXene.docx
Sim 48	Design 2	Set 6.1	With MXene	Report_Sim_48_Design2_Set6.1_With_MXene.docx
Sim 49	Design 2	Set 7.1	Without MXene	Report_Sim_49_Design2_Set7.1_Without_MXene.docx
Sim 50	Design 2	Set 7.1	With MXene	Report_Sim_50_Design2_Set7.1_With_MXene.docx
Sim 51	Design 2	Set 8.1	Without MXene	Report_Sim_51_Design2_Set8.1_Without_MXene.docx
Sim 52	Design 2	Set 8.1	With MXene	Report_Sim_52_Design2_Set8.1_With_MXene.docx
Sim 53	Design 2	Set 9.1	Without MXene	Report_Sim_53_Design2_Set9.1_Without_MXene.docx
Sim 54	Design 2	Set 9.1	With MXene	Report_Sim_54_Design2_Set9.1_With_MXene.docx


Also i will upload 3 f3d files and 3 Step files, rename each accordingly to this below and copy  or duplicate others accordingly but rename it as below. i should have 54 files each.

Fusion File Name (.f3d)	STEP File Name (.step)
Sim_01_Standard_Set1.1_Without_MXene.f3d	Sim_01_Standard_Set1.1_Without_MXene.step
Sim_02_Standard_Set1.1_With_MXene.f3d	Sim_02_Standard_Set1.1_With_MXene.step
Sim_03_Standard_Set2.1_Without_MXene.f3d	Sim_03_Standard_Set2.1_Without_MXene.step
Sim_04_Standard_Set2.1_With_MXene.f3d	Sim_04_Standard_Set2.1_With_MXene.step
Sim_05_Standard_Set3.1_Without_MXene.f3d	Sim_05_Standard_Set3.1_Without_MXene.step
Sim_06_Standard_Set3.1_With_MXene.f3d	Sim_06_Standard_Set3.1_With_MXene.step
Sim_07_Standard_Set4.1_Without_MXene.f3d	Sim_07_Standard_Set4.1_Without_MXene.step
Sim_08_Standard_Set4.1_With_MXene.f3d	Sim_08_Standard_Set4.1_With_MXene.step
Sim_09_Standard_Set5.1_Without_MXene.f3d	Sim_09_Standard_Set5.1_Without_MXene.step
Sim_10_Standard_Set5.1_With_MXene.f3d	Sim_10_Standard_Set5.1_With_MXene.step
Sim_11_Standard_Set6.1_Without_MXene.f3d	Sim_11_Standard_Set6.1_Without_MXene.step
Sim_12_Standard_Set6.1_With_MXene.f3d	Sim_12_Standard_Set6.1_With_MXene.step
Sim_13_Standard_Set7.1_Without_MXene.f3d	Sim_13_Standard_Set7.1_Without_MXene.step
Sim_14_Standard_Set7.1_With_MXene.f3d	Sim_14_Standard_Set7.1_With_MXene.step
Sim_15_Standard_Set8.1_Without_MXene.f3d	Sim_15_Standard_Set8.1_Without_MXene.step
Sim_16_Standard_Set8.1_With_MXene.f3d	Sim_16_Standard_Set8.1_With_MXene.step
Sim_17_Standard_Set9.1_Without_MXene.f3d	Sim_17_Standard_Set9.1_Without_MXene.step
Sim_18_Standard_Set9.1_With_MXene.f3d	Sim_18_Standard_Set9.1_With_MXene.step
Sim_19_Design1_Set1.1_Without_MXene.f3d	Sim_19_Design1_Set1.1_Without_MXene.step
Sim_20_Design1_Set1.1_With_MXene.f3d	Sim_20_Design1_Set1.1_With_MXene.step
Sim_21_Design1_Set2.1_Without_MXene.f3d	Sim_21_Design1_Set2.1_Without_MXene.step
Sim_22_Design1_Set2.1_With_MXene.f3d	Sim_22_Design1_Set2.1_With_MXene.step
Sim_23_Design1_Set3.1_Without_MXene.f3d	Sim_23_Design1_Set3.1_Without_MXene.step
Sim_24_Design1_Set3.1_With_MXene.f3d	Sim_24_Design1_Set3.1_With_MXene.step
Sim_25_Design1_Set4.1_Without_MXene.f3d	Sim_25_Design1_Set4.1_Without_MXene.step
Sim_26_Design1_Set4.1_With_MXene.f3d	Sim_26_Design1_Set4.1_With_MXene.step
Sim_27_Design1_Set5.1_Without_MXene.f3d	Sim_27_Design1_Set5.1_Without_MXene.step
Sim_28_Design1_Set5.1_With_MXene.f3d	Sim_28_Design1_Set5.1_With_MXene.step
Sim_29_Design1_Set6.1_Without_MXene.f3d	Sim_29_Design1_Set6.1_Without_MXene.step
Sim_30_Design1_Set6.1_With_MXene.f3d	Sim_30_Design1_Set6.1_With_MXene.step
Sim_31_Design1_Set7.1_Without_MXene.f3d	Sim_31_Design1_Set7.1_Without_MXene.step
Sim_32_Design1_Set7.1_With_MXene.f3d	Sim_32_Design1_Set7.1_With_MXene.step
Sim_33_Design1_Set8.1_Without_MXene.f3d	Sim_33_Design1_Set8.1_Without_MXene.step
Sim_34_Design1_Set8.1_With_MXene.f3d	Sim_34_Design1_Set8.1_With_MXene.step
Sim_35_Design1_Set9.1_Without_MXene.f3d	Sim_35_Design1_Set9.1_Without_MXene.step
Sim_36_Design1_Set9.1_With_MXene.f3d	Sim_36_Design1_Set9.1_With_MXene.step
Sim_37_Design2_Set1.1_Without_MXene.f3d	Sim_37_Design2_Set1.1_Without_MXene.step
Sim_38_Design2_Set1.1_With_MXene.f3d	Sim_38_Design2_Set1.1_With_MXene.step
Sim_39_Design2_Set2.1_Without_MXene.f3d	Sim_39_Design2_Set2.1_Without_MXene.step
Sim_40_Design2_Set2.1_With_MXene.f3d	Sim_40_Design2_Set2.1_With_MXene.step
Sim_41_Design2_Set3.1_Without_MXene.f3d	Sim_41_Design2_Set3.1_Without_MXene.step
Sim_42_Design2_Set3.1_With_MXene.f3d	Sim_42_Design2_Set3.1_With_MXene.step
Sim_43_Design2_Set4.1_Without_MXene.f3d	Sim_43_Design2_Set4.1_Without_MXene.step
Sim_44_Design2_Set4.1_With_MXene.f3d	Sim_44_Design2_Set4.1_With_MXene.step
Sim_45_Design2_Set5.1_Without_MXene.f3d	Sim_45_Design2_Set5.1_Without_MXene.step
Sim_46_Design2_Set5.1_With_MXene.f3d	Sim_46_Design2_Set5.1_With_MXene.step
Sim_47_Design2_Set6.1_Without_MXene.f3d	Sim_47_Design2_Set6.1_Without_MXene.step
Sim_48_Design2_Set6.1_With_MXene.f3d	Sim_48_Design2_Set6.1_With_MXene.step
Sim_49_Design2_Set7.1_Without_MXene.f3d	Sim_49_Design2_Set7.1_Without_MXene.step
Sim_50_Design2_Set7.1_With_MXene.f3d	Sim_50_Design2_Set7.1_With_MXene.step
Sim_51_Design2_Set8.1_Without_MXene.f3d	Sim_51_Design2_Set8.1_Without_MXene.step
Sim_52_Design2_Set8.1_With_MXene.f3d	Sim_52_Design2_Set8.1_With_MXene.step
Sim_53_Design2_Set9.1_Without_MXene.f3d	Sim_53_Design2_Set9.1_Without_MXene.step
Sim_54_Design2_Set9.1_With_MXene.f3d	Sim_54_Design2_Set9.1_With_MXene.step



