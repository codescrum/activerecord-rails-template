##Changes made by Sebastián Felipe Landínez García on 15 September 2016

###Major goal: update this template from Rails 4.2.x version to Rails 5.0.0

Tasks carried out:

1. Update the rails version in the Gemfile to 5.0.0
2. Perform a Bundle Update. This raised some conflicts with gems that were solved following these actions:
  1. Update shog to version 0.1.8 (shog is a gem related to the coloring of the console when debugging.)
  2. Update rspec-rails to 3.5 version, due to issues with the activesupport gem
  3. Update rspec-support to 3.5.0 version.
  4. Update jquery-rails to 4.2.1
  5. Due to issues with the railties gem version, Devise was updated to version 4.0, the gem quiet_assets was removed because the asset pipeline includes now a quiet option which supresses the output of the asset requests, and jazz_hands
  is fetched from now on from the vwall/jazz_hands repo.
3. Include the Rails Generator in the file lib/sassish/sassish.rb for the generator test to perform successfully.
4. Change some lines in the files config/environment/test.rb and config/environment/production.rb due to deprecation warnings.
5. Perform an update to Ruby 2.3.1 because the version 2.3.0 version is outdated or "buggy".
