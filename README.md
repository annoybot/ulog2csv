# ulog2csv

Example program which uses the [yule_log](https://crates.io/crates/yule_log) parser to convert a [PX4 ULOG](https://docs.px4.io/main/en/dev_log/ulog_file_format.html) file to CSV.  

Follows [PlotJuggler](https://plotjuggler.io/) conventions for column naming.

## Usage

```shell
ulog2csv data/sample_log_small.ulg
```