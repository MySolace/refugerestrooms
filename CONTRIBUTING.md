## Setting Up Development Environment
* [ ] `git clone https://github.com/mysolace/refugerestrooms.git; git checkout -b feature-or-fix-name`
* [ ] Install [Vagrant](https://www.vagrantup.com/downloads.html)
* [ ] `cd refugerestrooms; vagrant up` (Safely ignore: 'dpkg-preconfigure: unable to re-open stdin: No such file or directory')
* [ ] Start the rails server:
  * [ ] `vagrant ssh`
  * [ ] `cd /vagrant/`
  * [ ] `rails s -b 0.0.0.0`
* [ ] Make changes; `vagrant provision`
* [ ] `rake db:fix_accents` (optionally append `[dry_run]` to preview)
* [ ] Cover new code with RSpec or Capybara for tests.
* [ ] Pull request


### Assets
* [Assets Repo](https://github.com/RefugeRestrooms/refuge_assets)
