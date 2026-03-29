# xml_release
Releases of the XML GUI

This project was originally completed several years ago. Matthew Ramsey (matthewlramsey@gmail.com), a co-op from Georgia Tech at the time, did the coding while Kory Glenn acted as the product lead and manager.
The goal was to create an enhanced channel link in a UI of our Cable Set Top boxes when a new guide product deployed but didn't include the features of the previous client.

## Version History

### v2.0 (2026) — `XML_GUI_V_2.0/`
Major update adding full support for the **CableLabs VOD Content Specification (ADI 1.1)**.

**New fields added:**
- **AMS (Asset Management System) attributes:** Asset_Name, Asset_Class, Provider, Product, Version_Major, Version_Minor, Creation_Date
- **App_Data metadata elements:** Rating, Genre, Run_Time, Year_Released, Summary_Short, Summary_Long, Suggested_Price, Licensing_Window_Start, Licensing_Window_End

**Other improvements:**
- Add/Edit dialog is now scrollable to support all 26 fields
- View Entry dialog fully implemented (was a stub)
- `sample_fields.csv` included with all field names, descriptions, and example values

### v1.7.4 Beta — `XML_GUI_V_1.7.4_Beta/`
The final production release of the original tool. Used for nearly a decade before decommissioning the guide client.

### v1.7.3 — `XML_GUI_V_1.7.3/`
Earlier production release.
