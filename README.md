# smallhands
A simple load generator for MongoDB using mentions of @realDonaldTrump  via the Twitter Streaming API.

!["make run"](https://github.com/timvaillancourt/smallhands/blob/master/screenshots/run.png)

## Required
1. A Twitter account
2. A set of read-only "Twitter Apps" keys (*See: [Twitter Apps Keys](#twitter-apps-keys) steps below*)
3. A Percona Server for MongoDB / MongoDB instance, replset or cluster
4. Python 2.7 (*Python 2.6 and 3.x not tested*) with 'json' and 'pip' modules
5. Pip dependencies specified in 'requirements.txt' (*installed by ["make"](#getting-started) command*)

### Twitter Apps Keys

Smallhands requires Twitter API auth keys. You will need to register a new read-only "app" at https://apps.twitter.com to get a set of Consumer and Access auth key pairs.

## Disclaimer

The test data is likely to contain sexist, racist and generally offensive or incorrect statements.

## Getting Started
```
git clone https://github.com/timvaillancourt/smallhands
cd smallhands
make
cp example.yml config.yml
# (edit config.yml for your situation)
make run
```

## The Future...
1. Better, trump-themed errors/handling
2. Install steps and indices for sharded deployment

##  Code
I beat Python with a hammer until it works. Your improvements are appreciated!

## Contact
Tim Vaillancourt - [Github](https://github.com/timvaillancourt), [Email](mailto:tim@timvaillancourt.com)
