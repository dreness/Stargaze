# Template for Satin & Forge & Youi

## Getting Started

Clone Satin, Forge & Youi one folder up from this Template

```
cd .. && git clone https://github.com/Hi-Rez/Satin.git && git clone https://github.com/Hi-Rez/Forge.git && git clone https://github.com/Hi-Rez/Youi.git
```

Install Bundler using:

```
[sudo] gem install bundler
```

Install the Bundler dependencies specified in the Gemfile:

```
bundle config set path vendor/bundle
bundle install
```

Finally, install the CocoaPod dependencies using Bundler:

```
bundle exec pod install
```
