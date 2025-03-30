# L-Shaped Bracket Design & Structural Optimization

## Objective
My goal was to design a simple **L-shaped bracket** that optimizes material usage while maintaining structural strength.

## Design Process

### Initial Design & Analysis
- Created a general **L-bracket model**.
- Performed **stress analysis** under a **1000N load** using built-in FEA software.
- Identified:
  - High-stress concentration at the **center**.
  - Significant **deformation** at the **top front-end**.

### Structural Improvements
To enhance performance, I implemented the following modifications:
1. **Added two diagonal support beams** (from the middle to the upper corners).
2. **Included a center rib** at the L-bend to:
   - Redistribute stress.
   - Reduce deformation.
3. **Placed reinforcements strategically** to:
   - Prevent mid-region stress buildup.
   - Minimize front-end deformation.

### Final Evaluation
After modifications:
- Re-ran **FEA simulation**.
- Observed:
  - **Significantly reduced deformation**.
  - **More even stress distribution**.
- **Conclusion**: Structural integrity improved successfully.

---

**Note**: This design balances material efficiency with mechanical strength, making it suitable for lightweight yet robust applications.