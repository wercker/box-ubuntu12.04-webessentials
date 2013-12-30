# ubuntu12.04-webessentials box

Base box with most popular libraries for the web installed.

# What's new

- Make sure $HOME/tmp exists and is owned by `ubuntu`.

# License

The MIT License (MIT)

# Changelog

## 1.0.1

- use version bumped chef box (for inheritence)

## 1.0.0

- Make sure $HOME/tmp exists and is owned by `ubuntu`.

## 0.0.13

- adds libjpeg-dev
- adds libpng-dev
- adds optipng

## 0.0.12

- update to pgdg-keyring for postgres

## 0.0.11

- Update postgres-client to 9.2

## 0.0.10

- GitHub and Bitbucket public keys added to known_hosts

## 0.0.5

- Update wercker-essential-cookbook to 0.0.4
  - Update phantomjs to 1.9.1

## 0.0.4

- Lock apt cookbook to 1.8.2
- Update readme

## 0.0.3

- Initial release
