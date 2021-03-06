## 0.9.9 (release date: 2014-03-25)

 * Upgraded to baseimage-docker 0.9.9.
 * Upgraded to Phusion Passenger 4.0.40.
 * Upgraded to Nginx 1.4.7. This also fixes several Nginx vulnerabilities.
 * Ports 80 and 443 are now by default made available for Docker linking.
 * Redis and Memcached have been reintroduced, but only in the `passenger-customizable` and `passenger-full` images.
 * Various minor improvements. (Amir Gur)

## 0.9.8 (release date: 2014-02-26)

 * Upgraded to baseimage-docker 0.9.8.

## 0.9.7 (release date: 2014-02-25)

 * Upgraded to baseimage-docker 0.9.7.

## 0.9.6 (release date 2013-02-06)

 * Upgraded to baseimage-docker 0.9.5.

## 0.9.5 (release date 2013-02-03)

 * Upgraded to baseimage-docker 0.9.4, which fixes a syslog-ng startup problem.

## 0.9.4 (release date 2013-02-01)

 * Upgraded to Phusion Passenger 4.0.37, which improves Node.js and Meteor support and fixes many bugs.
 * Upgraded to baseimage-docker 0.9.3.
 * Added support for Ruby 2.1. This is available in the phusion/passenger-ruby21 image.
 * Reintroduced the phusion/passenger-full image.

## 0.9.3 (release date 2013-12-12)

 * Upgraded to Phusion Passenger 4.0.28.
 * Upgraded to baseimage-docker 0.9.2.
 * passenger-docker has been split into multiple versions, each one targeted at only a single programming language. The following images are now available on the Docker index: phusion/passenger-ruby18, phusion/passenger-ruby19, phusion/passenger-ruby20, phusion/passenger-python, phusion/passenger-nodejs. There is also a phusion/passenger-customizable image which allows you to easily have multiple languages in a single container.

## 0.9.2 (release date 2013-11-13)

 * Fixed the pups wrapper script.

## 0.9.1 (release date 2013-11-12)

 * Upgraded to baseimage-docker 0.9.1.

## 0.9.0 (release date 2013-11-12)

 * Initial release.
