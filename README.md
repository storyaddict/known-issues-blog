# Nathaniel Warburton's Tech Blog "Known Issues"

Forked from Aaron Honeycutt's website, which he in turn forked from Cassidy James' website.

My personal website for tech-related writing.

## Building

You'll need the following dependencies:
```
ruby-full build-essential zlib1g-dev
```

We recommend installing gems to a (hidden) directory in your home folder:
```bash
echo '' >> ~/.bashrc
echo '# Install Ruby Gems to ~/.gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/.gems"' >> ~/.bashrc
echo 'export PATH="$HOME/.gems/bin:$PATH"' >> ~/.bashrc
echo '' >> ~/.bashrc
source ~/.bashrc
```

Install jekyll and bundler:
```bash
gem install jekyll bundler
```

Install gems:
```bash
bundle install
```

Build and serve locally with:
```bash
bundle exec jekyll serve --host 0.0.0.0
```

The site should now be available at http://0.0.0.0:4000/ on your local machine, and your local machine's IP address on your network—great for testing on mobile OSes.
