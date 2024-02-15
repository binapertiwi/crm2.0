# Table of contents

- [Title](#dashboard-lead-sales-by-bpt)
- [Prerequisites Tables](#prerequisites-tables)
    - [Tables](#tables)
    - [Design Data Source](#design-data-source)
      - [Access Context](#access-context)
      - [Join List Field](#join-list-field)
    - [Design Reports](#design-reports)
      - [Views Name](#views-name)
      - [Selection Name](#selection-name)
- [Open Issue](#open-issue)
- [Release History](#release-history)
- [Helpfull Links](#helpfull-links)

# Dashboard Lead Sales by BPT 
[(Back to top)](#table-of-contents)
Dashboard comparation between journey vs activities by BPT at [SAP CX]([https://my364156.crm.ondemand.com/sap/ap/ui/clogin?app.component=/SAP_BYD_TF/Analytics/Dashboard/Ana_Dashboard_Standalone.QA.uicomponent&app.inport=LaunchDashboard&param.DashboardID=B99C5D103AD71EDEA7BCEDBC07C757&param.NodeID=B99C5D103AD71EDEA7BCEDBC07C7F7FB&param.RUIMode=X&client_type=newhtml&saml2=disabled&redirectUrl=/sap/public/ap/ui/runtime&sap-ui-language=en_us#Nav/1/eyJzb3VyY2UiOiI0JC9TQVBfQllEX1RGL0FuYWx5dGljcy9LZXlVc2VyQW5hbHl0aWNzL0FOQV9EQVNIQk9BUkRfT1dMX0VDTy5PV0wudWljb21wb25lbnQiLCJ0YXJnZXQiOiIvU0FQX0JZRF9URi9BbmFseXRpY3MvRGFzaGJvYXJkL0FuYV9EYXNoYm9hcmRfU3RhbmRhbG9uZS5RQS51aWNvbXBvbmVudCIsImluUG9ydCI6IkxhdW5jaERhc2hib2FyZCIsImxpc3RzIjp7fSwicGFyYW1zIjp7IkRhc2hib2FyZElEIjp7InZhbHVlIjoiQjk5QzVEMTAzQUQ3MUVERUE3QkNFREJDMDdDNzU3In0sIkRhc2hib2FyZE5hbWUiOnsidmFsdWUiOiJKb3VybmV5IHZzIEFjdGl2aXRpZXMgVi40LjAyLjI0IGJ5IEJQVCJ9LCJOb2RlSUQiOnsidmFsdWUiOiJCOTlDNUQxMDNBRDcxRURFQTdCQ0VEQkMwN0M3RjdGQiJ9LCJOZXdEYXNoYm9hcmQiOnsidmFsdWUiOiIifSwiUlVJTW9kZSI6eyJ2YWx1ZSI6IlgifSwiUGFyYW1ldGVyIjp7InZhbHVlIjoiIn0sIlBhcmFtZXRlcjEiOnsidmFsdWUiOiJYIn0sIkNvcHlEYXNoYm9hcmQiOnsidmFsdWUiOiIifX0sIndpbklkIjoiMThmZjg5ZTc5NmMxYjEwZjQyNjZjMmFmOTQ2ZDhlNjUifQ==).

# Prerequisites Tables

## Tables
[(Back to top)](#table-of-contents)
List Table Join:
* Lead (**CODMKLEAH**)
* Mapping Area (**ZMAPPINGAREA**)

## Design Data Source
[(Back to top)](#table-of-contents)
Table Name:
* **Join Lead Mapping Area for New Account, Unit & Parts by BPT**: Table Join Lead and Mapping Area only for New Account, Unit & Parts by BPT.
  
### Access Context:
* 6 Marketing Unit
* 4 Sales Unit
* 1015 Employee, Territory, Account, Sales Data
* 1010 Employee

### Join List Field:
* **Lead - Lead** (key with left outer join)
* **Mapping Area - Territory ID** (key with left outer join)

## Design Reports
[(Back to top)](#table-of-contents)
Reports Name:
* **Join Lead Mapping Area for New Account, Unit & Parts by BPT**
  Table Join Lead and Mapping Area only for New Account, Unit & Parts by BPT

### Views Name:
* Lead by BC - Top 15 Person
* Lead by Cabang
* Lead by Cabang Details - Full Download [**default**]
* Lead by Categories
* Lead by Month
* Lead by Status
* 
### Selection Name:
* Initial
* Initial (all cabang - only new account, unit & part) [**default**]

# Open Issue
[(Back to top)](#table-of-contents)

* The list of lead numbers with status **converted** and **connected to the opportunity** number still appears. 
Proposed Fix: Number lead with status converted cannot be deleted. Exclude lead number with status converted dan connected to the opportunity.

# Release History
[(Back to top)](#table-of-contents)
Changelog:
* V.1.13.02.24 - On February 13, 2024, launched the initial version which included two joined tables - mapping area and leads with filter new account, lead unit & parts.

# Helpfull Links
[(Back to top)](#table-of-contents)
* [Work with Reports in a Web Browser](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/de3a8c2bb9ea4de0a3a82dff497440a9.html)
* [Create Data Sources](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/5ba8e4b4c3bb47ffabbe6b1b268b8334.html)
* [Create Key Figures](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/2917e99667eb44298a02d0bb06a6caad.html)
* [Create Key Performance Indicators (KPIs)](https://help.sap.com/docs/SAP_CLOUD_FOR_CUSTOMER/66e9a9081a7b40e38c8604d6617d0311/8c4e3cdbef7a4dde80695c15155a6c03.html)


---
“Sebaik-baik manusia adalah yang paling banyak manfaatnya bagi manusia”
