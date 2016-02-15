Russian Roulette Plugin for Cinch
========================
Play a game of Russian Roulette

Usage
-----

Until I figure out how to make it into a gem, download the .rb file, and place 
it in a subdirectory of your bot entitled 
`plugins` then require it via `require_relative`. 
Add it to your bot like so:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ ruby
require 'cinch'
require_relative 'plugins/roulette.rb'

bot = Cinch::Bot.new do
configure do |c|
  c.server = 'your server'
  c.nick = 'your nick'
  c.realname = 'your realname'
  c.user = 'your user'
  c.channels = ['#yourchannel']
  c.plugins.plugins = [Cinch::Plugins::Roulette]
end

bot.start
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Contained Commands
------------------

[rr]

Take your chances with the six shooter.

License
-------

Licensed under Creative Commons by-nc-sa 4.0
http://creativecommons.org/licenses/by-nc-sa/4.0/
