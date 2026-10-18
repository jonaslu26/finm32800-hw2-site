# Dataframe: `hw2:crsp_treasury_consolidated` - CRSP Treasury Consolidated

Consolidated CRSP US Treasury database combining daily pricing data (prices, yields, durations) with issue-level characteristics (coupon, maturity, issue date). Sourced from WRDS.


## DataFrame Glimpse

```
Rows: 2530592
Columns: 20
$ kytreasno                  <f64> 200695.0
$ kycrspid                   <str> '19701115.205000'
$ tcusip                     <str> '912827AJ'
$ caldt             <datetime[ns]> 1970-01-02 00:00:00
$ tdatdt            <datetime[ns]> 1966-02-15 00:00:00
$ tmatdt            <datetime[ns]> 1970-11-15 00:00:00
$ tfcaldt                    <i64> 0
$ tdbid                      <f64> 97.15625
$ tdask                      <f64> 97.28125
$ tdaccint                   <f64> 0.66298342541437
$ tdyld                      <f64> 0.00022462008231759
$ price                      <f64> 97.88173342541437
$ tcouprt                    <f64> 5.0
$ itype                      <f64> 2.0
$ original_maturity          <f64> 5.0
$ years_to_maturity          <f64> 1.0
$ tdduratn                   <f64> 312.43877115662997
$ tdretnua                   <f64> 0.0009215955254947601
$ days_to_maturity           <i64> 317
$ callable                  <bool> False


```

## Dataframe Manifest

| Dataframe Name                 | CRSP Treasury Consolidated                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [crsp_treasury_consolidated](../dataframes/hw2/crsp_treasury_consolidated.md)                                       |
| Sources                        | CRSP                                          |
| Providers                      | WRDS                                        |
| Provider Links                 | https://wrds-www.wharton.upenn.edu/                                   |
| Tags                           | Treasury, Fixed Income, Yield Curve                                             |
| Access Types                   |                                       |
| How is data pulled?            | WRDS via Python                                                   |
| Data available up to (min)     | N/A (large file)                                                             |
| Data available up to (max)     | N/A (large file)                                                             |
| Dataframe Path                 | /Users/jonaslu/hw2-jonaslu26/_data/TFZ_consolidated.parquet                                             |


**Linked Charts:**

- None


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

