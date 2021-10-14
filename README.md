# Codespaces.Jekyll.Theme
Sandbox for showing usage of a theme with Jekyll problem

Steps:

```
gem install jekyll bundler
```
Show version
```
jekyll -v
```

Create template
```
jekyll new . --force
```
```
bundle install
```

Now run:
```
bundle exec jekyll serve
```

Now PROBLEM:

Replace `miminal` with `just-the-docs` in `_config.yml`
```
theme: just-the-docs
```

Add gem to Gemfile:
```
gem "just-the-docs"
```

Install again:
```
bundle install
```

Run
```
bundle exec jekyll serve
```

The porting forwarding not working. 