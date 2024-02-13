# Table of contents

- [Title](#dashboard-journey-vs-activities-by-bpt)
- [Prerequisites Tables](#prerequisites-tables)
    - [Tables](#tables)
    - [Design Data Source](#design-data-source)
    - [Design Reports](#design-reports)
      - [Views Name](#views-name)
      - [Selection Name](#selection-name)
- [Release History](#release-history)

# Dashboard Journey vs Activities by BPT 

Dashboard comparation between journey vs activities by BPT at [SAP CX](https://my364156.crm.ondemand.com/sap/ap/ui/clogin?app.component=/SAP_BYD_TF/Analytics/Dashboard/Ana_Dashboard_Standalone.QA.uicomponent&app.inport=LaunchDashboard&param.DashboardID=B99C5D103AD71EDEA7BCEDBC07C757&param.NodeID=B99C5D103AD71EDEA7BCEDBC07C7F7FB&param.RUIMode=X&client_type=newhtml&saml2=disabled&redirectUrl=/sap/public/ap/ui/runtime&sap-ui-language=en_us#Nav/1/eyJzb3VyY2UiOiI0JC9TQVBfQllEX1RGL0FuYWx5dGljcy9LZXlVc2VyQW5hbHl0aWNzL0FOQV9EQVNIQk9BUkRfT1dMX0VDTy5PV0wudWljb21wb25lbnQiLCJ0YXJnZXQiOiIvU0FQX0JZRF9URi9BbmFseXRpY3MvRGFzaGJvYXJkL0FuYV9EYXNoYm9hcmRfU3RhbmRhbG9uZS5RQS51aWNvbXBvbmVudCIsImluUG9ydCI6IkxhdW5jaERhc2hib2FyZCIsImxpc3RzIjp7fSwicGFyYW1zIjp7IkRhc2hib2FyZElEIjp7InZhbHVlIjoiQjk5QzVEMTAzQUQ3MUVERUE3QkNFREJDMDdDNzU3In0sIkRhc2hib2FyZE5hbWUiOnsidmFsdWUiOiJKb3VybmV5IHZzIEFjdGl2aXRpZXMgVi40LjAyLjI0IGJ5IEJQVCJ9LCJOb2RlSUQiOnsidmFsdWUiOiJCOTlDNUQxMDNBRDcxRURFQTdCQ0VEQkMwN0M3RjdGQiJ9LCJOZXdEYXNoYm9hcmQiOnsidmFsdWUiOiIifSwiUlVJTW9kZSI6eyJ2YWx1ZSI6IlgifSwiUGFyYW1ldGVyIjp7InZhbHVlIjoiIn0sIlBhcmFtZXRlcjEiOnsidmFsdWUiOiJYIn0sIkNvcHlEYXNoYm9hcmQiOnsidmFsdWUiOiIifX0sIndpbklkIjoiMThmZjg5ZTc5NmMxYjEwZjQyNjZjMmFmOTQ2ZDhlNjUifQ==).

# Prerequisites Tables

## Tables
List Table Join:
* All Activities (**CODACTU**)
* Lead (**CODMKLEAH**)
* Mapping Area (**ZMAPPINGAREA**)
[(Back to top)](#table-of-contents)

## Design Data Source
Table Name:
* **Join Lead Activities by BPT**: Table join lead and activities (Preceding Lead) by BPT.
[(Back to top)](#table-of-contents)
  
Access Context:
* 6 Marketing Unit;
* 4 Sales Unit;
* 5 Service Unit;
* 1010 Employee;
* 1016 Employee,
* Territory,
* Account,
* Sales Data
[(Back to top)](#table-of-contents)

List Field:
* All Activities - Activity ID
* All Activities - Activity Life Cycle Status
* All Activities - Activity Type
* All Activities - Category Appointment
* All Activities - Changed On in Local Time Zone
* All Activities - Completed On
* All Activities - Created By
* All Activities - Created On
* All Activities - Created On Date/Time in Local Time Zone
* All Activities - End Date
* All Activities - Latest Notes
* All Activities - Main Account
* All Activities - Main Contact
* All Activities - Month/Calendar Year
* All Activities - Start Date
* **All Activities - Precending Lead** (key with left outer join)
* Lead - Account
* Lead - Calendar Day
* Lead - Category
* Lead - Conversion Status
* Lead - Division
* Lead - Expected Revenue
* Lead - Industry
* Lead - Industry System
* **Lead - Lead** (key with left outer join))
* Lead - Sales Group
* Lead - Sales Office
* Lead - Sales Organization
* Lead - Sales Unit
* Lead - Source
* Lead - Status
* Mapping Area - Area
* **Mapping Area - Territory ID** (key with left outer join)
* Mapping Area - TerritoryName
[(Back to top)](#table-of-contents)

## Design Reports
Reports Name:
* **Join Journey Plan and Call Report by BPT**
  Table join lead and activities (Preceding Lead) by BPT with data source joint table column Lead and Preceding Lead.
[(Back to top)](#table-of-contents)

### Views Name:
* Activities by BC & Status - Top 15 Person
* Activities by Cabang
* Activities by Cabang Details - Full Download [**default**]
* Activities by Categories
* Activities by Month
* Activities by Status (chart)
* Activities by status (doughnut)
[(Back to top)](#table-of-contents)

### Selection Name:
* Initial
* Initial (all cabang - journey plan) [**default**]

# Release History
Changelog:
* V.1.02.24
    * 01 Feb 2024: First Launching Version 1.02.24 with 3 table join (mapping area, leads & activities).
* V.2.02.24
    * 02 Feb 2024: Fix relation column join tables.
* V.6.02.24
    * 06 Feb 2024: Change Create On to Start Date.
* V.9.02.24
    * 09 Feb 2024: Add Activities  by Catagories.
 
# Helpfull Links
* [Work with Reports in a Web Browser](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/de3a8c2bb9ea4de0a3a82dff497440a9.html)
* [Create Data Sources](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/5ba8e4b4c3bb47ffabbe6b1b268b8334.html)
* [Create Key Figures](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/2917e99667eb44298a02d0bb06a6caad.html)
* [Create Key Performance Indicators (KPIs)](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/8c4e3cdbef7a4dde80695c15155a6c03.html)


---
“Sebaik-baik manusia adalah yang paling banyak manfaatnya bagi manusia”
