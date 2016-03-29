Connecting to the API
===============

When you have created your account, by default you have a “development” subscription but no further costs for you, so you can test some of major cases of main feature of the BookingFor platform. Plerase note that an API key authentication is valid only for a single subscription, even if a customer has more BookingFor subscriptions.

Once you are able to switch on your implementation in production, you must make a request you your customer to obtain his API key authentication.

To connect with the api, you have two methods to authenticate yourself:

* Basic Authentication

* API key in query string

The subscription will provide automatically an account dedicated for the API.

You can get the API key in the Users section of our platform and get the user with role APIAdmin. Once you have found it, in the editing section you can get its key.

Our API supports natively the Basic authentication. However we recommend for safety to add the key as a header as in this example:

Authorization: Basic yourapikey

Also you can append the Api key in HTTP query string as in this example:

https://api.bookingfor.com/BookingService.svc/GetUsers?apikey=yourapikey