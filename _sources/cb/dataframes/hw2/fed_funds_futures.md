# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures (ZQ)

Daily OHLCV bars (schema ohlcv-1d) from the CME Globex feed (dataset GLBX.MDP3), pulled with the parent symbol ZQ.FUT so that every listed ZQ contract arrives in one query. Each contract settles at 100 minus the calendar-day average of the daily effective federal funds rate (EFFR) over its month, so 100 minus the price is the market-implied average rate for that month. Symbols are root + month code + year digit (ZQU6 is September 2026). The parent query also returns calendar spreads and butterflies such as ZQU6-ZQZ6; keep only outright contracts before reading prices as rates. Thinly traded far months may have no bar on a given day.


## DataFrame Glimpse

```
Rows: 11806
Columns: 7
$ date   <datetime[ns]> 2026-10-16 00:00:00
$ symbol          <str> 'ZQ:BF J7-K7-N7'
$ open            <f64> -1.0
$ high            <f64> -1.0
$ low             <f64> -1.5
$ close           <f64> -1.5
$ volume          <u64> 22


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures (ZQ)                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Group                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           | Monetary Policy, Futures, Fed Funds                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento API via Python                                                   |
| Data available up to (min)     | 2026-10-16 00:00:00                                                             |
| Data available up to (max)     | 2026-10-16 00:00:00                                                             |
| Dataframe Path                 | /Users/jonaslu/hw2-jonaslu26/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///Users/jonaslu/hw2-jonaslu26/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-18 12:00:24           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

