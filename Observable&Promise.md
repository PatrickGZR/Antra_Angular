## Difference between Observable and Promise
### Observable
1. Observable is multicast, which means every time we subscribe to the observable, it will
be executed again and again.\
2. Observable has subscriptions that are cancellable using the unsubscribe() method, which can stop the listener rom 
receiving further values.\
3. Observable provides the map for forEach, filter, reduce, retry and retryWhen operators.\
4. Observable delivers errors to the subscribers.

### Promise
1. Promise is unicast, which means promises will be executed only once, even if we can then() muultiple times.\
2. Promise execute immediately after creation.\
3. Promise is not cancellable.\
4. Promise doesn't provide any operations.\
5. Promise pushes errors to the child promises.
