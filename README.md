# koeri-json-parse

this python script program gets last earthquakes in Turkey data from "http://www.koeri.boun.edu.tr/scripts/lst0.asp"  it parses and converts to json
if you want to print screen you can run print_to_screen.py
or you can access directly [http://api.egemeric.gen.tr/deprem.php](http://api.egemeric.gen.tr/deprem.php)
# You can print data with shell_exec() function with php

```bash

<?php

$command = escapeshellcmd('python3 /var/www/api.egemeric.gen.tr/koeri-json-parse/parse.py');
$output = shell_exec($command);
echo $output;

?>


```
## requirements

```bash

beautifulsoup4==4.8.1

requests==2.22.0

```


her türlü bilgi, veri ve haritalara ilişkin telif hakları münhasıran Boğaziçi Üniversitesi Rektörlüğü’ne ait olup, Boğaziçi Üniversitesi Kandilli Rasathanesi ve Deprem Araştırma Enstitüsü Bölgesel Deprem-Tsunami İzleme Ve Değerlendirme Merkezi kaynak gösterilerek kullanılabilir. Söz konusu bilgi, veri ve haritalar Boğaziçi Üniversitesi Rektörlüğü’nün yazılı izni ve onayı olmadan herhangi bir şekilde ticari amaçlı kullanılamaz.



Upon use of KOERI data, proper attribution should be given to KOERI-RETMC in scientific articles and general purpose reports by referencing the network citation.
