=======
History
=======

0.0.6 (2020-11-04)
------------------

* Fixed stale time limit computation.
* Added max queue waiting time timeout.


0.0.5 (2020-09-07)
------------------

* Fix of task unique key generator. Task unique key is generated with celery serializer and UUID5.


0.0.4 (2020-09-05)
------------------

* Partial fix of celery key generator.


0.0.3 (2020-09-01)
------------------

* Locked beater uses new redis cache. Fixed locked scheduler with low lock timeout value.


0.0.2 (2020-08-27)
------------------

* Added DJANGO_CELERY_EXTENSIONS_TASK_STALE_TIMELIMIT_FROM_TIME_LIMIT_CONSTANT setting which is used to compute task_stale_limit from task_time_limit

0.0.1 (2020-08-14)
------------------

* First release of the library
