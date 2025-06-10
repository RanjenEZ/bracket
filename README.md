# L-Shaped Bracket Design & Structural Optimization

## Objective
My goal was to design a simple **L-shaped bracket** that optimizes material usage while maintaining structural strength.



## Design Process

### Initial Design & Analysis
- I started off by creating a general **L-bracket model**.
- Which I then put in a built-in FEA simulation for a 1000N load
- Using the simulation I identified:
  - High stress concentration at the **center** of the model
  - As well as **deformation** at the **top front-end** of the model

### Structural Improvements
To enhance structure, I added the following modifications:
1. **Two diagonal support beams** (from the middle to the upper corners).
2. **Also included a center rib** at the L-bend to:
   - Better distribute stress
   - Reduce deformation
3. I **placed structural reinforcements strategically** to:
   - Prevent stress buildup in any specific part of the model
   - Minimize the front end deformation

### Final Evaluation
After modifications:
- I redid **FEA simulation**.
- Observed:
  - **Heavily reduced deformation**
  - **An even stress distribution**.
- **Conclusion**: I improved structural integrity by analysis of the general L-bracket model, and implemented techniques that I have learned to improve deformation with material efficiency, stress path optimization, and load path simplifications.
---

![image](https://github.com/user-attachments/assets/a51155f0-e46b-4a2a-b6b5-3917572feb9d)

