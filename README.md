This repository is for keeping track of my reading and learning, inspired by many other [TIL repositories](https://github.com/search?utf8=%E2%9C%93&q=til&ref=simplesearch). These are too short for a blog post, too long for a tweet 😉.

## 2018-11-07

  * Pandas has a [Timestamp](https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.Timestamp.html) type that is compatible with python datetime.
  * [Optimistic locking vs Pessmistic locking](http://www.orafaq.com/papers/locking.pdf)
  * [Rai stones: There is an island uses stones for money, but the stones are too large to move, so buying an item simply means changing the ownership...](https://en.wikipedia.org/wiki/Rai_stones)

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
