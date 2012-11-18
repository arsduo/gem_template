# Gem Template

A template for creating new gems.  Mainly useful in that it contains the test setup I prefer -- RSpec, linting with Pelusa, documentation via RDoc -- along with the

### Usage

Clone the repo, then run `rake rename[ClassName, class_name]`, where ClassName is the Ruby constant name of the new project and class_name is the name of the file/directory.  (Obviously the one can be derived from the other, I just haven't taken the 3 minutes to copy the ActiveRecord code.)  This will change all the references and commit the updates.
