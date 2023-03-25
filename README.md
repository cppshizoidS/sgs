# sgs

.NET 7
ASP .NET Core Web API

  Hangfire(used to  in order not to send a request to the site every time, because it turns out there are restrictions on the request per day.
The Central Bank updates all currencies by about half past 3 pm, so HangFire is set to an approximate time.
I get json with a list of exchange rates at ~14:35 Moscow time and write it to a static dictionary, and then I work with the dictionary)
