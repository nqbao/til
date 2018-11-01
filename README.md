This repository is for keeping track of my reading and learning, inspired by many other [TIL repositories](https://github.com/search?utf8=%E2%9C%93&q=til&ref=simplesearch). These are too short for a blog post, too long for a tweet 😉.

## 2018-11-01

  * Python: Use `isinstance(x, numbers.Number)` to check if an instance is number
  * [tornado.httpclient only handles 10 concurrent requests by default](https://stackoverflow.com/questions/33411493/max-clients-limit-reached-request-queued-tornado)
  * [Overview of Pandas dtypes](http://pbpython.com/pandas_dtypes.html)
    * DateTime has `NaT` and Int/Float has a `NaN`, but boolean will become object. So `DataFrame({"test": [True, False]})` has dtype is `bool` but `DataFrame({"test": [True, None]})` has dtype is `object`. Unless you force the dtype explicitly. Maybe we need a `NaB` type ...
  * [Spark does not truely support unsigned integer](https://issues.apache.org/jira/browse/SPARK-7697)
  * [How to use binary number to represent decimal number](https://blog.angularindepth.com/the-simple-math-behind-decimal-binary-conversion-algorithms-d30c967c9724)
