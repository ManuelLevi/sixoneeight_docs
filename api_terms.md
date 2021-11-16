## About our SEO service and application

SEO is an information service that is licensed for individual use and requires a login session.

Sessions control entitlements and reasonable use for a single user. SEO users might not share their access, access the data through a server or use, distribute or redistribute information in any way to others.

The provided data cannot be used to:
- use of data for the creation of new original works/derived data;
- use of data to create indices;
- use of data in trading systems for the purpose of generating orders and executing transactions in a automated and/or semi-automated manner without the display of the original data.
- use of data in risk managemetn systems and portfolio managment applications.

By using the API, you consent to SEO retaining and processing usage data for the purposes of support, capacity planning, to detect and prevent breaches of our network security, the law or our contract terms, and other activities related to administration, managment and improvement of our services.

We might suspend or terminate access to the API at any time, for maintenance, to protect our systems and security or to in case of suspecion of terms violation.

SOE is also not responsible for erronious or outdated data, and it's the users responsbility to do their own research and garantee the data validity. SOE is not responsible for any decisions made based on its data.

## Resell and redistribution

If you wish to resell or redistribute any applications which you develop using the SOE data API to third parties, you must hold a developer's license agreement.

## Limits

The number of requets are associated to an access token. If an access token is used twice, in two different  applications, and each application does one request, the system will count two requests.

| Type | Description |
| -- | -- |
| Requests per second | 4 requests |
| Requests per day | 10,000 requests |
| Datapoints per request | 1000 data points |

### What happeneds when a limit is reached?

When the limit is reached, the platform returns an HTTP response with status code 429 and the message "Too many requests, please try again later."

### What can be done when a limit is reached?

Wait, and do not silently discard SOE exceptions, they might have important information.

Repeating requests after your application has been throttled might get your token suspended.
