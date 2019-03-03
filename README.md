This repository is for keeping track of my reading and learning, inspired by many other [TIL repositories](https://github.com/search?utf8=%E2%9C%93&q=til&ref=simplesearch). These are too short for a blog post, too long for a tweet 😉.

## 2019-03-02

I was too busy with random stuff, but anyway, here I am again.

  * [ElasticSearch: ignore_malformed does not work correctly for all field types](https://github.com/elastic/elasticsearch/issues/12366). This would basically make ES not suitable for storing schemaless documents, when a field you may have mutiple value types.


## 2018-12-28

  * [[Why prime numbers are important in Cryptography]](https://stackoverflow.com/questions/439870/why-are-primes-important-in-cryptography)

## 2018-12-14

  * [[The truth about Hydrogen]](https://www.youtube.com/watch?v=f7MzFfuNOtY)

## 2018-12-12

  * [Top 5 mistakes in Spark application](https://www.slideshare.net/SparkSummit/top-5-mistakes-when-writing-spark-applications-by-mark-grover-and-ted-malaska)
  * [E911 Fee](https://www.att.com/shop/wireless/prepaidE911.html)

## 2018-12-11

  * [Wifi 802.11ax](https://www.networkworld.com/article/3215907/mobile-wireless/why-80211ax-is-the-next-big-thing-in-wi-fi.html)
  * [ElasticSearch as primary data store](https://vlkan.com/blog/post/2018/11/14/elasticsearch-primary-data-store/)

## 2018-12-06

  * [What happens if you can't pay a toll](https://www.businessinsider.com/what-happens-when-you-cant-pay-a-toll-2013-7)
  * [IEEE 42010-2011: System and software engineering architecture description](https://www.slideshare.net/luctrudeau/architecture-vs-design)

## 2018-12-05

  * [No principles software architecture](https://www.innoq.com/en/blog/no-principles-software-architecture/): interesting article about some software design principles can cause more harm than good.

## 2018-12-04

  * [Continuation-passing style](https://en.wikipedia.org/wiki/Continuation-passing_style)

## 2018-12-03
  
  * [Circuit Breaker](https://martinfowler.com/bliki/CircuitBreaker.html) design pattern.


## 2018-12-02

  * [You can't use your iPhone as a bluetooth speaker](https://www.quora.com/How-do-you-use-your-iPhone-as-a-bluetooth-speaker). Silly idea though ...

## 2018-12-01

  * [Differences between 3.5mm jack for laptop and mobiles](https://www.quora.com/What-is-the-difference-between-3-5-mm-jack-in-mobiles-and-laptops)

## 2018-11-30

  * [udev](https://wiki.debian.org/udev): linux dynamic device management - An interface allows you to define rules to run when device connects the computer.

## 2018-11-29

  * A [vulnerability](https://schneid.io/blog/event-stream-vulnerability-explained/) in event-stream module that allows  attacker to steal bitcoin from your wallet.
  * [Saleor](https://getsaleor.com): an ecommerce system written in Django
  * [OData](https://blogs.sap.com/2016/02/08/odata-everything-that-you-need-to-know-part-3/): open data access protocol from Microsoft that allows the creation and consumption of query-able and interoperable RESTful APIs in a simple and standard way

## 2018-11-28

  * [Flic](https://flic.io/): smart button, kinda like AWS IoT button. It's expensive though ..
  * [Synthetic Sensor from CMU](https://www.cmu.edu/news/stories/archives/2017/may/internet-of-things-sensors.html)

## 2018-11-27

  * [Advanced Linux Sound Architecture](https://en.wikipedia.org/wiki/Advanced_Linux_Sound_Architecture)
  * [Add AirPlay to your FireTV](https://www.ikream.com/2018/11/add-airplay-amazon-fire-tv-25126)

## 2018-11-23

  * [Origin of Blackfriday](https://www.thebalance.com/what-is-the-history-of-black-friday-3305711)

## 2018-11-22

  * Happy Thanksgiving 🦃

## 2018-11-20

  * [Laplacian smoothing](https://www.quora.com/Could-someone-explain-Laplacian-smoothing-or-1-up-smoothing) can be used to estimate the probability of unseen data with small data sample.
  * Be [careful](https://github.com/golang/go/issues/6376) when you do cross-compiling with golang.

## 2018-11-18

  * Use `sudo airport -s` to scan for wifi from your mac terminal.
  * [MacOs Wifi Scanning](https://clburlison.com/macos-wifi-scanning/)
  * [airport-bssid](https://github.com/deekayw0n/airport-bssid) allows you to connect to wifi using BSSID
    * For [macOs 10.14 or later](https://developer.apple.com/documentation/macos_release_notes/macos_mojave_10_14_release_notes), you will need to enable location service to use this feature.

## 2018-11-14

  * [MQTT vs REST](https://medium.com/@flespi/http-vs-mqtt-performance-tests-f9adde693b5f)
  * [Sublime Remote Edit](https://packagecontrol.io/packages/RemoteEdit)

## 2018-11-12

  * [AWS Pinpoint](https://aws.amazon.com/pinpoint/): A mailchimp-like service by AWS
  * [AWS Transcribe](https://aws.amazon.com/transcribe/) currently only supports English and Spanish 😟.

## 2018-11-07

  * Pandas has a [Timestamp](https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.Timestamp.html) type that is compatible with python datetime.
  * [Optimistic locking vs Pessmistic locking](http://www.orafaq.com/papers/locking.pdf)
  * [Rai stones](https://en.wikipedia.org/wiki/Rai_stones): There is an island uses stones for money, but the stones are too large to move, so buying an item simply means changing the ownership...

## 2018-11-06

  * [Modin: Pandas on ray](https://rise.cs.berkeley.edu/blog/modin-pandas-on-ray-october-2018/). This is interesting as they also provide a way to fallback to Pandas if the API is not implemented (yet).
  * Spark: use `partitionBy()` can help improve performance of subsequence `groupByKey()`
  * Pandas now supports [read / write](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_parquet.html) parquet files.

## 2018-11-05

  * Terraform ebs_optmized flag is troublesome. There is even a [module](https://github.com/terraform-aws-modules/terraform-aws-ebs-optimized) to determined the default state for this flag.
  * [Dataflow Diagram Templates](https://creately.com/blog/examples/data-flow-diagram-templates/)

## 2018-11-03

  * [Brain of Things](https://dzone.com/articles/the-brain-of-things-and-home-automation): I heard it for a while, but I only really read about it today.

## 2018-11-02

  * [How does Bayesian Optimization work?](https://www.quora.com/How-does-Bayesian-optimization-work)
  * [Use pandas `category` can reduce memory usage a lot](https://www.dataquest.io/blog/pandas-big-data/)
  * Fidelity has a [self-funded overdraft protection](https://www.fidelity.com/cash-management/faqs-cash-management-account), which automatically move money within accounts to avoid overdraft. Typical bank charges you interest as soon as the overdraft happens.
  * Chase Cardless ATM works with Apply Pay. You can just hold your phone near the icon to make the transaction.

## 2018-11-01

  * Python: Use `isinstance(x, numbers.Number)` to check if an instance is number
  * [tornado.httpclient only handles 10 concurrent requests by default](https://stackoverflow.com/questions/33411493/max-clients-limit-reached-request-queued-tornado)
  * Pandas None handling is confusing:
    * DateTime has `NaT` and Float has a `NaN`, but boolean with null value will become object. So `DataFrame({"test": [True, False]})` has dtype is `bool` but `DataFrame({"test": [True, None]})` has dtype is `object`. Unless you force the dtype explicitly. Maybe we need a `NaB` type ...
    * In fact, integer will be converted to float if there is a None value as well.
    * For number bigger than uint64, you will need to cast to object.
    * [Overview of Pandas dtypes](http://pbpython.com/pandas_dtypes.html)
  * [Spark does not truely support unsigned integer](https://issues.apache.org/jira/browse/SPARK-7697)
  * [How to use binary number to represent decimal number](https://blog.angularindepth.com/the-simple-math-behind-decimal-binary-conversion-algorithms-d30c967c9724)

## 2018-31-01

  * [TimescaleDB](https://github.com/timescale/timescaledb): Open source postgres extension for time series databases.
  * [Opensource Timeseries DB Comparison](https://docs.google.com/spreadsheets/d/1sMQe9oOKhMhIVw9WmuCEWdPtAoccJ4a-IuZv4fXDHxM/edit#gid=0)
