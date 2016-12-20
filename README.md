# smart-meter
To demonstrate a Smart Meter Big Data Application.

![SmartMeter.png](SmartMeter.png "SmartMeter Architecture")

## Excel

### Install the ODBC Driver

* Get the Driver from http://www.simba.com/drivers/cassandra-odbc-jdbc/
* Follow the Installation Instructions (on MacOS, don't forget first to instal [iODBC](http://www.iodbc.org/))
* Save the Licence file you recieved by Mail (`SimbaApacheCassandraODBCDriver.lic`) into the right location

### Create a SDN File

* Define a SDN file, as [excel/cassandra.dsn](excel/cassandra.dsn)
* You could load & test it directly through the iODBC Administrator App:
![iODBC_test_sdn_file.png](excel/iODBC_test_sdn_file.png)

### Connect to the External Data from Excel using the `iODBC Data Source Chooser` (File DSN)

* You might use the SQL syntax, such as `select * from raw_voltage_data limit 10;`
