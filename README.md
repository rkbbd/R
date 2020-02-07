# R (data-table) plug-in for Javascript
R (data-table) is most efficient table plug-in for JavaScript. It enhance table feature like paging, sorting, filtering, download table data(MS word/excel format), print data etc. disable feature also available with this plug-in. The main goal of R(data-table) is to enhance flexibility of data in html tables.


__R(data-table) is developed with two distinct groups of users in mind:__

*For Developer*\
For developers R (data-table) provides a wide array of options for how data should be obtained, displayed and acted upon, along with an extensive API for accessing and manipulating the table.

*End users*\
For those using the interface DataTables presents, actions to get the most from the information contained in tables, such as sorting and filtering, along with paging and scrolling of the data in table, are easy to use, intuitive and fast.

## Installation
We suggest all to include this plug-in after loading Dom.\
CDN [Link](https:///).



## Usage
R(data-table) can be initialised with a single line of Javascript:

```Javascript
R('#tbl').dataTable();
```

selector is used to obtain a reference to the table you want to enhance with R(data-table). Optional configuration parameters can be passed to perform certain actions by using a configuration object as the parameter.\
*For example:*

```python
R('#tbl').dataTable( {
  paginate: false,
 
} );
```
#### Optional Parameters

***Theme***
```python
 R("table").DataTable({
      _theme:"Night" || "White", "Day", "default"
   });

```
***Feature***
```python
 R("table").DataTable({
          _paging: true,
          _searching: true,
          _itemPerPage: true,
          _totalNoOfPage: true,
          _sorting: true,
          _download: true,
          _print: true,
          _lastRow: false,
          _OFF: false
   });
```

***Ajax***
```python
    R("#tbl").DataTable({
            _theme: "default",
            _ajax: {
                url: "https://api.github.com/repos/vmg/redcarpet/issues?state=closed",
                tableId: "01",
                params: { method: "GET" }
            }
        });
```

***Color***
```python
    R("#tbl").DataTable({
                _header: "#69a0c9",
                _headerFont: "White",
                _evenRow: "#f2f2f2",
                _evenRowFont: "black",
                _oddRow: "#d5eaf0",
                _oddRowFont: "",
                _LastRow: "#c5cae1",
                _page: "#f2f2f2",
                _pageFont: "#000",
                _pageSelected: "#69a0c9",
                _pageSelectedFont: "#ffffff",
                _pageDisableFont: "#bdbdbd",
                _searchMatch: "#78a83d",
                _search: "white",
                _printBtn: "#69a0c9",
                _tableHover: "#bcd9e1"
        });
```

***Table***
```python
    R("#tbl").DataTable({
                _font:"14px Baskerville, 'Palatino Linotype', 'Times New Roman', Times, serif",
                _borderCollapse: "collapse",
                _width: "100%",
                _border: "1px solid #fff",
        });
```


## For Contributors
If you want to help and provide a patch for a bugfix or new feature, please take a few minutes and e-mail us (rakib424@gmail.com). In particular check out the Coding standards and Commit Message Style Guide.

In general, fork the project, create a branch for a specific change and send a pull request for that branch. Don't mix unrelated changes. You can use the commit message as the description for the pull request.


## Documentation
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.\

*Default* \
 <img src="https://github.com/rakib434/R/blob/master/demo/default.PNG"> \
*Day* \
<img src="https://github.com/rakib434/R/blob/master/demo/Day.PNG"> \
*Night* \
<img src="https://github.com/rakib434/R/blob/master/demo/Night.PNG"> \
*White* \
<img src="https://github.com/rakib434/R/blob/master/demo/White.PNG"> \
*Ajax* \
<img src="https://github.com/rakib434/R/blob/master/demo/dataTable.PNG"> \
*Ajax table of table* \
<img src="https://github.com/rakib434/R/blob/master/demo/table%20of%20table.PNG"> 


## License
[||R||](https:/rakib.azurewebsites.net)