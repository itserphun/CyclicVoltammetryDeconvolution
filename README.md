# Introduction
In today’s world, there is an ever-increasing demand for electrochemical energy storage like batteries and supercapacitors due to **sustainable energy** and **technological advancements**. Researchers have been looking for **state-of-the-art materials** and designs to deal with this need. While these efforts have significantly enhanced energy storage systems, the **underlying mechanisms** driving their effectiveness are not yet fully understood. One of the essential techniques is **Cyclic Voltammetry (CV).**

# Cyclic Voltammetry
CV is a **multifaceted** and **powerful tool** in the realms of material science and electrochemistry, holistically providing insights into the **redox behavior** of materials. This test can be applied to a wide range of materials in diverse applications involving the **electron-transfer process**. 

In CV, the working electrode's **potential is varied** stepwise between two predetermined values, and the response **current is recorded**. During the negative potential scanning, all species at the electrode interface undergo **reduction**, resulting in the recording of a **cathodic current**. Conversely, when the potential is positively swept, the **oxidation** of these species produces an **anodic current**. The reiteration of these cycles will be continued until reaching a **cyclical steady state**. 

# Handling Complex Systems
Since most systems are **inherently complex** and often include **multiple redox reactions simultaneously**, resulting in **overlapped peaks**, we need to accurately separate these from each other to examine the **electron transfer-initiated chemical reactions** in more detail.

# Dunn Method for Capacitive and Diffusive Contributions
The **Dunn method** is a widely used approach to differentiate and analyze the **capacitive and diffusive contributions** to the total current in electrode materials. This method is particularly used for studying **energy storage devices** like supercapacitors and batteries.

Capacitive current: i(v) ∝ v   →   i(v) = k₁v  
Diffusion-controlled current: i(v) ∝ v¹/²   →   i(v) = k₂v¹/²
i(v) = k₁v + k₂v¹/²


# How to use this repository
This repository includes a **Python-based script** designed to perform **deconvolution and visualization** of cyclic voltammetry (CV) data using the **Dunn method**. The script facilitates the separation of **capacitive** and **diffusive contributions** to the total current.
1. Perform CV experiments at least two scan rates (ensure the recorded potential interval remains consistent across all scan rates).
2. Format the data Excel as follows:
   - **First Column:** Keep the potentials in this column.
   - **Subsequent Columns:** Organize the corresponding currents for each scan rate in the following columns.

  
