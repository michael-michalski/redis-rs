# 0.9.1 (2018-09-10)

* Add ttl command

# 0.9.0 (2018-08-08)

Some time has passed since the last release.
This new release will bring less bugs, more commands, experimental async support and better performance.

Highlights:

* Implement flexible PubSub API (#136)
* Avoid allocating some redundant Vec's during encoding (#140)
* Add an async interface using futures-rs (#141)
* Allow the async connection to have multiple in flight requests (#143)

The async support is currently experimental.

# 0.8.0 (2016-12-26)

* Add publish command

# 0.7.1 (2016-12-17)

* Fix unix socket builds
* Relax lifetimes for scripts

# 0.7.0 (2016-07-23)

* Add support for built-in unix sockets

# 0.6.0 (2016-07-14)

* feat: Make rustc-serialize an optional feature (#96)

# 0.5.4 (2016-06-25)

* fix: Improved single arg handling (#95)
* feat: Implement ToRedisArgs for &String (#89)
* feat: Faster command encoding (#94)

# 0.5.3 (2016-05-03)

* fix: Use explicit versions for dependencies
* fix: Send `AUTH` command before other commands
* fix: Shutdown connection upon protocol error
* feat: Add `keys` method
* feat: Possibility to set read and write timeouts for the connection
