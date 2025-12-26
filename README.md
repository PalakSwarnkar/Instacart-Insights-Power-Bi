## Instacart Orders & Customer Insights (Power BI)

End-to-end Power BI project focused on analytical correctness, data modeling,  
and business-ready insights using the Instacart dataset.

---

### 🔗 Project Links

 End-to-End Project Walkthrough**  
[Explore the complete project approach on Maven Showcase](https://mavenshowcase.com/project/54415)

 Interactive Power BI Dashboard**  
[Open the live Power BI report to explore insights interactively](https://app.powerbi.com/view?r=eyJrIjoiMjEzMGQyZWEtZmVmNy00MTRkLWE2MWUtZjIzYmFhMGQ3OGU0IiwidCI6IjdlNDY4Y2ZkLTcwZWYtNGE2Mi04NDdhLTFlOTU1MzQ5ZGU5YyIsImMiOjN9)

---

###  Key Decisions & Problems Solved

**No quantity or revenue available**  
Each order-product row was treated as one unit.  
All KPIs were designed using row-level DAX logic to avoid inflated or misleading metrics.

**Slicers breaking across visuals**  
Diagnosed filter-flow issues and fixed them by redesigning relationship direction,  
ensuring consistent cross-visual interaction.

**Raw tables not analysis-ready**  
Cleaned, standardized, and aligned multiple datasets in Power Query  
to support accurate joins and scalable modeling.

**Incorrect product rankings**  
Replaced column-based sorting with measure-driven Top-N logic  
to reflect true demand and performance.
