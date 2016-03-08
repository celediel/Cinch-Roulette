Russian Roulette Plugin for Cinch
========================
Play a game of Russian Roulette

Usage
-----

[![Gem Version](https://badge.fury.io/rb/Cinch-Roulette.svg)](https://badge.fury.io/rb/Cinch-Roulette)

Install the gem with *gem install Cinch-Roulette*
add it to your bot like so:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ ruby
require 'cinch'
require 'cinch/plugins/roulette'

bot = Cinch::Bot.new do
  configure do |c|
    c.server = 'your server'
    c.nick = 'your nick'
    c.realname = 'your realname'
    c.user = 'your user'
    c.channels = ['#yourchannel']
    c.plugins.plugins = [Cinch::Plugins::Roulette]
  end
end

bot.start
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Contained Commands
------------------

[rr]

Take your chances with the six shooter.

[spin]

Spin the relvover, resetting the position of the bullet.

License
-------

Licensed under The MIT License (MIT)
Please see LICENSE
