Applies changes for upgrade issue 376 to include supplies, works and services codelist. 

Based on issue [#376](https://github.com/open-contracting/standard/issues/376)

## Codelist description

The procurement category codelist is used to indicate the **primary** focus of a contracting process. Where a contracting process covers more than one of the options below, publishers should either: 

* (a) select the category that accounts for the greatest value; or 
* (b) use the 'mixed' code;

depending on the available data in source systems. 

Where a publisher is using the code 'consultingServices', then the 'services' code should be used only for non-consulting services. However, users should note that not all publishers are able to make this distinction from their source data. 


| Code               | Title               | Description | 
|--------------------|---------------------|-------------| 
| supplies           | Goods and supplies  | The primary object of this contracting process involves physical or electronic goods or supplies (such as electricity)  | 
| works              | Works               | The primary object of this contracting process involves construction, repair, rehabilitation, demolition, restoration or maintenance of some asset or infrastructure. | 
| services           | Services            | The primary object of this contracting process involves professional services of some form, generally contracted for on the basis of measurable outputs or deliverables. When the consultingServices code is also available or in use for data from a particular dataset, the service code must only be used for non-consulting services.  | 
| consultingServices | Consulting Services | The primary object of this contracting process involves professional services provided on a consultancy basis.  | 
| mixed              | Mixed               | There is no identified primary object of this contracting process. The object of the contracting process  involves two or more of supplies, works and services. | 
