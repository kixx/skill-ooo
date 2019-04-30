# opsdroid skill ooo
A skill for [opsdroid](https://github.com/opsdroid/opsdroid) to track out-of-office

## Requirements

 * A database must be configured in opsdroid

## Configuration

None.

## Usage

#### ooo add _start_ [to _end_] [I'm _reason_]

##### ooo add tomorrow I'm gone fishing

Mark yourself as out-of-office tomorrow because you're going fishing

##### ooo add May 16 to May 31 I'm touring the alps

Mark yourself as out-of-office between May 16th and May 31 because you're touring the alps

##### ooo add December 1st

Mark yourself as out-of-office on December 1st with no reason

### ooo list

List all your out-of-office periods

### ooo delete _n_

Delete the _n_-th out-of-office period

### ooo clear

Delete all out-of-office periods

### ooo is _name_ in

Check if _name_ is in today

### ooo is _name_ in on _date_

Check if _name_ is in the office on _date_

### ooo who's out

List all people out-of-office today

### ooo who's out on _date_

List all people out-of-office on _date_
