# esphome
Past and present ESPHome projects using CircuitSetup power monitoring solutions.  For more information check out https://github.com/CircuitSetup

## cs2
This was my first CircuitSetup project, just the basic Split Single Phase Energy Meter system.  Hardware came with emonESP which worked fine but ESPHome is much more powerful for my purposes.

## cs24
24-channel system employing the CircuitSetup Expandable 6 Channel ESP32 Energy Meter, monitors most of the home circuit of any consequence.

Now connected to the cs_esphome project using the ESPHome API and sending data to an InfluxDB2 database with Grafana used for the visualizations.
