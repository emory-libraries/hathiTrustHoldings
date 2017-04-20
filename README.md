# hathiTrustHoldings

### Requirements:

#### Python 2.7.12

#### Flask 0.12.1

### Contributors:

#### Alex Cooper, Lisa Hamlett, Elizabeth Peele Mumpower

### Purpose:

#### Produce [HathiTrust Annual Print Holdings Reports](https://www.hathitrust.org/print_holdings)

----

#### Needs hathi_config.py

```
#!/usr/bin/python

def deleted_config(I_need):

    URL=str('[Your analytics url]')
    PATH=str('[path to your analytics report]')
    APIKEY=str('[Your analytics apikey]')
    LIMIT=str('1000')
    if I_need == "url":
        return URL
    elif I_need == "path":
        return PATH
    elif I_need == "apikey":
        return APIKEY
    elif I_need == "limit":
        return LIMIT
```

> is part of .gitignore to keep secrets secret

----
