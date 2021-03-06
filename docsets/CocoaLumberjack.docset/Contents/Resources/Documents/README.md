# CocoaLumberjack documentation
CocoaLumberjack Documentation https://cocoaLumberjack.github.io

This repository hosts the in source documentation for [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack). You can view this at [cocoaLumberjack.github.io](https://cocoaLumberjack.github.io).

## Maintenance

The documentation is auto-generated using [Jazzy](https://github.com/realm/jazzy).

#### Install jazzy

```
[sudo] gem install jazzy
```

#### Generate the CocoaLumberjack documentation

```
jazzy \
  --objc \
  --author CocoaLumberjack \
  --github_url https://github.com/CocoaLumberjack/CocoaLumberjack \
  --github-file-prefix https://github.com/CocoaLumberjack/CocoaLumberjack/tree/3.6.1 \
  --module-version 3.6.1 \
  --umbrella-header Sources/CocoaLumberjack/Supporting\ Files/CocoaLumberjack.h \
  --documentation=Documentation/\*.md \
  --module CocoaLumberjack \
  --output ../cocoaLumberjack.github.io
  --framework-root Sources
```

(assuming CocoaLumberjack and cocoaLumberjack.github.io live in the same folder)
