# add
Version 0.1.0

Remake of "add" that adds some pre-hook filters, such as "due:today" adding todays actual date.

## Installing

```
cd ~/.todo.actions.d
git clone git@github.com:betsythefc/add.git
```

## Usage

```
$ date
Mon Jan  8 13:35:30 PST 2018
$ todo.sh list
(A) 2018-01-04 Clean @Apartment due:2018-01-08
(B) 2018-01-04 Finish homework
$ todo.sh add "Test due:today"
$ todo.sh list
(A) 2018-01-04 Clean @Apartment due:2018-01-08
(B) 2018-01-04 Finish homework
Test due:2017-01-08
```
