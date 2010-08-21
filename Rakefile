# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.add_include_dirs("../../vlad/dev/lib",
                     "../../rake-remote_task/dev/lib")

Hoe.plugin :seattlerb

Hoe.spec 'vlad-perforce' do
  developer 'Ryan Davis', 'ryand-ruby@zenspider.com'

  extra_deps << ["vlad", "~> 2.1.0"]

  self.rubyforge_name = 'hitsquad'
end

# vim: syntax=ruby
