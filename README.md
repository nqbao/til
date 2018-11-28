This repository is for keeping track of my reading and learning, inspired by many other [TIL repositories](https://github.com/search?utf8=%E2%9C%93&q=til&ref=simplesearch). These are too short for a blog post, too long for a tweet 😉.

## 2018-11-17

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
  * [macOs Wifi Scanning](https://clburlison.com/macos-wifi-scanning/)
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
