
## Adding leading Zero

Youtube [Youtube](https://regex101.com/r/xyKKg6/1) Screenshot [Sereenshot](https://regex101.com/r/xyKKg6/1)

|                 Syntax            |   Uses                        |DataType                     |Process link                     |
|-----------------------------------|-------------------------------|-----------------------------|---------------------------------|
|Cint(CurrentRow("ColumnName").ToString).ToString("0000000")                |String             |     String                        |[Link](https://regex101.com/r/xyKKg6/1)  |


## Get top N rows from a datatable

Youtube [Youtube](https://regex101.com/r/xyKKg6/1) Screenshot [Sereenshot](https://regex101.com/r/xyKKg6/1)

|                 Syntax            |   Uses                        |DataType                     |Process link                     |
|-----------------------------------|-------------------------------|-----------------------------|---------------------------------|
|Dt2 = Dt1.Clone Dt2=Dt1.AsEnumerable().Take(50).CopyToDataTable()                |Taking top N Rows             |     DataTable                        |[Link](https://regex101.com/r/xyKKg6/1)  |
|drLastVar = dtData.AsEnumerable.Last()                |Taking last row from dataTable            |     DataTable                        |[Link](https://regex101.com/r/xyKKg6/1)  |
|(From d In dtData.AsEnumerable()
Group d By k1= d(0).toString.Trim,k2= d(1).toString.Trim
Into grp=Group
Let r = grp.Last
Order By Array.IndexOf(dtData.AsEnumerable.toArray,r)
Select r).CopyToDatatable()                |Taking last row from dataTable            |     DataTable                        |[Link](https://regex101.com/r/xyKKg6/1)  |






