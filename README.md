# supplier-quality-sample

This is a Doku for supplier quanlity analysis sample with Power BI.

Source: 
https://docs.microsoft.com/en-us/power-bi/sample-supplier-quality from http://obvience.com/

Before going further, we need understand the concept of the data model, please read the link below:
https://en.wikipedia.org/wiki/Data_model

This analysis contains 8 entity (table) and every table has to attribute.

1. defect type

* Defect Type	
* Defect Type ID	
* Sort

2. defect

* Defect	
* Defect ID

3. material type

* Material Type	
* Material Type ID

4. plant

* Plant	
* Plant ID

5. category

* Sub Category	
* Sub Category ID	
* Category

6. vendor

* Vendor	
* Vendor ID

7. date

* Year	
* MonthNumber	
* Week	
* Date	
* Month


8. metrics

* Date	
* Sub Category ID	
* Plant ID	
* Vendor ID	
* Material ID	
* Defect Type ID	
* Material Type ID	
* Defect ID	
* Defect Qty	
* Downtime min

### Let's make the data model from the 8 entity. Just drag every [Primary Key](https://en.wikipedia.org/wiki/Primary_key) of the entity in power pivot or power bi data model


### After that, create [a measure in power bi or power pivot](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-create-measures)

Below are the measure of every graph,

Note! we use the format of table and attribut with in [DAX language](https://docs.microsoft.com/en-us/power-bi/desktop-quickstart-learn-dax-basics) 

Extras: [Quick Guide DAX](https://support.office.com/en-us/article/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a?omkt=en-US&ui=en-US&rs=en-US&ad=US)

---------------------------------------------------------------------------
Drag this entity for every graph







