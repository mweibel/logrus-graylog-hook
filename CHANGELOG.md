# Logrus Graylog hook

## 2.0.2 - 2016-09-28

* Get rid of github.com/SocialCodeInc/go-gelf/gelf (#14)

## 2.0.1 - 2016-08-16

* Fix an issue with entry constructor (#12)

## 2.0.0 - 2016-07-02

* Remove facility param in constructor, as it's an optional param in Graylog 2.0 (credits: @saward / #9)
* Improve precision of TimeUnix (credits: @RaphYot / #2)
* Expose Gelf Writer (we will make this an interface in later versions) (credits: @cha-won / #10)

## 1.1.2 - 2016-06-03

* Fix another race condition (credits: @dreyinger / #8)

## 1.1.1 - 2016-05-10

* Fix race condition (credits: @rschmukler / #6)

## 1.1.0 - 2015-12-04

* The default behavior is now to send the logs synchronously.
* A new asynchronous hook is available through `NewAsyncGraylogHook`


