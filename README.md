# Stratifyd Document Website Template

## How to use

1. Fork this project
2. Clone it to local
3. Setup dev env, you might have to intall bundler, `gem install bundler`
4. Write markdown
5. Commit
6. Deploy

The default host is on Github.io

You can find the URL under "GitHub Pages" in the repository setting page.

## Setup 

```shell
bundle install --path vendor/bundle
```

## Test

### Local Server

```shell
bundle exec middleman server
```

Open the host address in the terminal.

### Local Static Build

```shell
bundle exec middleman build --clean
```

Open build/index.html .

## Deploy

### Github

1. Commit changes
2. Run `./deploy.sh`

### S3

1. Run `./upload.sh {bucket_name}`

## More Help

For help of the Slate, check out [Slate](https://github.com/lord/slate)

