# Monzo → Notion

This project is an effort to develop an AWS Lambda function that syncs transactions in a Monzo account to a database in Notion. It'll do this by listening for [a webhook from Monzo](https://docs.monzo.com/#transaction-created) when a transaction is created and [creating a page](https://developers.notion.com/reference/post-page) in a Notion database.

It's being developed in the open by [Connor Gurney](https://www.connorgurney.me.uk), a founder, developer and emergency planner based in the UK. Updates can be found on [his Twitter thread](https://twitter.com/connordoner/status/1599071583381106689?s=20&t=FWz28pva7Qpu3hYjAa6MgQ).

## License

The world is better with more open software, so do what the fuck you want to with this software (though I'd obviously prefer you didn't somehow use it to cause harm in the real world).
