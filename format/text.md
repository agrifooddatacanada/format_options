| Description-en                                                  | Description-fr                             | Format rule                                                                      |
|-----------------------------------------------------------------|-------------------------------------------|----------------------------------------------------------------------------------|
| Entries of any length with only capital letters                 | Entrées de toute longueur avec uniquement des lettres majuscules | ^[A-Z]*$                                                                         |
| Capital or lower case letters only, at least 1 character, and 50 characters max | Lettres majuscules ou minuscules uniquement, au moins 1 caractère, et 50 caractères max | ^[A-Za-z]{1,50}$                                                                 |
| Capital or lower case letters only, 50 characters max           | Lettres majuscules ou minuscules uniquement, 50 caractères max | ^[A-Za-z]{0,50}$                                                                |
| Short text, 50 characters max                                   | Texte court, 50 caractères max             | ^.{0,50}$                                                                        |
| Short text, 250 characters max                                  | Texte court, 250 caractères max            | ^.{0,250}$                                                                       |
| long text, 800 characters max                                   | Texte long, 800 caractères max             | ^.{0,800}$                                                                      |
| long text, 4000 characters max                                  | Texte long, 4000 caractères max            | ^.{0,4000}$                                                                      |
| Canadian postal codes (A1A 1A1)                                 | Codes postaux canadiens (A1A 1A1)          | ^[A-Z][0-9][A-Z]\\s[0-9][A-Z][0-9]$                                             |
| Zip code                                                        | Code postal                                | ^\d{5,6}(?:[-\s]\d{4})?$                                                        |
| Email address                                                   | Adresse e-mail                             | [a-zA-Z0-9_\\.\\+-]+@[a-zA-Z0-9-]+\\.[a-zA-Z0-9-\\.]+                          |
| URL                                                             | URL                                        | https?\\:\\/\\/[a-zA-Z0-9\\-\\.]+\\.[a-zA-Z]{2,}                               |
| Phone number                                                    | Numéro de téléphone                        | \\+?\\(?\\d{2,4}\\)?[\\d\\s-]{3,}                                              |
| Latitude in formats S30°15'45.678" or N12°30.999"	              | Latitude aux formats S30°15'45.678" ou N12°30.999" | ^[NS]-?(?:[0-8]?\\d\|90)°(?:\\d+(?:\\.\\d+)?)(?:'(\\d+(?:\\.\\d+)?)")?$ |
| Longitude in formats E30°15'45.678" or W90°00.000"	            | Longitude aux formats E30°15'45.678" ou W90°00.000" | ^[WE]-?(?:[0-8]?\\d\|90)°(?:\\d+(?:\\.\\d+)?)(?:'(\\d+(?:\\.\\d+)?)")?$ |
 
