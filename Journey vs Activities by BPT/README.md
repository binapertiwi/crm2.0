# Dashboard Journey vs Activities by BPT at [SAP CX](https://www.sap.com/sea/products/crm.html)

Dashboard comparation between journey vs activities by BPT.

## Prerequisites Tables

### Tables
List Table Join:
* All Activities (**CODACTU**)
* Lead (**CODMKLEAH**)
* Mapping Area (**ZMAPPINGAREA**)

### Design Data Source
Table Name:
* **Join Lead Activities by BPT**: Table join lead and activities (Preceding Lead) by BPT.

### Design Reports
Reports Name:
* **Join Journey Plan and Call Report by BPT**
  Table join lead and activities (Preceding Lead) by BPT with data source joint table column Lead and Preceding Lead.

Views Name:
* Activities by BC & Status - Top 15 Person
* Activities by Cabang
* Activities by Cabang Details - Full Download [**default**]
* Activities by Categories
* Activities by Month
* Activities by Status (chart)
* Activities by status (doughnut)

Selection Name:
* Initial
* Initial (all cabang - journey plan) [**default**]

## Release History
Changelog:
* V.1.02.24
    * 01 Feb 2024: First Launching Version 1.02.24 with 3 table join (mapping area, leads & activities).
* V.2.02.24
    * 02 Feb 2024: Fix relation column join tables.
* V.6.02.24
    * 06 Feb 2024: Change Create On to Start Date.
* V.9.02.24
    * 09 Feb 2024: Add Activities  by Catagories.
