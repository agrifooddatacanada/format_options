| Description                                                     | Format rule                                                                      |
|-----------------------------------------------------------------|----------------------------------------------------------------------------------|
| Entries of any length with only capital letters                 | /^[A-Z]*$/gm                                                                         |
| Capital or lower case letters only, at least 1 character, and 50 characters max | /^[A-Za-z]{1,50}$/gm                                                                 |
| Capital or lower case letters only, 50 characters max           | /^[A-Za-z]{0,50}$/gm                                                                 |
| Short text, 50 characters max                                   | /^.{0,50}$/gm                                                                        |
| Short text, 250 characters max                                  | /^.{0,250}$/gm                                                                       |
| long text, 800 characters max                                   | /^.{0,800}$/gm                                                                       |
| long text, 4000 characters max                                  | /^.{0,4000}$/gm                                                                      |
| Canadian postal codes (A1A 1A1)                                 | /^[A-Z][0-9][A-Z]\\s[0-9][A-Z][0-9]$/gm                                             |
| Zip code                                                        | /^\d{5,6}(?:[-\s]\d{4})?$/gm                                                        |
| Email address                                                   | /[a-zA-Z0-9_\\.\\+-]+@[a-zA-Z0-9-]+\\.[a-zA-Z0-9-\\.]+/gm                           |
| URL                                                             | /https?\\:\\/\\/[a-zA-Z0-9\\-\\.]+\\.[a-zA-Z]{2,}/gm                                |
| Phone number                                                    | /\\+?\\(?\\d{2,4}\\)?[\\d\\s-]{3,}/gm                                               |
