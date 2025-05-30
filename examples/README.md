# Examples

## Writes
- [import_data_set.py](import_data_set.py) - How to import CSV file
- [import_data_set_multiprocessing.py](import_data_set_multiprocessing.py) - How to large CSV file by Python Multiprocessing
- [ingest_dataframe_default_tags.py](ingest_dataframe_default_tags.py) - How to ingest DataFrame with default tags
- [ingest_large_dataframe.py](ingest_large_dataframe.py) - How to ingest large DataFrame
- [iot_sensor.py](iot_sensor.py) - How to write sensor data every minute by [RxPY](https://rxpy.readthedocs.io/en/latest/)
- [import_data_set_sync_batching.py](import_data_set_sync_batching.py) - How to use [RxPY](https://rxpy.readthedocs.io/en/latest/) to prepare batches for synchronous write into InfluxDB
- [write_api_callbacks.py](write_api_callbacks.py) - How to handle batch events
- [write_structured_data.py](write_structured_data.py) - How to write structured data - [NamedTuple](https://docs.python.org/3/library/collections.html#collections.namedtuple), [Data Classes](https://docs.python.org/3/library/dataclasses.html) - (_requires Python v3.8+_)
- [logging_handler.py](logging_handler.py) - How to set up a python native logging handler that writes to InfluxDB
- [import_parquet.py](import_parquet.py) - How to import [Apache Parquet](https://parquet.apache.org/) data files, 
  the example requires: 
  - manually download [NYC TLC Trip Record Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page) 
  - install Apache Arrow `pip install pyarrow` dependency
- [write_batching_by_bytes_count.py](write_batching_by_bytes_count.py) - How to use RxPY to prepare batches by maximum bytes count.
- [http_error_handling.py](http_error_handling.py) - How to leverage HttpHeader information when errors are returned on write.

## Queries
- [query.py](query.py) - How to query data into `FluxTable`s, `Stream` and `CSV`
- [query_from_file.py](query_from_file.py) - How to use a Flux query defined in a separate file
- [query_response_to_json.py](query_response_to_json.py) - How to serialize Query response to JSON
- [query_with_profilers.py](query_with_profilers.py) - How to process profilers output by callback

## Management API
- [buckets_management.py](buckets_management.py) - How to create, list and delete Buckets
- [monitoring_and_alerting.py](monitoring_and_alerting.py) - How to create the Check with Slack notification.
- [task_example.py](task_example.py) - How to create a Task by API
- [templates_management.py](templates_management.py) - How to use Templates and Stack API
- [authorizations.py](authorizations.py) - How to create and use authorizations.

## InfluxDB Cloud

:warning: The following examples are related to [InfluxDB Cloud](https://docs.influxdata.com/influxdb/cloud/) and not available on a local InfluxDB OSS instance.

- [influx_cloud.py](influx_cloud.py) - How to connect to InfluxDB 2 Cloud
- [invokable_scripts.py](invokable_scripts.py) - How to use Invokable scripts Cloud API to create custom endpoints that query data
- [bucket_schemas.py](bucket_schemas.py) - How to manage explicit bucket schemas to enforce column names, tags, fields, and data types for your data

## Others
- [influxdb_18_example.py](influxdb_18_example.py) - How to connect to InfluxDB 1.8
- [nanosecond_precision.py](nanosecond_precision.py) - How to use nanoseconds precision
- [connection_check.py](connection_check.py) - How to check connection configuration

## Asynchronous
- [asynchronous.py](asynchronous.py) - How to use Asyncio with InfluxDB client
- [asynchronous_management.py](asynchronous_management.py) - How to use asynchronous Management API
- [asynchronous_batching.py](asynchronous_batching.py) - How to use [RxPY](https://rxpy.readthedocs.io/en/latest/) to prepare batches
- [asynchronous_retry.py](asynchronous_retry.py) - How to use [aiohttp-retry](https://github.com/inyutin/aiohttp_retry) to configure retries
  
