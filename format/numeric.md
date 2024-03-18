| Description                                                      | Format Rule                                                                                        |
|------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| any integer or decimal number, may begin with + or -            | /^[-+]?\\d*\\.?\\d+$/gm                                                                             |
| any positive integer or decimal number which includes zero      | /^(0\|[1-9]\\d*)(\\.\\d+)?$/gm                                                                       |
| decimal numbers between 0 and 1, inclusive                      | /^(0?(\\.\\d+)?\|1(\\.0+)?)$/gm                                                                      |
| positive integers                                                | /^[0-9]*[1-9][0-9]*$/gm                                                                             |
| any integer                                                      | /^-?[0-9]+$/gm                                                                                      |
| any number between 0 and 100, inclusive                         | /^(100(\\.0+)?\|0*([1-9]?\\d(\\.\\d+)?)\|0)$/gm                                                        |
| Latitude in formats S30°15'45.678" or N12°30.999"               | /^\\/[NS]-?(?:[0-8]?\\d\|90)°(?:\\d+(?:\\.\\d+)?)(?:'(\\d+(?:\\.\\d+)?)")?$/gm                       |
| Longitude in formats E30°15'45.678" or W90°00.000"              | /^\\/[EW]-?(?:[0-8]?\\d\|90)°(?:\\d+(?:\\.\\d+)?)(?:'(\\d+(?:\\.\\d+)?)")?$/gm                        |
