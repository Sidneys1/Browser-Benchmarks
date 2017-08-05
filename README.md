Browser Benchmarks
====

__Browsers are run in private mode where applicable.__

Some entries are marked __best__ or _worst_ compared to other browsers.

Dates are `YYMMDD`.

## Table of Contents

* [BrowserBench](#browserbench)
    * [Speedometer](#speedometer)
    * [JetStream](#jetstream)
    * [MotionMark](#motionmark)

# Tests

## [BrowserBench](http://BrowserBench.org)

###  [ARES-6 1.0.1](http://browserbench.org/ARES-6/)

> ARES-6 measures the execution time of JavaScript's newest features. [Read more details...](http://browserbench.org/ARES-6/about.html)

_Lower scores and lower variance is better._

|Browser | Version             | Date     | Score        | Variance     |
|:------:|:-------------------:|:--------:|-------------:|-------------:|
|Edge    |`41.16257.1000.0 x64`|`20170805`|  `112.87ms`  |  `± 9.61ms`  |
||
|Chromium|`57.0.2987.110   x64`|`20170805`| _`Failed  `_ | _`Failed  `_ |
|Chromium|`60.0.3112.90    x64`|"         |__` 47.36ms`__|__`± 0.93ms`__|

#### Details

|Browser |Test   |Version              |Date      |First Iter    |Worst 4 Iter  |       Average|Avg. Variance |
|:------:|:-----:|:-------------------:|:--------:|-------------:|-------------:|-------------:|-------------:|
|Edge    |Air    |`41.16257.1000.0 x64`|`20170805`|  ` 98.03ms`  | _` 90.93ms`_ | _` 56.73ms`_ |  `± 2.99ms`  |
|"       |Basic  |"                    |"         | _`173.70ms`_ | _`213.96ms`_ | _`164.13ms`_ |  `± 4.52ms`  |
|"       |Babylon|"                    |"         |__` 75.94ms`__|  ` 31.95ms`  |  ` 18.79ms`  |  `± 2.88ms`  |
|"       |ML     |"                    |"         |  `335.00ms`  |  `336.77ms`  |  `301.19ms`  |  `±20.18ms`  |
||
|Chromium|Air    |`57.0.2987.110   x64`|`20170805`| _`138.62ms`_ |__` 72.72ms`__|  ` 41.09ms`  |        _n/a_ |
|"       |Basic  |"                    |"         |  ` 89.46ms`  |  ` 34.12ms`  |  ` 27.97ms`  |        _n/a_ |
|"       |Babylon|"                    |"         |  _Failed_    |  _Failed_    | _Failed_     |    _Failed_  |
|"       |ML     |"                    |"         | _n/a_        | _n/a_        | _n/a_        |        _n/a_ |
|Chromium|Air    |`60.0.3112.90    x64`|`20170805`|__` 89.06ms`__|  ` 73.08ms`  |__` 15.66ms`__|__`± 0.12ms`__|
|"       |Basic  |"                    |"         |__` 83.62ms`__|__` 22.93ms`__|__` 17.05ms`__|__`± 0.53ms`__|
|"       |Babylon|"                    |"         |  ` 78.77ms`  |__` 24.44ms`__|__`  9.05ms`__|__`± 0.13ms`__|
|"       |ML     |"                    |"         |__`186.84ms`__|__`112.30ms`__|__`105.46ms`__|__`± 1.05ms`__|

### [Speedometer](http://BrowserBench.org/Speedometer)

> Speedometer is a browser benchmark that measures the responsiveness of Web applications.
> It uses demo web applications to simulate user actions such as adding to-do items.

_Bigger scores and lower variance is better._

|Browser   |Version              |Date      |     Score|        Max|        Min|     Variance|
|----------|---------------------|:---------|---------:|----------:|----------:|------------:|
|Chrome    |`56.0.2924.87    x64`|`21070205`|  `50.4`  |  `85.14`  |  `32.27`  | _`±  8.70`_ |
||
|Chromium  |`57.0.2964.0     x64`|`20170205`|  `73.7`  |  `82.54`  |  `45.17`  |  `±  4.80`  |
|Chromium  |`58.0.3009.0     x64`|`20170215`|  `84.3`  |  `87.52`  |  `78.91`  |  `±  1.10`  |
||
|Edge      |`40.15025.1000.0 x64`|`20170205`|  `35.9`  |  `37.29`  |  `34.06`  |  `±  0.38`  |
|Edge      |`40.15042.0.0    x64`|`20170226`|  `56.1`  |  `59.97`  |  `54.20`  |  `±  0.61`  |
||
|Firefox   |`51.0.1          x86`|`20170205`|  `27.0`  |  `31.96`  |  `22.72`  |  `±  1.10`  |
||
|Firefox DE|`53.0a2          x64`|`20170205`| _` 5.1`_ | _` 5.53`_ | _` 4.76`_ |__`±  0.13`__|
||
|Opera     |`43.0.2442.806   x64`|`20170215`|__`88.2`__|__`94.61`__|__`79.88`__|  `±  1.90`  |

Winner: Opera `43.0.2442.806 x64`

Most Stable: Firefox DE `53.0a2 x64`

### [JetStream](http://BrowserBench.org/JetStream)

> JetStream is a JavaScript benchmark suite focused on the most advanced web applications.

_Bigger scores and lower variance is better._

_Individual test scores are omitted for brevity._

|Browser   |Version              |Date      |Test Name       |       Score|     Variance|
|----------|---------------------|:---------|----------------|-----------:|------------:|
|Chrome    |`56.0.2924.87    x64`|`20170205`|__Overall__     | _`121.27`_ |  `±  6.66`  |
|"         |"                    |"         |_Latency_       |  ` 71.44`  |  `± 12.31`  |
|"         |"                    |"         |_Throughput_    |  `210.29`  |  `±  9.73`  |
|"         |"                    |"         |_Geometric Mean_|  `131.27`  |  `±  6.66`  |
||
|Chromium  |`57.0.2964.0     x64`|`20170205`|__Overall__     |  `146.56`  | _`± 15.85`_ |
|"         |"                    |"         |_Latency_       |  ` 78.18`  | _`± 15.85`_ |
|"         |"                    |"         |_Throughput_    |  `238.36`  |  `±  8.30`  |
|"         |"                    |"         |_Geometric Mean_|  `146.56`  | _`± 15.85`_ |
|Chromium  |`58.0.3009.0     x64`|`20170215`|__Overall__     |  `153.10`  |  `±  7.19`  |
|"         |"                    |"         |_Latency_       |  ` 89.53`  |  `±  9.07`  |
|"         |"                    |"         |_Throughput_    |  `231.80`  |__`±  1.29`__|
|"         |"                    |"         |_Geometric Mean_|  `153.10`  |  `±  7.19`  |
||
|Edge      |`40.15025.1000.0 x64`|`20170205`|__Overall__     |  `152.02`  |  `±  4.54`  |
|"         |"                    |"         |_Latency_       |  `115.92`  |  `± 11.77`  |
|"         |"                    |"         |_Throughput_    | _`187.53`_ |  `±  5.91`  |
|"         |"                    |"         |_Geometric Mean_|  `152.02`  |  `±  4.54`  |
|Edge      |`40.15042.0.0    x64`|`20170226`|__Overall__     |__`195.92`__|  `±  4.93`  |
|"         |"                    |"         |_Latency_       |__`166.36`__|  `±  5.22`  |
|"         |"                    |"         |_Throughput_    |  `222.32`  |  `±  5.51`  |
|"         |"                    |"         |_Geometric Mean_|__`195.92`__|  `±  4.93`  |
||
|Firefox   |`51.0.1          x86`|`20170205`|__Overall__     |  `122.90`  |  `± 14.58`  |
|"         |"                    |"         |_Latency_       |  ` 63.53`  |  `±  3.11`  |
|"         |"                    |"         |_Throughput_    |  `204.92`  | _`± 43.64`_ |
|"         |"                    |"         |_Geometric Mean_| _`122.90`_ |  `± 14.58`  |
||
|Firefox DE|`53.0a2          x64`|`20170205`|__Overall__     |  `131.08`  |  `±  6.12`  |
|"         |"                    |"         |_Latency_       | _` 62.24`_ |  `±  3.77`  |
|"         |"                    |"         |_Throughput_    |  `233.09`  |  `± 10.69`  |
|"         |"                    |"         |_Geometric Mean_|  `131.08`  |  `±  6.12`  |
||
|Opera     |`43.0.2442.806   x64`|`20170215`|__Overall__     |  `162.98`  |__`±  1.24`__|
|"         |"                    |"         |_Latency_       |  ` 99.14`  |__`±  1.43`__|
|"         |"                    |"         |_Throughput_    |__`239.30`__|  `±  2.10`  |
|"         |"                    |"         |_Geometric Mean_|  `162.98`  |__`±  1.24`__|

Winner: Edge `40.15042.0.0 x64`

Most Stable: Opera `43.0.2442.806 x64`

### [MotionMark](http://BrowserBench.org/MotionMark)

> MotionMark is a graphics benchmark that measures a browser’s capability to animate complex scenes at a target frame rate.

_Bigger scores and lower variance is better._

|Browser   |Version              |Date      |Test Name     |        Score|      Variance|
|----------|---------------------|:---------|--------------|------------:|-------------:|
|Chrome    |`56.0.2924.87    x64`|`20170205`|__Overall__   |  ` 127.92`  |  `± 21.18%`  |
|"         |"                    |"         |_Multiply_    |  ` 431.95`  |  `±  6.90%`  |
|"         |"                    |"         |_Canvas Arcs_ |  ` 276.88`  |  `±  4.94%`  |
|"         |"                    |"         |_Leaves_      |__` 598.94`__|  `±  3.17%`  |
|"         |"                    |"         |_Paths_       |  ` 784.85`  |  `± 47.17%`  |
|"         |"                    |"         |_Canvas Lines_| _`   5.00`_ |  `± 40.00%`  |
|"         |"                    |"         |_Focus_       |  `   8.46`  | _`± 65.55%`_ |
|"         |"                    |"         |_Images_      |__`  94.65`__|  `±  1.83%`  |
|"         |"                    |"         |_Design_      |__`  82.06`__|  `±  3.27%`  |
|"         |"                    |"         |_Suits_       |__` 496.33`__|  `±  5.32%`  |
||
|Chromium  |`57.0.2964.0     x64`|`20170205`|__Overall__   | _`  47.05`_ | _`± 49.65%`_ |
|"         |"                    |"         |_Multiply_    |  ` 532.70`  |  `±  1.03%`  |
|"         |"                    |"         |_Canvas Arcs_ | _`  87.00`_ | _`±617.12%`_ |
|"         |"                    |"         |_Leaves_      | _`   1.00`_ | _`±200.00%`_ |
|"         |"                    |"         |_Paths_       | _`   4.45`_ |  `±  6.60%`  |
|"         |"                    |"         |_Canvas Lines_|  ` 826.00`  | _`± 88.26%`_ |
|"         |"                    |"         |_Focus_       | _`   4.82`_ |  `± 58.51%`  |
|"         |"                    |"         |_Images_      |  `  89.70`  |  `±  1.66%`  |
|"         |"                    |"         |_Design_      |  `  73.09`  |  `±  3.41%`  |
|"         |"                    |"         |_Suits_       |  ` 209.83`  |  `±  5.39%`  |
|Chromium  |`58.0.3009.0     x64`|`20170215`|__Overall__   |  ` 228.69`  |  `±  9.33%`  |
|"         |"                    |"         |_Multiply_    |  ` 478.82`  |  `±  1.66%`  |
|"         |"                    |"         |_Canvas Arcs_ |  ` 283.34`  |  `±  1.57%`_ |
|"         |"                    |"         |_Leaves_      |  ` 554.31`  |  `± 45.45%`  |
|"         |"                    |"         |_Paths_       |  ` 790.37`  |  `±  1.31%`  |
|"         |"                    |"         |_Canvas Lines_|  `2778.30`  |__`±  0.33%`__|
|"         |"                    |"         |_Focus_       |  `   7.64`  |  `± 18.81%`  |
|"         |"                    |"         |_Images_      |  `  74.95`  |  `±  5.13%`  |
|"         |"                    |"         |_Design_      |  `  73.74`  |  `±  5.37%`  |
|"         |"                    |"         |_Suits_       |  ` 245.83`  |  `±  6.15%`  |
||
|Edge      |`40.15025.1000.0 x64`|`20170205`|__Overall__   |  ` 109.09`  |  `± 11.07%`  |
|"         |"                    |"         |_Multiply_    | _`   7.47`_ | _`± 73.22%`_ |
|"         |"                    |"         |_Canvas Arcs_ |  ` 474.59`  |  `±  6.44%`  |
|"         |"                    |"         |_Leaves_      |  ` 104.37`  |  `± 35.55%`  |
|"         |"                    |"         |_Paths_       |  `1523.54`  |  `± 18.56%`  |
|"         |"                    |"         |_Canvas Lines_|  `2279.18`  |  `± 12.39%`  |
|"         |"                    |"         |_Focus_       |__`  14.84`__|  `±  5.57%`  |
|"         |"                    |"         |_Images_      | _`  15.80`_ | _`± 11.24%`_ |
|"         |"                    |"         |_Design_      | _`   8.64`_ | _`±  7.70%`_ |
|"         |"                    |"         |_Suits_       |  `  70.85`  |  `±  9.87%`  |
|Edge      |`40.15042.0.0    x64`|`20170226`|__Overall__   |  ` 168.37`  |  `±  3.44%`  |
|"         |"                    |"         |_Multiply_    |  ` 222.61`  |  `±  2.42%`  |
|"         |"                    |"         |_Canvas Arcs_ |  ` 623.64`  |  `± 17.48%`  |
|"         |"                    |"         |_Leaves_      |  ` 187.71`  |__`±  1.20%`__|
|"         |"                    |"         |_Paths_       |  `2372.99`  |__`±  0.93%`__|
|"         |"                    |"         |_Canvas Lines_|__`3073.60`__|__`±  0.25%`__|
|"         |"                    |"         |_Focus_       |  `  16.53`  |  `±  4.13%`  |
|"         |"                    |"         |_Images_      |  `  29.26`  |__`±  1.21%`__|
|"         |"                    |"         |_Design_      |  `  11.28`  |__`±  1.46%`__|
|"         |"                    |"         |_Suits_       |  ` 104.81`  |__`±  0.55%`__|
||
|Firefox   |`51.0.1          x86`|`20170205`|__Overall__   |  ` 143.08`  |  `±  6.66%`  |
|"         |"                    |"         |_Multiply_    |  ` 138.61`  |  `±  1.87%`  |
|"         |"                    |"         |_Canvas Arcs_ |  ` 979.60`  |  `±  2.49%`  |
|"         |"                    |"         |_Leaves_      |  ` 222.65`  |  `± 37.53%`  |
|"         |"                    |"         |_Paths_       |  `2643.74`  |  `±  2.91%`  |
|"         |"                    |"         |_Canvas Lines_|  `1592.52`  |  `±  9.89%`  |
|"         |"                    |"         |_Focus_       |  `  11.35`  |  `±  1.97%`  |
|"         |"                    |"         |_Images_      |  `  28.27`  |  `±  2.74%`  |
|"         |"                    |"         |_Design_      |  `  10.79`  |  `±  5.37%`  |
|"         |"                    |"         |_Suits_       | _`  57.04`_ |  `±  1.28%`  |
||
|Firefox DE|`53.0a2          x64`|`20170205`|__Overall__   |  ` 158.45`  |__`±  3.06%`__|
|"         |"                    |"         |_Multiply_    |  ` 133.12`  |  `±  1.32%`  |
|"         |"                    |"         |_Canvas Arcs_ |__`1170.56`__|  `±  1.38%`  |
|"         |"                    |"         |_Leaves_      |  ` 223.97`  |  `±  7.25%`  |
|"         |"                    |"         |_Paths_       |__`3082.88`__|  `±  5.32%`  |
|"         |"                    |"         |_Canvas Lines_|  `2044.25`  |  `±  5.99%`  |
|"         |"                    |"         |_Focus_       |  `  12.40`  |__`±  1.71%`__|
|"         |"                    |"         |_Images_      |  `  29.65`  |  `±  2.70%`  |
|"         |"                    |"         |_Design_      |  `  12.68`  |  `±  5.49%`  |
|"         |"                    |"         |_Suits_       |  `  61.42`  |  `±  1.35%`  |
||
|Opera     |`43.0.2442.806   x64`|`20170215`|__Overall__   |__` 242.20`__|  `± 10.55%`  |
|"         |"                    |"         |_Multiply_    |__` 555.47`__|__`±  1.02%`__|
|"         |"                    |"         |_Canvas Arcs_ |  ` 289.74`  |__`±  1.01%`__|
|"         |"                    |"         |_Leaves_      |  ` 523.29`  |  `±  1.64%`  |
|"         |"                    |"         |_Paths_       |  ` 795.44`  | _`± 50.68%`_ |
|"         |"                    |"         |_Canvas Lines_|  `2422.32`  |  `±  0.41%`  |
|"         |"                    |"         |_Focus_       |  `   6.69`  |  `± 15.71%`  |
|"         |"                    |"         |_Images_      |  `  84.18`  |  `±  4.05%`  |
|"         |"                    |"         |_Design_      |  `  70.47`  |  `±  2.38%`  |
|"         |"                    |"         |_Suits_       |  ` 445.51`  | _`± 10.62%`_ |

Winner: Chrome `56.0.2924.87 x64`

Most Stable: Edge `40.15042.0.0 x64`