# Dataframe: `hw2:fed_yield_curve` - Federal Reserve Yield Curve

Daily zero-coupon yields (SVENY01 to SVENY30, in percent) implied by the Nelson-Siegel-Svensson curve that Gurkaynak, Sack, and Wright estimate and the Federal Reserve Board publishes.


## DataFrame Glimpse

```
Rows: 17043
Columns: 31
$ SVENY01          <f64> 4.4929
$ SVENY02          <f64> 4.7593
$ SVENY03          <f64> 4.8821
$ SVENY04          <f64> 4.9442
$ SVENY05          <f64> 4.9865
$ SVENY06          <f64> 5.0277
$ SVENY07          <f64> 5.0747
$ SVENY08          <f64> 5.1288
$ SVENY09          <f64> 5.1884
$ SVENY10          <f64> 5.2514
$ SVENY11          <f64> 5.3154
$ SVENY12          <f64> 5.3783
$ SVENY13          <f64> 5.4384
$ SVENY14          <f64> 5.4944
$ SVENY15          <f64> 5.5454
$ SVENY16          <f64> 5.5907
$ SVENY17          <f64> 5.6301
$ SVENY18          <f64> 5.6633
$ SVENY19          <f64> 5.6903
$ SVENY20          <f64> 5.7112
$ SVENY21          <f64> 5.7262
$ SVENY22          <f64> 5.7356
$ SVENY23          <f64> 5.7395
$ SVENY24          <f64> 5.7382
$ SVENY25          <f64> 5.7322
$ SVENY26          <f64> 5.7216
$ SVENY27          <f64> 5.7068
$ SVENY28          <f64> 5.6881
$ SVENY29          <f64> 5.6658
$ SVENY30          <f64> 5.6402
$ Date    <datetime[ns]> 2026-10-09 00:00:00


```

## Dataframe Manifest

| Dataframe Name                 | Federal Reserve Yield Curve                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_yield_curve](../dataframes/hw2/fed_yield_curve.md)                                       |
| Sources                        | Federal Reserve                                          |
| Providers                      | Federal Reserve Board                                        |
| Provider Links                 | https://www.federalreserve.gov/data/nominal-yield-curve.htm                                   |
| Tags                           | Treasury, Yield Curve, Federal Reserve                                             |
| Access Types                   |                                       |
| How is data pulled?            | Web download via Python                                                   |
| Data available up to (min)     | 2026-10-09 00:00:00                                                             |
| Data available up to (max)     | 2026-10-09 00:00:00                                                             |
| Dataframe Path                 | /Users/jonaslu/hw2-jonaslu26/_data/fed_yield_curve.parquet                                             |


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

