# Vilnius Golang community
vilniusgolang.github.io website source files

### Development

Assuming Go is installed:

1) Fork repositoy

2) Clone your new fork

```
git clone https://github.com/YOURNAME/website vilniusgolang
```

3) cd vilniusgolang

4) go get -u -v github.com/spf13/hugo

5) ./server

6) Browse: http://localhost:1313/

### Posting

1) hugo new posts/POSTNAME.md OR hugo new posts/POSTNAME.html

2) This will generate e.g.:

```toml
+++
categories = ["golang", "community"]
date = "2015-06-01T20:17:28+03:00"
tags = ["vilnius", "lithuania", "golang", "community"]
title = "Test"
+++
```

3) Please add additional meta data [example](https://raw.githubusercontent.com/vilniusgolang/website/master/content/posts/hello-gophers.md)

```toml
author = "Your name"
bio = "short info about you"
contact = "@twitter"
avatar = "https://avatars1.githubusercontent.com/u/avatar_url"
keywords = "golang meetups Lithuania golang Vilnius meetups"
```

4) Submit Pull Request
