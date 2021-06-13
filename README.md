
# Example syntax
```
nft list table inet filter
nft list ruleset
```

## Base commands
```
nft add    <table|chain|rule> ...
nft list   <table|chain|rule> ...
nft flush  <table|chain|rule> ...
nft delete <table|chain|rule> ...
```


Debug rule changes
```
nft monitor               # Reports all rule changes live
nft monitor new tables
nft monitor destroy rules
```
