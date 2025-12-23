# KLiNG0NE / Benchmark / Browser

Hier befinden sich die Browserbenchmarks in tabellarischer Darstellung.

### 2025-12

| Browser            | Version        | Main           | [JetStream 2.2][1] | [Speedometer 3.0][2] | [MotionMark 1.3.1][3][^1] | [SunSpider 1.0][4] | [HTML5test][5][^2]
| ------------------ | -------------- | -------------- | :----------------: | :------------------: | :-----------------------: | :----------------: | :-------------------:
| [Chromium][chr]    |                |                | 67.050             |                      |                           |                    | 
| [Firefox][fir]     | 146.0.1        |                | 219.250            |                      |                           |                    | 

### 2024-12

| Browser            | Version        | Main           | [JetStream 2.2][1] | [Speedometer 3.0][2] | [MotionMark 1.3.1][3][^1] | [SunSpider 1.0][4] | [HTML5test][5][^2]
| ------------------ | -------------- | -------------- | :----------------: | :------------------: | :-----------------------: | :----------------: | :-------------------:
| [Chromium][chr]    | 131.0.6778.69  |                | 265.426            | 13.7 ± 0.46          | 1367.74 ±8.41%            | 52.0ms +/- 3.5%    | 581
| [Firefox][fir]     | 133.0.3        |                | 186.935            | 15.0 ± 0.62          | 1151.14 ±6.64%            | 49.9ms +/- 13.8%   | 546
| [Edge][edg]        | 131.0.2903.99  |                | 275.349            | 20.4 ± 1.40          | 2641.24 ±2.38%            | 49.4ms +/- 2.4%    | 581
| [Brave][bra]       | 131.0.6778.139 |                | 276.216            | 17.9 ± 0.89          | 1862.81 ±2.45%            | 49.1ms +/- 2.8%    | 581
| [LibreWolf][lib]   | 133.0.3-1      |                | 168.020            |  9.26 ± 0.45         |  710.78 ±8.08%            | 36.7ms +/- 45.1%   | 539
| [Tor Browser][tor] |                | 128.5.0 ESR    | 152.268            |  9.33 ± 0.59         |  914.98 ±11.30%           | 75.0ms +/- 29.0%   | 457
| [Vivaldi][viv]     | 7.0.3495.27    | 130.0.0.0      | 278.574            | 20.5 ± 1.0           | 2165.41 ±2.72%            | 53.6ms +/- 4.4%    | 581
| [Zen][zen]         | 1.0.2-b.2      | 133.0.3        | 192.687            | 15.3 ± 0.43          | 1227.54 ±3.30%            | 50.2ms +/- 12.6%   | 546
| [Floorp][flo]      | 11.21.0        | 128.0          | 183.493            | 16.0 ± 0.36          | 1090.78 ±3.19%            | 44.6ms +/- 4.0%    | 546
| [Midori][mid]      | 11.4.3         | 128.0          | 171.244            | 12.4 ± 0.26          | 1001.36 ±3.26%            | 45.6ms +/- 3.8%    | 546
| [Pale Moon][pal]   | 33.0.5         |                |                    |                      |  363.98 ±16.36%           | 93.2ms +/- 8.7%    | 477
| [Arc][arc]         | 1.33.0 (3189)  | 131.0.6778.205 | 273.540            | 19.2 ± 0.91          | 1776.17 ±2.56%            | 55.0ms +/- 2.9%    | 581

[1]: <https://browserbench.org/JetStream/> "JetStream 2.2"
[2]: <https://browserbench.org/Speedometer3.0/> "Speedometer 3.0"
[3]: <https://browserbench.org/MotionMark1.3.1> "SunSpider 1.0"
[4]: <http://proofcafe.org/jsx-bench/js/sunspider.html> "SunSpider 1.0"
[5]: <https://html5test.co/> "HTML5test"

[arc]: <https://arc.net/> "arc.net"
[bra]: <https://brave.com/de/> "brave.com"
[chr]: <https://chromium.woolyss.com/download/de/> "chromium.woolyss.com"
[edg]: <https://www.microsoft.com/de-de/edge/business/download> "www.microsoft.com"
[fir]: <https://www.mozilla.org/de/firefox/all/> "www.mozilla.org"
[flo]: <https://floorp.app/en> "floorp.app"
[lib]: <https://librewolf.net> "librewolf.net"
[mid]: <https://astian.org/midori-browser/> "astian.org"
[pal]: <https://www.palemoon.org> "www.palemoon.org"
[tor]: <https://www.torproject.org/de/> "www.torproject.org"
[viv]: <https://vivaldi.com/de/> "vivaldi.com"
[zen]: <https://zen-browser.app> "zen-browser.app"

## Tests

### JetStream
JetStream 2.2 ist eine JavaScript- und WebAssembly-Benchmark-Suite, die sich auf die fortschrittlichsten Webanwendungen konzentriert. Sie belohnt Browser, die schnell starten, Code schnell ausführen und reibungslos funktionieren. Höhere Punktzahlen sind besser.  
https://browserbench.org/JetStream/

### Speedometer
Speedometer ist ein Browser-Benchmark, der die Reaktionsfähigkeit von Webanwendungen misst. Er verwendet Demo-Webanwendungen, um Benutzeraktionen wie das Hinzufügen von Aufgaben zu simulieren. (Niedrigere Werte sind besser.)  
https://browserbench.org/Speedometer3.0/

### MotionMark
MotionMark ist ein Grafik-Benchmark, der die Fähigkeit eines Browsers misst, komplexe Szenen mit einer bestimmten Bildfrequenz zu animieren. Höhere Punktzahlen sind besser.  
https://browserbench.org/MotionMark1.3.1

### SunSpider
SunSpider ist ein JavaScript-Benchmark. Dieser Benchmark testet nur die Kernsprache JavaScript, nicht das DOM oder andere Browser-APIs. Er ist dazu gedacht, verschiedene Versionen desselben Browsers und verschiedene Browser miteinander zu vergleichen.

#### Reale Welt
Dieser Test vermeidet Mikrobenchmarks und versucht, sich auf die Probleme zu konzentrieren, die Entwickler heute mit JavaScript lösen, und auf die Probleme, die sie in Zukunft angehen wollen, wenn die Sprache schneller wird. Dazu gehören Tests zur Erzeugung einer Tagcloud aus JSON-Eingaben, ein 3D-Raytracer, Kryptographie-Tests, Code-Dekompression und viele weitere Beispiele. Es gibt ein paar Mikrobenchmarks, die aber meist echte Leistungsprobleme darstellen, auf die Entwickler gestoßen sind.

#### Ausgewogen
Dieser Test ist ausgewogen zwischen verschiedenen Bereichen der Sprache und verschiedenen Arten von Code. Es geht nicht nur um Mathematik, um die Verarbeitung von Zeichenketten oder um das Timing einfacher Schleifen. Zusätzlich zu den Tests in vielen Kategorien wurden die einzelnen Tests so abgestimmt, dass sie auf den aktuellen Versionen der gängigen Browser ähnlich viel Zeit benötigen.

#### Statistisch fundiert
Eine der Herausforderungen beim Benchmarking besteht darin, zu wissen, wie viel Ungenauigkeit in den Messungen steckt. Dieser Benchmark führt jeden Test mehrmals durch und bestimmt einen Fehlerbereich (technisch gesehen ein 95%-Konfidenzintervall). Im Vergleichsmodus können Sie außerdem feststellen, ob Sie über genügend Daten verfügen, um festzustellen, ob der Unterschied statistisch signifikant ist. (Niedrigere Werte sind besser.)  
http://proofcafe.org/jsx-bench/js/sunspider.html

### HTML5test
Diese Website testet wie gut der HTML5-Standard von dem Browser unterstützt wird.  
Original-Website: https://html5test.com/  
Inoffizielles Update: https://html5test.co/

### BrowserAudit
BrowserAudit ist ein kostenloser Dienst, mit dem Sie testen können, wie gut die gängigsten Sicherheitsstandards und -funktionen in Ihrem Webbrowser implementiert sind. Die Website beinhaltet eine Sammlung von über 400 Tests. Nach ein paar Minuten erhalten Sie einen persönlichen Bericht, in dem beschrieben wird, was gut und was schlecht an der Umsetzung dieser Sicherheitsfunktionen in Ihrem Webbrowser ist.  
https://browseraudit.com/

###### Fußnoten
[^1]: @ 60fps
[^2]: von 594 mögl. Punkten
