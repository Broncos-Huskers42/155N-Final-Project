# 155N-Final-Project
Final project for CSCE 155N over summer 2020 

##How to Reproduce the Results of the code
    
    Funtion Names:
    
        1) plotFinalProject
            a) Takes in 8 pieces of information, then distributes them to the interlying functions (plotEfficiency and plotEndurance)
    
        2) plotEfficiencyVsPowerIn (is called within plotFinalProject)
            a) Requires input from 4 different parameters
                  i) C0, C1, C2, and xLim (a two dimensional array vector is needed here)
                  
        3) plotEnduranceVsFuelCapacity (is called within plotFinalProject)
            a) Requires input from 4 different parameters
                  i) P (engine power), Te (thermal efficiency), Ge (gasoline energy), xLim (a two dimensional array vector is needed here)
                  
    Recommended call function: plotFinalProject(0.6,0.02,0.0015,[0 125],298,8.8,0.25,[25 100])
                  
