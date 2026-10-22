# Dataframe: `hw2:fed_funds_futures` - Federal Funds Futures

OHLCV bar per contract per trading day


## DataFrame Glimpse

```
Rows: 11744
Columns: 7
$ date   <datetime[ns]> 2026-10-20 00:00:00
$ symbol          <str> 'ZQ:BF J7-K7-N7'
$ open            <f64> -1.5
$ high            <f64> -1.5
$ low             <f64> -1.5
$ close           <f64> -1.5
$ volume          <u64> 4


```

## Dataframe Manifest

| Dataframe Name                 | Federal Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME                                          |
| Providers                      | Databento                                        |
| Provider Links                 |                                    |
| Tags                           | Treasury, Yield Curve, Federal Reserve                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento API                                                   |
| Data available up to (min)     | None                                                             |
| Data available up to (max)     | None                                                             |
| Dataframe Path                 | C:\Users\julia\Desktop\UChicago\FINM32800-DataPipelines\hw2-aaronjjay\_data\fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file://C:/Users/julia/Desktop/UChicago/FINM32800-DataPipelines/hw2-aaronjjay/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-22 07:40:54           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

