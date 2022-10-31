<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/542606441/22.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1118438)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# DataGrid for DevExtreme - How to obtain all filtered and sorted rows
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/542606441/)**
<!-- run online end -->

This example demonstrates how to obtain all filtered and sorted rows from the DataGrid component.

To test this functionality, you can filter or sort data in the UI and press "Get All Filtered And Sorted Data". See results in the second grid.

To implement this functionality, access a bound Store object and pass [loadOptions](https://js.devexpress.com/Documentation/ApiReference/Data_Layer/DataSource/Methods/#loadOptions) along with the [combined filtering expression](https://js.devexpress.com/Documentation/ApiReference/UI_Components/dxDataGrid/Methods/#getCombinedFilterreturnDataField) to its load() method. 

## Files to Look At

- **jQuery**
    - [src.js](jQuery/src/src.js)
- **Angular**
    - [app.component.html](Angular/src/app/app.component.html)
    - [app.component.ts](Angular/src/app/app.component.ts)
- **Vue**
    - [App.vue](Vue/src/App.vue)
- **React**
    - [App.js](React/src/App.js)
- **NetCore**    
    - [Index.cshtml](ASP/ASP/Pages/Index.cshtml)

## Documentation

- [getDataSource()](https://js.devexpress.com/Documentation/ApiReference/UI_Components/dxDataGrid/Methods/#getDataSource)
- [DataSource.store()](https://js.devexpress.com/Documentation/ApiReference/Data_Layer/DataSource/Methods/#store)


