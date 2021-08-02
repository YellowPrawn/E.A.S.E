# E.A.S.E
## Essentially A Simple Economist

EASE is a simplified finance calculator that is currently made for RBC bank statements in CSV form. Transactions are classified according to their vendor and a graphical representation of your spending will be displayed in a line chart

Usage
---------
Additional vendors and classifications/types of purchases can be added under the `/data/lookup_table.csv` file. This can either be done manually or by using the `edit-lookup.ipynb` file in the root directory which adds any currently unclassified vendors to the `lookup_table.csv` file (the classification still has to be manually added directly by editing the file)

Version description
----------------------------
V0 includes a prototype version of EASE. Subsequent releases will include inference to allow for future spending predictions, more graphical representations, user friendly data output, and possibly an intuitive interface.
![image](https://user-images.githubusercontent.com/52597940/127818256-adf5a564-6e4d-4883-bee1-4b344c621e2e.png)
