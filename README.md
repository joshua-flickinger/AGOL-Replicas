# Summarize and Remove Replicas

This Jupyter Notebook provides tools for working with ArcGIS Online replicas.  
It is designed to connect to an ArcGIS Online account, analyze existing replicas, and optionally unregister outdated ones.

---

## Notebook Overview

- **Total cells:** 31  
  - **Code cells:** 22  
  - **Markdown cells:** 9  

### Major Sections
- **Import Packages** – Load required Python and ArcPy/ArcGIS API libraries.  
- **Connect to ArcGIS Online** – Authenticate into an ArcGIS Online organization.  
- **Access Layer** – Retrieve the target feature layer for analysis.  
- **Generate List of Replicas** – Build a list of replicas associated with the layer.  
- **Check Out One Replica for Testing** – Inspect replica details interactively.  
- **Print List of Replicas** – Display all replicas for review.  
- **Analyze Replica Sync Dates** –  
  - Identify replicas last synced on their creation date.  
  - Identify replicas that were synced more recently.  
- **Unregister** – Demonstrate unregistering replicas that are no longer needed.

---

## Usage

1. **Authentication**: Update the connection cell with valid ArcGIS Online credentials or token-based login.  
2. **Layer Access**: Modify the `layer` variable to point to your feature layer of interest.  
3. **Replica Review**: Run the summary cells to view replica counts and sync dates.  
4. **Cleanup**: Execute the unregister cell to remove replicas that are outdated.  

---

## Notes

- This notebook assumes access to the ArcGIS Python API and a valid ArcGIS Online subscription.  
- Clearing notebook outputs before committing is recommended to keep diffs small and avoid GitHub rendering issues.  

