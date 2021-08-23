# laravel-elastic-beanstalk
Laravel elastic beanstalk settings

This is currently for horizon and the task scheduler.

A quick and easy way to run laravel horizon in your laravel elastic beanstalk enviroment. I created this because I couldn't find lots of info online, so hopefully someone stumbles across this and it helps. The enviroment file loaded in at /opt/elasticbeanstalk/deployment/env is the enviroment properties you set in elastic beanstalk.

I have only tested this on PHP 8.0 running on 64bit Amazon Linux 2/3.3.4.

Add your .ebextensions to the root directory of your beanstalk and it should run the service at startup.
