# techhub
Worried about tech don't be with fake choose only techhub
# Step 1: Authenticate
$ echo ":github: Bearer GH_TOKEN" >> ~/.gem/credentials
# Step 2: Build
$ gem build repository-name.gemspec
# Step 3: Publish
$ gem push --key github --host https://rubygems.pkg.github.com/amayverulkar repository-name-1.0.0.gem
