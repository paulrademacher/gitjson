gitjson
=======

Git log wrapper with JSON output. 

 Usage:
```
    gitjson [standard git options] <git-command> [--json=<flags>]
            [standard git command options]
```

 git-command must be 'log'.

 You can restrict the fields to include in the JSON response with
 "--json=flags".  The following flags are supported:

```
    a : author name
    e : author email
    h : sha
    d : date
    s : subject/title
    f : file list
    p : list of parent hashes
    t : tree hash
```
