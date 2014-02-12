---
  tags: rails, join tables, micro
  languages: ruby
---

# Join the Fun

## Deliverables

Fork this repository and submit your solution in master.

## Instructions

Flatiron School has started it's own taxi service, FlatironX, and we need to
start developing the application's domain model!

Three basic models have already been created, Passenger, Ride, and Taxi. Just run
`rake db:migrate` to apply their migrations to the database.

The next step is set up a "has_many :through" relationship between
these three models so that we can keep track of who's driving who around.
It will work like this:

`Taxi -< Rides >- Passengers`

This way, a taxi can have many passengers and a passenger can have many taxis!

Check out the join table section in the [Active Record Association Rails Guide](http://guides.rubyonrails.org/association_basics.html#the-has-many-through-association).

Run the tests using the `rspec` command.
