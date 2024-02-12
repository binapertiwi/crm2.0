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

## Design Data Source
Table Name:
* **Join Lead Activities by BPT**: Table join lead and activities (Preceding Lead) by BPT.

## Design Reports
Reports Name:
* **Join Journey Plan and Call Report by BPT**
  Table join lead and activities (Preceding Lead) by BPT with data source joint table column Lead and Preceding Lead.

### Views Name:
* Activities by BC & Status - Top 15 Person
* Activities by Cabang
* Activities by Cabang Details - Full Download [**default**]
* Activities by Categories
* Activities by Month
* Activities by Status (chart)
* Activities by status (doughnut)

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
