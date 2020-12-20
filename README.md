# Chainink External Retweet Adapter

This external adapter is used to verify whether or not a specified twitter user has retweeted a tweet. It takes two parameters, "userid" and "tweetid", and returns true or false based on whether or not the user has retweeted the specific tweet.

## Input Params

- `userid`: The id of a specific twitter user
- `tweetid`: The id of a specific tweet

## Output

```json
{
 "jobRunID": "1",
 "data": {
  "userid": "1234567",
  "tweetid": "1234567891011"
 },
 "result": true,
 "statusCode": 200
}
```

