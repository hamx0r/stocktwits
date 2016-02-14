# stocktwits
Python client for the [StockTwits API](http://stocktwits.com/developers/docs/api)

This module makes use of either [`requests`](http://docs.python-requests.org/en/master/) or Google App Engine's [`urlfetch`](https://cloud.google.com/appengine/docs/python/urlfetch/) to do your dark bidding with StockTwits.  Modify api.py to import the Requestor of your choice.  

Get your StockTwits Access Token and set it as an environment variable called `ST_ACCESS_TOKEN`:
Use this URL to get an access_token:
`https://<USER>:<PASSWORD>@api.stocktwits.com/api/2/oauth/authorize?client_id=<CLIENT_ID>&response_type=token&redirect_uri=http://<YOUR DOMAIN>&scope=read,watch_lists,publish_messages,publish_watch_lists,follow_users,follow_stocks`
